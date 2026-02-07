Day 3: TCP/IP Architecture, MAC vs. IP, & Mastering IPv4 Addressing

Summary: 

Today was about moving from the theoretical to the practical. I broke down the differences between the rigid OSI model, the TCP/IP suite, and the Hybrid model that we actually use in the real world. The focus then shifted heavily to addressing—understanding the distinct roles of MAC (Hardware) and IP (Logical) addresses. I also started the deep dive into IPv4 math, grinding out binary conversions to prepare for subnetting.

Steps Taken:

Model Comparison: Analyzed the differences between OSI, TCP/IP, and the Hybrid model to understand where they overlap.

Layer Deep Dive: Looked at how Layer 1 media changes (copper vs. fiber vs. air), but Layer 2 remains consistent by using MAC addresses.

Starlink Overview: Briefly explored how Starlink handles data transmission via satellite constellations.

Video Study: Completed "IPv4 Addressing (Part 1) - Day 7" by Jeremy’s IT Lab.

Math Drills: Practiced converting octets from decimal to binary and vice versa.

Commands & Exercises:

Binary Conversions: Completed quizzes (5 questions each) on converting Decimal to Binary and Binary to Decimal.

Address Analysis: Practiced identifying the Network portion vs. the Host portion of an address.

Class Identification: Worked on distinguishing IPv4 Address Classes (A, B, C, D, E) and Loopback addresses.

Notes & Screenshot:

[Directory to Day 3 Notes and Quizzes](../Screenshots%20and%20Notes/Day3_Notes_images/)


Lessons Learned:

The Great Equalizer: Even though physical media (Layer 1) varies, Layer 2 standardizes everything using MAC addresses so devices can identify each other.

Logical vs. Physical: MAC addresses are "burned-in" hardware IDs (though spoofable), whereas IP addresses are logical and configured by an administrator to connect networks.

Tunnel Vision: Serial links use Point-to-Point connections; one transmitter, one receiver. They don't care about anything outside their direct range.

The Math Matters: Understanding the IPv4 Header and Netmasks is impossible without a solid grip on the binary number system.