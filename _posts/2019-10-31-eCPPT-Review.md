---
layout: post
title: eCPPT (PTP) Review
---

## Overall

The PTP course was my first very in-depth penetration testing course after completing my eJPT (PTS), both from eLearnSecurity. At its fundamentals, it covers in-depth Windows and Linux exploitation, networking fundamentals, system security (buffer overflows), web exploitation, and if you buy the Elite version, you also get access to the Wireless and Ruby modules which are invaluable. I just recently sat for the exam and passed on my free retake (more on this later) and I could not have been happier with the information that this course has taught me. 

I will note ahead of time that though the eCPPT and eLearnSecurity as a whole may not have the industry recognition that they deserve (yet), I would still highly recommend this course for anybody interested in the realm of penetration testing. One of my favorite things about this course has been the practical nature of it from the Hera Labs which are fantastic and the fully practical exam. If you plan to take the OSCP, I highly recommend at least taking the eCPPT (or eJPT if you feel you aren't ready for it) beforehand to get yourself accustomed to some of the techniques and tools that penetration testers use and to establish a baseline methodology that you can use on any machine you encounter.

NOTE: PTP is the actual course and the eCPPT is the name of the certification you obtain after completing the course and passing the exam. For simplicity, I will refer to both as the eCPPT for the rest of this article.

## Pricing

The eCPPT pricing comes in three tiers: Barebone, Full, and Elite. I purchased the Elite tier which gave me access to all of the lectures as PDFs instead of HTML with the other plans, 120 hours of lab time with Hera Labs, an infinity voucher (regular voucher expires six months after you begin the course), and access to the Wireless and Ruby sections of the course. The Barebone tier comes in at $1199, Full tier comes in at $1299, and the Elite tier comes in at $1599. I was lucky enough to get this purchase reimbursed through my employer so I highly recommend you pursue this avenue if possible.

NOTE: eLearnSecurity does have sales occasionally during times like Black Friday (coming up soon) and other random months throughout the year, I would subscribe to their mailing list to stay up to date for any discounts to this course.

## Course

The course is divided into a few sections including: System Security, Network Security, Powershell for Pentesters, Linux Exploitation, and Web App Security (not including Wifi and Ruby from Elite Version). I will discuss each of the individual sections down below.

### System Security

The materials for this section were highly technical and this is undoubtedly the hardest part of the course to understand completely. This section goes into the technical aspects of buffer overflows, shellcoding, cryptography, and assemblers. Admittedly, this is the section of the course that I studied the least as I figured I could get by knowing how to perform a buffer overflow and then focus on actually understanding each step that is happening after I passed the course. 

This approach worked for me and by no means am I going to suggest an approach that you should follow. I will say that you can get by with knowing how to perform a basic buffer overflow without modern protetion like ASLR and DEP. 

### Network Security

Coming from a networking background in college, this was my favorite section of the course. This section discussed how to scan targets, enumerate services and ports running on them as well as how to exploit services running on a machine. The post exploitation module of this section was by far invaluable and showed many different ways to search for important information on a machine after you have already acquired access. This is one section that you absolutely cannot overlook for a future in penetration testing and for the exam. 

I'd also like to note that this section does include modules on Sniffing and MITM attacks. This was extremely interesting material and it will be very helpful for future engagements where this is in scope.

### Powershell for Pentesters

Having never touched Powershell in my life, this section went into a very in depth look at how attackers can utilize Powershell to attack Windows systems and perform post-exploitation while evading detection. Powershell is highly useful in red-team engagements and this will definitely be a section to review as I pursue a career in penetration testing.

### Linux Exploitation

This section covered the fundamentals of Linux and common services you will see running such as Samba and multiple ways to attack it. It also covered historical vulnerabilities such as Shellshock and Heartbleed and though these are several years old and are mostly patched (one would hope), it still gives an idea of the types of vulnerabilites that can exist on Linux systems.

The most interesting part of this section for me was Linux privilege escalation. eLearnSecurity gave a fantastic breadth of things to enumerate when performing post exploitation and multiple vectors to use instead of the traditional Kernel exploit approach. One invaluable resource that I will paste down below that I used in addition to this section for privilege escalation is a blog post from g0tm1lk. 

<https://blog.g0tmi1k.com/2011/08/basic-linux-privilege-escalation/>
