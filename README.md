# Cybersecurity Penetration Testing Learning Path

A self-directed learning path for cybersecurity penetration testing, covering fundamental concepts, web application hacking, network security, and Active Directory exploitation. This path was inspired by a [Reddit comment by wolfxanta](https://www.reddit.com/r/cybersecurity/comments/1az6o84/comment/ks2ygi9/).

I've significantly modified the original order and titles of the items, prioritizing core concepts before diving into practical applications. I've also updated materials, removed outdated resources (like sub3lister), and included **PortSwigger Academy** as a primary resource due to its exceptional quality in web security. It complements TryHackMe rooms, especially those requiring premium subscriptions, and I've integrated supplementary YouTube resources.

Please note that an AI chatbot assisted with numerous suggestions and recommendations, given my limited experience in the field.

I'll be updating the checklist items as I complete them to track my progress and stay motivated!

---

## Key

- `[ ]` - **To Do:** Item not yet started.
- `[x]** - **Done:** Item successfully completed.
- **(THM)** - TryHackMe Room
- **(PSA)** - PortSwigger Academy (Free, includes labs)
- **(YT)** - YouTube Playlist/Video (Free)
- **(Other)** - Other free resources/platforms

---

## My Progress

Here's a snapshot of my current learning journey:

**Overall Completion:** Approximately **35%** complete (19 out of 55 items finished).

**Last Updated:** May 31, 2025

---

### Level 1: Core Foundations

**Goal:** Understand basic concepts, Linux, networking, and how to connect & research.

- [x] **(THM)** Welcome - [https://tryhackme.com/jr/welcome](https://tryhackme.com/jr/welcome)
- [x] **(THM)** Intro to Researching - [https://tryhackme.com/room/introtoresearch](https://tryhackme.com/room/introtoresearch)
- [x] **(THM)** OpenVPN - [https://tryhackme.com/room/openvpn](https://tryhackme.com/room/openvpn) (Essential for connecting)
- [x] **(THM)** Learn Linux - [https://tryhackme.com/room/zthlinux](https://tryhackme.com/room/zthlinux)
- [x] **(THM)** Linux Fundamentals Part 2 - [https://tryhackme.com/room/linuxfundamentalspart2](https://tryhackme.com/room/linuxfundamentalspart2)
- [x] **(THM)** Linux Fundamentals Part 3 - [https://tryhackme.com/room/linuxfundamentalspart3](https://tryhackme.com/room/linuxfundamentalspart3)
- [x] **(THM)** What the Shell? - [https://tryhackme.com/room/whattheshell](https://tryhackme.com/room/whattheshell) (Understanding shells, reverse/bind shells)
- [x] **(THM)** Crash Course Pentesting - [https://tryhackme.com/room/ccpentesting](https://tryhackme.com/room/ccpentesting) (Broad overview)

---

### Level 2: Essential Tools & Reconnaissance

**Goal:** Get comfortable with core pentesting tools and information gathering techniques.

- [x] **(THM)** tmux - [https://tryhackme.com/room/rptmux](https://tryhackme.com/room/rptmux) (Terminal multiplexer)
- [x] **(THM)** Nmap - [https://tryhackme.com/room/rpnmap](https://tryhackme.com/room/rpnmap) (Network scanning)
    - _Also explore Nmap's official documentation and other THM Nmap rooms like "Nmap Live Host Discovery" and "Nmap Basic Port Scans" within the "Nmap" module if you need more depth._
- [x] **(THM)** Burp Suite: The Basics - [https://tryhackme.com/room/burpsuitethebasics](https://tryhackme.com/room/burpsuitethebasics)
- [x] **(THM)** Burp Suite Repeater - [https://tryhackme.com/room/burpsuiterepeater](https://tryhackme.com/room/burpsuiterepeater)
- [x] **(THM)** Metasploit: Introduction - [https://tryhackme.com/room/rpmetasploit](https://tryhackme.com/room/rpmetasploit) (Learn the basics, but aim for manual exploitation later)
- **OSINT (Open Source Intelligence):**
    - [x] **(THM)** Google Dorking - [https://tryhackme.com/room/googledorking](https://tryhackme.com/room/googledorking)
    - [x] **(THM)** OhSINT - [https://tryhackme.com/room/ohsint](https://tryhackme.com/room/ohsint)
    - [x] **(THM)** Shodan.io - [https://tryhackme.com/room/shodan](https://tryhackme.com/room/shodan)
- **Content Discovery & Web Scanning:**
    - [x] **(THM)** Web Scanning - [https://tryhackme.com/room/rpwebscanning](https://tryhackme.com/room/rpwebscanning) (Covers tools like Nikto, Gobuster)
    - [x] **(PSA)** Information disclosure - [https://portswigger.net/web-security/information-disclosure](https://portswigger.net/web-security/information-disclosure) (Labs cover finding sensitive info)
- **Introductory CTFs (Putting basics together):**
    - [x] **(THM)** Vulnversity - [https://tryhackme.com/room/vulnversity](https://tryhackme.com/room/vulnversity)
    - [x] **(THM)** Blue - [https://tryhackme.com/room/blue](https://tryhackme.com/room/blue) (Windows focus)

---

### Level 3: Web Application Hacking Fundamentals

**Goal:** Understand and exploit common web vulnerabilities (OWASP Top 10 focus).

- [x] **(THM)** OWASP Top 10 - [https://tryhackme.com/room/owasptop10](https://tryhackme.com/room/owasptop10) (Core concepts)
- **Injection Vulnerabilities:**
    - [x] **(THM)** Injection - [https://tryhackme.com/room/injection](https://tryhackme.com/room/injection) (Covers SQLi, Command Injection)
      - _Alternative: [https://tryhackme.com/room/sqlinjectionlm](https://tryhackme.com/room/sqlinjectionlm)_
    - [x] **(PSA)** SQL Injection - [https://portswigger.net/web-security/sql-injection](https://portswigger.net/web-security/sql-injection) (Extensive labs)
      - Helpful: [SQL injection cheat sheet](https://portswigger.net/web-security/sql-injection/cheat-sheet)
    - [ ] **(PSA)** Command Injection - [https://portswigger.net/web-security/os-command-injection](https://portswigger.net/web-security/os-command-injection)
- **Cross-Site Scripting (XSS):**
    - [ ] **(THM)** Cross-site Scripting - [https://tryhackme.com/room/xss](https://tryhackme.com/room/xss)
    - [ ] **(PSA)** Cross-Site Scripting - [https://portswigger.net/web-security/cross-site-scripting](https://portswigger.net/web-security/cross-site-scripting) (Very comprehensive labs)
- **File Inclusion Vulnerabilities:**
    - [ ] **(THM)** Inclusion - [https://tryhackme.com/room/inclusion](https://tryhackme.com/room/inclusion) (LFI/RFI)
    - [ ] **(THM)** LFI basics - [https://tryhackme.com/room/lfibasics](https://tryhackme.com/room/lfibasics)
    - [ ] **(PSA)** File path traversal - [https://portswigger.net/web-security/file-path-traversal](https://portswigger.net/web-security/file-path-traversal)
- **Server-Side Request Forgery (SSRF):**
    - [ ] **(THM)** SSRF - [https://tryhackme.com/room/ssrf](https://tryhackme.com/room/ssrf)
    - [ ] **(PSA)** Server-side request forgery (SSRF) - [https://portswigger.net/web-security/ssrf](https://portswigger.net/web-security/ssrf)
- **XML External Entity (XXE) Injection:**
    - [ ] **(THM)** XXE - [https://tryhackme.com/room/xxes](https://tryhackme.com/room/xxes)
    - [ ] **(PSA)** XML external entity (XXE) injection - [https://portswigger.net/web-security/xxe](https://portswigger.net/web-security/xxe)
- **API Hacking Intro:**
    - [ ] **(THM)** Introduction to API Hacking - [https://tryhackme.com/room/introtoapihacking](https://tryhackme.com/room/introtoapihacking)
    - [ ] **(PSA)** API testing - [https://portswigger.net/web-security/api-testing](https://portswigger.net/web-security/api-testing)
- **Authentication & Authorization:**
    - [ ] **(THM)** Auth Bypass - [https://tryhackme.com/room/authbypass](https://tryhackme.com/room/authbypass)
    - [ ] **(PSA)** Authentication - [https://portswigger.net/web-security/authentication](https://portswigger.net/web-security/authentication)
    - [ ] **(PSA)** Business logic vulnerabilities (often related to auth issues) - [https://portswigger.net/web-security/logic-flaws](https://portswigger.net/web-security/logic-flaws)
- **Web CTF Practice:**
    - [ ] **(THM)** OWASP Juice Shop - [https://tryhackme.com/room/owaspjuiceshop](https://tryhackme.com/room/owaspjuiceshop) (Also available to run locally)
    - [ ] **(THM)** Ignite - [https://tryhackme.com/room/ignite](https://tryhackme.com/room/ignite)
    - [ ] **(THM)** Simple CTF - [https://tryhackme.com/room/easyctf](https://tryhackme.com/room/easyctf)

---

### Level 4: Basic Exploitation, Password Attacks & Intro to PrivEsc

**Goal:** Exploit simpler vulnerabilities, crack hashes, and understand basic privilege escalation.

- **Password Cracking & Brute Forcing:**
    - [ ] **(THM)** Hydra - [https://tryhackme.com/room/hydra](https://tryhackme.com/room/hydra)
    - [ ] **(THM)** Crack the Hash - [https://tryhackme.com/room/crackthehash](https://tryhackme.com/room/crackthehash)
    - [ ] **(THM)** Hashing & Cracking - [https://tryhackme.com/room/hashingandcracking](https://tryhackme.com/room/hashingandcracking) (If not covered well enough by "Crack the Hash")
- **Linux Privilege Escalation (Foundations):**
    - [ ] **(THM)** Linux PrivEsc - [https://tryhackme.com/room/linuxprivesc](https://tryhackme.com/room/linuxprivesc) (This is a general room, often a starting point)
    - [ ] **(YT)** Linux Privilege Escalation (IppSec) - [https://www.youtube.com/@IppSec](https://www.youtube.com/@IppSec) (_Search his channel for "Linux PrivEsc" or specific machine walkthroughs._)
    - [ ] **(YT)** Linux Privilege Escalation (John Hammond) - [https://www.youtube.com/@_JohnHammond](https://www.youtube.com/@_JohnHammond) (_Search his channel for "Linux Privilege Escalation" or relevant CTF walkthroughs._)
- **Windows Privilege Escalation (Foundations):**
    - [ ] **(THM)** Windows Privesc - [https://tryhackme.com/room/windows10privesc](https://tryhackme.com/room/windows10privesc) (This title seems generic, ensure it covers techniques not just a single exploit)
    - [ ] **(YT)** Windows Privilege Escalation (IppSec) - [https://www.youtube.com/@IppSec](https://www.youtube.com/@IppSec) (_Search his channel for "Windows PrivEsc" or relevant machine walkthroughs._)
    - [ ] **(YT)** Windows Privilege Escalation (John Hammond) - [https://www.youtube.com/@_JohnHammond](https://www.youtube.com/@_JohnHammond) (_Search his channel for "Windows Privilege Escalation" or relevant CTF walkthroughs._)
- **CTF Practice (Combining Web & Basic System Exploits):**
    - [ ] **(THM)** Basic Pentesting - [https://tryhackme.com/room/basicpentestingjt](https://tryhackme.com/room/basicpentestingjt)
    - [ ] **(THM)** Bounty Hacker - [https://tryhackme.com/room/cowboyhacker](https://tryhackme.com/room/cowboyhacker)
    - [ ] **(THM)** The Cod Caper - [https://tryhackme.com/room/thecodcaper](https://tryhackme.com/room/thecodcaper)
    - [ ] **(THM)** Agent Sudo - [https://tryhackme.com/room/agentsudoctf](https://tryhackme.com/room/agentsudoctf)
    - [ ] **(THM)** Lazy Admin - [https://tryhackme.com/room/lazyadmin](https://tryhackme.com/room/lazyadmin)

---

### Level 5: Active Directory Hacking

**Goal:** Understand Active Directory environments, enumeration, common attacks, and privilege escalation within AD.

- [x] **(THM)** Active Directory Basics - [https://tryhackme.com/room/activedirectorybasics](https://tryhackme.com/room/activedirectorybasics) (Module/Path on THM)
- [ ] **(THM)** Attacktive Directory - [https://tryhackme.com/room/attacktivedirectory](https://tryhackme.com/room/attacktivedirectory)
- [ ] **(THM)** Wreath - [https://tryhackme.com/room/wreath](https://tryhackme.com/room/wreath) (AD focused network)
- [ ] **(THM)** Throwback - [https://tryhackme.com/room/throwback](https://tryhackme.com/room/throwback) (AD network)
- [ ] **(YT)** Hacking Active Directory (TCM Security) - [https://www.youtube.com/playlist?list=PLBf0hzazHTOOJ-TqX_k39wR4i0I6Y_Qe7](https://www.youtube.com/playlist?list=PLBf0hzazHTOOJ-TqX_k39wR4i0I6Y_Qe7) (_This is a well-regarded playlist from Heath Adams (The Cyber Mentor) on his TCM Security channel._)
- [ ] **(YT)** Active Directory Enumeration (IppSec) - [https://www.youtube.com/@IppSec](https://www.youtube.com/@IppSec) (_Search his channel for specific machine walkthroughs that demonstrate AD enumeration._)
- **Key AD Tools/Techniques to research alongside rooms (if not explicitly covered):**
    - BloodHound & Sharphound
    - PowerView, PowerUpSQL
    - Kerberoasting, AS-REP Roasting
    - Pass the Hash, Pass the Ticket
    - GPP Passwords, ACL Misconfigurations
    - LLMNR/NBT-NS Poisoning

---

### Level 6: Scripting, Intro to Exploit Dev & Post-Exploitation

**Goal:** Learn basic scripting, understand buffer overflows, reverse engineering basics, and post-exploitation techniques.

- **Scripting for Pentesters:**
    - [ ] **(THM)** Python for Pentesters - [https://tryhackme.com/room/pythonforpentesters](https://tryhackme.com/room/pythonforpentesters)
    - [ ] **(YT)** Python for Pentesters (TCM Security) - [https://www.youtube.com/playlist?list=PLBf0hzazHTOOQ_C2D64zE-f_P673tUe5H](https://www.youtube.com/playlist?list=PLBf0hzazHTOOQ_C2D64zE-f_P673tUe5H) (_This is The Cyber Mentor's dedicated Python for Pentesters series._)
    - _Practice automating simple tasks you've done manually so far._
- **Buffer Overflow:**
    - [ ] **(THM)** Buffer Overflow Prep - [https://tryhackme.com/room/bufferoverflowprep](https://tryhackme.com/room/bufferoverflowprep) (OSCP-like focus)
    - [ ] **(YT)** Buffer Overflows Made Easy (The Cyber Mentor) - [https://www.youtube.com/playlist?list=PLL_o_9aF0YtU24_F185vJ03S052Bq5b-r](https://www.youtube.com/playlist?list=PLL_o_9aF0YtU24_F185vJ03S052Bq5b-r) (_This is the classic series on his TCM Security channel._)
- **Intro to Reverse Engineering:**
    - [ ] **(THM)** Intro to x86-64 - [https://tryhackme.com/room/introtox8664](https://tryhackme.com/room/introtox8664)
    - [ ] **(THM)** Reverse Engineering - [https://tryhackme.com/room/reverseengineering](https://tryhackme.com/room/reverseengineering) (General intro)
    - [ ] **(THM)** Reversing ELF - [https://tryhackme.com/room/reverselfiles](https://tryhackme.com/room/reverselfiles)
    - [ ] **(THM)** CC: Ghidra - [https://tryhackme.com/room/ccghidra](https://tryhackme.com/room/ccghidra)
    - [ ] **(THM)** CC: Radare2 - [https://tryhackme.com/room/ccradare2](https://tryhackme.com/room/ccradare2)
- **Steganography (Often part of CTFs):**
    - [ ] **(THM)** CC: Stego - [https://tryhackme.com/room/ccstego](https://tryhackme.com/room/ccstego)
- **Post-Exploitation:**
    - [ ] **(THM)** Post Exploitation Basics - [https://tryhackme.com/room/postexploit](https://tryhackme.com/room/postexploit)
    - [ ] **(THM)** Movement, Pivoting, and Persistence - [https://tryhackme.com/room/movementpivotingpersistence](https://tryhackme.com/room/movementpivotingpersistence)

---

### Level 7: Advanced Privilege Escalation & More CTFs

**Goal:** Deepen privilege escalation knowledge and practice on harder, more diverse machines.

- **Advanced Linux PrivEsc:**
    - [ ] **(THM)** Linux PrivEsc Arena - [https://tryhackme.com/room/linuxprivescarena](https://tryhackme.com/room/linuxprivescarena)
    - [ ] **(THM)** Sudo Security Bypass - [https://tryhackme.com/room/sudovulnsbypass](https://tryhackme.com/room/sudovulnsbypass)
    - [ ] **(THM)** Sudo Buffer Overflow - [https://tryhackme.com/room/sudovulnsbof](https://tryhackme.com/room/sudovulnsbof)
    - [ ] **(THM)** Kenobi - [https://tryhackme.com/room/kenobi](https://tryhackme.com/room/kenobi) (Classic for Linux privesc)
- **Advanced Windows PrivEsc:**
    - [ ] **(THM)** Windows PrivEsc Arena - [https://tryhackme.com/room/windowsprivescarena](https://tryhackme.com/room/windowsprivescarena)
    - [ ] **(THM)** Blaster - [https://tryhackme.com/room/blaster](https://tryhackme.com/room/blaster) (Windows focus)
- **More Challenging CTFs:**
    - [ ] **(THM)** Ice - [https://tryhackme.com/room/ice](https://tryhackme.com/room/ice) (Windows, Metasploit heavy but good for learning)
    - [ ] **(THM)** Dogcat - [https://tryhackme.com/room/dogcat](https://tryhackme.com/room/dogcat) (Web, LFI)
    - [ ] **(THM)** Overpass - [https://tryhackme.com/room/overpass](https://tryhackme.com/room/overpass) (Web, Crypto, RE)
    - [ ] **(THM)** Year of the Rabbit - [https://tryhackme.com/room/yearoftherabbit](https://tryhackme.com/room/yearoftherabbit)
    - [ ] **(THM)** DevelPy - [https://tryhackme.com/room/bsidesgtdevelpy](https://tryhackme.com/room/bsidesgtdevelpy)
    - [ ] **(THM)** Smag Grotto - [https://tryhackme.com/room/smaggrotto](https://tryhackme.com/room/smaggrotto)
    - [ ] **(THM)** Lian Yu - [https://tryhackme.com/room/lianyu](https://tryhackme.com/room/lianyu)
    - [ ] **(THM)** Pickle Rick - [https://tryhackme.com/room/picklerick](https://tryhackme.com/room/picklerick) (Fun, web focused)
    - [ ] **(THM)** Capture the flag - [https://tryhackme.com/room/c4ptur3th3fl4g](https://tryhackme.com/room/c4ptur3th3fl4g)
    - [ ] **(THM)** Jack of all trades - [https://tryhackme.com/room/jackofalltrades](https://tryhackme.com/room/jackofalltrades)
    - [ ] **(THM)** Bolt - [https://tryhackme.com/room/bolt](https://tryhackme.com/room/bolt)
