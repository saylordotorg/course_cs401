**Unit 3: Synchronization** <span id="3"></span> 
*Because a number of different entities will need to access data, it is
important to learn how to maintain a consistent view of data across the
OS.  This is why we need a good synchronization management system.  We
will begin this section with an overview of why synchronization is so
important to an Operating System and the problems that could arise if
synchronization is not handled properly.  The discussion will continue
with an overview of Race Conditions (or system flaws in which the output
of a given process is problematically dependent on the sequence of other
events), and finally, Semaphores as a way of preventing Race Conditions
and other more advanced alternatives to Semaphores, such as Monitors and
Messages.*

**Unit 3 Time Advisory**  
This unit will take you approximately 12.5 hours to complete.  
  
 <span dir="LTR">☐    Subunit 3.1: 3 hours</span>  
  
 <span dir="LTR">☐    Subunit 3.2: 2 hours</span>  
  
 <span dir="LTR">☐    Subunit 3.3: 7.5 hours</span>
<span dir="LTR"><span id="cke_bm_537S"
style="display: none; "> </span>  
 ☐    Introduction: 1.5 hours</span>  
  
 <span dir="LTR">☐    Subunit 3.3.1: 0.5 hour</span>  
  
 <span dir="LTR">☐    Subunit 3.3.3: 0.5 hour</span>  
  
 <span dir="LTR">☐    Subunit 3.3.4: 4 hours</span>  
  
 ☐    Subunit 3.3.5: 1 hour  
 <span id="cke_bm_537E" style="display: none; "> </span>

**Unit3 Learning Outcomes**  
Upon successful completion of this unit, the student will be able to:  
  
-   <span dir="LTR">Describe synchronization.</span>
-   <span dir="LTR">Explain a race condition.</span>
-   <span dir="LTR">Discuss interprocess communication.</span>
-   <span dir="LTR">Describe how semaphores can be used in an operating
    system.</span>
-   <span dir="LTR">Discuss three of the classic synchronization
    problems.</span>
-   Explain the alternatives to semaphores.

