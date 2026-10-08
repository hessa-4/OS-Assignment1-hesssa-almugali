📝 MY_WORK: Student Information, Development Log, Reflection & Answers
This is the only file your instructor reads to grade Parts 3 and 4 (documentation and video). Everything you write here must be in your own words.

🛑 STOP: Read This Before You Do Anything Else
1️⃣ Read the whole README.md first
The README.md in this repository contains the full instructions: class descriptions, feature specifications, question prompts and the video script. If you skip it, you will lose marks.
2️⃣ Understand the full code before answering any question
Open SchedulerSimulation.java and read it from top to bottom. You must be able to explain what Process, run(), runToCompletion(), addProcessToQueue(), Thread.start(), Thread.join() and Thread.sleep() do before you write a single answer in Parts B and C. Run the program at least once and watch the output.
3️⃣ Commit many times, not once
A single commit, or all commits made in the last hour, costs you -0.5 mark. See the Commit Rules below.

How to use this file:
1. Fill in your Student Information (below) right now.
2. Follow the steps in the Work Roadmap in order.
3. Update the Development Log every time you work on the assignment, not at the end.
4. Do not delete any section header. Replace the [...] placeholders with your own text.
👤 Student Information
⚠️ WARNING: Fill this in first. Your name and ID must match the student ID you set in SchedulerSimulation.java (line 150) and the one you say in your video.

Field	Your Answer
Full Name	Hessa Abdullah Almujali
Student ID	445052209
University Email	445052209@std.psau.edu.sa
GitHub Username	hessa-4
Repository Link	https://github.com/hessa-4/OS-Assignment1-hesssa-almugali


🎥 Video Link
Video Link: https://drive.google.com/file/d/1_5arDLip7KAzRFYdaekgTmfHaxWW1Fcp/view?usp=drivesdk
⚠️ WARNING: The video must be publicly accessible ("Anyone with the link can view") on Google Drive, YouTube (Unlisted or Public) or any other cloud file-sharing system. A private, restricted or broken link counts as a missing video (-1 mark).
💡 TIP: Open the link in a private/incognito window before you submit. If it asks you to log in or request access, it is not public.
📌 NOTE: The link goes in this file only (MY_WORK.md), not in README.md. Name your video file StudentID_Assignment1_Demo.mp4. It must last 2 to 3 minutes.

🗺️ Work Roadmap (follow in this order)
Step	What to do	Where	Marks
0	Read README.md, then read and run the full code	Your IDE	–
1	Fork, rename, keep the repo PUBLIC, set your student ID (line 150), commit	GitHub + code	Part 1 (1)
2	Feature 1: Process Priority, commit	Code	Part 2 (0.25)
3	Feature 2: Context Switch Counter, commit	Code	Part 2 (0.25)
4	Feature 3: Waiting Time Tracking, commit	Code	Part 2 (0.5)
5	Development Log (5+ entries, different dates)	This file, Part A	Part 3 (0.5)
6	Reflection (4 questions)	This file, Part B	Part 3 (0.5)
7	Technical Answers (4 questions)	This file, Part C	Part 3 (0.5)
8	Record the video, upload it, paste the link above	Video + this file	Part 4 (1.5)
9	Final check, then submit the repo link on Blackboard	Blackboard	–


💡 TIP: Tick each step off as you go. Do not leave the log, the reflection or the video for the last day.

🔁 Commit Rules (MANDATORY)
⚠️ MANY COMMITS ARE REQUIRED. A single bulk commit is penalized (-0.5 mark).

Minimum: 3 meaningful commits. Aim for 6 or more.
#	Commit	Example message
1	Student ID set	Set my student ID: 441234567
2	Feature 1: Priority	Feature 1: Added priority field to Process class
3	Feature 2: Context switches	Feature 2: Implemented context switch counter
4	Feature 3: Waiting time	Feature 3: Added waiting time tracking and summary table
5	Development log entries	Docs: Added development log entries 1-3
6	Reflection and answers	Docs: Completed reflection and technical answers
7	Video link	Docs: Added demo video link


Rules:
- ✅ One commit per feature. Do not put all three features in one commit.
- ✅ Commit after each work session, and after each part of this file.
- ✅ Spread your commits over different dates. Not all in one day.
- ❌ Do not make all commits in the last hour before the deadline.
- ❌ No vague messages like done, update or final version.
💡 TIP: Your commit history is checked and you show it in your video (at least 3 commits visible). Your development log dates should match your commit dates.
💡 TIP: Use VS Code (see Recommended Development Environment in README.md for the full setup). Sign in to GitHub in VS Code, then commit from the Source Control panel (Ctrl+Shift+G) → stage → write a message → Commit → Sync/Push. You can edit and commit this file the same way. Pushing matters: commits that are not pushed to GitHub are invisible to the instructor.

