<!SLIDE title-slide>
# PentestTO: The Pentester's Study Group

## Session 1: Introductions and Tools

> “If the mind is to emerge unscathed from this relentless struggle with the unforeseen, two qualities are indispensable: first, an intellect that, even in the darkest hour, retains some glimmerings of the inner light which leads to truth; and second, the courage to follow this faint light wherever it may lead.” (Carl von Clauswitz, 'On War')

Weltgeist ( weltgeist@protonmail.com )

August 29th, 2016

<!SLIDE>
# Goals of the Group

1. Develop practical skills as penetration testers.
2. Develop a theoretical and intuitive sense of systems security.
3. (Optional) Develop skills as exploit & attack chain developers and reverse engineers.
4. Longer-term goal: building a volunteer red team and its technical supporting team. Intended for testing open source community systems like [TOMesh](https://tomesh.net/), participation in competitions, giving talks, etc.
5. Have fun, empowerment, and become excellent.

<!SLIDE>
# DISCLAIMER: What we **won't** be doing
- Malicious / illegal shenanigans: **Don't exploit what you don't own, or explicitly have permission to pentest.** All of our labs will be on our own machines, or systems we've set up as a group.
- Teaching you how to break the law, condoning illegal activities

<!SLIDE>
# About Me
- Software engineer and SCRUM master by profession
- Web development, DevOps, continuous integration, system administration, help desk
- Interests: Security and privacy, technologies as they relate to human rights and freedoms, geopolitics, and the militarization of cyberspace
- Auxiliary interests: geopolitics, military history, history of technology, economics, mathematics

<!SLIDE>
# What is Penetration testing?
- Simulating the behaviour of an attacker, attempting to gain access to a computer system in ways not intended by designers, or the security policy.
- Typically done against corporate environments with high security / privacy requirements, or applications. Scope of what the pentester is allowed to test is always declared in a contract.
- Pentesting has come a long way -- user-friendly point-and-cilck applications simplifies experience. Libraries and frameworks shorten development time. Automation. Also means attackers draw on the same technologies and knowledge-base
- This group isn't just about pentesting particular system implementations -- it's about studying existing applications, systems, topologies, and services from an offensive perspective.

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

- Attack vectors

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
# Home Labs (Pick one, work in groups of 2 if necessary)

1. Demonstrate a successful man-in-the-middle attack between a machine and its router (`ettercap`), and inspect the traffic with a tool like `Wireshark`. Navigate to various HTTP and HTTPS websites. What kind of information can you see? What is encrypted? What is in plaintext?

2. Using MSF modules, exploit a vulnerability in Windows, OS X, Flash or Java that has been updated/patched within the past 6 months and gain remote access. Which CVE(s) does your exploit use? How did it work, and what did the fix do to solve the problem?

3. Compromise a well-known webserver like Apache, Nginx, or IIS, or a web application framework like Django, Ruby on Rails, Node.js, etc. (MSF, OWASP-ZAP)

4. Set up a wireless router using WEP encryption and break it with `aircrack-ng`. How does `aircrack-ng`'s attack work, and why is it so successful? Explain WEP's vulnerability.

5. Establish an SSH session with your own dummy SSH server, and use `Wireshark` or `tcpdump` capture the packets of the session. Decrypt the payload of the packets using the private key. Look into the concept of "Forward Secrecy" and explain why it's important.

6. With only using standard compilers, C/C++ or ASM, and the standard library of your language, write a program that injects shellcode to give you shell access to a Linux, Windows or Mac OS X machine.

7. Develop a plugin for MSF for an exploit that currently does not have an MSF implementation. Explain and demonstrate the vulnerability live for us. Tell us about your experience researching the vulnerability and programming the plugin.

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
