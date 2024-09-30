# Operating-System-for-Multi-Agent-Robotic-System
Developed an operating system for a multi-agent system using processes and threads on a multi-core processor. The system was designed to control 50 robots in a 100x100 environment, where each robot estimated the width of an exit and shared information using Inter-Process Communication (IPC). 

## Key Learnings & Results:

* Designed and implemented Inter-Process Communication (IPC) using pipes, enabling robots to share exit width estimates.
* Employed Process Synchronization techniques (semaphores and mutexes) to prevent race conditions and ensure exclusive access to shared resources.
* Implemented memory management for processes and threads, ensuring secure allocation and deallocation of memory.
* Managed concurrent robot processes using thread management techniques, allowing efficient use of multi-core processors.
* Integrated a process scheduling mechanism for optimal resource allocation.
* Achieved real-time estimation of exit width with an accuracy rate of 95%, demonstrating effective coordination and communication among robots.
