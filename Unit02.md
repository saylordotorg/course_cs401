---
layout: default
title: "CS401: Operating Systems"
course_description: "An examination of the evolution of operating systems and design, focusing on hardware/software evolution leading to contemporary operating systems, basic operating systems concepts, methods of operating systems design and construction, algorithms for CPU scheduling, memory and general resource allocation, and process coordination and management."
next: ../Unit03
previous: ../Unit01
---
**Unit 2: Processes and Threads** <span id="2"></span> 
**We will discuss two central building blocks of modern Operating
Systems:  Processes and Threads.  Processes (instances of a running
computer program) and threads (a specific task running within a program)
are integral to the understanding of how an OS executes a program and
the communication of information between each of the computer’s
architectural layers. * *We will start with an overview of each concept,
including definitions, uses, and types.  We will then discuss the
commonalities and differences between processes and threads.  We will
conclude this* *unit with a discussion on Context Switches and the
important role they play in CPU scheduling, which will be discussed more
in depth in Unit 4.**

**Unit 2 Time Advisory**  
This unit will take you approximately 10 hours to complete.  
  
 <span dir="LTR">☐    Unit 2 Lecture: 1.5 hours</span>  
  
 <span dir="LTR">☐    Subunit 2.1: 0.5 hour</span>  
  
 <span dir="LTR">☐    Subunit 2.2: 2 hours</span>  
  
 <span dir="LTR">☐    Subunit 2.3: 4 hours</span>
  
 <span dir="LTR">☐    Introduction: 3 hours</span>  
  
 <span dir="LTR">☐    Subunit 2.3.3: 1 hour</span>

  
 ☐    Subunit 2.4: 3 hours

**Unit2 Learning Outcomes**  
Upon successful completion of this unit, the student will be able to:
-   Discuss the importance and use of threads and processes in an
    operating system.
-   Describe concurrency.
-   Explain the difference between a thread and a process.
-   Discuss context switching and how it is used in an operating system.

