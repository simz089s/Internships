# Rio Tinto Alcan -- Summer 2018

* Description of the project(s) you worked on
* The amount/quality of training and supervision you received
* Any challenges you faced and how you dealt with them
* Describe 1 major accomplishment you attained during the work experience
* Any "surprises" you encountered: something you did not anticipate before starting work
* Some benefits of your experience: what will you take away from this work experience?
* What one piece of advice would you give to a student starting an internship?

## Summary

In the summer of 2018 I have worked as an intern for 4 months -- May through August -- at Rio Tinto Alcan in Jonquière, Quebec, Canada.
I was in the IT department and was tasked with finding solutions to IT-related problems the factory had and meeting demands of the clients, which were factory workers such as chemical and process engineers, as well as operators.
There would be weekly meetings for follow-ups, new tasks or projects and feedback.
Technologies that were mainly touched upon were OSIsoft's PI System suite and Visual Basic.
I also had to gather some understanding of the aluminium and carbon anodes creation and refinement processes.

Projects included:
connecting a GRADEX 2000 Particle Size Analyzers machine's computer to the Rio Tinto Alcan network, and automating the data analysis process by making it automatically send its output from its local database to the PI system, by passing through a Laboratory Information Management System (LIMS);
creating a PI ProcessBook interface that showed real-time temperatures, pressures and other data of sets of furnaces for operators;
adding features to their end-of-month report creation form;
using a program to enter old data into the PI system;
creating interfaces to allow operators to enter manually gathered data into the PI system;
adding features to an Excel file that extracted data from the PI system.

I have learned a lot about working with integrated proprietary systems and making different systems communicate with each others, both in terms of software and having to bridge the IT team and industrial team. I have also had to understand preexisting systems, instead of just, for example, building programs from scratch, which can be a whole different matter.
I have also learned a lot about the PI system.

They had a very hands-off approach and I was left with quite some freedom.
I was the one who had to ask help when needed, but I was certainly still guided a lot, and they would always accept.
But all of the main work was up to me.
I had to ensure proper progress of the projects, organize meetings, research technologies I did not understand well, find out about which person to contact for what, ask the client about their needs and implement the solutions almost all by myself.

At the beginning, it was difficult and slow because I had to learn about all the technologies involved, at least superficially, and had to complete many trainings.
But as I worked through them it would get better and my understanding would increase greatly.

The biggest challenge I had to face was the GRADEX project.
This project lasted the whole internship.  
First, connecting the computer to the network was much harder than expected as I had to go through many support tickets and had to wait for authorization for many things.
I had to ask the right person and to make sure things progressed smoothly by doing follow-ups.
Same things when I had to backup the computer before updating it when I finally managed to connect it.  
Second was making the data go from the GRADEX database to PI through their LIMS.
Three completely different systems had to be interfaced together in order to make everything work.
Everything was based on something that was already done for another factory, but their system was just different enough that I had to adapt many, many things.
Their databases had the same structure but the data inside was quite different, requiring me to reverse-engineer what they had done.
Similarly for the LIMS, it had a custom program to extract the data from the GRADEX.
It was written in a relatively obscure, outdated and badly documented proprietary programming language of the LIMS.
It was also very specific to the other factory and extremely old, so I had to reverse-engineer a huge part of the program and research what I could about it.
The main difficulty was the lack of good documentation, and the people who understood the program extensively were long gone from the company.
I had to seek people who had knowledge about their own side of things and whatever documentation I could find in order to put everything together, like a puzzle.
I also ended writing a program to imitate and simulate what it was doing using a programming language I was familiar with to understand what was happening under the hood.

The second biggest challenge was creating the PI ProcessBook interface for the furnace operators.
ProcessBook is quite old, and was very limited in what it could do, despite being good at it.
The project I was tasked with here involved creating a dynamic page could show real-time movement of the furnace "fire" (as they call it).
ProcessBook was designed to make static pages, where values shown would always be from the same source, and there would be no complex animation at all in the pages.
I had to come up with workarounds and use other technologies to help me meet the client's demands while staying within the limitations of the software.

In the end, I managed to complete most of the tasks, with the only ones left being these two.
It was frustrating as they seemed like relatively simple projects, but even my supervisor and other workers related to it were surprised by the unexpected difficulties that kept showing up.
But a large part of the work was done.
This actually also taught me to prepare documentation properly and meetings in order to transfer my work and knowledge that I had accumulated, as to allow the team to continue what I had started as smoothly as possible once I am gone.

Ultimately, I think what I learned the most in this internship was not software related.
I have learned much more about myself, how I deal with real world problems, how I work with many people with diverse background knowledge and being a "bridge", how I deal with their different schedules, how I manage my own time and projects, and how much I can commit myself to these projects and ensure their proper progress and completion.

The main feedback I received was that I was a little too reserved.
I agree completely, I have always been a shy person and an introvert and when I was writing my documentation and reports at the end of the internship, I realized just how much more I could have done if I had pushed myself to be more open, to talk more to other workers and supervisors for ensuring the advancement of my own projects, and participating even more in the meetings I had than I did.  
Overall I was told it was a good experience for them, and I think it was a really good one for me as I have learned so much about technologies and myself.
I now have more confidence and feel like I can do better in the future.

One thing that surprised me a lot was the atmosphere.
I expected it to be much more stressful and "strict" than it was, but in fact everyone was very understanding and relaxed, in some way.
They were all very helpful towards me and did not pressure me too much if I was having difficulties on a particular case, instead pointing me to some possible paths of solutions and being patient.

If I had an advice to give to anyone starting an internship, of even their first job, it would be to not put yourself down just because you are new.
What I have heard and seen from other employers and interns or myself, whether in real life or online, was that many newcomers will often forget that they are also part of the team and the company, because they are still new and an "outsider".
While it is true people with more seniority will have more knowledge and experience, we should not be afraid of putting down our foot when necessary and affirming our position as an equal, when our job demands it.
Everyone has a job, and to do ours we cannot always wait after everyone, we will all be busy.
Sometimes we might feel like we are bothering a colleague or our manager or supervisor, sometimes we might disagree on certain things, even with your client, but it is normal and sometimes necessary to move forward.
As my supervisor said, and I paraphrase:

> "Let them be the one to tell you 'no'. Don't say 'no' to yourself before even talking to them. If you are always scared of bothering someone even when you really need to, you will never progress. Whether they want to prioritize you or not will be their decision. Like this, you did your job, and if they don't at least try to meet you in the middle, then it will be on them. If you ever have problems like these, people in my position are the ones you should go see, and we will take care of it."

In conclusion, I think internships are very important and a huge boost to our confidence and experience, and I hope I get more opportunities to work with people like I have.
It is as much about growing our technical knowledge than it is about improving our mindset.