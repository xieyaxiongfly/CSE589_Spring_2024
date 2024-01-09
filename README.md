---
layout: home
title: CSE589 Modern Networking Concepts 
nav_exclude: true
permalink: /:path/
seo:
  type: Course
  name: Modern Networking Concepts 
---

## Modern Networking Concepts 
{: .fs-9 } 

Spring 2024, University at Buffalo 
{: .fs-6 .fw-300 }

**Instructor:** 


{% assign instructors = site.staffers | where: 'role', 'Instructor' %}
{% for staffer in instructors %}
{{ staffer }}
{% endfor %}

{% assign teaching_assistants = site.staffers | where: 'role', 'Teaching Assistant' %}
{% assign num_teaching_assistants = teaching_assistants | size %}
{% if num_teaching_assistants != 0 %}
## Teaching Assistants

{% for staffer in teaching_assistants %}
{{ staffer }}
{% endfor %}
{% endif %}

## Course Description

The course introduces basic elements of modern computer and telecommunication networks. The focus is on the four upper layers of the popular five-layer TCP/IP model. In each layer, the state-of-the-art hardware and software technologies are introduced. These include, for example, DNS, HTTP, SMTP, and P2P systems at the application layer, TCP/UDP protocols at the transport layer, routing and forwarding, intra-domain and inter-domain routing algorithms at the network layer, random access protocols at the MAC layer, and local area networks (Ethernet and WiFi). Advanced topics such as multipath TCP and software defined networking are also briefly discussed.

The objective of the course is to enable students to
- gain fundamental knowledge of computer and telecommunications networks
- understand various tradeoffs and choices in current networking technologies
- learn basic network programming
- prepare for studying advanced topics (e.g. CSE 620, CSE 630, CSE 646), and a career in the field of computer networking.

At the end of this course, each student should be able to:
- Have a good overall picture of computer networking in general and the Internet in particular.
- Have a rough idea of how various networking components (hardware/software) work and where they belong in the 5-layer protocol stack.
- Know how to do network programming in C/C++ under Unix.
- Know how to do basic performance analysis of popular networking protocols.
- Know how to use popular networking tools such as WireShark and iperf.
- Start reading more advanced/research-oriented networking materials.


## Lecture Time & Location

Tuesday 2:00PM-4:00PM, 440 Park Hall, North Campus

## Prerequisites

Students need to have some basic knowledge of operating systems, 
calculus and probability theory, data structures, and algorithms. 
In addition, they must be **proficient in C or C++ programming**.


## Required Textbook
<img src="/assets/images/cover_7th.jpg" alt="Alt text" width="100"> James F. F. Kurose and Keith W. Ross, "Computer Networking: A Top-Down Approach Featuring the Internet", 7th edition, Addison Wesley, 2017.



