<!SLIDE title-slide>
# The Pentester's Study Group

## Session 1: Introductions and Tools

> “If the mind is to emerge unscathed from this relentless struggle with the unforeseen, two qualities are indispensable: first, an intellect that, even in the darkest hour, retains some glimmerings of the inner light which leads to truth; and second, the courage to follow this faint light wherever it may lead.” (Carl von Clauswitz, 'On War')

Weltgeist ( weltgeist@protonmail.com ) <br/>
August 29th, 2016

<!SLIDE>
# Goals of the Group

1. Develop practical skills as penetration testers, ie, as users of penetration testing tools.
1. Develop a theoretical and intuitive sense of computer / systems security.
1. (Optional) Develop skills as exploit & attack chain developers and reverse engineers. Intended for those already with software building experience.
1. Longer-term goal: building a volunteer red team and its technical supporting team. Intended for testing open source community systems like [TOMesh](https://tomesh.net/), participation in competitions, giving talks, etc.
1. Have fun and become excellent. Seriously.

<!SLIDE>
# What we **won't** be doing
- Malicious / illegal shenanigans: **Do not exploit what you don't own, or explicitly have permission to test.** All of our labs will be on our own machines, or other systems we've set up as a group.
- Teaching you how to break the law, condoning illegal activities

<!SLIDE>
# About Me
- Software engineer and SCRUM master by profession
- Web development, DevOps, continuous integration, system administration, help desk
- Interests: Security and privacy, technologies as they relate to human rights and freedoms, geopolitics, and the militarization of cyberspace
- Auxiliary interests: geopolitics, military history, history of technology, economics, mathematics

<!SLIDE>
# The scope of penetration testing
- Simulating the behaviour of an attacker, attempting to gain access to a computer system in ways not intended by designers, or the security policy.
- Typically done against corporate environments with high security / privacy requirements, or applications. Scope of what the pentester is allowed to test is always declared in a contract.
- Pentesting has come a long way -- user-friendly point-and-cilck applications simplifies experience. Libraries and frameworks shorten development time. Automation. Also means attackers draw on the same technologies and knowledge-base
- This group isn't just about pentesting particular networks or your home systems (although is much what we're doing) -- it's about studying existing applications, systems, topologies, and services from an offensive perspective.

<!SLIDE>
# To build a Cyber Warrior

## Pre-requisites
1. Basic Unix/Linux familiarity
    1. The shell (bash, zsh, etc): file system traversal and manipulation, `find`, `grep`, a terminal text editor (`vim`, `nano`, `pico`, or `emacs`)
    2. Basic system diagnostic and services tools like `top`, `ps`, `dmesg`, `systemd` and `systemv`
    3. Basic familiarity with at least one Linux distro. You may use Kali Linux if you want, but not required.
2. Basic understanding of networking
    1. OSI model, TCP/IP stack, IPv4
    2. Basic network diagnostic tools like `ping`, `tracert`, `ifconfig`, `iproute2` suite,
3. Self-guided learning.
    1. Knowing how to get help (manpages, Wikis, user groups, Stackoverflow, tutorials, Freenode, books)
    2. Being courteous when asking and answering questions

## Exploit Developer Prereqs:
1. Familiarity with at least one programming language
    1. (Recommended) Popular languages in InfoSec: Ruby and Python
2. Bonus: Systems or Network programming
    1. C/C++, Assembly

<!SLIDE>
# Phases
1. Reconnaissance
2. Scanning
3. Exploitation & Malicious payload
4. Covering your tracks and exit
5. Reporting and reflection


<!SLIDE>
# Scanning and Exploitation
1. 

Many pentesting course don't focus much on why these exploits work
<!SLIDE>
# Tools
- Metasploit Framework - a unified framework
- OWASP-ZAP - optimized for web application exploitation
- Wireshark / tcpdump
- ettercap
- nmap
- john / Hashcat

<!SLIDE>
# Metasploit

<!SLIDE>
# Lab: Exploit a Metasploitable machine


<!SLIDE>
# Lab: Exploit a Windows machine


<!SLIDE>
# Home Labs (Pick one)
1. Demonstrate a successful man-in-the-middle attack against a machine and a routerm (ettercap)
2. Exploit a vulnerability in a Windows or OS X system that has been updated within the past 6 months and gain remote access. (MSF)
3. Compromise a well-known webserver like Apache, Nginx, or IIS, or a web application framework like Django, Ruby on Rails, Node.js, etc. (MSF, OWASP-ZAP)
4. Set up a wireless router using WEP encryption and break it with aircrack-ng. Why is aircrack-ng successful? Explain WEP's vulnerability.

<!SLIDE>
# Further Reading
## Theory
- *Gray Hat Hacking: The Ethical Hacker's Handbook* (4th edition) by Daniel Regaldo, et al. McGraw-Hill, 2015
- *Reverse Engineering for Beginners* by Dennis Yurichev. http://beginners.re/
- *Cryptography Engineering* by Bruce Schneier
- *Computer Networks* (5th edition) by Andrew Tanenbaum, David Wetherall. Pearson 2011

## Practice
- https://www.metasploit.com/
- *Violent Python*
- *Blackhat Python*
- https://nmap.org/

## Other
- *2600: The Hacker Quarterly*
