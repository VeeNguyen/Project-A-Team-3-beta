# Project A-Team 3
#### VCU, Spring 2020, CMSC 355: Software Developmant Spec & Des

### Intro:
Programming is hard but with practice, anyone can learn it. Novice programmers need consistent practice reading code and hand tracing through code to understand how variables change, learn syntax, and develop problem-solving skills. This app uses daily mini-lessons to help beginning programming students develop a regular programming practice.

* Students create an account with a password to log into the application.
* Each registered student’s progress is stored.
* Students are given five daily mini-lessons each that can be completed in 5 - 10 minutes but must be completed on the day assigned.
* On the sixth day, a short 5 - 10 question quiz is given on the topics from the previous 5 lessons.
* On the seventh day, a record of all students who completed all 6 days is sent to the course instructor.
* If desired, a student can have a record of their progress sent to them via email.


### Questions:
#### 1. Are there any specific languages that we need to cover?
* No. You can consider any languages.
#### 2. How advanced/in-depth should the tutorials get?
* Consider this: A user wants to be a Java programmer. So he start with basic concepts. Then he gradually learns about Conditions, Loops, Arrays, Lists, etc. Afterwards, he learns about Classes and Objects. Afterwards, he learns harder stuff such as OOP, Exceptions, Threads, Files, etc. Once a user can learn those things, you can say that he should now be proficient in Java. Same goes for any other language. Also consider the case that besides learning syntax, language, etc, the user should also develop problem-solving skills too. 
#### 3. Is there a limit on how many times a student can take the quiz/lessons? Are retakes allowed? Would there be any point deductions?
* It should depend on the instructor. An instructor may allow retakes, take decisions on point deduction, etc. By default, you may allow three retakes with a 25% deduction each time. 
#### 4. What happens if a student doesn't finish yesterday’s work? Will it be added up to today’s work? If yes will there be any point deductions?
* Yes, due tasks should add today's work. But today's work should get the first priority. By that I mean, for example, there are 5 tasks today and 2 due tasks. In one tab, you should show today's 5 tasks and in another tab, 2 due tasks. On point deduction, it depends on the instructor. In case of due tasks, an instructor may have a 75% deduction, another instructor may have a 60% deduction. 
* If a student does not finish the assignment on the due date there should be point deductions(75%, 60%, etc up to the instructor). If an already due assignment does not finish before the weekly quiz, the student would automatically get zero on the assignment. One can take a quiz without submitting an assignment, in that case, the assignment would automatically get a zero.
#### 5. Another question related to our previous question, if a student has past due assignments from a day, two days, or more, would they be allowed to take the quiz on the 6th day? If yes, are they supposed to take the quiz before finishing their assignments?
* They are allowed but all assignments must be finished before taking a quiz. 
#### 6. Does the instructor have the ability to extend due dates? Are the due dates assigned by the instructor or they are generated automatically when a student signs in to the app for the first time? For example if student A downloads the app and signs up on Sunday, they start their 6 day training from then, or the instructor will say, you must finish the 6 day training by the end of some date?
* They are automatic. No extension of due dates. if student A downloads the app and signs up on Sunday, they start their 6-day training from then.
#### 7. Is any part of the daily lessons graded? Or is it all just for completion?
* Graded
#### 8. Are hints allowed in the daily lessons? Can students view the answer if they give up?
* Allowed. Yes. Grades should reduce based on hints are unlocked or not.
#### 9. Do all students need to belong to a class or can the app be used w/o an instructor?
* A student can start and end at his/her own convenience.
#### 10. Can students communicate with each other through the app? Can there be an option for a public profile where students can help each other?
* You can have a discussion board for each problem. Students can also create a post-specific(think about StackOverflow q&a style).
#### 11. Is the quiz timed? Are there any limits on the quiz? 
* Timed/not timed - both are okay.
#### 2. Should student accounts be timed out and required to log in again after a period of inactivity?
* You can have a 'remember me' option. If the user doesn't check out remember me, then log out after a certain period of inactivity.
#### 1. Should users be given a way to show their understanding of a language before starting a lessor, for example a short diagnostics quiz to gage where they stand and where they should start?
* You can have a starter diagnostics quiz. A good idea. But I would prefer everyone starts the lesson in the same way.
#### 2. Do you want some sort of website that goes with that app? 
* Not required.




### Build with:
* Android Studio

### Authors
* Vy Nguyen 
* Pedram M
* Nathaniel Ekanem
* Paul S
