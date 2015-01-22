**Unit 6: Memory Management** <span id="6"></span> 
**Memory is the oil that keeps the computer running smoothly.  It is
present in various forms throughout the entire computer system.* * As
software developers, it is absolutely essential to have a solid
understanding of the role memory* *plays so that you are able to
efficiently use memory in your programs, as well as understand what is
going on “under the hood” should a problem arise. * *We will discuss the
role of memory in an Operating System, first with an overview of the
memory hierarchy and how memory and the OS interact with each other. 
Next, we will move on to discussing how memory is allocated for
different purposes.  Finally, we will discuss the two main topics
regarding memory access: segmentation and paging.**

**Unit 6 Time Advisory**  
This unit will take you approximately 11.75 hours to complete.  
  
 <span dir="LTR">☐    Unit 6 Introduction: 1 hour</span>  
  
 <span dir="LTR">☐    Subunit 6.1: 2.75 hours</span>  
  
 <span dir="LTR">☐    Subunit 6.2: 5 hour</span>  
  
 <span dir="LTR">☐    Subunit 6.3: 3 hours</span>

**Unit6 Learning Outcomes**  
Upon successful completion of this unit, the student will be able to:  
  
-   <span dir="LTR">Explain the memory hierarchy.</span>
-   <span dir="LTR">Discuss how the operating system interacts with
    memory.</span>
-   <span dir="LTR">Describe how virtual memory works.</span>
-   <span dir="LTR">Discuss three algorithms for dynamic memory
    allocation.</span>
-   <span dir="LTR">Explain methods of memory access.</span>
-   Describe paging and page replacement algorithms.

