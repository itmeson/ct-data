Debrief  
#######

:date: 2018-12-07
:summary: A place to process what's happening in the class and how to improve it
:category: overview
:tags: debrief, meta, teacheronly


======
Week 1
======


======
Week 2
======

 1. A couple of students still have significant installation issues.  Getting this part of the process handled ahead of time in the 9th grade image will be critical, which means tooling decisions will need to be made a full year out of the required 10th grade core course.
 2. This particular setup has a *lot* of cognitive load.  Finding ways to reduce that will be critical, especially in the required context where learning support needs will be significant. 
 
   * Schoology to course website
   * Course  website to weekly and project materials
   * Course website links to github class invitation
   * Github account setup, login, and verification
   * Git client setup, login, and verification
   * Git client to pull project repository
   * Anaconda navigator to jupyter lab to navigate to project repository
   * jupyter lab manipulate files in project repository

   	a. Where is the working directory?
        b. What if I've got another jupyter instance running?
        c. What if I open the same file in more than one instance or more than one tab?
        d. Which version am I editing?
        e. Markdown vs. code cells
        f. Cells that have been run vs. cells that have not been run
        g. Order of execution
        h. Restarting the kernel or for other reasons variables going out of memory
        i. Saving files

   * Python overhead

        a. module imports
        b. inscrutable code words in the boilerplate
        c. Accessing data
        d. Manipulating data
        e. Generic details vs. specific details
        f. notional machine

   * Git client to stage, commit, and push

 3. A key thing is to find ways to short circuit this load
 4. I need to make sure they whiteboard, pseudocode, human-instruction for the actual tasks.  It seems to be quite effective to talk to them about "How would you do that task, if you were to do it yourself?  Okay, now translate, as specifically as you can, the instructions to accomplish that.  Okay, now add even more detail because you can't assume that the reader (the interpreter) will be able to read between the lines."  This is one of the cores of thinking computationally, and I haven't really forced it at all.  Not doing this turns the class into a code deciphering course rather than a liberal studies course.
 5. Classrooom management.  The big room is hard to get around in, and the experienced kids can very easily dominate the room.  Need to do some work on them and about them.  Look at what HMC did with intro CS.
 6. I do think the additional structure this time is a really good move.  They will definitely get more out of the course this time, but I've lost a little of the free-wheeling culture by doing so -- need to get back a little more of the digital humanities feel.
 7. I find it very hard to find good videos and enrichments -- they take too long to watch and there are too many potential issues with any particular resource.  Need help curating content.



======
Week 3
======

 1. So this morning I (re)discovered Runestone Interactive and their hosted textbook platform.  It's amazing.  And probably what I should be using for the CT10 course.  I can have a text, assignments, quizzes, checkpoints, and a codeLens system all in one place.  You can even have audio commentary play as the code runs on a line-by-line basis.  I think the available textbooks would have to be remixed significantly for our purposes, though -- the short trimester, low contact time, no homework, and range of students make all the ones there problematic.  I'm going to show it to the deans and see about getting support to work on a text for it.

 2. The flowcharting assignment was tough for them -- they just think of "add all the items in a list" as an atomic operation.  But I still think it was a good thing to do.  Perhaps I need to adopt a style convention for them to teach them.


======
Week 4
======

 1. This was the week before the winter break, and it was dominated by getting people caught up on project 4 and getting back some of the "seeing cool things others have done" feel

 2. We took a look at the Information is Beautiful awards site and I asked them to write about one of the award winning visualization projects.  Most of them enjoyed this project a lot and they got something out of seeing what is possible.  However, there wasn't a lot of understanding of how the data was acquired, processed, or displayed, and not a lot of connection/transfer to what we have been doing with pandas.

======
Week 5
======

 1. This was the week after the winter break, and there was a lot of getting people reminded how to do things, finishing project 4 (!) and watching some videos

 2. It's hard to find videos that are completely un-problematic.  


======
Week 6
======

 1. I punted on Monday with some more videos of artists and historians doing data visualization

 2. Started project 5, which is intended to get a little more concrete about functions by backing way up, and then to write a function to access data from a twitter data set.

   * I definitely need to walk them through code more often.  The codelens tool and pythontutor are very helpful, but I find it difficult in the big classto feel good about doing demos up front.  It is probably really worth it to get the screencast setup so they can actually *see* what I am doing, and I need to commit to doing the up-front stuff even though it doesn't feel comfortable to me
   * I need more things to have them do, so I can progressively de-scaffold more.  I want them to at least feel that they are doing a real thing, and I need to strip away the scaffold.  What I did was to progressively increase the complexity of the fully-worked examples, then remove the scaffold entirely for their actual tasks.  I think it needs to be the other way around.  Start with nearly the full complexity, full scaffolded.  Then strip away the scaffold as they complete tasks.
   
 3. Is it okay to go backward even more now?  Now that they've gotten going on this project?  

 4. The advanced kids are done with it already, and didn't need the practice.  Everyone else is still mystified by where to start, and they still have a distinct feeling that the code is a magic word incantation.  I think that is because they don't have a sense of what a variable is, so they think the variable names are part of the incantation.  That makes it just about impossible to understand what is happening when you call a function, pass a main-level scoped variable by value to the function, instantiate the function-scoped variable to hold that value, perform operations on it, then return by value back to the main-scope.

 5. I ended up solving it for several of them.  Not the right answer.



   
