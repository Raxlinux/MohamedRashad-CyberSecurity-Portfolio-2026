Day 2: Git & GitHub Mastery

Summary:

Today was about moving from "having a GitHub account" to actually speaking the language of Version Control. I finally bridged the gap between the internet café curiosity of my past and the professional CLI (Command Line Interface) workflows I'll need for Cybersecurity. Linus Torvalds really did us a favor—Git is basically a time machine for code, and GitHub is the global hub that connects all those tiny pieces of knowledge.

Steps Taken:

Course Completion: Finished the comprehensive Git & GitHub crash course by freeCodeCamp and logicBase labs. (https://youtu.be/mAFoROnOfHs?si=dgW9ZdegQE3YQBDO)

Environment Setup: Configured my local terminal, verified Git installation, and linked my local machine to my 2026 Portfolio repo.

The "VCS" Deep Dive: Learned the difference between the Git engine (local) and the GitHub library (remote).

Lab Work: Practiced the full lifecycle of a file: from untracked to staged, committed, and finally pushed to the cloud.
                                      
Commands Used:

The Big Three: git add ., git commit -m "message", and git push — the bread and butter of my daily workflow.

Investigation: git status (my best friend for checking what's happening any time i want) and git log --oneline to view my commit history.

Safety Nets: git stash to hide unfinished work and git restore to undo local mistakes.

Branching: git checkout -b <branch> to create "parallel universes" for testing features without breaking the main repo.

Collaboration: git pull and git fetch to keep my local files in sync with the remote server.

Notes & Screenshots:

[Git Command executions](./Git_GitHub_Notes/terminal images).
[Git Commands and fuctions: Handwritten notes pictures](./Git_GitHub_Notes/Written notes) 


Lessons Learned:

The Three Stages: Just like data has "outfits" in the OSI model, code has "states" in Git. It’s either Modified, Staged, or Committed.

Branching is Security: In a cybersecurity context, branching is vital. If I’m testing a script that might be "loud" on a network, I do it on a branch, not the main production line.

Commit Often, Perfect Later: I learned that it's better to save small, logical snapshots than one giant mess. It makes "time travel" (checking out previous commits) much easier if something breaks.

GitHub is the Portfolio: My code isn't just on my laptop anymore; it’s a living, breathing resume that proves I know how to manage a project's lifecycle.