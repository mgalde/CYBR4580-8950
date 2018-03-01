# CYBR4580/8950
This repository contains a digitized version of the course content for the CYBR 4580/8950 Certification and Accreditation capstone course at the University of Nebraska at Omaha.

## Viewing these materials
The class materials are best viewed at [https://mlhale.github.io/CYBR4580-8950/](https://mlhale.github.io/CYBR4580-8950/)

## Overview
In this course, students will extend and apply their knowledge, accumulated from their undergraduate/graduate studies, towards defining, implementing, and assessing secured information systems. Students will demonstrate their ability to specify, apply, and assess different types of countermeasures at different points in a system or enterprise.

## Table of contents
<!-- TOC START min:1 max:3 link:true update:true -->
- [CYBR4580/8950](#cybr45808950)
  - [Viewing these materials](#viewing-these-materials)
  - [Overview](#overview)
  - [Table of contents](#table-of-contents)
  - [Online Discussion Area (Slack)](#online-discussion-area-slack)
  - [Tentative Class Schedule](#tentative-class-schedule)
  - [Location](#location)
  - [Supplies](#supplies)
  - [Projects](#projects)
  - [Labs](#labs)
  - [Class Topics](#class-topics)
  - [Former Project Hall of Fame](#former-project-hall-of-fame)
  - [License](#license)

<!-- TOC END -->

## Online Discussion Area (Slack)
I have setup an online discussion board on slack.com for usage in this class. I can create some private channels for you to work in with your project teams (once created), but I want to be able to participate in your conversations - so please use the space on slack.

Go to [https://cybr-4580-8950.slack.com](https://cybr-4580-8950.slack.com) and use your unomaha email address to register an account. This will give you access to the course discussion and project collaboration spaces. Use the the general channel, your project channel, or private messages. I expect all project-related communication to live in your slack channel. If you need my attention please use the `@mlhale` syntax to get my attention (or `@Bill Mahoney ` to get Bill's).

## Tentative Class Schedule
| Dates | Week | Activity|
|-------|------|---------|
| January 8th | 1 | Course introduction. Cybersecurity is everywhere.|
| January 15th | 2 | Thoughts on Software Engineering. Track 1 bids due January 19!|
| January 22nd | 3 | 15minute presentations on your bids in random order. |
| January 29th | 4 | Work on Proposals |
| February 5th | 5 | Proposals due February 9! |
| February 12th | 6 | Milestone 1 due, 25minute presentations + 5 minute Q/A, random order. Milestone 2 assigned. |
| February 19th | 7 | Continue milestone 1 presentations. Work on Milestone 2. |
| February 26th | 8 | Work on Milestone 2. Track 1 progress reports due March 2! Track 1 presentations either March 2 or 9! |
| March 5th | 9 | Work on Milestone 2. Track 1 progress reports due March 7! Track 1 presentations March 9! |
| March 12th | 10 | Work on Milestone 2. |
| March 19th | 11 | (Spring Break) No class |
| March 26th | 12 | Milestone 2 due, 25minute presentations + 5 minute Q/A, random order. Milestone 3 assigned. |
| April 2nd | 13 | Work on Milestone 3. |
| April 9th | 14 | Work on Milestone 3. |
| April 16th | 15 | Work on Milestone 3. |
| April 23rd | 16 | Track 1 final reports due April 27! Track 1 presentation either April 27 or May 4! Final Milestone, 25minute presentations + 5 minute Q/A, random order. |
| April 30th | | Final is scheduled for 5:00 PM Tuesday May 1. We will use this time to finish up the final presentations if needed. |

## Location
All classroom activities will take place in PKI room 276 (graduate) or PKI 271 (undergraduate) unless otherwise noted ahead of time.

## Supplies

### Hardware/software
* [Virtualbox](http://www.virtualbox.org) or [VMWare Workstation (windows) or Fusion (mac)](/vmware/vmware.pdf)
* Your laptop (capable of running programming environments and/or needed dev/analysis tools)

## Projects
The structure of the course accommodates two types of projects on two tracks.

### Project types
#### Makers
In this project type, students will design, build, and secure a new full-fledged system or create a new, non-trivial, component for an existing system or product. Special attention will be paid towards open source environments. Relevant artifacts generated will include design documentation (use cases, architectures, interaction diagrams, etc), system/component code, unit/acceptance tests, and testing results.

#### Breakers
In this project type, students will select an existing product or system and rigorously evaluate it using a combination of system, network, and software testing methods. Relevant artifacts generated will include reversed design docs (i.e. an understanding of how the product works), vulnerability surface analysis documentation, test cases, and analysis results.

### Project Tracks
#### Track 1: Problems in National Information Security.
Students in this track will bid on, and be asked to perform research in directed areas under the supervision of an external partner, typically a national labor federal agency. These will be directed projects with an external Technical Director that the group will report to. The undergrad students in this track will be working in conjunction with graduate students in the graduate capstone class.de, unit/acceptance tests, and testing results.

#### Track 2: Industry partners or UNO organizations
In this track students will select or be assigned an existing product or system to develop or evaluate. Projects may originate with external local companies or internal UNO organizations.

Students will follow certification and accreditation techniques using best practices and security controls from standards documents (such as the NIST 800-53).

### Project Milestones
* [Capstone Milestone 1 rubric](./projects/milestone1.md) - Due Feb. 8th
* [Capstone Milestone 2 rubric](./projects/milestone2.md) - Due Mar. 26th
* [Capstone Final Milestone rubric] - TBA

#### Evaluation form
For team projects, please use the evaluation form below to assess your teammates.
[https://unomaha.az1.qualtrics.com/jfe/form/SV_6PYfOXdb4KpMtyB](https://unomaha.az1.qualtrics.com/jfe/form/SV_6PYfOXdb4KpMtyB)

### Project Process
Regardless of your Track you will do the following.
![Project Selection Process](assets/README-2461166f.png)

## Labs
- Introduction to the course (optional)
  - [Github primer](/modules/github/README.md)
  - [Container primer](/modules/containers/README.md)
  - [Virtualization primer](/modules/virtualization-primer.md)
  - [Creating a REST API](/modules/restful-api/README.md)
  - [Pen testing REST](/modules/penetration-testing/README.md)
- Project Selection and Bid process
- Team interaction and project management
  - Agile methods for development and assessment
  - Using collaboration tools
  - Keeping track of efforts

## Class Topics
- Intro to the class
- Review of software engineering ([Lecture 2](/lectures/lecture2.pdf), [Lecture 3 PDF](/lectures/lecture3.pdf))
  - Software Architectures
  - Software design principles
  - Security in the Software development lifecycle
- Test-driven Development Practices ([Lecture 4 pdf](lectures/lecture4.pdf))
  - Unit testing
  - Acceptance criteria
  - think-test-build-test-repeat
  - Blackbox testing
- Review of certification and assessment ([Lecture 5 pdf](lectures/lecture5.pdf))
  - Security controls, countermeasures, etc
  - Standards Documents: NIST SP800-53, FIPS200, 800-33, etc
  - Assessment tools
- Time to be creative
  - See [Projects](#project-milestones) area

## Former Project Hall of Fame
### 2017
#### Team Projects
* [PLC Hacking](https://github.com/groth001/Capstone)
  * Gary Roth
  * Richard Tanner
  * Daniel Ritter
* [Forensic Tool Deficiency Analysis](https://github.com/cbranan/Anti-Forensics)
  * Casey Branan
  * Preston Wells
  * Brandon Franklin
* [Analyzing and Penetration Testing an Amazon Echo Dot](https://github.com/jhautry/echo-dot)
  * James Autry
  * Matthew Sutton
  * Tim Gekas
* [Open Source Hypervisor Analysis and Evaluation](https://github.com/jhembree/IACapstone)
  * Jesse Hembree
  * Afnan Albokhari

#### Solo Projects
* [Data Loss Prevention System](https://github.com/leslieNOOP/InSpectreDLP) -- Private
  * Leonora Gerlock
* [DNS Intrusion Detection System](https://github.com/mfaltys/doic)
  * Matthew Faltys
* [Airlock - a P2P Encrypted Chat and Collaboration tool](https://github.com/Phosphoresce/airlock)
  * Darian Lepert
* [Windows Native Plugin for SFTP interaction](https://github.com/ChandlerHuston/CYBR4580Project) -- Private
  * Chandler Huston
* [Android Process inspector](https://github.com/pstratman/sector)
  * Paul Stratman

## Syllabus
### Date/Time: Thursday 5:30pm – 8:10pm (grad), Tuesday/Thursday 4:00-5:15 (undergrad)
### Instructor grad:  Dr. Hale
### Office:  PKI 174-D, (402) 554-3978
### Office Hours:  By appointment or walk-ins anytime the door is open
### E-mail:  mlhale@unomaha.edu (please message me on slack instead of emailing)

### Instructor (undergrad): Dr. Mahoney
### Office:  PKI 282F, 554-3975
### Office Hours:  By appointment
### E-mail:  wmahoney@unomaha.edu

### Grading Breakdown (see schedule for tentative due dates)
- (10%) Participation score (meetings, short tutorial participation, etc)
- (10%) Project Proposal / Description
- (25%) Semester Project Milestone 1 - ([rubric TBA]())
- (25%) Semester Project Milestone 2 - ([rubric TBA]())
- (30%) Semester Project Milestone Final - ([rubric TBA]())

Each project milestone will have a specific grading rubric that includes the core requirements for the project, any required intermediate milestone goals (such as short progress meetings with the instructor), the project due date, and the list of items that must be submitted. Each project will include a presentation component to be presented in class on the project due date. Projects build upon each other. The final Project is considered to be comprehensive. This means that <i>there is no final exam</i>. Final Project presentations will be presented according to the schedule

### Attendance
- Class Attendance: You do not have to attend class except on presentation days (see below). Given the course is one day a week, attendance is highly recommended. Missing a single class is equivalent to missing 2-3 classes of a normal course. If you miss class, you are responsible for getting the material – including any assigned project work. Not showing up for team work days and instructor meeting days WILL result in diminished participation score.
- Presentation Attendance (Mandatory): If you miss class on a presentation day you will receive a 0 on the presentation portion of the project grade unless you have a university-approved excuse or an approved extension (see below).

### Group Work
Students will work in groups. The instructor in this class will assign the groups. The capstone class is like the real world – you don’t always get to have your way! Each group will have five members, although obviously there may be an odd group or two depending on the class list. Students in Track 1 will have three undergraduates from CYBR 4580 and two graduate students from CYBR 8950. Students in Track 2 will have all five members from CYBR 4580.

Group projects will include an individual participation grade worth 50% of the total group points, e.g. a group may make a 100% on a particular project, but an individual with low participation in the group may make a 50%. Participation will be anonymously rated by other group team members and the instructor.

### Team formation
The instructor reserves the right to make a change to any team or any project during the course of the semester for any reason that may or may not be disclosed. Project rescoping will be performed in this event.

### Service Learning / Real World Customers
As part of UNO’s strategic initiatives, individuals or groups may be partnered with community organizations in Omaha for service learning through the center for community engagement. If community partners can be identified, student projects (group or individual) in the class may work towards meeting community needs. In the event of community projects, appropriate scoping will be considered to ensure that community needs can be met within the time constraints of the coursework.

### Project Extensions and Late work
Sometimes unforeseen events occur or development takes longer than expected. In such cases, project extensions will be allowed. To receive a project extension, individuals or groups must request an extension at least 24hours in advance of the project due date. Extension time frames are at the discretion of the instructor, but generally will not be longer than 1 week. Failure to request an extension 24 hours prior to the due date means that the work is due at the specified time. Late work without a requested extension will receive a 5% point reduction per day up to a total of 40%. Late work submitted 2 weeks after an original (or extended) due date will not be accepted.

### Special accommodations for students with disabilities
Students with disabilities requiring special accommodations must contact disability services. Disability services may be reached by phone at (402) 554-2872 or by email at unodisability@unomaha.edu.

### Special accommodations for active duty or reserve military
Students serving in the military requiring special accommodations (e.g. unit deployment) must contact the office of Military and Veteran Services by phone at (402) 554-2349 or by email at unovets@unomaha.edu.

### Plagiarism
The university policies on cheating and plagiarism apply in this course. Except on designated group work, the expectation is that every student will do their own work. Students under suspicion of plagiarism for individual assignment submitted materials will be given an opportunity to defend themselves. If after defense the instructor still believes the work to be plagiarized the department chair will be notified and the grade evaluation for the assignment will be lowered to a value between 50% and 0% at the discretion of the instructor. If a second occurrence of plagiarism occurs, the student will receive an F for the course and the registrar’s office will be notified that the student is not permitted to withdraw from the course. In addition the department chair and dean will be notified.

### Work Retainment
The CS and IS programs in the College of IS&T are accredited through ABET (the Accreditation Board for Engineering and Technology. This organization occasionally requires that we keep samples of student work.

The instructor may retain a copy of your exams (with names and any other identifying information removed) for accreditation or pedagogy purposes, unless you specify otherwise in writing.

In addition, the instructor retains the right to use any code or project artifacts developed in the course for pedagogy, research, or service learning purposes. Student web project code developed in the course may be used in future secure project development courses, by the instructor for research purposes, or by designated stakeholders.

## License
CYBR Capstone
Copyright (C) 2016-2017  Dr. Matthew L. Hale

<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" /></a><br /><span xmlns:dct="http://purl.org/dc/terms/" property="dct:title">CYBER4580/CYBR 8950 and related works</span> by <a xmlns:cc="http://creativecommons.org/ns#" href="http://faculty.ist.unomaha.edu/mlhale" property="cc:attributionName" rel="cc:attributionURL">Matt Hale</a> are licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License</a>.