-   **Lecture: YouTube: UC Berkeley: Professor John Kubiatowicz’s
    “Lecture 3: Concurrency: Processes, Threads, and Address Spaces”**
    Link: YouTube: UC Berkeley: Professor John Kubiatowicz’s “[Lecture
    3: Concurrency: Processes, Threads, and Address
    Spaces](http://www.youtube.com/watch?v=1I8Rg7065PE&feature=relmfu)”
    (YouTube)  
        
     Instructions: Watch the entire video (about 1 hour and 24
    minutes).  This video will be an introduction to Unit 2 and will
    touch on all topics outlined in this unit.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above

**2.1 Concurrency** <span id="2.1"></span> 
-   **Reading: Northwestern University: Professor Peter A. Dinda’s
    “Concurrency Lecture”**
    Link: Northwestern University: Professor Peter A. Dinda’s
    “[Concurrency
    Lecture](http://www.cs.northwestern.edu/~pdinda/ics-f09/)” (PDF)  
        
     Instructions: Scroll down the webpage to the “Important Hand-Outs”
    section, and click on the PDF link after Concurrency to open the
    file.  Please read the entire PDF document (4 pages).  This reading
    also applies to subunits 2.1.1 and 2.1.2.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above

**2.1.1 Definition** <span id="2.1.1"></span> 
*Note: This topic is covered by the reading underneath subunit 2.1.*

**2.1.2 How Concurrency Is Used within an OS** <span id="2.1.2"></span> 
*Note: This topic is covered by the reading underneath subunit 2.1*

**2.2 Processes** <span id="2.2"></span> 
-   **Reading: National Program on Technology Enhanced Learning: P.C.P
    Bhat’s “Module 3: Processes and Process Management”**
    Link: National Program on Technology Enhanced Learning: P.C.P Bhat’s
    [“Module 3: Processes and Process
    Management”](http://nptel.iitm.ac.in/courses/Webcourse-contents/IISc-BANG/Operating%20Systems/pdf/Lecture_Notes/Mod%203_LN.pdf)  
        
     Instructions: Read these lecture notes.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

-   **Lecture: Portland State University: Professor Jonathan Walpole’s
    “The Process Concept”**
    Link: Portland State University: Professor Jonathan Walpole’s “[The
    Process
    Concept](http://web.cecs.pdx.edu/~walpole/class/cs333/spring2007/home.html)”
    (PDF or PowerPoint)  
        
     Instructions: Scroll down to the Schedule and Syllabus section. 
    Click on the PDF link next to Class 2.  Read the entire set of
    slides (49 pages). This lecture also applies to the topics outlined
    in subunits 2.2.1-2.2.4.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

-   **Lecture: YouTube: International Technological University: Dr.
    Barbara Hecker’s “CEN 959: Principles of Operating Systems Video
    Lecture 4”**
    Link: YouTube: International Technological University: Dr. Barbara
    Hecker’s [“CEN 959: Principles of Operating Systems Video Lecture
    4”](http://www.youtube.com/watch?v=mwecn6UIzqc) (YouTube)  
        
     Instructions: Please watch the entire video (1:28:46).  
      
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**2.2.1 Definition** <span id="2.2.1"></span> 
*Note: This topic is covered by the lectures below subunit 2.2.*

**2.2.2 Difference between a “Process” and a “Program”** <span
id="2.2.2"></span> 
*Note: This topic is covered by the lectures below subunit 2.2.*

**2.2.3 What Is Included in a Process?** <span id="2.2.3"></span> 
*Note: This topic is covered by the lectures below subunit 2.2.*

**2.2.4 Process Operation** <span id="2.2.4"></span> 
*Note: This topic is covered by the lectures below subunit 2.2*

**2.3 Threads** <span id="2.3"></span> 
-   **Lecture: University of California at Santa Barbara: Rich Wolksi
    and Jame’s Plank’s “CS170 Lecture Notes: A Brief Introduction to
    Threads”**
    Link: University of California at Santa Barbara: Rich Wolksi and
    Jame’s Plank’s [“CS170 Lecture Notes: A Brief Introduction to
    Threads”](http://www.cs.ucsb.edu/~rich/class/cs170/notes/IntroThreads/) (HTML)  
      
     Instructions: Please read the entire page.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

-   **Lecture: Portland State University: Professor Jonathan Walpole’s
    “Threads and Concurrency”**
    Link: Portland State University: Professor Jonathan Walpole’s
    “[Threads and
    Concurrency](http://web.cecs.pdx.edu/~walpole/class/cs333/spring2007/home.html)”
    (PDF or PowerPoint)  
        
     Instructions: Scroll down to the “Schedule & Syllabus” section.  In
    the Class 3 row, please click on the PDF link to download the file. 
    Read the entire set of slides (79 pages).  This lecture also applies
    to the topics outlined in subunits 2.3.1-2.3.3 and any inclusive
    subunits.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above

-   **Lecture: YouTube: International Technological University: Dr.
    Barbara Hecker’s “CEN 959: Principles of Operating Systems Video
    Lecture 5”**
    Link: YouTube: International Technological University: Dr. Barbara
    Hecker’s [“CEN 959: Principles of Operating Systems Video Lecture
    5”](http://www.youtube.com/watch?v=trQAn9J0Q4E) (YouTube)  
        
     Instructions: Please watch the entire video (1:03:21).  
      
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**2.3.1 Definition** <span id="2.3.1"></span> 
*Note: This topic is covered by the lectures below subunit 2.3.*

**2.3.2 Comparison to Processes** <span id="2.3.2"></span> 
*Note: This topic is covered by the lectures below subunit 2.3*

**2.3.3 Types** <span id="2.3.3"></span> 
-   **Reading: Kent State University: Rashid Muhammad’s “Lecture Notes
    on Threads”**
    Link: Kent State University: Rashid Muhammad’s “[Lecture Notes on
    Threads](http://www.personal.kent.edu/~rmuhamma/OpSystems/Myos/threads.htm)”
    (HTML)  
        
     Instructions: Please read the entire webpage.  This reading covers
    topics in subunits 2.3.3.1 and 2.3.3.2.  This topic is also covered
    by the lecture below subunit 2.3.   
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**2.3.3.1 User Threads** <span id="2.3.3.1"></span> 
*Note: This topic is covered by the lectures below subunits 2.3 and
2.3.3*

**2.3.3.2 System (Kernel) Threads** <span id="2.3.3.2"></span> 
*Note: This topic is covered by the lectures below subunits 2.3 and
2.3.3*

**2.4 Context Switch** <span id="2.4"></span> 
**2.4.1 Definition** <span id="2.4.1"></span> 
-   **Reading: OSdev.org’s “Context Switching”**
    Link: OSdev.org’s “[Context
    Switching](http://resources.saylor.org.s3.amazonaws.com/CS/CS401/CS401-2.4.1-Context%20Switching-PD_files/CS401-2.4.1-Context%20Switching-PD.htm)”
    (HTML)  
        
     Instructions: Read the entire article.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above

**2.4.2 Steps** <span id="2.4.2"></span> 
-   **Reading: Ustudy: Polytechnic College, Pavoorchatram: Director
    Anand K. Lakshmi’s “Context Switches”**
    Link: Ustudy: Polytechnic College, Pavoorchatram: Director Anand K.
    Lakshmi’s “[Context
    Switches](http://resources.saylor.org.s3.amazonaws.com/CS/CS401/CS401-2.4.2-ContextSwitches-BYNCSA_files/CS401-2.4.2-ContextSwitches-BYNCSA.htm)”
    (HTML)  
      
     Instructions: Read the entire article.  This reading applies to the
    topics outlined in subunits 2.4.2.1-2.4.2.3 and any inclusive
    sections.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above

**2.4.2.1 Current Process Saves State from Registers** <span
id="2.4.2.1"></span> 
*Note: This topic is covered by the reading below subunit 2.4.*

**2.4.2.2 Kernel Actions** <span id="2.4.2.2"></span> 
*Note: This topic is covered by the reading below subunit 2.4.2*

**2.4.2.2.1 Process Context Switch** <span id="2.4.2.2.1"></span> 
-   **Reading: Florida International University: Dr. Scott Graham’s
    Operating Systems Lecture Notes: “Processes and Threads”**
    Link: Florida International University: Dr. Scott Graham’s Operating
    Systems Lecture Notes: “[Processes and
    Threads](http://users.cis.fiu.edu/~grahams/COP_5614/)”
    (PowerPoint)  
        
     Instructions: Click on the “Processes & Threads” link next to
    January 18<sup>th</sup>.  Read slides 4 through 10.  Please note
    that this topic is also covered by the reading below subunit
    2.4.2.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**2.4.2.2.2 Thread Context Switch** <span id="2.4.2.2.2"></span> 
-   **Reading: University of California at Santa Barbara: Rich Wolksi’s
    “CS170 Lecture Notes: Putting the P in Threads”**
    Link: University of California at Santa Barbara: Rich Wolksi’s
    [“CS170 Lecture Notes: Putting the P in
    Threads”](http://www.cs.ucsb.edu/~rich/class/cs170/notes/Threads/index.html)
    (HTML)  
        
     Instructions: Please read the entire page.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**2.4.2.3 New Process Loads Data into Registers** <span
id="2.4.2.3"></span> 
*Note: This topic is covered by the reading below subunit 2.4.2.*


