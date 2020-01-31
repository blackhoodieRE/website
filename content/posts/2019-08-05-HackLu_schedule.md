---
title: "Blackhoodie @ HackLu announcements"
exerpt: "Reverse Engineering Workshop for women at Hack.lu 2019"
tags: [workshop, conferences, BlackHoodie]
date: 2019-08-01 00:00:00 -0500
---

You already knew we had a master plan to come back to Luxembourg. You asked for it, we heard and we know you are pressing F5 like crazy to check what we have for you this time! So here it is! We are finally publishing the agenda for yet another Blackhoodie event in 2019.

Hard facts can be found [here](../Blackhoodie_HackLu_19/) and if you want to join us, please register to your favorite track using our [form](https://docs.google.com/forms/d/e/1FAIpQLSeFHlEqBwPj238QXAJ081jyRu6THwr4zlXlRukarRbKLzJn3w/viewform).

---
## **Track 1:**

### Offensive Security 101

Teacher: [Valentine M.](https://twitter.com/vm00z), ethical hacker for application and infrastructure pentesting, KPN - Royal Dutch Telekom

Topic: An advanced introduction to Offensive Security. This includes offensive security principles, some hacking demos, and common techniques on how to break into things.

The workshop will include:
- Infrastructure and web introduction
- Web application pwnage
- OWASP Top 10
- Offensive Security tooling
- Vulnerability scanning
- Kernel exploits
- Privesc and lateral movement
- Hands-on sessions
- Demos and more demos!

Prerequisites:
- Bring a laptop!
- A working Kali virtual machine
https://www.kali.org/downloads/ (Virtual Box will do https://www.virtualbox.org/)

There is some pre-knowledge required: some (web application) coding knowledge and being familiar with Unix terminology and command line usage.

Regarding web applications, which is a strong subject in this workshop, there are multiple web guides to follow. This one is quite alright: https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web

W3Schools also provide multiple tutorials regarding web applications: https://www.w3schools.com/

This is to acquire basic knowledge on web architectures, JavaScript and HTML, and also how to deal with databases (SQL language).
Prerequisites: some web application, coding, and Unix knowledge.

### Windows pwning

Teacher: [Essy](https://twitter.com/casheeew)

Topic: Congrats, you’ve made it, after some exploit shenanigans you’ve got your first foothold on a Windows client at Kitty Corporation. Now what? Where to go from here? Where am I? Who am I? Who can I (pretend to) be? And what can I do? We’ll explore some tools and techniques that help us try to answer those questions. This is going to be a starter workshop to get a first feeling on how to have fun with (domain joined) Windows systems. We’ll be focusing on the basic concepts of a Windows based infrastructure that you’ll usually find in corporate environments. This will include authentication protocols and weaknesses as well as tools that let’s you have fun in those infrastructures.

Prerequisites: Ability to run 2 Windows based VMs at the same time (>=8GB RAM, >=60GB free disk space). That’s it, detailed knowledge of Windows is not required to attend the training, we’ll start with the basics and explore this playground together. I’ll provide you with information & scripts how to setup the lab beforehand.

### Introduction to Return Oriented Programming

Teacher: [Chiliz](https://twitter.com/chiliz16)

Topic: This is an introductory workshop to Return Oriented Programming, a technique to overcome non-executable stacks during exploitation. The workshop aims to be fitting for people with varying background, as it starts easy and with detailed
explanation on hands-on exercises but increases difficulty over time. The workshop is a good fit for attendees who already know about buffer overflows but want to go further. For them it's a perfect next step which will take their exploiting skills to the next level!

The basic example of exploiting a buffer overflow is pushing shellcode on the stack and jumping to it. This is successful when there are no security mechanisms. But how can we get a shell if the stack is not executable? Return Oriented Programming (ROP) is a neat technique to defeat this protection.

In this workshop, we will step up the game by turning on the NX-bit and using ROP to exploit the buffer overflow anyway. The basic idea of ROP is to use code snippets that are already in the binary. This way, we can put the shellcode together like we would tinker a blackmailing letter from old newsletters, putting the fitting pieces one after another, until we get the payload we want.

Prerequisites:
- Bring a laptop with a hypervisor (e.g. VirtualBox, VMware) installed.
- Import the Workshop VM.
- Have basic knowledge about buffer overflows and x86 assembler (The workshop features a quick introduction to these topics, if you are a quick learner you can also participate without prior knowledge).

## **Track 2:**

### Windows EDR 101

Teachers: [Dana Baril](https://twitter.com/dana_baril), Security Software Engineer, Microsoft Defender ATP & [Noa Bratman](https://www.linkedin.com/in/noa-bratman-9b758195), Software Engineer, Microsoft Defender ATP

We would like to provide a glimpse to a day in the blue team. In the beginning, we will explain the idea behind EDR in general, and share implementation concepts. In the end of this part you will practice code writing for EDR features. In the second part, we will discuss malware analysis using EDR data and together you will run an exercise of data analysis, hunting malicious activity.

### Java Web Application Secure Coding

Teacher: [Eva Szilagyi](https://twitter.com/EvaSzilagyiSec), IT Security Consultant, Alzette Information Security

Topic: Context-dependent output encoding? Prepared statement with bind variables? Disable external entity resolution? Storing passwords in salted hash format? If you are involved in Java development, you should join this workshop and see, why these are important from a security perspective! This workshop is meant for developers and security professionals alike. It is delivered by an information security professional with the purpose of demystifying web application secure coding.

Prerequisites: A laptop with at least 8 GB of RAM and 40-50 GB of free disk space, VMware Workstation, VMware Fusion or VMware Player installed.

### Intro to Dark Arts: Getting Started with CTFs

Teacher: [Geethna T K](https://twitter.com/geethnatk) and [Sowmya P](https://twitter.com/__4lph4__)

Topic: This workshop will introduce the participants to the world of CTF contests as a way to learn real-world security skills, providing them with the basic knowledge for playing CTF, and to get started with solving hands-on challenges in the domains of Cryptography and Binary Exploitation. The workshop will consist of hands-on sessions for each domain as mentioned above to help participants get familiarised with the tools and libraries for each corresponding domains.

Key takeaways:
The participants will be able to walk away with the following takeaways from this class:
- Understanding of how CTFs can help getting started with security
- An overview of a jeopardy style CTF and basic tactics and techniques to solve them
- How to be fluent with scripting for sending exploits to the challenge server
- Practise challenges to help in applying learned concepts and deepen the understanding
- Insight into RSA cryptosystem and learn how to implement basic attacks
- Pwning Lab will help in getting a better understanding of binaries and exploiting them

Prerequisites:
- Familiarity with working in Linux OS  https://lym.readthedocs.io/en/latest/

- Basic knowledge about:
  - C programming https://www.tutorialspoint.com/cprogramming/
  - Instructions in x86 assembly https://www.tutorialspoint.com/assembly_programming/
  - Python programming https://www.learnpython.org/
  - Knowledge about stack and function call http://www.securitytube.net/groups?operation=view&groupId=5

- Laptop requirements:  a laptop having more than 4GB RAM along with a Virtualbox 5.2 or higher or Vmware installed.

## **Track 3:**

### Linux Device Drivers and Loadable Kernel Modules for Offensive and Defensive Purposes

Teachers: Dalila Lima & Anna-Lena

Topic: This workshop intends to dive into the world of hardware devices, how they and their drivers work and how this is interesting to know for both offensive and defensive security purposes.
Attendees will be able to write a rootkit keylogger Linux Loadable Kernel Module and experiment with it inside a VM. If you have ever wondered what happens whenever you press a key in your keyboard, move your mouse or even how you can see everything that appears in your screen and are curious to understand how attackers can use that to their own benefit, this workshop is for you.

Prerequisites: a laptops with VMware or Virtual Box. Virtual machine image will be provided before the workshop date.

### Scripting the reverse of a malware using Miasm

Teacher: Caroline Leman, Security Research Engineer, CEA DAM, focus on RE and log analysis.

Topic: I am going to introduce concepts which can be generalized to other reverse-engineering tools. We will study 2 samples that focuses each on different aspect of reverse engineering analysis. We will study: dependency analysis, emulation, ida scripting (for auto commenting code).

Prerequisites: a basic knowledge of x86 assembly, things like ABI, calling conventions and so on.

---


## Saturday, October 19th, 2019 - Workshop schedule


| Time  | Track 1 Intro to Offense                                     | Track 2 Intro to Defense                             | Track 3 Advanced  |
| :---: | :----------------------------------------------------------- | :--------------------------------------------------- | :--------------------------------------------------- |
| 09:00 | Offensive Security 101                        | Windows EDR 101                                         | Linux Device Drivers and Loadable Kernel Modules for Offensive and Defensive Purposes   |
| 13:15 | Lunch          |          |
| 14:15 | Offensive Security 101                             | Java Web App Secure Coding | Linux Device Drivers and Loadable Kernel Modules for Offensive and Defensive Purposes   |
| 18:30 | Call it a day |  |    |



## Sunday, October 20th, 2019 - Conference schedule


| Time  | Track 1 Intro to Offense                                     | Track 2 Intro to Dark Arts                             | Track 3 Advanced  |
| :---: | :----------------------------------------------------------- | :--------------------------------------------------- | :--------------------------------------------------- |
| 09:00 | Windows Pwning                        | Getting Started with CTFs                                         | Scripting the Reverse of Malware using Miasm   |
| 13:15 | Lunch          |          |
| 14:15 | Intro to ROP                             | Getting Started with CTFs | Scripting the Reverse of Malware using Miasm   |
| 18:30 | Call it a day |  |    |



## Monday, October 21th, 2019 - Conference schedule


| Time  | Talk                                                         | Presenter                                            |
| :---: | :----------------------------------------------------------- | :--------------------------------------------------- |
| 09:00 | Welcome :D                                                   |                                                      |
| 09:30 | Introduction to Web Application Penetration Testing          | [Andrea Hauser](https://twitter.com/aha_181)         |
| 10:00 | Fingerpointing false positives                               | [Desiree](https://twitter.com/d3sre)                 |
| 10:30 | Compiler Bugs and bug compilers                              | [Mari0n](https://twitter.com/pinkflawd)              |
| 11:30 | Linux Kernel and/or Driver Development 101                   | Anna-Lena                                            |
| 12:30 | BinCAT: purrfecting binary static analysis                   | Sarah Zennou                                         |
| 13:00 | Lunch                                                        |                                                      |
| 14:00 | Exploiting bug report systems in the game industry           | [Andreia Gaita](https://twitter.com/sh4na)           |
| 15:00 | A QuickLook at macOS cache forensics                         | [Kinga Kieczkowska](https://twitter.com/kieczkowska) |
| 15:30 | Don’t think outside the box - keep it to yourself (and your VM) | Bell Levin                                        |
| 16:00 | Closing Remarks                                              |                                                      |

Please notice that the registration will be worked on FIFO basis and the space is limited. Be sure you check the prerequisites for the workshops before signing in, as you can only sign for a track and not for a single class.

The conference day will be on Monday and the schedule for it can also be found if you just scroll down for some seconds :)

Also, please note that we cannot cover travel or accommodation for attendees. We'll be able to provide one or another snack though. More details will be communicated prior to the event.

## **What is BlackHoodie?**

BlackHoodie is a series of free, women only hacker bootcamps, which started in 2015, and since 2018 started going global. BlackHoodie Bay Area is organized in cooperation with Google, and in 2018 was the first BlackHoodie event to be held within the United States. More information on the idea of BlackHoodie and upcoming other events can be found at [www.blackhoodie.re](https://www.blackhoodie.re/).

## **Why women only?**

The number of female engineers working on complex low level security topics is crushingly low. My past teaching experience shows me, that is not due to lack of interest in challenges, but has to do with aspiring hackerettes sporting impressive anxieties. And I get it, modern day computer security is an intimidating field, and the fact that this field's engineers are usually all male, fancy death metal fashion and are offensive by definition, doesn't help. But, among us, one doesn't need to be male and death metal to be successful there. The BlackHoodie workshops aim to make complex subjects more tangible and less intimidating for women, in order to get motivated hackerettes started on their security careers. It is not about building walls around a minority, but about creating space, where participants can build confidence, foster shared interests, build connections, and in the end contribute themselves as part of a happier community. It keeps fascinating me how many former BlackHoodies keep sticking around, and do impressive work in several different areas of security.
