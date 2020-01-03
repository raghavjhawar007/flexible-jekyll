---
layout: post
title: OSCP 101- The Hard Way
date: 2020-01-04
description: You’ll find this post in your `_posts` directory. Go ahead and edit it and re-build the site to see your changes. # Add post description (optional)
img: oscp-certs.jpg # Add image post (optional)
fig-caption: # Add figcaption (optional)
tags: [OSCP,Security,Pentesting,InfoSec]
---

First of all thank you for coming here. This Blog post is about My experience in OSCP Journey. What all did I learn, Doing Hard work plus smart work, Trying Harder.

> I will be dividing this post into four sections- PRE Enrollment, POST Enrollment, mid time of labs and exam, Exam. 

* Pre-enrollment would be all about what you should do before taking up the labs, how you should prepare for OSCP Labs.
* Post-Enrollment would be all about OSCP labs and exam preparations and keeping your cheatsheets ready.
* Time between lab ends and Exam - What you should do when the labs has ended and your exam is a week later.
* Exam Day- For what all challenges you should be prepared for.

![Macbook]({{site.baseurl}}/assets/img/battle.jpeg){: .center-image }


### Pre-Enrollment:

I started to work for OSCP somewhere in May-June. To tell you about my basic knowledge, I was a noob when I started my journey though now also i consider myself a noob. I was learning then, I am learning now ,I ll do the same in future too. So, I had basic understanding of Networks,Linux, Python and also I knew about web application security. So was that enough to get directly enrolled to OSCP Labs?

I read couple of blogs(which I am gonna attach in the links section and I highly recommend reading those). I started with VULNHUB's OSCP like machines. Well It was not easy for me because I didn't know the methodology and what  "Enumeration is the Key" is all about. I faced lot of issues, had to see every machines walkthroughs. But after 3–4 machines of Vulnhub, I was little comfortable with the process- the Methodology. After a week or two, I started from HTB, well it was not at all easy and I highly recommend people preparing for OSCP should go for HackTheBox. I Struggled in few machines but atleast I knew by then how should I approach, what will I do when I come across certain kind of situation. Still, One thing was missing- Confidence, I was lacking confidence whether I would be able to crack OSCP or not. By further working on the same, I started watching IPPSEC videos(and that I think if I had done that earlier It would have been more easy for me or if not easy then the process of pentesting would be clear.) After Watching his videos of OSCP playlist, I made my notes and I knew my weapons are getting ready.

But Still I was missing something about which I had no Knowledge- our very own- Buffer Overflow. I was so afraid with the buffer overflow that I thought I would not do Buffer overflow machine in the exam. But everything is a mind game, Just know that mind works how you want it to work. I started searching for Buffer Overflow Blogs , videos, courses but nothing seemed working because I was facing issues to understand registers of assembly language(don't worry, it was my bad because Buffer Overflow is basic in OSCP). I locked myself in the house for three days and studied Assembly Language, Registers and Buffer Overflow, 4th day I had no doubts on Buffer Overflow. You can get clear with Buffer Overflow machine in less than 1 hour.

Also, I didn't want to leave anything untouched before taking labs. I tried understanding the concepts of Port Knocking,Pivoting, Port forwarding but you cannot understand anything unless you practice it couple of times. I read couple of blogs and followed them for Privilege Escalation in Linux and Window, to clear the approach. I had few tools ready too for privilege escalation which helped me a lot in my labs. 

> Note: I would highly recommend two telegram groups where people are so helpful that if you get stuck, you can ask them and someone would reply for sure. Please find link in the Links section.I had just shared one group link because other one is private.

![Macbook]({{site.baseurl}}/assets/img/sixhours.png){: .center-image }

> By now, I knew that "Enumeration is the key", "Google is always your best friend", and "It's all about dedication, Hard work, and Patience".

### The basic takeaway and what I recommend is-: 
* Buy Hackthebox 1 month VIP membership( This will boost your confidence and Htb is real time, you will learn a lot)
* Do vulnhub's OSCP like VMs(Follow Abachy's blog for this)
* Watch IPPSEC videos everyday before taking labs.
* Do look buffer overflow a little.
* Keep your weapons ready.

> Remember one thing, "Every Battle is won before it is fought". How you prepare for your goals is most important thing.


### Post-Enrollment:

