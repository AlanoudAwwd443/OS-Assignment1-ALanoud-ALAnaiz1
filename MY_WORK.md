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
| **Full Name** | [AL-Anoud Awwd AL-Anaiz] |
| **Student ID** | [443830523] |
| **University Email** | [443830523]@std.psau.edu.sa |
| **GitHub Username** | [AlanoudAwwd443] |
| **Repository Link** | [https://github.com/AlanoudAwwd443/OS-Assignment1-ALanoud-ALAnaiz1.git] |
 
---

## 🎥 Video Link

**Video Link**: [https://drive.google.com/file/d/10KV9EUN0ANry0bNoMnyQuiGz9m76xpsu/view?usp=sharing]

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

### Entry 1 - [ October 8 2026 ,4:00 pm]
**What I did**:i logo in in git hub

**Details**:
 change id student in the code and open my account in visual studio
**Challenges**:
Linking an account to GitHub in Visual Studio in begin it doesn't work and try 2 hours then finally work 
**Solution**:
i use terminal to To link the account so I can write the comment in Visual Studio and get it to GitHub quickly
**Time spent**:
2 hours
---

### Entry 2 - [:October 9 2026 , 12:30 pm]
**What I did**:
i modified code
**Details**:
I edited the code, I modified feature 1 and 2
**Challenges**:
It was normal; he faced difficulty in changing the code because it was large.
**Solution**:
I searched online to help me find the solution
**Time spent**:
1 hour
---

### Entry 3 - [October 9 2026 , 2:23 pm]
**What I did**:
modified code feature 3
**Details**:
I modified Feature 3; it was a bit long and required a lot of time.
**Challenges**:
I modified Feature 3, which was a bit long and required a lot of time; I had many errors.
**Solution**:
I used the internet to help me fix the error
**Time spent**:
3 hours
---

### Entry 4 - [October 9 2026 , 4:00 pm]
**What I did**:
editing code
**Details**:
I am about to finish the code because the output does not appear on the screen.
**Challenges**:
output does not appear on the screen.
**Solution**:
close the app and rewrite the code
**Time spent**:
6 hours
---

### Entry 5 - [October 10 2026 ,2:04 ]
**What I did**:
I answer the questions
**Details**:
I answered all the questions; there were a lot of them and they took a lot of time.
**Challenges**:
Comparison questions
**Solution**:
Reviewing the slides and the code
**Time spent**:
2 houers
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

**Total time spent on assignment**: [12 hours]

**Most challenging part**:The second part was fun, but he faced some problems with the code and the output, though he benefited from it a lot.

**Most interesting learning**: Part 3 was fun because it shows how we calculate waiting time and turnaround time, and it explains the effect of the time quantum on each process.

**What I would do differently next time**:
I'm trying to simplify the printing and focus more on presenting the data in a simpler way, so tracking the execution is easier.
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

[Multithreading allows the program to execute multiple tasks simultaneously by creating threads using **Runnable** or by creating a **Thread** object and running it using `Thread.start()`. You also learned how `Thread.sleep()` can be used to simulate work or delays within the thread. What amazed me is how easy it is to implement Multithreading code.]

## Question 2: What was the most challenging part of this assignment?

> 💡 **TIP:** Pick **one** specific challenge (understanding the code, one of the features, Git, the video) and say *why* it was hard.

**Your Answer:** *(5-7 sentences)*

[The most difficult part was writing the code. I faced some difficulties in coding, especially in restoring addProcessToQueue, where there was an error that I could not resolve until several hours later. Task 3 involved a lot of work, and the comments were not being saved.]

## Question 3: How did you overcome the challenges you faced?

> 💡 **TIP:** Describe your method: reading documentation, adding `System.out.println` to debug, re-reading the README, testing after each small change, asking for help.

**Your Answer:** *(5-7 sentences)*

[By using the internet and websites such as greekforfreeks and w3schools, I faced difficulties with Turnaround Time and Feature 3 in general. However, after researching and verifying the information, I realized that the topic is easy but requires practice and focused study.]

## Question 4: How can you apply multithreading concepts in real-world applications?

> 💡 **TIP:** Use real applications you know (web browser, game, mobile app, music player) and connect each one to what you built here.

**Your Answer:** *(5-7 sentences)*

[Multithreading appears in many applications that we use daily, such as browsers, which open each tab in an independent thread so that the entire browser does not freeze if a problem occurs on a single page. Games also rely on multithreading to run physics, sound, artificial intelligence, and player movement simultaneously without delay. In mobile applications, playing music occurs in an independent thread so that the song continues while browsing the app. Even messaging applications use threads to receive messages in the background while the user writes a new message at the same time. ]

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

[A process is an independent program with its own memory, whereas a thread is a lightweight execution path that runs within the same process and shares its memory. In our project, the class named Process is merely a simulation of a process, but the actual execution is carried out via a thread created in the line containing new Thread(process) inside addProcessToQueue(). Using real processes would make communication between them slower and increase the creation overhead, whereas threads are lighter and share the same memory, which is suitable for fast scheduling like Round Robin. Additionally, threads allow us to implement concepts such as Thread.start() and Thread.join() easily, as seen in currentThread.start() and currentThread.join() within the main loop. For this reason, multithreading was the best choice for simulating the CPU scheduler in this project.]

## Question 2: Ready Queue Behavior

**Question**: In Round-Robin scheduling, what happens when a process doesn't finish within its time quantum? Explain using an example from **your** program output, including **how many times that process was re-queued** before it finished, and explain why re-queueing matters for fairness.

> ⚠️ **WARNING:** The output snippet must come from **your own run** (with your student ID), not from a classmate or from this README.
>
> 💡 **TIP:** Pick a process with a large burst time (e.g., more than 2 × time quantum) and count how many "added to ready queue" lines it has after the first one. Search your console for its name (e.g., `P3`).

**Your Answer:** *(3-5 sentences)*

[In the Round-Robin algorithm, if a process does not complete within the time quantum, it is immediately returned to the ready queue to receive a new turn later. In the output of my program, process P4 had a large burst time of 5959ms and therefore did not finish during the first quantum, as shown in the line:
➕ P4 (Priority: 5) added to ready queue │ Burst time: 5959ms
After checking the console, I found that P4 was rescheduled (write the number here) times before it completed entirely. Returning the process to the ready queue is important because it ensures fairness, so that processes with large burst times do not monopolize the CPU and every thread gets an equal opportunity in each cycle.]

Example from my output:
```
[➕ P7 (Priority: 1) added to ready queue │ Burst time: 3296ms
┌─ Ready Queue ──────────────────────────────────────────────────────────────────
│ [P9 → P10 → P11 → P12 → P13 → P14 → P15 → P1 → P2 → P3 → P4 → P5 → P7]
└───────────────────────────────────────────────────────────────────────────────
]
```

**Explanation of example:**
[In this example, process P7 was added to the ready queue with a burst time of 3296ms, which means it requires more than one cycle if the time quantum is smaller than this value. Its appearance in the ready queue alongside other processes illustrates that the scheduler goes through each process sequentially and allocates it the same quantum. When process P7 does not complete its execution within the quantum, a context switch is performed, and it is placed back into the ready queue to get another chance in a subsequent cycle. Reintroducing the process into the ready queue in this manner maintains fairness among all threads, ensuring that no single process monopolizes the CPU, and each process receives a portion of time until it completes entirely.]

## Question 3: Thread Lifecycle

**Question**: A thread goes through these states: **New**, **Runnable**, **Running**, **Waiting**, **Terminated**. Walk through these states for one process (e.g., P1) from your simulation. For each state, explain **when** P1 enters it and **which line or method call** triggers the transition (`Thread.start()`, `Thread.join()`, `Thread.sleep()`, etc.).

> 💡 **TIP:** Follow P1 through the code: created in `addProcessToQueue()`, started in the scheduler loop, sleeping inside `run()`, and the main thread waiting on `join()`. Remember that **the main thread waits** on `join()`, while **P1's thread sleeps** in `Thread.sleep()`. Be clear about which thread is in which state.

**Your Answer:** *(3-5 sentences overall; one short explanation per state)*

1. **New**: [P1 is in the New state at the moment it is created inside addProcessToQueue() when we call:
Thread thread = new Thread(process);
Here, the thread has been created but hasn’t started executing yet.]

2. **Runnable**: [P1 moves to the Runnable state right after being added to the ready queue using:
processQueue.add(thread);
At this moment, the thread is ready to run and is waiting for the scheduler to call it.]

3. **Running**: [P1 enters the Running state when the scheduler calls: currentThread.start(); Here, the process's run() function starts executing, and the quantum begins.]

4. **Waiting**: [p1 enters a Waiting state while executing Thread.sleep(stepTime) inside run(), where it pauses temporarily to simulate the execution of the quantum. Also, the main thread itself goes into a Waiting state when it calls: currentThread.join(); because it’s waiting for P1 to finish before moving on to the next process.]

5. **Terminated**: [p1 reaches the Terminated state when run() or runToCompletion() ends and remainingTime == 0. After that, it doesn't go back to the ready queue and is added to the list of completed processes.]

## Question 4: Real-World Applications

**Question**: Give **TWO** real-world examples where Round-Robin scheduling with threads would be useful. **At least one** must be an operating-system-level scenario (e.g., how an OS scheduler shares CPU time among running programs). The second can be any application you choose. For each, explain what the system is and **why Round-Robin fits** (fairness, responsiveness, predictability).

> 💡 **TIP:** Relate each example back to your simulation: what plays the role of the "process", the "time quantum" and the "context switch" in that scenario?

**Your Answer:** *(3-5 sentences per example)*

### Example 1 (operating-system level): [online gameing]

**Description**:
[In multiplayer game servers, like an online game with 20 players, each player sends events (movement, shooting, jumping…) and the server has to handle each player quickly. The server can run each player in a thread and give each player a small time quantum to process their event, then do a context switch to move to the next player. This is similar to your simulation, where each process represents a player, and the quantum is the time allotted to handle the player's event.]

**Why Round-Robin works well here**:
[Round-Robin keeps the response fast for all players, so no single player causes delays for the others. It also ensures fairness, because every player gets the same amount of time to handle their events. And since the quantum is fixed, the game becomes predictable and stable, like we saw in your simulations when the processes took turns running without any single process hogging the CPU.]

### Example 2: [operating system]

**Description**:
[In real operating systems, like Windows or Linux, there are dozens of programs running at the same time, and each program has multiple threads. The OS uses an algorithm like Round-Robin to give each thread a small slice of CPU time called a time quantum, then does a context switch to move to the next program. This is exactly what happens in my simulation, where each process like P1 or P7 represents a program, and the quantum is the time each thread gets before going back to the ready queue.]

**Why Round-Robin works well here**:
[Round-Robin is suitable for operating systems because it ensures fairness among all programs, so no single program monopolizes the CPU. It also provides high responsiveness for interactive applications like browsers, since each program gets a small slice of time periodically. And because the quantum is fixed, the system's performance is predictable and controllable, just like we saw in our simulations when processes took turns on the CPU in an organized way.]

## Summary

**Key concepts I understood through these questions:**
1.I understood the role of Round-Robin and how sending the process back to the ready queue after the time quantum ends ensures fairness and prevents monopoly.
2.I understood the difference between a process and a thread, and how the Process class in the code is just a simulation, while the real execution happens through Thread.start() and Thread.join().
3.I understood the importance of threading in programming and how it makes processes in multi-tasking programs easier and faster.

**Concepts I need to study more:**
1.How to use each thread, the right time to use it, and how I add it in a program and an app so that programs run faster and better
2.I need to look more into how waiting time is calculated precisely, especially the relationship between lastReadyTime and updateWaitingTime().

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
