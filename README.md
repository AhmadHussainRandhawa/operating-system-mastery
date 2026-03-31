# Operating System – Handwritten Notes 🖋️

A complete, handwritten and carefully structured set of notes covering core Operating System concepts — built for **clarity, depth, and precision**.

These notes are the result of **systematic study, cross-referencing, and deep exploration** of OS concepts, organized to reflect how systems actually work internally.

---

## 📘 Scope of the Notes

This repository covers the full spectrum of fundamental Operating System concepts:

- Introduction & System Foundations  
- Process Management  
- CPU Scheduling  
- Process Synchronization  
- Deadlocks  
- Memory Management  
- File Systems  

Each section is developed with **detailed explanations, diagrams, and problem-solving approaches**.

---

## Conceptual Coverage (Depth Overview)

### 1. Introduction & Background

- What an Operating System really is (beyond definitions)  
- Hardware components and system interaction  
- Von Neumann Architecture  
- Goals and design philosophy of OS  
- Types of systems: Uniprogramming vs Multiprogramming  
- User Mode vs Kernel Mode  
- Mode switching and protection mechanisms  

---

### 2. Process Management

- Process abstraction in depth  
- Process states and transitions (with detailed diagrams)  
- State transition and queueing models  
- Process Control Block (PCB) structure and role  
- Schedulers:
  - Long-term (job scheduler)  
  - Short-term (CPU scheduler)  
  - Medium-term (swapping)    
- Dispatcher and context switching  

---

### 3. CPU Scheduling

- Scheduling objectives and performance metrics  
- Algorithms implemented and analyzed:

  - FCFS  
  - SJF (Preemptive & Non-preemptive)  
  - SRTF (Shortest Remaining Time First)  
  - prediction techniques for Burst Time (static vs Dynamic)
  - HRRN (Highest Response Ratio Next)
  - LRTF (Longest Remaining Time First)
  - Priority Scheduling  
  - Round Robin  
  - Multilevel Queue Scheduling  

- Numerical problem solving for each algorithm  
- Trade-offs: throughput, turnaround time, response time  

---

### 4. Process Synchronization

A deeply explored section covering both **theory and mechanisms**:

- Independent vs Cooperating Processes  
- Inter-Process Communication (IPC)  
- Synchronization problem and its necessity  
- Conditions for correct synchronization  

#### Synchronization Techniques:

**Software-based:**
- Lock variables  
- Strict alternation  
- Peterson’s Solution  
- Dekker’s Algorithm  

**Hardware-based:**
- Test-and-Set (TSL)  
- Swap  
- Compare-and-Swap  
- LL/SC  

**OS-based:**
- Sleep & Wakeup  
- Semaphores  

#### Classical Problems:
- Producer–Consumer  
- Reader–Writer  
- Dining Philosophers  

#### Concurrency Concepts:
- Sequential vs Concurrent execution  
- PARBEGIN / PAREND (COBEGIN / COEND)  
- Process graphs and transformations  
- Fork and Join models  

---

### 5. Deadlocks

- Coffman Conditions (all 4 necessary conditions)  
- Resource Allocation Graph (RAG)  
- Deadlock handling strategies:

  - Prevention  
  - Avoidance  
  - Detection  
  - Recovery  
  - Ignorance (Ostrich approach)  

---

### 6. Memory Management

One of the most detailed sections:

- CPU–Memory interaction  
- Linear memory model and byte-addressability  
- Address binding:
  - Compile-time  
  - Load-time  
  - Execution-time  

- Linking:
  - Static vs Dynamic  

#### Memory Allocation Techniques:

**Contiguous:**
- Overlays  
- Fixed partitions  
- Variable partitions  

**Non-Contiguous:**
- Paging (deep coverage):
  - Simple paging  
  - Multilevel paging  
  - TLB  
  - Physical address cache  
  - Hashed paging  

- Segmentation  

#### Virtual Memory:

- Demand paging  
- Page replacement algorithms  
- Reference strings  
- Thrashing  
- Thrashing control strategies  

---

### 7. File Management

- Disk structure (physical and logical)  
- Boot process  
- File vs Directory (deep comparison)  
- Directory structures  

#### File System Internals:

- File system implementation  
- Allocation methods  
- Free space management  
- Disk scheduling  

#### Case Studies:

- Linux inode structure  
- ext4 file system  

---

## 📂 Access to Notes

All chapters are available as scanned PDFs:

- [Introduction & Background](GOOGLE_DRIVE_LINK_1)  
- [Process Management](GOOGLE_DRIVE_LINK_2)  
- [CPU Scheduling](GOOGLE_DRIVE_LINK_3)  
- [Process Synchronization](GOOGLE_DRIVE_LINK_4)  
- [Deadlock](GOOGLE_DRIVE_LINK_5)  
- [Memory Management](GOOGLE_DRIVE_LINK_6)  
- [File Management](GOOGLE_DRIVE_LINK_7)  

---

## 📊 Nature of the Notes

- Handwritten and diagram-heavy  
- Focused on **understanding, not memorization**  
- Built to explain **why things work**, not just how  
- Suitable as both:
  - A **learning resource**
  - A **revision/reference guide**

---

## 🖼️ Sample Pages

![Sample 1](link_to_image_1.png)  
![Sample 2](link_to_image_2.png)

---

## 🙏 Acknowledgement

I would like to express my sincere gratitude to my teacher, **Kshitij Sharma**.

If I have to credit one person for my understanding of Operating Systems, it would be him.  
His teaching played a central role in shaping my clarity on this subject.
