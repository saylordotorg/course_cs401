**Unit 7: File System** <span id="7"></span> 
**File systems play an important role in the operating system. From the
user’s perspective, the file system is a simple filing cabinet. 
However, behind the scenes there is much complexity.  We will discuss a
general overview of file systems, a look at file allocation and methods
as well as disk allocation algorithms.**

**Unit 7 Time Advisory**  
This unit will take you approximately 15 hours to complete.  
  
 <span dir="LTR">☐    Subunit 7.1: 3 hours</span>  
  
 <span dir="LTR">☐    Subunit 7.2: 2 hours</span>  
  
 <span dir="LTR">☐    Subunit 7.3: 4 hours</span>
<span dir="LTR">☐    Lectures (Reading): 2 hours</span>  
  
 <span dir="LTR">☐    Lectures (Video): 2 hours</span>

☐    End of Unit Lab and Exercises: 6 hours

**Unit7 Learning Outcomes**  
Upon successful completion of this unit, the student will be able to:  
  
-   <span dir="LTR">Describe a file system and its purpose.</span>
-   <span dir="LTR">Discuss various file allocation methods.</span>
-   Explain disk allocation and associated algorithms.

**7.1 Introduction to File Systems** <span id="7.1"></span> 
-   **Reading: Florida State University: Andy Wang’s “Lecture 14 File
    Systems and Disk Management”**
    Link: Florida State University: Andy Wang’s “[Lecture 14 File
    Systems and Disk
    Management](http://www.cs.fsu.edu/~awang/courses/cs111/)” (.doc)  
        
     Instructions: Scroll down to Lecture 14 under “Handouts,” and
    select the Word 2000 link after File Systems and Disk Management. 
    Read the entire document (7 pages).  Note: this reading applies to
    all of Unit 7.  
      
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above

-   **Lecture: YouTube: UC Berkeley: Professor John Kubiatowicz’s
    “Lecture 19: File Systems”**
    Link: YouTube: UC Berkeley: Professor John Kubiatowicz’s “[Lecture
    19: File
    Systems](http://www.youtube.com/watch?v=nJ8v-PZ9bhQ&feature=relmfu)”
    (YouTube)  
        
     Instructions: Watch the entire video (about 1 hour and 22
    minutes).  Please note that this video applies to all of Unit 7.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

-   **Reading: University of Western Australia: Professor Amitava
    Datta’s Operating Systems Lecture Notes: “Lecture 10: File System
    Management”**
    Link: University of Western Australia: Professor Amitava Datta’s
    Operating Systems Lecture Notes: “[Lecture 10: File System
    Management](http://undergraduate.csse.uwa.edu.au/units/CITS2230/resources.html)”
    (PDF)  
        
     Instructions: Near the top of the webpage, click on the File
    Systems link next to lecture notes.  Please read the first 9 pages. 
    Note that this reading covers the topics outlined in subunits
    7.1.1-7.1.4.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above

**7.1.1 Purpose of a File System** <span id="7.1.1"></span> 
*Note: This topic is covered by the reading beneath subunit 7.1*

**7.1.2 Components** <span id="7.1.2"></span> 
*Note: This topic is covered by the reading beneath subunit 7.1*

**7.1.3 Directory Structures** <span id="7.1.3"></span> 
*Note: This topic is covered by the reading beneath subunit 7.1*

**7.1.4 File Information Structure** <span id="7.1.4"></span> 
*Note: This topic is covered by the reading beneath subunit 7.1*

**7.2 File Allocation Methods** <span id="7.2"></span> 
-   **Reading: University of Western Australia: Operating Systems
    Lecture Notes: “Lecture 10: File System Management”**
    Link: University of Western Australia: Operating Systems Lecture
    Notes: “[Lecture 10: File System
    Management](http://undergraduate.csse.uwa.edu.au/units/CITS2230/resources.html)”
    (PDF)  
        
     Instructions: Near the top of the webpage, please click on the File
    Systems link next to lecture notes.  Read pages 9-12.  Please note
    that this reading covers the topics outlined in subunits
    7.2.1-7.2.4.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

-   **Web Media: Virginia Tech: Animations to Assisting Learning Some
    Key Computer Science Topics: Operating Systems: “File Management”**
    Link: Virginia Tech: Animations to Assisting Learning Some Key
    Computer Science Topics: Operating Systems: “[File
    Management](http://courses.cs.vt.edu/~csonline/OS/Lessons/FileManagement/index.html)”
    (HTML)  
        
     Instructions: Read through the entire page.  Also, please be sure
    to complete the simulations for each type of file management  
      
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**7.2.1 Contiguous** <span id="7.2.1"></span> 
-   **Reading: John Hopkins University: Dr. Yair Amir’s Lecture Notes:
    “Contiguous File Allocation”**
    Link: John Hopkins University: Dr. Yair Amir’s Lecture Notes:
    “[Contiguous File
    Allocation](http://www.cs.jhu.edu/~yairamir/cs418/os7/index.htm)”
    (HTML)  
        
     Instructions: Scroll down toward the bottom of the webpage, and
    click on the link for Contiguous File Allocation.  Read slide 29. 
    Please note that this topic is also covered by the reading below
    subunit 7.2.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above

**7.2.2 Linked** <span id="7.2.2"></span> 
-   **Reading: John Hopkins University: Dr. Yair Amir’s Lecture Notes:
    “Linked File Allocation”**
    Link: John Hopkins University: Dr. Yair Amir’s Lecture Notes:
    “[Linked File
    Allocation](http://www.cs.jhu.edu/~yairamir/cs418/os7/index.htm)”
    (HTML)  
        
     Instructions: Scroll down toward the bottom of the webpage, and
    click on the link for Linked File Allocation.  Read slides 30-32. 
    Please note that this topic is also covered by the reading below
    subunit 7.2.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above

**7.2.3 Indexed** <span id="7.2.3"></span> 
-   **Reading: John Hopkins University: Dr. Yair Amir’s Lecture Notes:
    “Indexed File Allocation”**
    Link: John Hopkins University: Dr. Yair Amir’s Lecture Notes:
    “[Indexed File
    Allocation](http://www.cs.jhu.edu/~yairamir/cs418/os7/index.htm)”
    (HTML)  
        
     Instructions: Scroll down to the bottom of the webpage, and click
    on the link for Indexed File Allocation.  Read slides 33-34.  Please
    note that this topic is also covered by the reading below subunit
    7.2.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**7.2.4 Compaction** <span id="7.2.4"></span> 
*Note: This topic is covered by the reading beneath subunit 7.2.*

**7.3 Disk Management Algorithms** <span id="7.3"></span> 
-   **Lecture: Johns Hopkins University: Professor Yair Amir’s
    “Operating Systems: File System (cont.) and Disk Management” Lecture
    Slides**
    Link: Johns Hopkins University: Professor Yair Amir’s “[Operating
    Systems: File System (cont.) and Disk
    Management](http://www.cs.jhu.edu/~yairamir/cs418/os8/sld001.htm)”
    (HTML)  
      
     Instructions: Read through all slides (39 total).  Use the arrow
    keys to move back and forth between slides.  Note: These lecture
    notes pertain to topics listed in subunits 7.3.1-7.3.4.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above

-   **Lecture: YouTube: UC Berkeley: Professor John Kubiatowicz’s
    “Lecture 17: I/O Devices (Cont.), Disk Performance and Queueing
    Models”**
    Link: YouTube: UC Berkeley: Professor John Kubiatowicz’s “[Lecture
    17: I/O Devices (Cont.), Disk Performance and Queueing
    Models](http://www.youtube.com/watch?v=G7pnLVKktIo)” (YouTube)  
        
     Instructions: Watch the video starting at 54 minutes until the
    end.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

-   **Lecture: YouTube: UC Berkeley: Professor John Kubiatowicz’s
    “Lecture 18: Queueing Theory (cont.): File Systems, Naming, and
    Directories"**
    Link: YouTube: UC Berkeley: Professor John Kubiatowicz’s “[Lecture
    18: Queueing Theory (cont.): File Systems, Naming, and
    Directories](http://www.youtube.com/watch?v=Q12Ms_z5APc&feature=relmfu)”
    (YouTube)  
        
     Instructions: Watch the first hour of the video.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above

-   **Lecture: University of Buffalo: Bina Ramamurthy’s “Disk Scheduling
    Lecture Notes”**
    Link: University of Buffalo: Bina Ramamurthy’s “[Disk
    Scheduling](http://www.cse.buffalo.edu/~bina/cse421/spring2011/)[Lecture
    Notes](http://www.cse.buffalo.edu/~bina/cse421/spring2011/)”
    (PowerPoint)  
        
     Instructions: Scroll down to the DSched link next to Disk I/O
    (after dates 3/30-4/1).  Read slides 4 through 15.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above

-   **Interactive Lab: Saylor Foundation's "Disk Scheduling Simulation
    Lab"**
    Link: Saylor Foundation's "[Disk Scheduling Simulation
    Lab](http://www.saylor.org/site/wp-content/uploads/2011/12/CS401-Disk-Scheduling-Algorithms-Simulation-Lab-FINAL.pdf)"
    (PDF)  
        
     Instructions: Please complete both parts of the lab.  Compare your
    results to the second part with those contained in the Saylor
    Foundation's "[Disk Scheduling Simulation Lab Answer
    Key](http://www.saylor.org/site/wp-content/uploads/2011/12/CS401-Disk-Scheduling-Algorithms-Simulation-Lab-Answer-Key-FINAL.pdf)"
    (PDF).

**7.3.1 STTF** <span id="7.3.1"></span> 
*Note: This topic is covered by the lectures in subunit 7.3.*

**7.3.2 SCAN** <span id="7.3.2"></span> 
*Note: This topic is covered by the lectures in subunit 7.3.*

**7.3.3 C-SCAN** <span id="7.3.3"></span> 
*Note: This topic is covered by the lectures in subunit 7.3.*

**7.3.4 C-LOOK** <span id="7.3.4"></span> 
*Note: This topic is covered by the lectures in subunit 7.3.*

**Unit 7 Interactive Lab** <span id="7.4"></span> 
-   **Interactive Lab: The Saylor Foundation's "File System Simulation
    Lab"**
    Link: The Saylor Foundation's "[File System Simulation
    Lab](http://www.saylor.org/site/wp-content/uploads/2011/12/CS401-File-System-Simulation-Lab-FINAL.pdf)"
    (PDF)  
        
     Instructions: Please follow all directions and complete the entire
    laboratory.  Save your results to a Word document as instructed and
    compare your results to The Saylor Foundation's "[File System
    Simulation Lab
    Results](http://www.saylor.org/site/wp-content/uploads/2011/12/CS401-File-System-Simulation-Lab-Solutions-FINAL1.pdf)."
    (PDF)

**Unit 7 Assessment** <span id="7.5"></span> 
-   **Assessment: The Saylor Foundation's "Disk Management Algorithms
    Exercises"**
    Link: The Saylor Foundation's "[Disk Management Algorithms
    Exercises](http://www.saylor.org/site/wp-content/uploads/2011/12/CS401-Disk-Management-Algorithms-Exercises-FINAL.pdf)"
    (PDF)  
        
     Instructions: Review the material on disk management algorithms.
     Complete all problems. For problems 1 and 3, it might be easiest to
    use a spreadsheet to track the movement of the disk head as well as
    to calculate the number of cylinders moved. Compare your results
    with the answer key
    [here](http://www.saylor.org/site/wp-content/uploads/2011/12/CS401-Disk-Management-Algorithms-Solutions-FINAL.pdf).
    (PDF)