-   **Reading: Worcester Polytechnic Institute: Dr. Jerry Breecher’s
    “Operating Systems Memory Management” Lecture Notes**
    Link: Worcester Polytechnic Institute: Dr. Jerry Breecher’s
    “[Operating Systems Memory
    Management](http://web.cs.wpi.edu/~cs3013/c07/)” (PDF)  
        
     Instructions: Scroll down to the Lectures section of the webpage.
     Then, click on the Mem\_Mgmt.pdf link.  Read the entire document
    (35 pages).  This applies to all of Unit 6.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**6.1 Overview of Memory Management** <span id="6.1"></span> 
**6.1.1 Memory Hierarchy** <span id="6.1.1"></span> 
-   **Reading: Ravenbrook: The Memory Management Reference’s Beginner’s
    Guide: “Overview”**
    Link: Ravenbrook: The Memory Management Reference’s *Beginner’s
    Guide:*
    “[Overview](http://www.memorymanagement.org/articles/begin.html)”
    (HTML)  
        
     Instructions: Read the entire webpage.  
      
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**6.1.2 OS Interaction with Memory Levels** <span id="6.1.2"></span> 
-   **Reading: University of Idaho: Dr. Axel Kring’s “OS Lecture
    Notes”**
    Link: University of Idaho: Dr. Axel Kring’s [“OS Lecture
    Notes”](http://www2.cs.uidaho.edu/~krings/CS240/) (PDF)  
        
     Instructions: Scroll down the webpage to Lecture 28.  Click on the
    PDF link after “Sequence 19.”  Read through the first seven
    slides.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**6.1.3 Virtual Memory** <span id="6.1.3"></span> 
-   **Lecture: Thomas Finley’s “Virtual Memory” Lecture Notes**
    Link: Thomas Finley’s “[Virtual
    Memory](http://www.tfinley.net/notes/cps104/virtual.html)” (HTML)  
                              
     Instructions: Read the entire webpage of lecture notes.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above

-   **Lecture: MIT Opencourseware: Professor Hari Balakrishnan and
    Professor Samuel Madden’s Computer Systems Engineering: Lecture 6:
    Virtualization, Virtual Memory**
    Link: MIT Opencourseware: Professor Hari Balakrishnan and Professor
    Samuel Madden’s Computer Systems Engineering: [Lecture 6:
    Virtualization, Virtual
    Memory](http://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-033-computer-system-engineering-spring-2009/video-lectures/lecture-6/)
    (Adobe Flash)  
        
     Also available in:  
     [iTunesU and
    MP4](http://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-033-computer-system-engineering-spring-2009/video-lectures/lecture-6/)  
        
     Instructions: Watch the entire video  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**6.2 Allocating Memory** <span id="6.2"></span> 
-   **Lecture: The University of Wisconsin, Madison: Professor Marvin
    Solomon’s “Lecture Notes on Operating Systems: Memory Management”**
    Link: The University of Wisconsin, Madison: Professor Marvin
    Solomon’s “[Lecture Notes on Operating Systems: Memory
    Management”](http://pages.cs.wisc.edu/~solomon/cs537-old/s07/memory.html)
    (HTML)  
        
     Instructions: Read the entire webpage of lecture notes.  This
    reading also covers the topics in subunits 6.2.1-6.2.4 and any
    inclusive subunits.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**6.2.1 Memory Management** <span id="6.2.1"></span> 
*Note: This topic is covered by the reading in subunit 6.2.*

**6.2.2 Cleaning Up** <span id="6.2.2"></span> 
*Note: This topic is covered by the reading in subunit 6.2.*

**6.2.3 Data Swapping** <span id="6.2.3"></span> 
*Note: This topic is covered by the reading in subunit 6.2.*

**6.2.4 Algorithms for Dynamic Allocation** <span id="6.2.4"></span> 
*Note: This topic is covered by the reading in subunit 6.2.*

**6.2.4.1 First-Fit** <span id="6.2.4.1"></span> 
*Note: This topic is covered by the reading in subunit 6.2.*

**6.2.4.2 Worst-Fit** <span id="6.2.4.2"></span> 
*Note: This topic is covered by the reading in subunit 6.2.*

**6.2.4.3 Best Fit** <span id="6.2.4.3"></span> 
*Note: This topic is covered by the reading in subunit 6.2*

-   **Interactive Lab: The Saylor Foundation's “Memory Management
    Simulation”**
    Link: The Saylor Foundation's "[Memory Management
    Simulation](http://www.saylor.org/site/wp-content/uploads/2012/01/CS401-Memory-Management-Simulation-Interactive-Lab-FINAL.pdf)"
    (PDF)  
        
     Instructions: Please complete the entire assignment.  You can check
    your answers against the answer key
    [here](http://www.saylor.org/site/wp-content/uploads/2012/01/CS401-Memory-Management-Simulation-Interactive-Lab-Solutions-FINAL.pdf).
    (PDF)

**6.3 Memory Access** <span id="6.3"></span> 
*Note: This topic is covered by the resources beneath subunits 6.3.1 and
6.3.2.*

**6.3.1 Segmentation** <span id="6.3.1"></span> 
*Note: This topic is covered by the resources beneath subunits 6.3.1.1
and 6.3.1.2.*

**6.3.1.1 Definition** <span id="6.3.1.1"></span> 
-   **Lecture: The University of Wisconsin, Madison: Professor Marvin
    Solomon’s “Lecture Notes on Operating Systems: Segmentation”**
    Link: The University of Wisconsin, Madison: Professor Marvin
    Solomon’s “[Lecture Notes on Operating Systems:
    Segmentation](http://pages.cs.wisc.edu/~solomon/cs537-old/s07/segmentation.html)”
    (HTML)  
        
     Instructions: Read the entire webpage of lecture notes.  This
    reading also touches on the topics outlined under subunit 6.3.2.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above

**6.3.1.2 x86/x64 Architecture** <span id="6.3.1.2"></span> 
-   **Reading: Ox90.org: Jeremy Pierre’s “An Introduction to Intel
    Memory Management”**
    Link: Ox90.org: Jeremy Pierre’s [“An Introduction to Intel Memory
    Management”](https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=1&cad=rja&ved=0CCsQFjAA&url=http%3A%2F%2Fstatic.ow.ly%2Fdocs%2Fmemory_Rt7.pdf&ei=xCuBUtP0AamqsAS6y4D4DQ&usg=AFQjCNEz588WyWwWkkRFDX5Bt0SmdLUEKg&bvm=bv.56146854,d.cWc)
    (PDF)  
        
     Instructions: Read the entire document (5 pages). Note that
    clicking on the link will automatically download the file to your
    computer.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above

**6.3.1.2.1 Global Descriptor Table** <span id="6.3.1.2.1"></span> 
-   **Reading: Bona Fide OS Development: Brenden F.’s “The GDT"**
    Link: Bona Fide OS Development: Brenden F.’s “[The
    GDT](http://www.osdever.net/bkerndev/Docs/gdt.htm)” (HTML)  
        
     Instructions: Read the entire article.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above

**6.3.1.2.2 Local Descriptor Table** <span id="6.3.1.2.2"></span> 
*Note: This topic is covered by the reading in subunits 6.3.1.2*

**6.3.2 Paging** <span id="6.3.2"></span> 
-   **Lecture: The University of Wisconsin, Madison: Professor Marvin
    Solomon’s “Lecture Notes on Operating Systems: Paging**
    Link: The University of Wisconsin, Madison: Professor Marvin
    Solomon’s “[Lecture Notes on Operating Systems:
    Paging](http://pages.cs.wisc.edu/~solomon/cs537-old/s07/paging.html)”
    (HTML)  
        
     Instructions: Read the entire webpage of lecture notes.  This
    reading also covers the topics outlined in subunits
    6.3.2.1-6.3.2.3.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**6.3.2.1 Page Tables** <span id="6.3.2.1"></span> 
*Note: This topic is covered in the lecture notes for subunit 6.3.2.*

**6.3.2.2 Page Replacement** <span id="6.3.2.2"></span> 
*Note: This topic is covered in the lecture notes for subunit 6.3.2.*

**6.3.2.3 Frame Allocation** <span id="6.3.2.3"></span> 
*Note: This topic is covered in the lecture notes for subunit 6.3.2.*


