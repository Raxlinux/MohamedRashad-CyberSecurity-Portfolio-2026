
## 1. Layer 2 Forwarding Logic

At the Access layer, the switch acts as a transparent bridge. It builds and maintains a **MAC Address Table** to ensure frames are only sent to the specific port where the destination device resides, rather than broadcasting to the entire network.

**Learning:** The switch populates the table by looking at the **Source MAC** of incoming frames.
**Forwarding:** The switch makes forwarding decisions based on the **Destination MAC**.
**Logic:** If the Destination MAC is unknown, the switch floods the frame out of all ports except the one it arrived on (Unknown Unicast Flooding).

## 2. Hardware Tables: CAM vs. TCAM

To achieve "wire-speed" switching, network hardware uses specialized memory instead of a standard CPU/RAM lookup.

| Feature | CAM (Content Addressable Memory) | TCAM (Ternary CAM) |
| --- | --- | --- |
| **Logic Type** | Binary (0, 1) | Ternary (0, 1, **X** "Don't Care") |
| **Match Type** | Exact Match Only | Partial/Range Matches |
| **Primary Use** | Layer 2 MAC Address Table | Layer 3 Routing (LPM), ACLs, QoS |
| **Speed** | Extremely Fast | Extremely Fast |

### Key Takeaways from GeeksforGeeks:

* **The "X" Factor:** TCAM allows for "masking." This is why it’s essential for IP routing—the router can match a packet to a subnet (like `/24`) by "ignoring" the host bits.
* **ASIC Integration:** Both CAM and TCAM are typically baked into **ASICs** (Application-Specific Integrated Circuits), allowing the switch to process millions of packets per second without hitting the main CPU.
* **Cost & Power:** TCAM is more complex, expensive, and power-hungry than standard CAM, which is why switches usually have limited TCAM space (often leading to "TCAM Exhaustion" in massive data centers).