Part A: Development Log (0.5 mark)
⚠️ WARNING: Minimum 5 entries, spread over different dates. Five entries written on the same day, or written all at once at the end, will lose marks and look like a copy. Entry dates should be between the start of the assignment and the deadline (October 10, 2026).
💡 TIP: Write an entry at the end of each work session, while you still remember what happened. It takes 5 minutes.
💡 TIP: Be specific. "Worked on the code" is a weak entry. "Added a static int contextSwitches counter and incremented it before currentThread.start()" is a strong one.
📌 NOTE: Each entry needs: date and time, what you did, details, challenges, solution, and time spent. Real challenges are fine (and expected). Do not invent fake ones.

Example Entry (do not copy it, write your own)
Entry 1 - [September 22, 2026, 2:30 PM]
What I did: Forked the repository and set up my student ID
Details:
- Created GitHub account with university email
- Forked the starter repository and renamed it
- Changed student ID on line 150 to my actual ID (441234567)
- Compiled and ran the program successfully
- Committed and pushed: Set my student ID: 441234567
Challenges: Had to install JDK first because javac wasn't recognized
Solution: Downloaded JDK 17 and set the PATH variable
Time spent: 30 minutes
Your Development Log
Entry 1 - [Date and Time]
What I did: Set up project and opened files.
Details: Reviewed assignment requirements.
Challenges: Understanding scheduler logic.
Solution: Read instructions again.
Time spent: 1 hour
Entry 2 - [Date and Time]
What I did: Started SchedulerSimulation.java.
Details: Created basic structure.
Challenges: Choosing scheduling method.
Solution: Checked example code.
Time spent: 1.5 hours
Entry 3 - [Date and Time]
What I did: Implemented scheduling logic.
Details: Added process handling.
Challenges: Logic errors appeared.
Solution: Debugged step by step.
Time spent: 1.5 hours
Entry 4 - [Date and Time]
What I did: Tested the program.
Details: Ran different cases.
Challenges: Output mismatch.
Solution: Fixed calculation issue
Time spent: 1 hour
Entry 5 - [Date and Time]
What I did: Updated README and answers.
Details: Explained implementation steps.
Challenges: Formatting markdown.
Solution: Used examples.
Time spent: 45 minutes
Entry 6 - October 8, 2026, approximately 7:30-8:10 PM (Saudi Arabia)
What I did: Updated my earlier project for the current assignment requirements.
Details: Changed random priorities to 1-10, added getTurnaroundTime(), displayed turnaround times and their average, aligned the table columns, and started MY_WORK.md.
Challenges: I needed help finding the correct lines and keeping the table column order consistent.
Solution: I made small edits with guidance, reviewed screenshots, and saved the changes in GitHub.
Time spent: Approximately 40 minutes.
Development Log Summary
💡 TIP: Fill this in last, after all entries are written.

Total time spent on assignment: To be confirmed from my actual work sessions.
Most challenging part: Understanding the scheduler and editing the correct code sections.
Most interesting learning: How fixed time slices share CPU time and how waiting and turnaround times are calculated.
What I would do differently next time: Start earlier and record each session immediately.
Part B: Reflection (0.5 mark)
🛑 STOP: Do not start this part until you have read the README.md, read the entire SchedulerSimulation.java, run it, and finished the three features.
⚠️ WARNING: Each answer must be 5 to 7 sentences, in your own words. Copied or AI-generated answers without understanding get 0 marks for the whole assignment. You may be asked to explain them in person.
💡 TIP: Mention concrete things you actually did: a method you wrote, an error you hit, a line of output you saw. Generic answers score low.
💡 TIP: Draft your answer in a few bullet points first, then turn them into sentences.

Question 1: What did you learn about multithreading?
💡 TIP: Talk about thread creation (Runnable, Thread.start()), waiting with Thread.join(), simulating work with Thread.sleep(), and what surprised you.

Your Answer: (5-7 sentences)
I learned that multithreading allows multiple tasks to run at the same time within a program. It helps improve system performance and makes applications more responsive. I also understood how threads share CPU time using scheduling techniques like Round Robin. The assignment helped me learn how threads move between different states such as ready, running, and waiting. I learned how context switching allows the CPU to switch between processes quickly. This made me understand how operating systems manage multiple processes efficiently.
Question 2: What was the most challenging part of this assignment?
💡 TIP: Pick one specific challenge (understanding the code, one of the features, Git, the video) and say why it was hard.

