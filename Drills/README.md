# CS 210 Drill Writeups

credits: Russ Lewis wrote most of the original drills for 127A&B in CloudCoder, 
         Michelle Strout converted some into a github and gradescope organization,
         Michelle Strout and Allison Obourn developed drills to support the PAs in 210

This file is online at github 
https://github.com/UACS210Fall2018/PA-Drill-Section-Writeups/new/master/Drills.

## Drills for Fall 2018

Computer Science is the art of solving problems with computers.  The main mechanism
we use to solve problems with a computer is programming.  This semester, you will be 
learning and practicing the skill of programming in Java.  For the last couple of 
decades, Java has been the first or second most popular programming language 
(https://fossbytes.com/most-popular-programming-languages/).

Programming is a skill that like all other skills require practice to learn and improve.  
In CS 210 this Fall 2018, you will be doing programming drills that are due on Fridays.
These drills provide you an opportunity to learn and practice the basic syntax and semantics
of Java and how to use Java to solve and test solutions for the kinds of problems
that will appear in the larger programming assignments.

### Getting Started with Drills

Let's start by having you create your own private drill repository on github,
which you will be using all semester.  No one but you and the CS 210 staff
can see the code in your private drill repository.

 * (ONE TIME SETUP)Fill out the google form at ([FIXME]) with your github email address.  
   This needs to be a .edu email address that is associated with the free github account
   you are going to use for this course.

 * (ONE TIME SETUP) Each student will create their own drill repository by 
   accepting the drill assignment at https://classroom.github.com/a/dzc3_cjr.
   ALL of your drills should be committed and pushed to your drill github repository to 
   enable the CS 210 staff to help you with any questions or issues you are 
   having remotely.
   
 * (ONE TIME SETUP) In Eclipse (see [FIXME] to set up Eclipse), import the drill repository.
   In Eclipse: File --> Import --> Git,Projects from Git, Next, Clone URI, Provide the
   link of the github repository that was created for you, and then click Finish.
   
### Running a Drill within Eclipse

In the src/edu/uacs210fall2018/drill##/ directories, there will be
a Drill##.java file (and later other files) that you will be editing.
   
Give it a try!  There is a src/edu/uacs210fall2018/drill00/ 
subdirectory with the files Drill00TestClass.java and Drill00.java.
   
     * In the Eclipse Package Explorer, right click on the 
       Drill00TestClass.java and click Run As --> JUnit Test.  
       All of the test cases should work with no Failures.
       
     * Go to Gradescope and submit the Drill00.java file to
       the Drill00 Assignment.  Note that the autograder is running
       the same tests that are in Drill00TestClass.java and it
       will tell you your grade for drill00.  Drill00 has already been
       implemented for you so we can illustrate how drills work.
LEFTOFF 
     * Back in Eclipse, uncomment the implementations of the drill solutions 
       in the DrillExample.java file.  Try running the JUnit tests again.
       All the tests should now pass.  DO NOT FORGET to do a commit
       and a push to your drill github repository to capture the changes
       you have made (see instructions for working with github repositories FIXME).
     

### Doing Drill01 through Drill09

Doing a drill consists of (1) downloading the files for the drill,
(2) adding those files to your drill repository, (3) writing code
to solve one drill problem at a time, (3) test each drill problem
solution in Eclipse using JUnit, and (4) submitting the solution
to the appropriate drill assignment in Gradescope.

#### (1) Downloading the files for the drill

For each drill assignment, there is a src/edu/uacs210fall2018/drill##/
subdirectory in your drill github repository.  Your drill github repository
was initially copied from the drills public repository
https://github.com/UACS210Fall2018/Drills-Public.
As the semester progresses, we will be posting the Drill##TestClass.java,
Drill##.java, and any other needed files in the drills public repository.

You just put the files for Drill01 into your repository
   on your machine and if you did a commit and push a copy is also in your
   repository on github.
the Drill##TestClass.java,



Give it a try!  In the Eclipse Package Explorer, right click
   on the CS210-Drills/src/edu/uacs210fall2018/drill01/Drill01TestClass.java 
   file and select "Run As" --> "JUnit Test".
   One of the test cases will pass, but the rest are broken right now.
   Your job is to fix them by editing the corresponding Drill01.java file.
   The drill is complete when all of the test cases pass.
 



The purpose of this exercise is show you how drills will work this semester.




You will then import the drill repository into Eclipse.  [FIXME: more needed]



Running the test cases in Eclipse.  [FIXME]  Run the test cases right
away.  Some might actually pass, but most should fail initially.

Work on one method implementation at a time.
For the drills, you will be given simple Java methods and (and later classes) 
to implement.  A method is a small block of code that takes some inputs and 
returns an output - a lot like a function from Python.  Your job is to write 
a small amount of Java code that will produce the correct result for any
valid inputs.

Submit to gradescope as many times as you would like.  Gradescope
will autograde your drill and tell you your grade for each drill.
Each drill will indicate at the top of the drill##-README.md file
exactly what file(s) need to be submitted to gradescope for that
drill.  There are no hidden test cases for drills.  You can test
all of your drill method implementations in Eclipse before uploading
your file(s) to Gradescope.  Feel free to submit partially done drills
to check on your progress (and provide yourself at least some partial
credit if you forget to finish the drill).


Each drill includes a description page, see 
src/edu/uacs210fall2018/drill01/drill01-README.md for an example.
The README file will describe the purpose of the exercise, what the 
inputs are, and what the return value ought to be.  You will write your
code in the Drill##.java file.  Each exercise comes with "skeleton code" 
- that is, the basic mechanics of the method.  Your job is to fill in 
the part in the middle marked with a TODO.

NOTE: The drills are meant to take less than one hour to 
complete each week.  If you get stuck, then post a question on piazza
right away.  You can post a question anonymously to your classmates
or privately the CS 210 instructors and section leaders.