One month before Enrolling, I worked to prepare myself for the labs. I took a short break, Enjoyed with my friends a little and Now it was time to enroll for this giant and expensive course. Mostly People advised me to go for atleast two months lab access. But Hey, I am a warrior(as Zakir Khan said- Bhai Tumhara Warrior hai),After discussing with my brother( Because he had cleared OSCP in 2013 when No HTB , vulnhub and Ippsec's page existed, He is a legend) and also with few legends in InfoSec, I decided to go for one month because I wanted to challenge myself this time. I enrolled and I got lab access on 18th August. I quickly finished the lab videos and pdf. I jumped into the labs. Well, I was not able to pawn even a single machine by the evening. I took a short break and came back, I rooted 2 machines in next few hours. I was happy. I made a prime target of rooting atleast two machines everyday for the first week and trying atleast 3 machines every day. I divided my slot of 5–5hours, and then I fell sick because I had left everything and was spending too much time on the terminal.Even after falling sick I was still trying to pawn machines. After 2 days I was okay. I started again and now working smartly i.e keeping health and labs balanced. I had rooted 15 boxes in very first week and that was quite a good progress.

> Here, I would suggest that setting short targets are better, and in the labs you should know one day before that what machines you are going to try the next day.

My Target for 2nd week was to do 1 boxes every day because now boxes which will come would be little tricky. I completed my targeted, then my family visited me and I took a break for around 5 days. I started again and this time with more enthusiasm and I decided that I will try to do Big 4 boxes before my lab ends. I did three of them. The most frightening part on this journey was Windows Privilege Escalation and frankly speaking there are not much machines in the labs where you will learn privilege escalation of windows, In most machines you'll directly get privileges of the Administrator. So I decided to go through few blogs . My Lab ended on 17th September and I was able to root 35 machines in 25days. I scheduled my exam for 24th September at 2:30pm. That was a great experience, I knew my weapons, was clear with my methodology and also I was clear with my next target. I went through Ippsec videos , notes and buffer overflow.

> Also, Make Sure you do Post Exploitation while rooting the machines because I didn't do Post Exploitation in my first week so I had to do all the machines again and complete post expoitation, that took another two days.

![Macbook]({{site.baseurl}}/assets/img/whoami.jpeg){: .center-image }

### Usage of Metasploit-: 
I did Use metasploit on few machines but I just marked them and when My lab was ending and making sure that I was able to root those with an intended way. Use Metasploit if it is needed but Make sure you do those machines again with the intended way. Metasploit is powerful and this will be always there with you.

What you should do in Post Exploitation is Save- Hashdumps, shadow+passwd file, arp and route history, Mail if any,Password of any new user you found in any machine.

### Total Machines Rooted in 25days  - 35, Networks Unlocked- 2

### Basic Takeaway-:
* Set Short Goals(per week wise)
* Just Understand the methodology and enumeration process.
* Try Not to use Metasploit much (but you should know how to use it).
* Keep reading blogs, reviews(that keeps you motivated).
* Post Exploitation
* Try Harder

> The basic Takeaway from above is just be clear with your goals. Set Small small targets and don't think about next week, just complete this week first. Setting a small and achievable target is the key here. Stay motivated by reading blogs.


### The Time Before Exam and After Labs-:

I had completed my labs with great count of machines pawned. I scheduled my exam a week after. I planned this week of mine in such a way that I relax also and revise my notes too, including practicing buffer overflow. I planned to do Buffer Overflow everyday and my final goal was to complete buffer overflow in less than 15 mins when I was practicing, the reason to this was since there were not much BadChars present in the vulnerable applications I found online. The idea behind doing this was I wanted to keep atleast 5–10mins in exam for BadChars. By the end of the week, I was able to complete buffer overflow in 12mins and that was quite great. I revised all my notes I had made since last two months(i.e Notes from Pre Enrollment and also from Post). I went through IPPSEC's OSCP playlist again and saw few VulnHub machine's walkthrough along with Privilege escalation blogs. Finally, I stopped my studies two days before exam and enjoyed those two days like anything.

![Macbook]({{site.baseurl}}/assets/img/keep-calm.png){: .center-image }


### The Big Day- The Exam:

Frankly speaking, I was not afraid even a day before, but on the exam day I was hell lot afraid. Everyone around me motivated me a lot still nothing seemed to work, but I knew I had worked hard in my labs so whatever happens I was ready. I set my short target (as always) to do 2 machines(i.e Buffer Overflow and 10mark) before 5pm. My exam started at 2:45 after the setup and everything. I jumped into Buffer Overflow also Running few scans in the background for other machines. I took proper screenshots of each steps and Noted my points( I highly recommend using cherrytree for penning down your notes because it makes your work easy). I finished my buffer overflow in 25–30mins. I was happy and motivated. Also I had thought I would Not close any terminal windows(which is a good practice one should do or Use TERMINATOR in Linux) in case I forget to take any screenshot of terminal commands I would refer while making report. But not always your strategy works, and this time my laptop Hanged, which was not at all expected because I had given 8gb ram to my Kali Linux  host. I quickly hard rebooted my laptop but I had lost all my terminal commands. I started my scans again and the 10marks machines irritated me a lot. I was doing everything correctly but I was getting some errors. It was 5:10 but I was not able to achieve my target. I decided to go for 20marks, but again some errors which was not expected. I quickly switched to OffSec VM(Please Use OffSec's VM else you will also face some issues like SSL errors and others). I was able to root both my 20marks machines before 7:30. So by now, I had 65 marks in my hand. I again Started 10marks Machine, this time on OffSec VM, and I completed my machine this time. Huh, I had passed my exam by 8:30 with proper breaks in Between. I took a long break for dinner but I ran my recon scans so that When I am back I could just jump into exploitation part. At 12:30, I got user shell of that 25marks machine. I Enumerated but failed to escalate the privileges. I decided to sleep. But for 2 hours I could not sleep. I slept at 3 then at 6:30 my father called me(because He was expecting me that I will be awake by now..Lol). I had already decided to sleep ignoring my alarm like anything. But I woke up at 7(which still I think was a big mistake, please have proper sleep of atleast 5–6hrs). I started working on my last Priv Esc again. I tried everything , used everything I knew and but at 12, I was frustated. I called my brother and said I won't be able to do now because It's frustating. I just left my laptop and took a break. I went back but this time I wanted to check all my notes - whether I have taken proper screenshots, Whether I have taken proper flags with IP addresses, Checked my url links in the screenshots so that I am sure that my report Would not trouble my progress.

 At 2:15, my exam ended and I was happy that I had rooted 4.5 machines. Now it was time for the report.

### Takeaways from here:-
* Don't Panic,Stay Calm and Trust Your preparation.
* Take Proper Screenshots with flags and IP address.
* Set small targets i.e Divide your 24hrs in such a way that you don't get stuck a lot on one machine for too long.
* Take Regular Breaks.
* Check Your Screenshots 1hr before ending your exam.
* Try Not to close terminal windows.
* Try Harder and Try again.


### The Report:-

You have done your exam, you have rooted required machines. Now what? OffSec gives you 24hrs to complete your report. Report is the most important part. I spent around 5–6hours to complete my report with proper proof of concepts. Please make sure you have attached every flags along with IP addresses showing that you have got access of right target machine. Highlight every important details in the report and also make sure You have written terminal commands(if any like running exploits, generating Shellcode). The most important point before sending your report is read the EXAM GUIDE carefully. Proper zipping and password protection is needed before sending your report.

After you have send your report Just Relax and Wait for your results.

### Basic Takeaways from here:-

* Read Exam Guide carefully
* Highlight and mark every important details like flags, IP address, terminal commands and the like.
Finally , I got my Results . I got a mail from offensive security in the morning 4:26am. I had literally woke everyone up. I called everyone at 5 itself. For a moment I could not actually believe that I have got my results.Well, Everything went well.I would like to Thank offensive security team for this amazing course.

![Macbook]({{site.baseurl}}/assets/img/index.jpeg){: .center-image }


Finally, I have tried to include every possible meaningful experience of mine and the challenges I faced in this journey.
But Before ending my blog I would like to Thank everyone who supported me throughout.

> Special Mentions - My whole family(Papa,Mummy,Bhabhi,Di,Specially Bhaiya- Ajay Srivastava) , Prakhar Prasad Bhaiya, Pushkar Bhaiya, Pulkit Bhaiya, Dhanajay Bhaiya, Anjana and many more.


### Important Links-:

### How To Prepare:- 

[https://www.abatchy.com/2017/03/how-to-prepare-for-pwkoscp-noob](https://www.abatchy.com/2017/03/how-to-prepare-for-pwkoscp-noob)

[https://www.netsecfocus.com/oscp/2019/03/29/The_Journey_to_Try_Harder-_TJNulls_Preparation_Guide_for_PWK_OSCP.html#section-13-port-redirection-and-pivoting](https://www.netsecfocus.com/oscp/2019/03/29/The_Journey_to_Try_Harder-_TJNulls_Preparation_Guide_for_PWK_OSCP.html#section-13-port-redirection-and-pivoting)

[https://www.abatchy.com/2017/02/oscp-like-vulnhub-vms](https://www.abatchy.com/2017/02/oscp-like-vulnhub-vms)

[https://github.com/0x4D31/awesome-oscp](https://github.com/0x4D31/awesome-oscp)

[https://scund00r.com/all/oscp/2018/02/25/passing-oscp.html#interactive-shell](https://scund00r.com/all/oscp/2018/02/25/passing-oscp.html#interactive-shell)


### Telegram Group - [https://t.me/OSCP_OSCE](https://t.me/OSCP_OSCE)


### Priviledge Escalation and cheat sheets:-

### Linux Priv Esc-:

[https://github.com/lucyoa/kernel-exploits](https://github.com/lucyoa/kernel-exploits)

[https://github.com/SecWiki/linux-kernel-exploits](https://github.com/SecWiki/linux-kernel-exploits)

[https://github.com/rebootuser/LinEnum](https://github.com/rebootuser/LinEnum)

[https://github.com/mzet-/linux-exploit-suggester](https://github.com/mzet-/linux-exploit-suggester)

[https://github.com/jondonas/linux-exploit-suggester-2](https://github.com/jondonas/linux-exploit-suggester-2)


### Windows Priv Esc-:

[https://sevrosecurity.com/checklists/windows-priv-esc/](https://sevrosecurity.com/checklists/windows-priv-esc/)

[http://virgil-cj.blogspot.com/2018/02/escalation-time.html](http://virgil-cj.blogspot.com/2018/02/escalation-time.html)

[https://github.com/rasta-mouse/Sherlock](https://github.com/rasta-mouse/Sherlock)

[https://github.com/SecWiki/windows-kernel-exploits](https://github.com/SecWiki/windows-kernel-exploits)

[https://github.com/AlessandroZ/BeRoot](https://github.com/AlessandroZ/BeRoot)

[https://github.com/frizb/Windows-Privilege-Escalation](https://github.com/frizb/Windows-Privilege-Escalation)

[https://hackingandsecurity.blogspot.com/2017/09/oscp-windows-priviledge-escalation.html](https://hackingandsecurity.blogspot.com/2017/09/oscp-windows-priviledge-escalation.html)

[https://toshellandback.com/2015/11/24/ms-priv-esc/](https://toshellandback.com/2015/11/24/ms-priv-esc/)

[https://sushant747.gitbooks.io/total-oscp-guide/privilege_escalation_windows.html](https://sushant747.gitbooks.io/total-oscp-guide/privilege_escalation_windows.html)


### Cheat Sheets and other Useful Links:

[http://www.0daysecurity.com/penetration-testing/enumeration.html](http://www.0daysecurity.com/penetration-testing/enumeration.html)

[https://ired.team/offensive-security-experiments/offensive-security-cheetsheets](https://ired.team/offensive-security-experiments/offensive-security-cheetsheets)

[https://www.greyhathacker.net/?p=500](https://www.greyhathacker.net/?p=500)

[https://netsec.ws/?p=337](https://netsec.ws/?p=337)

[https://github.com/doffensive/wired-courtyard](https://github.com/doffensive/wired-courtyard)

[https://github.com/sagishahar/lpeworkshop](https://github.com/sagishahar/lpeworkshop)

[https://jivoi.github.io/2015/07/01/pentest-tips-and-tricks/](https://jivoi.github.io/2015/07/01/pentest-tips-and-tricks/)


### Verify my OSCP Badge Here:
> [https://www.youracclaim.com/badges/3d792a25-00f2-4c61-b9ad-7d2b65d383d2/public_url](https://www.youracclaim.com/badges/3d792a25-00f2-4c61-b9ad-7d2b65d383d2/public_url)
