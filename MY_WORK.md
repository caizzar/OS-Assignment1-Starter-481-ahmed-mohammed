# 📝 MY_WORK: Student Information, Development Log, Reflection & Answers

> This is the **only file** your instructor reads to grade Parts 3 and 4 (documentation and video). Everything you write here must be **in your own words**.

---

## 🛑 STOP: Read This Before You Do Anything Else

> ### 1️⃣ Read the whole `README.md` first
> The `README.md` in this repository contains the full instructions: class descriptions, feature specifications, question prompts and the video script. **If you skip it, you will lose marks.**
>
> ### 2️⃣ Understand the full code before answering any question
> Open `SchedulerSimulation.java` and read it **from top to bottom**. You must be able to explain what `Process`, `run()`, `runToCompletion()`, `addProcessToQueue()`, `Thread.start()`, `Thread.join()` and `Thread.sleep()` do **before** you write a single answer in Parts B and C. Run the program at least once and watch the output.
>
> ### 3️⃣ Commit many times, not once
> A single commit, or all commits made in the last hour, costs you **-0.5 mark**. See the [Commit Rules](#-commit-rules-mandatory) below.

**How to use this file:**
1. Fill in your **Student Information** (below) right now.
2. Follow the steps in the **Work Roadmap** in order.
3. Update the **Development Log** *every time* you work on the assignment, not at the end.
4. Do not delete any section header. Replace the `[...]` placeholders with your own text.

---

## 👤 Student Information

> ⚠️ **WARNING:** Fill this in first. Your name and ID must match the student ID you set in `SchedulerSimulation.java` (line 150) and the one you say in your video.

| Field | Your Answer |
|-------|-------------|
| **Full Name** | Ahmed amr adel mohammed |
| **Student ID** | 445052835 |
| **University Email** | 445052835@std.psau.edu.sa |
| **GitHub Username** | caizzar |
| **Repository Link** | https://github.com/caizzar/OS-Assignment1-Starter-481-ahmed-mohammed |
 
---

## 🎥 Video Link

**Video Link**: https://drive.google.com/file/d/1J3tD7gX8GZI0GTuZHkQI0RQ0OmawypDJ/view?usp=sharing
> ⚠️ **WARNING:** The video must be **publicly accessible** ("Anyone with the link can view") on **Google Drive**, **YouTube (Unlisted or Public)** or any other cloud file-sharing system. A private, restricted or broken link counts as a **missing video (-1 mark)**.
>
> 💡 **TIP:** Open the link in a **private/incognito window** before you submit. If it asks you to log in or request access, it is not public.
>
> 📌 **NOTE:** The link goes in **this file only** (`MY_WORK.md`), **not** in `README.md`. Name your video file `StudentID_Assignment1_Demo.mp4`. It must last **2 to 3 minutes**.

---

## 🗺️ Work Roadmap (follow in this order)

| Step | What to do | Where | Marks |
|:----:|------------|-------|:-----:|
| 0 | Read `README.md`, then read and run the full code | Your IDE | – |
| 1 | Fork, rename, keep the repo **PUBLIC**, set your student ID (line 150), **commit** | GitHub + code | Part 1 (1) |
| 2 | Feature 1: Process Priority, **commit** | Code | Part 2 (0.25) |
| 3 | Feature 2: Context Switch Counter, **commit** | Code | Part 2 (0.25) |
| 4 | Feature 3: Waiting Time Tracking, **commit** | Code | Part 2 (0.5) |
| 5 | Development Log (5+ entries, different dates) | This file, Part A | Part 3 (0.5) |
| 6 | Reflection (4 questions) | This file, Part B | Part 3 (0.5) |
| 7 | Technical Answers (4 questions) | This file, Part C | Part 3 (0.5) |
| 8 | Record the video, upload it, paste the link above | Video + this file | Part 4 (1.5) |
| 9 | Final check, then submit the repo link on Blackboard | Blackboard | – |

> 💡 **TIP:** Tick each step off as you go. Do not leave the log, the reflection or the video for the last day.

---

## 🔁 Commit Rules (MANDATORY)

> ### ⚠️ MANY COMMITS ARE REQUIRED. A single bulk commit is penalized (-0.5 mark).

**Minimum: 3 meaningful commits. Aim for 6 or more.**

| # | Commit | Example message |
|:-:|--------|-----------------|
| 1 | Student ID set | `Set my student ID: 441234567` |
| 2 | Feature 1: Priority | `Feature 1: Added priority field to Process class` |
| 3 | Feature 2: Context switches | `Feature 2: Implemented context switch counter` |
| 4 | Feature 3: Waiting time | `Feature 3: Added waiting time tracking and summary table` |
| 5 | Development log entries | `Docs: Added development log entries 1-3` |
| 6 | Reflection and answers | `Docs: Completed reflection and technical answers` |
| 7 | Video link | `Docs: Added demo video link` |

**Rules:**
- ✅ **One commit per feature.** Do not put all three features in one commit.
- ✅ **Commit after each work session**, and after each part of this file.
- ✅ **Spread your commits over different dates.** Not all in one day.
- ❌ **Do not make all commits in the last hour** before the deadline.
- ❌ **No vague messages** like `done`, `update` or `final version`.

> 💡 **TIP:** Your commit history is checked and you **show it in your video** (at least 3 commits visible). Your development log dates should match your commit dates.
>
> 💡 **TIP:** **Use VS Code** (see *Recommended Development Environment* in `README.md` for the full setup). Sign in to GitHub in VS Code, then commit from the Source Control panel (Ctrl+Shift+G) → stage → write a message → Commit → Sync/Push. You can edit and commit this file the same way. **Pushing** matters: commits that are not pushed to GitHub are invisible to the instructor.

---

# Part A: Development Log (0.5 mark)

> ⚠️ **WARNING:** Minimum **5 entries**, spread over **different dates**. Five entries written on the same day, or written all at once at the end, will lose marks and look like a copy. Entry dates should be **between the start of the assignment and the deadline (October 10, 2026)**.
>
> 💡 **TIP:** Write an entry at the **end of each work session**, while you still remember what happened. It takes 5 minutes.
>
> 💡 **TIP:** Be specific. "Worked on the code" is a weak entry. "Added a `static int contextSwitches` counter and incremented it before `currentThread.start()`" is a strong one.
>
> 📌 **NOTE:** Each entry needs: date and time, what you did, details, challenges, solution, and time spent. Real challenges are fine (and expected). Do not invent fake ones.

## Example Entry (do not copy it, write your own)

### Entry 1 - [September 22, 2026, 2:30 PM]
**What I did**: Forked the repository and set up my student ID

**Details**:
- Created GitHub account with university email
- Forked the starter repository and renamed it
- Changed student ID on line 150 to my actual ID (441234567)
- Compiled and ran the program successfully
- Committed and pushed: `Set my student ID: 441234567`

**Challenges**: Had to install JDK first because `javac` wasn't recognized

**Solution**: Downloaded JDK 17 and set the PATH variable

**Time spent**: 30 minutes

---

## Your Development Log

### Entry 1 - [7 October , 07:00 AM]
**What I did**:Initial project setup and student ID configuration.

**Details**:
- Created GitHub account with my university email.
- Forked the repository and cloned it to my MacBook.
- Updated the studentID variable to 445052835 to seed the random generator.
- Ran the initial code to understand the Round-Robin logic.

**Challenges**: Making sure the Java environment was ready on my VS Code.

**Solution**: Verified the JDK installation and tested a simple print statement.

**Time spent**: 35 minutes

---

### Entry 2 - [7 October 7:47 AM]
**What I did**: Implemented Feature 1: Process Priority.

**Details**:
- Added the priority field to the Process class.
- Modified the constructor to accept priority. 
- Updated the main loop to generate random values (1-5).

**Challenges**: Updating the constructor without breaking the existing object creation.

**Solution**: Carefully refactored the Process instantiation in the main method.

**Time spent**: 1 hour

---

### Entry 3 - [9 October 6:57 AM ]
**What I did**: Implemented Feature 2: Context Switch Counter.

**Details**:
- Added a static contextSwitches variable in the SchedulerSimulation class.
- Incremented the counter inside the while loop right before each thread starts.
- Displayed the total count (18 in my test run) at the end of the simulation.

**Challenges**: Locating the exact point where a "switch" occurs in the loop.

**Solution**: Placed the increment logic before currentThread.start() to count every time the CPU picks a new thread.

**Time spent**: 1 hour

---

### Entry 4 - [9 October 7:30 AM ]
**What I did**: Implemented Feature 3: Waiting Time Tracking.

**Details**:
- Added creationTime, totalWaitTime, and lastReadyTime fields to the Process class.
- Updated the logic in run() and addProcessToQueue to calculate time spent in the queue.
- Created a final summary table to display the results.

**Challenges**: Managing the time timestamps correctly for processes that yield and re-enter the queue.

**Solution**: Used System.currentTimeMillis() to track when a process enters and leaves the "Ready" state.

**Time spent**: 1.5 hours 

---

### Entry 5 - [9 October 8:15 AM ]
**What I did**: Final Documentation and Code Review.

**Details**:
- Provided specific examples from my terminal output for the Ready Queue behavior.
- Conducted a final code review to ensure all three features (Priority, Counter, and Waiting Time) work together seamlessly.

**Challenges**: Formatting the terminal output snippets inside the Markdown file to ensure they are readable on GitHub.

**Solution**: Used triple backticks (```) to create code blocks, which preserves the ANSI-like structure and makes the output snippets clear and professional on the repository page.

**Time spent**: 1 hour

---

### Entry 6 - [Optional - Date and Time]
**What I did**:

**Details**:

**Challenges**:

**Solution**:

**Time spent**:

---

## Development Log Summary

> 💡 **TIP:** Fill this in **last**, after all entries are written.

**Total time spent on assignment**: 5 hours and 35 minutes.

**Most challenging part**:
Implementing Feature 3 (Waiting Time Tracking) was the most difficult because it required careful management of timestamps using System.currentTimeMillis() as processes moved between the Running and Ready states multiple times.

**Most interesting learning**:
Gaining a hands-on understanding of the Thread Lifecycle (New, Runnable, Running, Waiting, Terminated) and seeing how a Round-Robin scheduler manages these states to ensure CPU fairness.

**What I would do differently next time**:
I would implement a dynamic input system that allows users to add new processes while the scheduler is already running, making the simulation feel more like a real-time operating system.

---

# Part B: Reflection (0.5 mark)

> 🛑 **STOP:** Do **not** start this part until you have read the `README.md`, read the **entire** `SchedulerSimulation.java`, run it, and finished the three features.
>
> ⚠️ **WARNING:** Each answer must be **5 to 7 sentences**, in **your own words**. Copied or AI-generated answers without understanding get **0 marks for the whole assignment**. You may be asked to explain them in person.
>
> 💡 **TIP:** Mention concrete things you actually did: a method you wrote, an error you hit, a line of output you saw. Generic answers score low.
>
> 💡 **TIP:** Draft your answer in a few bullet points first, then turn them into sentences.

## Question 1: What did you learn about multithreading?

> 💡 **TIP:** Talk about thread creation (`Runnable`, `Thread.start()`), waiting with `Thread.join()`, simulating work with `Thread.sleep()`, and what surprised you.

**Your Answer:** *(5-7 sentences)*

I learned that multithreading allows a program to run multiple tasks at the same time. I learned how to create threads using the `Runnable` interface and start them with `Thread.start()`. I also learned how to use `Thread.join()` to make one thread wait for another thread to finish. Using `Thread.sleep()` helped me understand how to pause a thread for a short time. I discovered that threads can run in different orders, so the output may not always be the same. Overall, this assignment helped me understand how multithreading works in Java and why it is useful.


## Question 2: What was the most challenging part of this assignment?

> 💡 **TIP:** Pick **one** specific challenge (understanding the code, one of the features, Git, the video) and say *why* it was hard.

**Your Answer:** *(5-7 sentences)*

The hardest part of this assignment was correctly keeping track of the waiting time for Feature 3. It was difficult to manage the timestamps using the System.currentTimeMillis() method as the processes were constantly yielding the CPU and returning to the ready queue after a certain time quantum. I had to make sure that the logic for the waiting time only included the waiting time for the processes and did not include their execution time. Another challenge was making sure the Context Switch Counter was implemented correctly so that it only increased the count when a new process started execution. This required a lot of digging through the loop structure to understand the flow of the simulation.

## Question 3: How did you overcome the challenges you faced?

> 💡 **TIP:** Describe your method: reading documentation, adding `System.out.println` to debug, re-reading the README, testing after each small change, asking for help.

**Your Answer:** *(5-7 sentences)*

To address this problem, I used a systematic debugging method by printing logs to the terminal to observe the states of variables such as remainingTime and totalWaitTime. In addition, I studied the documentation of the starter code and the README.md file to understand the relationship between the Process class and the SchedulerSimulation loop. In the waiting time part of the code, I utilized the lastReadyTime field to find the time difference every time a process was retrieved from the queue and scheduled to run. Furthermore, I utilized professional tools such as the built-in Git feature of Visual Studio Code to track my commits on each feature before moving to the next one. This systematic approach helped me detect logic errors and ensured that the context switch counter was being incremented at the right time during the scheduling simulation.

## Question 4: How can you apply multithreading concepts in real-world applications?

> 💡 **TIP:** Use real applications you know (web browser, game, mobile app, music player) and connect each one to what you built here.

**Your Answer:** *(5-7 sentences)*

The concepts of multithreading programming are very important for developing real-life applications like Web Browsers, where each tab of the browser can be run on a different thread to ensure that if one website is taking too long to load, it does not freeze the entire window. Another example is Media Players, where one thread can be used for user interface and another thread for decoding and playing a video file in the background. Game Engines also require threads for different tasks like physics, rendering, and sound processing to ensure high frame rates. This assignment has taught me how important the concept of Round Robin Scheduling is for these types of applications, where fairness and avoidance of CPU monopolization by a single task are required. By applying these concepts of multithreading programming, developers can ensure efficiency and predictability of their systems to handle multiple users or tasks at once.

### Optional: What would you like to learn more about?

[Any topics related to threading or operating systems that you're curious about?]

### Optional: How confident do you feel about multithreading concepts now?

[Beginner / Intermediate / Confident. What do you understand well? What needs more practice?]

### Optional: Feedback on the assignment

[Any comments? Was it helpful? Too easy or hard? Suggestions?]

---

# Part C: Technical Answers (0.5 mark)

> 🛑 **STOP:** You cannot answer these questions without understanding the code. Re-read `SchedulerSimulation.java` and **run it** first. Your answers must reference **your own code and your own output** (your student ID makes your output unique).
>
> ⚠️ **WARNING:** Each answer must be **3 to 5 sentences**, with specific examples from your code or output. Use correct terms: thread, process, time quantum, ready queue, context switch, burst time.
>
> 💡 **TIP:** Keep your program output in a text file or screenshot so you can copy real snippets for Question 2.

## Question 1: Thread vs Process

**Question**: Explain the difference between a **thread** and a **process**. Why did we use threads in this assignment instead of creating separate processes? Mention at least **TWO** specific differences (e.g., memory sharing, creation overhead, communication speed), and reference relevant parts of `SchedulerSimulation.java`.

> 💡 **TIP:** Note that the class named `Process` in our code is a *simulated* process, and it is run by a real Java *thread*. Explain that distinction and point to the `new Thread(process)` line in `addProcessToQueue()`.

**Your Answer:** *(3-5 sentences)*

A process is an independent execution unit that has its own dedicated memory space and system resources assigned by the operating system. In contrast, a thread is a "lightweight" unit of execution that exists within a process and shares the same memory and resources with other threads in that process. We used threads in this assignment because they have much lower creation and context-switching overhead compared to processes, making them more efficient for simulating CPU scheduling. Additionally, threads allow for easier communication and data sharing through the shared process memory, which was necessary for our processMap and shared variables.

## Question 2: Ready Queue Behavior

**Question**: In Round-Robin scheduling, what happens when a process doesn't finish within its time quantum? Explain using an example from **your** program output, including **how many times that process was re-queued** before it finished, and explain why re-queueing matters for fairness.

> ⚠️ **WARNING:** The output snippet must come from **your own run** (with your student ID), not from a classmate or from this README.
>
> 💡 **TIP:** Pick a process with a large burst time (e.g., more than 2 × time quantum) and count how many "added to ready queue" lines it has after the first one. Search your console for its name (e.g., `P3`).

**Your Answer:** *(3-5 sentences)*

In Round-Robin scheduling, if a process does not finish its execution within the assigned time quantum, it is "preempted" by the scheduler to ensure fairness. The current thread is stopped, and the process is placed at the back of the Ready Queue to wait for its next turn. This prevents any single process from hogging the CPU and ensures that all processes get a chance to run periodically.

Example from my output:
```⏸ P1 completed quantum 3000ms │ Overall progress: [████░░░░░░] 40%
     Remaining time: 4500ms
  ↻ P1 yields CPU for context switch
  ➕ P1 added to ready queue │ Burst time: 7500ms
```

**Explanation of example:**
In this snippet, P1 ran for the full time quantum (3000ms) but still had 4500ms remaining. Because it wasn't finished, the program printed a "yields CPU" message and used the addProcessToQueue method to put P1 back at the end of the queue.

## Question 3: Thread Lifecycle

**Question**: A thread goes through these states: **New**, **Runnable**, **Running**, **Waiting**, **Terminated**. Walk through these states for one process (e.g., P1) from your simulation. For each state, explain **when** P1 enters it and **which line or method call** triggers the transition (`Thread.start()`, `Thread.join()`, `Thread.sleep()`, etc.).

> 💡 **TIP:** Follow P1 through the code: created in `addProcessToQueue()`, started in the scheduler loop, sleeping inside `run()`, and the main thread waiting on `join()`. Remember that **the main thread waits** on `join()`, while **P1's thread sleeps** in `Thread.sleep()`. Be clear about which thread is in which state.

**Your Answer:** *(3-5 sentences overall; one short explanation per state)*

1. **New**: P1 is in the New state immediately after the new Thread(process) statement is executed but before start() is called

2. **Runnable**: P1 enters the Runnable state after currentThread.start() is called, meaning it is ready to execute and waiting for the JVM thread scheduler to give it CPU time

3. **Running**: P1 is in the Running state when the code inside its run() method is actually being executed by the processor

4. **Waiting**: P1 enters a Timed Waiting state during the Thread.sleep(stepTime) calls which simulate the time taken for execution

5. **Terminated**: P1 reaches the Terminated state once the run() method finishes execution because the remainingTime has reached zero.

## Question 4: Real-World Applications

**Question**: Give **TWO** real-world examples where Round-Robin scheduling with threads would be useful. **At least one** must be an operating-system-level scenario (e.g., how an OS scheduler shares CPU time among running programs). The second can be any application you choose. For each, explain what the system is and **why Round-Robin fits** (fairness, responsiveness, predictability).

> 💡 **TIP:** Relate each example back to your simulation: what plays the role of the "process", the "time quantum" and the "context switch" in that scenario?

**Your Answer:** *(3-5 sentences per example)*

### Example 1 (operating-system level): Web Server Handling Requests

**Description**:
A web server (like Apache or Nginx) handling multiple simultaneous user requests to view different pages on a website

**Why Round-Robin works well here**:
It provides excellent responsiveness and fairness. By giving each request a small time slice, the server ensures that no single large file download blocks other users from loading simple text pages, keeping the system interactive for everyone.

### Example 2: Multitasking in Modern Operating Systems

**Description**:
A desktop OS (like macOS or Windows) running multiple applications at once, such as a web browser, a music player, and VS Code.

**Why Round-Robin works well here**:
It allows the user to feel like all programs are running "simultaneously". Because the time quantum is very small, the CPU switches between these apps so fast that the music keeps playing smoothly while you type code, providing a seamless multitasking experience.

## Summary

**Key concepts I understood through these questions:**
1. The efficiency of using Threads for concurrent tasks over heavy Processes.
2. How Round-Robin ensures fairness by using time quantums and a Ready Queue.
3. The importance of Thread synchronization and lifecycle states in Java.

**Concepts I need to study more:**
1. Thread Safety and Synchronization
2. Advanced Scheduling Algorithms

---

# ✅ Final Checklist (complete before submitting)

> ⚠️ **WARNING:** Go through every line. Late submission costs **-1 mark per day**, and the deadline is **October 10, 2026**.

**Repository**
- [ ] Repository is **PUBLIC** (Settings → Danger Zone → Visibility)
- [ ] Repository is renamed to `OS-Assignment1-YourFirstName-YourLastName`
- [ ] GitHub account uses the university email (`@std.psau.edu.sa`)

**Code**
- [ ] Student ID is set in `SchedulerSimulation.java` (line 150)
- [ ] Code compiles and runs with no errors
- [ ] Feature 1 (priority), Feature 2 (context switches) and Feature 3 (waiting time table) all work
- [ ] Each feature has clear comments

**Commits**
- [ ] **At least 3 meaningful commits, ideally 6 or more**
- [ ] **One commit per feature**
- [ ] Commits are spread over **different dates** (not all in the last hour)
- [ ] Everything is **pushed** to GitHub

**This file (`MY_WORK.md`)**
- [ ] Full name and student ID filled in at the top
- [ ] Development log has **5+ entries** on different dates
- [ ] Reflection: 4 questions, 5-7 sentences each
- [ ] Technical answers: 4 questions, 3-5 sentences each, with examples from **your** output
- [ ] No `[...]` placeholders left
- [ ] No section headers deleted

**Video**
- [ ] 2-3 minutes long, named `StudentID_Assignment1_Demo.mp4`
- [ ] Shows your name, ID, repository, 3 features, IDE execution, one threading concept, and commit history
- [ ] Link is **public** (tested in an incognito window) and pasted in the **Video Link** section above

**Blackboard**
- [ ] Submit **only** the link to your public GitHub repository

> 🎯 **Good luck!** Start early, commit regularly, and make sure you can explain every line you submit.
