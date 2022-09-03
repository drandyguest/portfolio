# Marking

All modules in Computing are marked by the Module Lead for the module. As such I set the assessments, marked the submissions and provided feedback to all the students on the modules I taught. We also have a moderation system where a second lecturer not involved with the running of the module moderates the assessment marking.  

## General Approach

My approach to assessment is to give students a general description of the task(s) required then a more detailed description of the steps involved. As part of the assessment brief I provide a marking scheme which breaks down how the marks for the assessment are awarded based on each task/step. Students should be able to use the marking scheme to identify which parts of the assessment require most effort.  

For marking I use an Excel spreadsheet that generates a sheet for each student. I use the sheet to enter marks based on the marking scheme (which is summarised on the sheet) and add comments by the marks to help the students understand the marks. At the bottom of the spreadsheet is a rubric that shows the students achievement at the broad task level for the assessment. When the marking is complete I run a macro that generates a pdf report for each student (it exports each students page as a pdf) and attach each report in Moodle so students have access to the feedback. I try to give feedback that is as clear an comprehensive as possible (Boud & Malloy 2013)  .

Over the degree programme the depth and detail of the assessment task description. In first year I try to be as specific as possible - "You should do this, then this, then this in task one, then these steps in task 2" - with a detailed breakdown of how many marks for each individual step. In second year I describe the tasks but give less detail on the steps involved. The marking scheme still contains a detailed breakdown but those steps aren't spelled out. In third year the assessment is intentionally very broad, the tasks are not spelled out other than in broadstrokes and the marking scheme is less detailed. I find this reflects well the progress the students should (and generally are making). It also works well for the third year modules as they are generally of the "make a game that does X" format and students like the freedom to interpret that and not be (too) proscribed by required tasks.  

## Plagiarism & Code

Teaching and assessing programming has a complex issue with plagiarism, specifically with the copying of code from sources on the internet. Sites like [Stack Overflow](https://stackoverflow.com/) exist to aid programmers in industry by sharing solutions to coding problems. This is invaluable in industry where the goal is to solve problems as efficiently as possible rather than coming up with a new solution (or worse still, the same solution). In teaching our students we want to prepare them for working in industry and sites like Stack Overflow are a tool that is used in industry. However we need to ensure our students do learn the material and can write code solutions themselves. This clash means we need to teach our students how to use such tools but ask them not to use them, particularly for assessments.  

In addition we find out students naturally work in small groups on the exercises we give them. This is, again, good, it reflects the realities of sofware development in industry. The industry practice of [Pair Programming](https://en.wikipedia.org/wiki/Pair_programming) is based on working in just this way. Students learn better working this way, stronger students improve through helping weaker students learn. Students of similar ability levels and figure out solutions between them. However this leads to a problem when it comes to code submitted by students for assessments. When two students work together to solve a programming solution their code will be very similar, so similar that it is difficult from the code alone to tell if they worked together or one student simply copied another.  

How, given both issues above, can we determine if code submitted by students for an assessment is their own code or plagiarised? There is no easy solution here. Turnitin does not work with code and there is no similar product for code. I use a couple of different techniques.  

To check if code has come from Stack Overflow (or somewhere similar) a simple Google search is used. I copy a line or two of code from the submission and paste it in to Google. If the code has been plagiarised from an online source it will usually be one of the first two or three results returned by Google. Thankfully students who resort to copying from online sources tend to be poor at disguising that they have done so.  

The second technique is simply to look out for similar code when marking the work. This is harder. While there are many ways to code a solution, our students have all been taught the same way and worked on the same exercises so there is often similarity at a high level. Usually though it is easy to distinguish different pieces of work on a line by line comparison. When code is still similar, at that line by line level, it can be difficult to distinguish between students who worked together and students who copied another's solution. Where a judgement can't be made based on knowledge of the students and code comparison we need to speak to the students, potentially holding a misconduct inquiry.  

This tends to be a first year issue, though it does happen occasionally in second year. Third year student work tends to be more individual and copying another student's work is seldom helpful so seldom occurs. 

## Third Year Assessment

The assessment of code in first and second year tends to be relatively easy. Each student is producing a solution to the same problem, the lecturer knows exactly what they are looking for and they are looking for the same thing in each assessment. In third year (for the modules I teach) each student is creating a game to demonstrated the concepts/techniques discussed in the module. Each submission is very different and it can be complicated to understand their submission and find the relevant content (a game can contain a lot of code!). I find using a demonstration session helps me immensely. I sit down with each student individually and ask them to demonstrate their game to me, highlighting the aspects they have implemented for the assessment. It makes assessing the work faster and easier for me and students like to know I've considered everything they consider important. It also gives them some direct feedback as we discuss the game.  

## Anonymous Marking

We have an issue where the University wants assessments to be anonymously marked so submissions through Moodle are anonymised. Our students submit their code through our GitLab server which is not anonymised. So the best case is we get anonymised reports/essays that contain a link to GitLab which identifies the student. The worst case is the student doesn't include the link in the report and doesn't put their name in the report, and we have no idea if they submitted code until the submission is de-anonymised and we aren't supposed to do that till marking is complete.  


## Evidence

* [Assessment Brief Example](../evidence/AssessmentBriefExample.docx)
* [Marking Spreadsheet Example (anonymised)](../evidence/MarksExample.xlsm)
* [Feedback Example (anonymised)](../evidence/FeedbackExample.pdf)

## References

* Boud, David; Molloy, Elizabeth, *Feedback in higher and professional education : understanding it and doing it well* London, New York: Routledge 2013
* Boud, David; Molloy, Elizabeth, *Rethinking models of feedback for learning: the challenge of design* Assessment & Evaluation in Higher Education pages 698-712, Routledge 2013