**3.1 Synchronization: Relevance and Problems** <span id="3.1"></span> 
-   **Lecture: YouTube: UC Berkeley: Professor John Kubiatowicz’s
    “Lecture 6: Synchronization”**
    Link: YouTube: UC Berkeley: Professor John Kubiatowicz’s “[Lecture
    6: Synchronization](http://www.youtube.com/watch?v=24DTq1gSK98)”
    (YouTube)  
        
     Instructions: Watch the entire video lecture (about 1 hour and 23
    minutes).  Please note that this video also covers the topics
    outlined in subunits 3.1.1 and 3.1.2.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

-   **Reading: Green Tea Press: Allen B. Downey’s Little Book of
    Semaphores: “Chapter 1”**
    Link: Green Tea Press: Allen B. Downey’s "[*Little Book of
    Semaphores:* Chapter 1](http://greenteapress.com/semaphores/)”
    (PDF)  
        
     Instructions: Click the Download the book in PDF link and read all
    of Chapter 1 (pages 1-6).   
        
     Terms of Use: Permission is granted to copy, distribute and/or
    modify this document under the terms of the GNU Free Documentation
    License, Version 1.1 or any later version published by the Free
    Software Foundation.  Please respect the copyright and terms of use
    for this text.

**3.1.1 Processes and Threads Share Data and Resources** <span
id="3.1.1"></span> 
*Note: This topic is covered by the resources beneath subunit 3.1.*

**3.1.2 Need to Maintain Consistent View of Data and Resources** <span
id="3.1.2"></span> 
*Note: This topic is covered by the resources beneath subunit 3.1*

**3.2 Race Conditions** <span id="3.2"></span> 
-   **Reading: Drexel University: Brian Mitchell’s “Operating Systems:
    Interprocess Communications”**
    Link: Drexel University: Brian Mitchell’s “[Operating Systems:
    Interprocess
    Communications](https://web.archive.org/web/20120725003940/https://www.cs.drexel.edu/~bmitchel/course/mcs720/)”
    (PDF)  
        
     Instructions: Please scroll down the webpage to the “Schedule”
    section.  Then, click on the Process Synchronization link in topic
    4.  Read the first three pages. This reading also covers subunits
    3.2.1, 3.2.2, and all inclusive sections (3.2.2.1-3.2.2.3.).  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above

-   **Reading: Virginia Tech: Dr. Ali Butt’s Lecture Slides:
    “Introduction to Race Conditions”**
    Link: Virginia Tech: Dr. Ali Butt’s Lecture Slides: “[Introduction
    to Race
    Conditions](http://courses.cs.vt.edu/~cs3204/spring2009/butta/local/lectures.html)”
    (PDF)  
        
     Instructions: Please scroll down to the date 2/10.  Then, click on
    the PDF link next to the title “Intro to Race Conditions.”  Read the
    entire set of slides (20 pages).  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above

**3.2.1 Definition** <span id="3.2.1"></span> 
*Note: This topic is covered by the resources beneath subunit 3.2.*

**3.2.2 Example** <span id="3.2.2"></span> 
*Note: This topic is covered by the resources beneath subunit 3.2*

**3.2.2.1 Two Threads Executing Same Function with Same Variables**
<span id="3.2.2.1"></span> 
*Note: This topic is covered by the resources beneath subunit 3.2*

**3.2.2.2 Possible Thread Interruption at Any Time** <span
id="3.2.2.2"></span> 
*Note: This topic is covered by the resources beneath subunit 3.2*

**3.2.2.3 How to Handle Data Consistency?** <span id="3.2.2.3"></span> 
*Note: This topic is covered by the resources beneath subunit 3.2*

**3.3 Semaphores** <span id="3.3"></span> 
-   **Reading: YouTube: UC Berkeley: Professor John Kubiatowicz’s
    “Lecture 7: Mutual Exclusion, Semaphores, Monitors and Condition
    Variables"**
    Link: YouTube: UC Berkeley: Professor John Kubiatowicz’s “[Lecture
    7: Mutual Exclusion, Semaphores, Monitors and Condition
    Variables](http://www.youtube.com/watch?v=bQT3OpcJJ64&feature=relmfu)”
    (YouTube)  
                                
     Instructions: Watch the entire video (about 1 hour and 24
    minutes).  Please note that this lecture covers the topics in
    subunits 3.3.1-3.3.5.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above

**3.3.1 Definition** <span id="3.3.1"></span> 
-   **Reading: Green Tea Press: Allen B. Downey’s Little Book of
    Semaphores: “Chapter 2”**
    Link: Green Tea Press: Allen B. Downey’s "*[Little Book of
    Semaphores: Chapter
    2](http://resources.saylor.org.s3.amazonaws.com/CS/CS401/CS401-3.3.1-LittleBookofSemaphores-GNU_files/CS401-3.3.1-LittleBookofSemaphores-GNU.htm)"* 
    (PDF)  
        
     Instructions: Read all of Chapter 2 (pages 7-9).  This reading
    covers the topics outlined in subunits 3.3.1-3.3.3.  
        
     Terms of Use: Permission is granted to copy, distribute and/or
    modify this document under the terms of the GNU Free Documentation
    License, Version 1.1 or any later version published by the Free
    Software Foundation.  Please respect the copyright and terms of use
    for this text.

**3.3.2 Uses** <span id="3.3.2"></span> 
*Note: This topic is covered by the reading below subunit 3.3.1.*

**3.3.3 Example using Java** <span id="3.3.3"></span> 
-   **Reading: Wikidot’s Programming Examples: “Java Semaphore”**
    Link: Wikidot’s Programming Examples: “[Java
    Semaphore](http://resources.saylor.org.s3.amazonaws.com/CS/CS401/CS401-3.3.3-JavaSemaphore-BYSA_files/CS401-3.3.3-JavaSemaphore-BYSA.htm)”
    (HTML)  
        
     Instructions: Please read the entire webpage.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**3.3.4 Classic Synchronization Problems** <span id="3.3.4"></span> 
-   **Reading: Green Tea Press: Allen B. Downey’s Little Book of
    Semaphores: “Chapter 4”**
    Link: Green Tea Press: Allen B. Downey’s "*[Little Book of
    Semaphores: Chapter
    4](http://resources.saylor.org.s3.amazonaws.com/CS/CS401/CS401-3.3.4-LittleBookofSemaphoresChap4-GNU_files/CS401-3.3.4-LittleBookofSemaphoresChap4-GNU.htm)"* (PDF)  
        
     Instructions: Read all of Chapter 4 (pages 61-120).  This reading
    also covers the topics outlined in sections 3.3.4.1-3.3.4.3.  
        
     Terms of Use: Permission is granted to copy, distribute and/or
    modify this document under the terms of the GNU Free Documentation
    License, Version 1.1 or any later version published by the Free
    Software Foundation.  Please respect the copyright and terms of use
    for this text

-   **Lecture: YouTube: Stanford University: Professor Jerry Cain’s
    “Programming Paradigms Lecture 16”**
    Link: YouTube: Stanford University: Professor Jerry Cain’s
    “[Programming Paradigms Lecture
    16](http://www.youtube.com/watch?index=15&feature=PlayList&v=OGHN_zVTMMo&list=PL9D558D49CA734A02)”
    (YouTube)  
        
     Instructions: Please watch the entire lecture (51:32 minutes).  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above

**3.3.4.1 Produces vs. Consumers Problem** <span id="3.3.4.1"></span> 
*Note: This topic is covered by the resources beneath subunit 3.3.4*

**3.3.4.2 Readers-Writers Problems** <span id="3.3.4.2"></span> 
*Note: This topic is covered by the resources beneath subunit 3.3.4.*

**3.3.4.3 Dining Philosopher Problem** <span id="3.3.4.3"></span> 
*Note: This topic is covered by the resources beneath subunit 3.3.4*

**3.3.5 Alternatives** <span id="3.3.5"></span> 
**3.3.5.1 Monitors** <span id="3.3.5.1"></span> 
-   **Reading: Florida State University: Andy Wang’s “Lecture 8 Monitors
    and Condition Variables”**
    Link: Florida State University: Andy Wang’s “[Lecture 8 Monitors and
    Condition Variables](http://www.cs.fsu.edu/~awang/courses/cs111/)”
    (Word .doc)  
        
     Instructions: Scroll down to the webpage to Lecture 8 under the
    “Handouts” heading.  Then, click on the Word 2000 link after
    Monitors and Condition Variables to open the Word document. Read the
    entire document (6 pages).  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**3.3.5.2 Messages** <span id="3.3.5.2"></span> 
-   **Reading: University of Linkopings: Ola Dahl’s “TSEA81 Computer
    Engineering and Real-time Systems Lecture – Message Passing”**
    Link: University of Linkopings: Ola Dahl’s [“TSEA81 Computer
    Engineering and Real-time Systems Lecture – Message
    Passing”](http://www.da.isy.liu.se/courses/tsea81/dcm/lecture_messages.html)
    (HTML)  
        
     Instructions: Read the entire page.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.