Your Answer: (5-7 sentences)
The most challenging part of this assignment was understanding how the scheduling simulation works in the code. It was difficult at first to understand how processes move between the ready queue and execution state. Running the program correctly in the terminal was also challenging for me. I needed time to understand how to compile and execute Java files properly. However, after practicing the steps several times, it became easier. This helped me improve my confidence in working with Java programs.
Question 3: How did you overcome the challenges you faced?
💡 TIP: Describe your method: reading documentation, adding System.out.println to debug, re-reading the README, testing after each small change, asking for help.

Your Answer: (5-7 sentences)
I overcame the challenges by reviewing the instructions carefully and practicing the commands step by step. I also checked errors in the terminal and tried to fix them one by one. I asked for help when I did not understand some steps. Reading the error messages helped me identify what was wrong. I also followed examples from the instructor’s guide. These steps helped me successfully run the program and complete the assignment.
Question 4: How can you apply multithreading concepts in real-world applications?
💡 TIP: Use real applications you know (web browser, game, mobile app, music player) and connect each one to what you built here.

Your Answer: (5-7 sentences)
Multithreading is used in many real-world applications such as web browsers and mobile apps. For example, a browser can load multiple tabs at the same time using threads. Mobile apps use threads to run background tasks without freezing the screen. Games also use multithreading to manage graphics, sound, and user input simultaneously. In operating systems, scheduling helps manage multiple running programs efficiently. This assignment helped me understand how these concepts work in practical situations.
Optional: What would you like to learn more about?
I would like to learn more about synchronization and how threads communicate safely.
Optional: How confident do you feel about multithreading concepts now?
Beginner: I can follow the scheduling flow with guidance, but I need more practice with Java thread states and synchronization.
Optional: Feedback on the assignment
The assignment helped me connect CPU scheduling concepts to program output, although editing and understanding the code was challenging.
Part C: Technical Answers (0.5 mark)
🛑 STOP: You cannot answer these questions without understanding the code. Re-read SchedulerSimulation.java and run it first. Your answers must reference your own code and your own output (your student ID makes your output unique).
⚠️ WARNING: Each answer must be 3 to 5 sentences, with specific examples from your code or output. Use correct terms: thread, process, time quantum, ready queue, context switch, burst time.
💡 TIP: Keep your program output in a text file or screenshot so you can copy real snippets for Question 2.

Question 1: Thread vs Process
Question: Explain the difference between a thread and a process. Why did we use threads in this assignment instead of creating separate processes? Mention at least TWO specific differences (e.g., memory sharing, creation overhead, communication speed), and reference relevant parts of SchedulerSimulation.java.
💡 TIP: Note that the class named Process in our code is a simulated process, and it is run by a real Java thread. Explain that distinction and point to the new Thread(process) line in addProcessToQueue().

Your Answer: (3-5 sentences)
A process normally has its own address space, while threads within one process share memory. Creating threads generally has lower overhead than creating separate operating-system processes, and shared memory makes communication easier. In this assignment, the class named Process is a simulation object rather than an actual operating-system process. The program creates a real Java worker using new Thread(process) in addProcessToQueue(), which lets the simulation execute one time slice and then coordinate with join().
Question 2: Ready Queue Behavior
Question: In Round-Robin scheduling, what happens when a process doesn't finish within its time quantum? Explain using an example from your program output, including how many times that process was re-queued before it finished, and explain why re-queueing matters for fairness.
⚠️ WARNING: The output snippet must come from your own run (with your student ID), not from a classmate or from this README.
💡 TIP: Pick a process with a large burst time (e.g., more than 2 × time quantum) and count how many "added to ready queue" lines it has after the first one. Search your console for its name (e.g., P3).

Your Answer: (3-5 sentences)
An unfinished simulated process is added to the end of the FIFO ready queue so other processes can receive their turns. The program calls addProcessToQueue() again, creating a new Thread for the same Process object. For example, my earlier saved output shows P1 completing a 4000 ms quantum with 3556 ms still remaining, then yielding the CPU and being added back to the queue. This re-queueing prevents that process from monopolizing CPU time. The complete updated run is still needed to confirm the total number of re-queues before that process finishes.
Example from my output:
Earlier saved output (replace with the updated run before submission):
P1 completed quantum 4000ms
Remaining time: 3556ms
P1 yields CPU for context switch
P1 added to ready queue | Burst time: 7556ms
Explanation of example:
P1 still needs CPU time after the quantum, so the scheduler re-enqueues it and gives other processes a turn. Total re-queue count: [Confirm from the complete updated run].
Question 3: Thread Lifecycle
Question: A thread goes through these states: New, Runnable, Running, Waiting, Terminated. Walk through these states for one process (e.g., P1) from your simulation. For each state, explain when P1 enters it and which line or method call triggers the transition (Thread.start(), Thread.join(), Thread.sleep(), etc.).
💡 TIP: Follow P1 through the code: created in addProcessToQueue(), started in the scheduler loop, sleeping inside run(), and the main thread waiting on join(). Remember that the main thread waits on join(), while P1's thread sleeps in Thread.sleep(). Be clear about which thread is in which state.

