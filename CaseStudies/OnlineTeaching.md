# Online Teaching

In response to the Covid pandemic lockdown restrictions we undertook to move as much of our teaching online as possible. There were issues we had to deal with to make this happen. This page discusses the issues and the lessons and practices we are taking forward to the future.  

## Lectures

Lectures were the easiest part of our teaching to take online. Lectures were given through MS Teams with lecture slides shared through the Teams application. This also made it easy to video record the lectures and make them available through Moodle afterwards so students could review the lectures as and when they want. This worked well and students really like being able to rewatch the lectures (usually running the lectures at high speed it seems!).  

## Programming Environment

The biggest issue considered while planning the module was providing the students with a consistant programming environment they could use for coding. When teaching in person, on campus, our students use our computers which we ensure are setup with the software they need. With students working from home we have no control over their home computers or the software they have installed. They use different platforms (Windows, Linux, Mac), some don't have computers and have to rely on tablets or smart phones or take the risk of coming on to campus to use our labs. We can recommend software to them but cannot install it for them. We'd also run in to issues where we'd have to recommend different software for different platforms which could raise issues in lab sessions. Additionally, we know from experience that some students require assistance setting up their home machines/laptops. This is hard to provide when it is only a few students and we could speak to them face to face, online for a larger number of students would be far too impractible.  

The solution I settled on was Replit (https://replit.com/)[https://replit.com/]. Replit is an online, web-browser based programming environment. All that a student requires is a web-browser, the code is compiled and executed on the web server with the results displayed to the screens. Replit supports a large number of programming languages including the Java and C I required for my modules. Replit also has strong GitHub integration allowing applications to be stored and shared with full version control. Replit also features live code sharing/editing where two people can access the same code at the same time and see the changes the other makes. This is invaluable as a lecturer trying to help students in programming labs online. The ability to highlight a line of code, make changes, demonstrate techniques where the student can see what is happening is essential and happens naturally when a lecturer sits down with a student in class. Replicating that with online teaching is a challenge without these features.  

Code from Replit can also be embedded in webpages, allowing for live code demonstrations with accompanying text descriptions. To take advantage of this I began using a website to host module material (in addition to Moodle).

## Lecturer/Student Interaction

The interaction between lecturers and students is very important in the teaching of programming. Understanding code and fixing problems with code is a complex process. It isn't unusual to have to explain the same concept in a number of different ways before different students all understnad the concept. With face to face teaching this happens naturally as the lecturer talks to individual students in the lab session. Students are generally less willing to ask questions, especially the "I don't understand" questions in a group chat with the entire class. This was a big issue early on in the lockdown but became easier to manage when MS Teams introduced breakout meetings, meetings within meetings in which only a few of those in the whole meeting were involved.  

## Student Group Working

Working in groups is an essential skill in all areas of computing so we require a way for students to work together. Additionally in face to face programming labs students tend to work together in small groups of two to three on exercises and assessments. This is beneficial in a number of ways, different perspectives help understand coding concepts, more adept students can help less adept students (and in the process learn more themselves) and it mirrors the industry practice of [pair programming](https://en.wikipedia.org/wiki/Pair_programming).  

Once Microsoft introduced breakout meetings to MS Teams we were able to replicate this by automatically assigning students to breakout meetings with four or five students in them. I made these groups larger than they tend to be face to face because many students are reluctant to speak up in Teams, even in smaller groups (and because some are there in name only). This wasn't as good as the face to face equivalent but was better than nothing and the students who got involved benefitted from it.  

## Module Website

This wasn't necessitated by the move to online teaching but as a result of the decision to use Replit for coding it was an approach that allowed me to take advantage of some of Replit's other features. Moodle is a fine electronic blackboard but it isn't suited to the approach I wanted to take, especially with the programming modules.  

I used [Netlify](https://www.netlify.com/) to host webpages stored as [Github](https://github.com/) [Pages](https://pages.github.com/) and created using the [Jekyll Doc Theme](https://jekyllrb.com/docs/themes/).  

This gave me a number of advantages  

* Easy creation and modification of pages where uploading them to Github causes Netlify to automatically process and update the website
* Embedding code from Replit directly in to the webpages, allowing for live code demos.
* Examples applications, exercises and assessments could be easily linked making it easier for students to import applications directly in to their Replit accounts.
* Instructions/briefs can be created using the same techniques and displayed as formatted instructions in Replit.

It also allowed me to give more structure/organisation to the course material than a series of lecture slide sets. In my experience it was easier to find specific content with this approach than trying to search through separate presentation files. Students seemed to find this easier too.  

## Moving Forward

Post-lockdown we have returned to face to face teaching. It is worth reflecting on what we've learned from online teaching and identifying practices that should be continued.  

### Lecture Video Recording

Video recordings of lectures are very popular with students. They like being able to rewatch the lectures in their own time at their own speed. The techniques used to record the online lectures can be easily used to record live face to face lectures. We have continued doing this.  

### Module Website

I'm in two minds over the use of a website to host module material. The reason I began using it (integration with Replit) is no longer applicable, we are no longer using Replit. I prefer preparing material for the website than using Moodle, it is faster, easier and more intuitive to me. Still the material needs to be on Moodle and it is the University's electronic blackboard system. My intention is to return to Moodle for the new re-validated modules, phasing out the websites as the old modules are retired.