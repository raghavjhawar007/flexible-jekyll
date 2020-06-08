---
layout: post
title: Getting Started With Web Application Security
date: 2020-06-08
description: Web Application Security
img: web.jpg # Add image post (optional)
fig-caption: # Add figcaption (optional)
tags: [Web Application Security,Security,Pentesting,InfoSec]
---


First of all, I would like to thank you for coming here. This Blog is mainly focused on the people who are willing to get into Web Application Security. I will be sharing my resources and also my personal Experience from where I started learning Web Application Security.

### Let's get started.

I have heard many of them saying that you don't really need Development knowledge to get started with security. But, this is just partially true. I believe if you can code, you can break too, and that is how you learn security the hard way.
Web Application Security mainly comprises of Web Application Vulnerabilities which is exploited by an attacker mostly when there is a mistake in the developer's code.
![Macbook]({{site.baseurl}}/assets/img/dev.png){: .center-image }

### Pre-requisite to get started into Web Application Security.

So this is complete with my own experience, if you know a basic development you will be able to understand the vulnerability in a better way and also you will try to attack the application on keeping the developer's perspective too.
I strongly recommend starting with Basic Web Development. Learn the Basics of programming languages like PHP, MySql, Javascript.
When you are done with the basics of web development and once you will study Web Vulnerabilities, it will be easy for you to get in-depth exposure to the application.