Your Answer: (3-5 sentences overall; one short explanation per state)
1. New: new Thread(process) in addProcessToQueue() creates P1's worker in NEW, and it remains unstarted while in our queue.
2. Runnable: currentThread.start() makes the worker RUNNABLE and eligible to execute.
3. Running: When the JVM schedules it, the worker executes Process.run(); Java includes execution in RUNNABLE rather than a separate Thread.State called Running.
4. Waiting: Thread.sleep(stepTime) puts P1's worker in TIMED_WAITING, while currentThread.join() makes the main scheduler thread wait for that worker to finish.
5. Terminated: The worker terminates when run() returns after a quantum, even if simulated P1 still has remaining work; re-queueing creates a new worker thread.
Question 4: Real-World Applications
Question: Give TWO real-world examples where Round-Robin scheduling with threads would be useful. At least one must be an operating-system-level scenario (e.g., how an OS scheduler shares CPU time among running programs). The second can be any application you choose. For each, explain what the system is and why Round-Robin fits (fairness, responsiveness, predictability).
💡 TIP: Relate each example back to your simulation: what plays the role of the "process", the "time quantum" and the "context switch" in that scenario?

Your Answer: (3-5 sentences per example)
Example 1 (operating-system level): Time-sharing CPU scheduling
Description:
An operating system can share CPU time among runnable tasks of equal scheduling priority. In a Round-Robin scheduling policy, each task receives a bounded time slice before another ready task gets its turn.
Why Round-Robin works well here:
This prevents a long-running task from monopolizing the CPU and supports responsiveness. It resembles our FIFO queue, fixed time quantum, and re-queueing of unfinished simulated processes. Real operating systems also manage I/O, priorities, and other scheduling policies.
Example 2: Web server request handlers
Description:
A web server can use multiple worker threads to handle client requests. Each runnable worker competes for CPU time, just as each simulated Process does in our assignment.
Why Round-Robin works well here:
A Round-Robin-style allocation of CPU time can give runnable workers regular turns, preventing one CPU-heavy handler from blocking progress for others. This supports fairness and responsiveness, like moving unfinished work to the end of our queue. Actual servers also depend on I/O handling and the operating system's scheduler.
Summary
Key concepts I understood through these questions:
1. Threads share memory within a process.
2. Unfinished simulated processes return to the end of the queue.
3. A worker thread can terminate before its simulated process has finished all its work.
Concepts I need to study more:
1. Java thread states and coordination.
2. Synchronization and real operating-system scheduling.
✅ Final Checklist (complete before submitting)
⚠️ WARNING: Go through every line. Late submission costs -1 mark per day, and the deadline is October 10, 2026.

Repository
- [ ] Repository is PUBLIC (Settings → Danger Zone → Visibility)
- [ ] Repository is renamed to OS-Assignment1-YourFirstName-YourLastName
- [ ] GitHub account uses the university email (std.psau.edu.sa)
Code
- [ ] Student ID is set in SchedulerSimulation.java (line 150)
- [ ] Code compiles and runs with no errors
- [ ] Feature 1 (priority), Feature 2 (context switches) and Feature 3 (waiting time table) all work
- [ ] Each feature has clear comments
Commits
- [ ] At least 3 meaningful commits, ideally 6 or more
- [ ] One commit per feature
- [ ] Commits are spread over different dates (not all in the last hour)
- [ ] Everything is pushed to GitHub
This file (MY_WORK.md)
- [ ] Full name and student ID filled in at the top
- [ ] Development log has 5+ entries on different dates
- [ ] Reflection: 4 questions, 5-7 sentences each
- [ ] Technical answers: 4 questions, 3-5 sentences each, with examples from your output
- [ ] No [...] placeholders left
- [ ] No section headers deleted
Video
- [ ] 2-3 minutes long, named StudentID_Assignment1_Demo.mp4
- [ ] Shows your name, ID, repository, 3 features, IDE execution, one threading concept, and commit history
- [ ] Link is public (tested in an incognito window) and pasted in the Video Link section above
Blackboard
- [ ] Submit only the link to your public GitHub repository
