# Operating System – Handwritten Notes 🖋️

A complete, handwritten and carefully structured set of notes covering core Operating System concepts — built for **clarity, depth, and precision**.

These notes are the result of **systematic study, cross-referencing, and deep exploration** of OS concepts, organized to reflect how systems actually work internally.

---

## 📸 Notes Preview

<details>
<summary><b style="color:#1E90FF;">Click to see more</b></summary>  

---

<p>Take a quick look at selected pages from the handwritten notes — just a glimpse of the full depth and detail.<br/>
Scroll down for access to the complete PDFs.</p>

<div style="display:flex; flex-wrap:wrap; gap:12px; justify-content:center;">

<!-- Chapter 1: Introduction & Background -->
<img src="doc/screenshots/01_intro_and_background_6.jpg" width="240" alt="Introduction & Background - Types of OS" />
<img src="doc/screenshots/01_intro_and_background_8.jpg" width="240" alt="Introduction & Background - Architectural requirements for implementing a Multiprogrammed OS" />
<img src="doc/screenshots/01_intro_and_background_13.jpg" width="240" alt="Introduction & Background - Mode Shifting" />

<!-- Chapter 2: Process Management -->
<img src="doc/screenshots/02_process_management_14.jpg" width="240" alt="Process Management - Process" />
<img src="doc/screenshots/02_process_management_15.jpg" width="240" alt="Process Management - Process Structure" />
<img src="doc/screenshots/02_process_management_19.jpg" width="240" alt="Process Management - Process States" />

<!-- Chapter 3: CPU Scheduling -->
<img src="doc/screenshots/03_cpu_scheduling_4.jpg" width="240" alt="CPU Scheduling - Diagram" />
<img src="doc/screenshots/03_cpu_scheduling_14.jpg" width="240" alt="CPU Scheduling - FCFS" />

<!-- Chapter 4: Process Synchronization -->
<img src="doc/screenshots/04_process_synchronization_82.jpg" width="240" alt="Process Synchronization - Checking Perfect Sync" />
<img src="doc/screenshots/04_process_synchronization_94.jpg" width="240" alt="Process Synchronization - NASA Mars Path Finder Project's Problem" />
<img src="doc/screenshots/04_process_synchronization_118.jpg" width="240" alt="Process Synchronization - Dining Philosphers" />
<img src="doc/screenshots/04_process_synchronization_122.jpg" width="240" alt="Process Synchronization - Concurrency Models" />

<!-- Chapter 6: Memory Management -->
<img src="doc/screenshots/06_memory_management_171.jpg" width="240" alt="Memory Management - Loading vs Linking" />
<img src="doc/screenshots/06_memory_management_172.jpg" width="240" alt="Memory Management - Unresolved References" />
<img src="doc/screenshots/06_memory_management_177.jpg" width="240" alt="Memory Management - Address Binding" />
<img src="doc/screenshots/06_memory_management_210.jpg" width="240" alt="Memory Management - Hashed Page Table" />

<!-- Chapter 7: File Management -->
<img src="doc/screenshots/07_file_management_260.jpg" width="240" alt="File Management - Disk Physical Structure" />
<img src="doc/screenshots/07_file_management_272.jpg" width="240" alt="File Management - Directory Structure" />
<img src="doc/screenshots/07_file_management_294.jpg" width="240" alt="File Management - Case Study: Linux Inode Structure" />

</div>

---

</details>


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

## 🧠 Conceptual Coverage

<details>
<summary><b style="color:#1E90FF;">Click to explore full depth</b></summary>

---

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

- Process from a developer’s perspective:
  - A process modeled as an **Abstract Data Type (ADT)**  
  - Structured as:
    - **Definition**  
    - **Representation / Implementation**  
    - **Operations / Methods**  
    - **Attributes / Properties**  

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
  - Burst time prediction (static vs dynamic)  
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

</details>


## 📂 Access the Notes

> 📌 **Tip:** Open in full screen for best readability

- 🔹 [Introduction & Background](https://drive.google.com/file/d/1vat5ZCSkFStOPTCmRVmgBYPoIDQEji3y/view?usp=sharing)  
- 🔹 [Process Management](https://drive.google.com/file/d/1SFQJXRQHW8y3lg5t9Ol_7GbkFGe_mPE2/view?usp=sharing)  
- 🔹 [CPU Scheduling](https://drive.google.com/file/d/1X4UTFSjoGcDyTKbwXPCMDVdmyXMWjvs2/view?usp=sharing)  
- 🔹 [Process Synchronization](https://drive.google.com/file/d/13Ey1ZN9RDb8TlUxQEMmD6oHm62Z7WgRZ/view?usp=sharing)  
- 🔹 [Deadlock](https://drive.google.com/file/d/103FiO_v7nVY0MFG5fgK7wQpsEQLcGKj-/view?usp=sharing)  
- 🔹 [Memory Management](https://drive.google.com/file/d/1PUaVj4aranNXbzCEeg2Zb79qGCuEQTNm/view?usp=sharing)  
- 🔹 [File Management](https://drive.google.com/file/d/1LzSpb53Sqz13tXDkk2mKzIX4jF2OiMrJ/view?usp=sharing)  
- 🔹 [Complete Notes](https://drive.google.com/file/d/1HHS-uK46RtWdXde-Y2vJ29iYz8UwuW2z/view?usp=sharing)

---

## 🗂️ Nature of the Notes

- Handwritten and diagram-heavy  
- Focused on **understanding, not memorization**  
- Built to explain **why things work**, not just how  
- Useful as both:
  - A **learning resource**
  - A **revision/reference guide**

---

## 💬 Acknowledgement  

I would like to express my sincere gratitude to my teacher, **Kshitij Sharma**.

If I have to credit one person for my understanding of Operating Systems, it would be him.  
His teaching played a central role in shaping my clarity on this subject.

---

## 📬 Contact

[<img src="https://img.icons8.com/3d-fluency/30/secured-letter.png" alt="Email" style="vertical-align: middle;"/> official.ahmadrandhawa@gmail.com](mailto:official.ahmadrandhawa@gmail.com)   
[<img src="https://icon.icepanel.io/Technology/svg/LinkedIn.svg" width="26" alt="LinkedIn"/>  LinkedIn Profile](https://www.linkedin.com/in/ahmad-hussain-randhawa/)  
[<img src="https://icon.icepanel.io/Technology/svg/GitHub.svg" width="26" alt="GitHub"/>  GitHub Profile](https://github.com/AhmadHussainRandhawa)   

---

> *"If you have any questions or want to collaborate on something, feel free to email me (without any hesitation)... I might be a little busy sometimes, but I’ll definitely reply."*