### How I started: 
I had prior knowledge of Java Programming because I had learned in my school times. I did Python coding for a few months too so learning Languages like PHP was not much trouble for me. In August 2017, I started learning basic Web development. I followed lots of resources and courses from Udemy and another training website. After 2 months of proper Web Development, I was able to develop a website using PHP, MySQL, Javascript. I also learned a few basics of MongoDB, NodeJS, Jquery, Bootstrap. I was more or less now comfortable with Web Development. I took a project of my cousin to develop a website. I developed a website from Scratch using everything I had learned in my early stages.
> Link to the website-: [http://researcheers.com](http://researcheers.com)


The website got up in February 2018. The website which I had developed was missing the most important part i.e Security. But by then I didn't know anything about Web Application Security. 

Can you guess My next target?

### Time to Get started with Web Application Security.

![Macbook]({{site.baseurl}}/assets/img/party.jfif){: .center-image }

I started with a few free resources at first. I just took the overview of Basic vulnerabilities for a few weeks. 
OWASP Top 10- When you are getting into Web Application Security, you need to thoroughly know about Owasp top 10 asked in almost every security interview.
For OWASP Top 10- I also went through the Troy Hunt's Course on Pluralsight-: OWASP Top 10 2013-The Big Picture, which helped me to get an idea about basic top ten vulnerabilities.

I then started with one vulnerability and would go through different blogs, resources, and Labs. 
I took around 1.5 months to complete all the basic vulnerabilities.


> PortSwigger's Web Security Academy is one of the best resources I have come across lately, which is beginner-friendly and provides in-depth insights into vulnerabilities.

> Web Application Hacker's Handbook(WAHH) - This is called the Bible for those who are just getting started with Web Security Academy.

> Owasp Testing Guide.

> Modern Web Penetration Testing by Prakhar Prasad-: 
If you have got your basics clear and you want to study little extra and advanced stuff, then this is the book for you. Very Well documented and also the author has shared a few test cases to help you understand the Vulnerability in more depth. This is the only book that I keep in my backpack always.

### The above-mentioned resources are must read and one of the most recommended guides to get started. Please consider this first before going through the below-mentioned resources.

I would like to Mention Few Resources(Vulnerability wise) which I followed and which had helped me to get started.

### XSS-: 
Cross-Site Scripting is one of the most well-known vulnerabilities in Web Application Security, and also expected by every security researcher to have good command over it. 
### Resources:-
1. BruteLogic Blogs- [https://brutelogic.com.br/blog/](https://brutelogic.com.br/blog/)
The blogs on the website had helped me a lot in understanding the basics of XSS, its context, and its exploitability.
2. Ashar Javed's XSS Youtube videos-:
Links-: 
[https://www.youtube.com/watch?v=TKn5qdti66c&t=3364s](https://www.youtube.com/watch?v=TKn5qdti66c&t=3364s)
[https://www.youtube.com/watch?v=LLtOJNeMp7c](https://www.youtube.com/watch?v=LLtOJNeMp7c)

He is one of the great researchers who has done lots of research on XSS. I strongly recommend going through his videos.

3. Ajin Abraham XSS course from Udemy:
He is one of the most well known and finest researchers. If by chance you have an idea of Malware Analysis, MobSF- a very famous tool is one of its research. Though his course on Udemy is paid but it is worth taking.

4. SecurityIdiots.
Link: [http://www.securityidiots.com/](http://www.securityidiots.com/)

### Links to Practice XSS-:
1. [https://xss-quiz.int21h.jp/](https://xss-quiz.int21h.jp/)
2. [https://xss-game.appspot.com/](https://xss-game.appspot.com/)

### SQL Injection:-

![Macbook]({{site.baseurl}}/assets/img/sqli.jfif){: .center-image }

The most common and most critical vulnerability which exists till date. With SQLi, your entire database is at stake.

### Resources-:

1. SQLi Labs by AudiSec-: This is one of the best and in-depth resources that have got me to understand the SQL injection in depth. It has got Labs with around more than 75 challenges. Starting from Error Based SQLi and covering all tracks in SQLi like Blind, Time Based, Second Order SQLi, you name and you get everything here.

Link: [https://github.com/Audi-1/sqli-labs](https://github.com/Audi-1/sqli-labs)

2. SecurityIdiots-

Link-: [http://www.securityidiots.com/](http://www.securityidiots.com/)
       [http://leettime.net/sqlninja.com/](http://leettime.net/sqlninja.com/)

3. WAHH, Owasp testing guide.

### CSRF - Cross-Site Request Forgery.
CSRF is reported less nowadays due to the introduction of frameworks like Django. It was A7 in OWASP Top 10 2013.

Resources-

1. Troy Hunt - [https://www.troyhunt.com/understanding-csrf-video-tutorial/](https://www.troyhunt.com/understanding-csrf-video-tutorial/)

2. Link: [https://docs.spring.io/spring-security/site/docs/5.0.x/reference/html/csrf.html](https://docs.spring.io/spring-security/site/docs/5.0.x/reference/html/csrf.html)

### IDOR-: Insecure Direct Object Reference.

Resources:

1. [https://www.bugcrowd.com/blog/how-to-find-idor-insecure-direct-object-reference-vulnerabilities-for-large-bounty-rewards/](https://www.bugcrowd.com/blog/how-to-find-idor-insecure-direct-object-reference-vulnerabilities-for-large-bounty-rewards/)


2. [https://blog.detectify.com/2016/05/25/owasp-top-10-insecure-direct-object-reference-4/](https://blog.detectify.com/2016/05/25/owasp-top-10-insecure-direct-object-reference-4/)


### Other Basic Vulnerabilities-:

1. Local File Inclusion/Remote File Inclusion
2. OS Command Injection
3. Privilege Escalation

You can follow Portswiggers Lab, WAHH, OWASP Testing Guide for above these vulnerabilities.

### Places to practice:-

Once you have done the basic vulnerabilities, you can start working with online projects like- Owasp Web Goat, DVWA, Bwapp, Multidae, JuiceShop, and many more.

> "Hack to Learn, Not learn to Hack".
When you do hands-on, you will get better exposure to every vulnerability. I strongly recommend solving as many challenges as you can.

### Advanced Vulnerabilities-:

### 1. XXE attack- 
The most important and critical bugs reported these days and which eventually leads to a great bounty amount.

But before starting with XXE attacks, you should have basic knowledge of XML and its components like DTDs. 

At first, this vulnerability has troubled me a lot to understand, but the Modern Web Penetration Testing book helped me to understand the vulnerability and its impact. The book gave me a clear understanding of the XXE attacks.

For Labs, I followed PortSwigger, which gave me confidence.

### 2. SSRF -Server Side Request Forgery.
The vulnerability found by Orange Tsai and was presented in BlackHat. A critical vulnerability with a beautiful impact in itself.

### Resources-:
1. Portswigger
2. Modern Web Penetration Testing by Prakhar Prasad.

3. Links-:

   a. [https://medium.com/poka-techblog/server-side-request-forgery-ssrf-attacks-part-1-the-basics-a42ba5cc244a](https://medium.com/poka-techblog/server-side-request-forgery-ssrf-attacks-part-1-the-basics-a42ba5cc244a)
 
   b. [https://medium.com/@madrobot/ssrf-server-side-request-forgery-types-and-ways-to-exploit-it-part-1-29d034c27978](https://medium.com/@madrobot/ssrf-server-side-request-forgery-types-and-ways-to-exploit-it-part-1-29d034c27978)

   c. [https://www.netsparker.com/blog/web-security/server-side-request-forgery-vulnerability-ssrf/](https://www.netsparker.com/blog/web-security/server-side-request-forgery-vulnerability-ssrf/)
 
   d. [https://blog.detectify.com/2019/01/10/what-is-server-side-request-forgery-ssrf/](https://blog.detectify.com/2019/01/10/what-is-server-side-request-forgery-ssrf/)
 
   e. [https://www.acunetix.com/blog/articles/server-side-request-forgery-vulnerability/](https://www.acunetix.com/blog/articles/server-side-request-forgery-vulnerability/)
 
    f. [https://www.blackhat.com/docs/us-17/thursday/us-17-Tsai-A-New-Era-Of-SSRF-Exploiting-URL-Parser-In-Trending-Programming-Languages.pdf](https://www.blackhat.com/docs/us-17/thursday/us-17-Tsai-A-New-Era-Of-SSRF-Exploiting-URL-Parser-In-Trending-Programming-Languages.pdf)


### Other Advanced Vulnerabilities-:

Web Cache Poisoning, Server Side Template Injection, CORS Misconfiguration, HTTP Request Smuggling.

> Portswigger is one of the best resources which I could mention right now for the above mentioned advanced vulnerabilities.

![Macbook]({{site.baseurl}}/assets/img/practice.jpg){: .center-image max-width="100" }

### More sites to practice:-
There are plenty of websites online currently which has got great challenges to practice. Few of them are-:
1. Root-me.org
2. HackerOne 101
3. Hackthebox

### Importance of Python-:

Python is the most popular programming language amongst security researchers and also my favorite language. I strongly recommend every beginner to at least get basic hands-on experience in Python. I started learning python once I had decided to be in Security. HackerRank is the best place to solve Python challenges which will also help you to know various functions of python and also it is going to help you sharpen your logical skills. Python will help you to automate tasks which might be useful when you are doing Bug bounties.

![Macbook]({{site.baseurl}}/assets/img/lazy.jfif){: .center-image }

### Books for Python-:

1. Python- The Hard Way
2. Automating the boring stuff with Python.

If you are not a reader but like to watch videos, you can also go through the online Courses like:-

1. Python for security professional on Cybrary
2. Python for Security on Pentester Academy.

There are a few more development focussed courses on Udemy which will help you to understand Python in depth.

![Macbook]({{site.baseurl}}/assets/img/python.jpg){: .center-image }

I have tried to mention every resource and link which has helped me to get started with Web Application Security. Your Googling skills will help you a lot with security. If you wish you can google and can easily get more resources to learn. 
After you have got the basics clear and good understanding of the vulnerabilities, you should put your knowledge to practice in real-time. I strongly recommend starting with Bug bounties. With Bug bounties, you face real-time challenges and once you get used to bug bounties there is no looking back. I would also Recommend following Hacktivities, follow the best hackers on Twitter/LinkedIn. Make this a habit to go through your twitter feed every day. You should start reading Hackerone publicly disclosed reports.
To find Hackerone publicly Disclosed reports-: [http://h1.nobbd.de/](http://h1.nobbd.de/)

You can also follow a few telegram channel which will update you with the latest emerging bugs and technologies.

### Books for Bug hunting-:

1. Web Hacking 101 by Peter Yaworski
2. Real World Bug Hunting by Peter Yaworski.

![Macbook]({{site.baseurl}}/assets/img/bb.jfif){: .center-image }

> One more important thing which I would like to mention is to "Be Patient". You will not learn everything overnight, it will take you months. Start Slowly but learn the hard way.

This is all from my side for this blog. If you like the blog please do share. 
### Thank you again for coming here.
Feel free to connect with me on Twitter and LinkedIn.
