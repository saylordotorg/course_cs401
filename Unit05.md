---
layout: default
title: "CS401: Operating Systems"
course_description: "An examination of the evolution of operating systems and design, focusing on hardware/software evolution leading to contemporary operating systems, basic operating systems concepts, methods of operating systems design and construction, algorithms for CPU scheduling, memory and general resource allocation, and process coordination and management."
next: ../Unit06
previous: ../Unit04
---
**Unit 5: Deadlock** <span id="5"></span> 
**Deadlock is a paralyzing process state resulting from improper CPU
scheduling, process management, and synchronization management. *
*During this time, processes are blocked as they compete for system
resources or only communicate with each other.   Although* *it cannot be
guaranteed that deadlock* *may be avoided 100% of the time,* *it is
important to know how to avoid the deadlocked state and how to recover
from it once it has been achieved.  We will build upon the previous two*
*units of CPU Scheduling and Processes and Threads* *when discussing
Deadlock. * *First, we will discuss what deadlock is* *by establishing a
working definition and the conditions in which it presents itself. *
*Then, we will talk about how to prevent and avoid deadlock.  Finally,
we will* *learn about deadlock detection, as well as methods for
recovering from a deadlocked state.**

**Unit 5 Time Advisory**  
This unit will take you approximately 9.5 hours to complete.  
  
 <span dir="LTR">☐    Unit 5 Introduction: 2 hours</span>  
  
 <span dir="LTR">☐    Subunit 5.1: 1.5 hours</span>  
  
 <span dir="LTR">☐    Subunit 5.2: 2.5 hour</span>  
  
 ☐    Subunit 5.3: 3.5 hour

**Unit5 Learning Outcomes**  
Upon successful completion of this unit, the student will be able to:  
  
-   <span dir="LTR">Explain what deadlock is in relation to operating
    systems.</span>
-   <span dir="LTR">Discuss deadlock prevention, avoidance, and the
    differences between each.</span>
-   Describe deadlock detection and recovery.

-   **Lecture: YouTube: UC Berkeley: Professor John Kubiatowicz’s
    “Lecture 9: Cooperating Processes and Deadlock”**
    Link: YouTube: UC Berkeley: Professor John Kubiatowicz’s “[Lecture
    9: Cooperating Processes and
    Deadlock](http://www.youtube.com/watch?v=CoKFi293eAs&feature=relmfu)”
    (YouTube)  
        
     Instructions: Watch the video starting at 49 minutes.  Please note
    that this video applies to all of Unit 5.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above

-   **Lecture: YouTube: UC Berkeley: Professor John Kubiatowicz’s
    “Lecture 10: Deadlock (Continued) and Thread Scheduling”**
    Link: YouTube: UC Berkeley: Professor John Kubiatowicz’s “[Lecture
    10: Deadlock (Continued) and Thread
    Scheduling](http://www.youtube.com/watch?v=fl7BdyJQ814&feature=relmfu)”
    (YouTube)  
      
     Instructions: Watch the first 54 minutes of the video lecture. 
    Please note that this video applies to all of Unit 5.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above

**5.1 Definition** <span id="5.1"></span> 
-   **Reading: Rensselaer Polytechnic Institute: Professor Robert P.
    Ingalls’ “CSCL4210 Operating Systems: Deadlock”**
    Link: Rensselaer Polytechnic Institute: Professor Robert P. Ingalls’
    “[CSCL4210 Operating Systems:
    Deadlock](http://www.cs.rpi.edu/academics/courses/fall04/os/c10/index.html)”
    (HTML)  
                  
     Instructions: Read the entire set of lecture notes.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**5.1.1 Terminology** <span id="5.1.1"></span> 
*Note: This topic is covered by the resource under the Unit 5
introduction and subunit 5.1*

**5.1.2 Conditions** <span id="5.1.2"></span> 
**5.1.2.1 Mutual Exclusion** <span id="5.1.2.1"></span> 
*Note: This topic is covered by the resource under the Unit 5
introduction and subunit 5.1.*

**5.1.2.2 Non-preemption** <span id="5.1.2.2"></span> 
*Note: This topic is covered by the resource under the Unit 5
introduction and subunit 5.1.*

**5.1.2.3 Hold/Wait** <span id="5.1.2.3"></span> 
*Note: This topic is covered by the resource under the Unit 5
introduction and subunit 5.1.*

**5.1.2.4 Cycles** <span id="5.1.2.4"></span> 
*Note: This topic is covered by the resource under the Unit 5
introduction and subunit 5.1.*

**5.2 Deadlock Prevention and Avoidance** <span id="5.2"></span> 
-   **Reading: Johns Hopkins University’s Department of Computer
    Science: Professor Yair Amir’s “Operating Systems”: “Slides 10-16”
    Lecture**
    Link: Johns Hopkins University’s Department of Computer Science:
    Professor Yair Amir’s [“Operating Systems”: “Slides
    10-16”](http://www.cs.jhu.edu/~yairamir/cs418/os4/sld010.htm)
    (HTML)  
      
     Instructions: Click on the link to Professor Amir’s lecture above,
    and read only through slides 10-16 at this time.  Scroll through
    each slide by using the single arrow key on the webpage.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

-   **Assessment: The Saylor Foundation’s “Banker’s Algorithm Problem
    Set”**
    Link: The Saylor Foundation’s “[Banker’s Algorithm Problem
    Set](http://www.saylor.org/site/wp-content/uploads/2011/11/CS401-Bankers-Algorithm-Exercise-FINAL.pdf)”
    (PDF)  
        
     Instructions: Read through the review of the Banker’s Algorithm if
    you need to review the way that the algorithm works.  Complete both
    exercises and check your answers against the answer
    key [here](http://www.saylor.org/site/wp-content/uploads/2011/11/CS401-Bankers-Algorithm-Exercises-Solutions-FINAL.pdf)
    (PDF).

**5.3 Deadlock Detection and Recovery** <span id="5.3"></span> 
-   **Reading: Florida State University: Andy Wang’s “Lecture 9
    Deadlock”**
    Link: Florida State University: Andy Wang’s “[Lecture 9
    Deadlock](http://www.cs.fsu.edu/~awang/courses/cs111/)” (.doc)  
        
     Instructions: Scroll down to Lecture 9 under “Handouts,” and click
    on the Word 2000 link after Deadlock to open the file.  Please read
    the entire document (5 pages).  
      
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above

-   **Interactive Lab: The Saylor Foundation’s “Deadlock Simulation
    Lab”**
    Link: The Saylor Foundation’s “[Deadlock Simulation
    Lab](http://www.saylor.org/site/wp-content/uploads/2011/11/CS401-Deadlock_Simulation_Lab-FINAL.pdf)”
    (PDF)  
        
     Instructions: Complete the entire lab. All instructions are
    included for downloading and running the simulator.  Compare the
    results of your experiments to the answer
    key [here](http://www.saylor.org/site/wp-content/uploads/2011/11/CS401-Deadlock-Simulation-Lab-Solutions-FINAL.pdf)
    (PDF).


