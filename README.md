# Oscp study

Notes of my Offensive Security Certified Professional (OSCP) study plan.

**Last updated**: 2018-01-07

## OSCP-like VMs on Vulnhub:
- Beginner friendly:
	- Kioptrix: Level 1 (#1) [ok]
	- Kioptrix: Level 1.1 (#2) [ok]
	- Kioptrix: Level 1.2 (#3) [ok]
	- Kioptrix: Level 1.3 (#4) [ok]
	- FristiLeaks: 1.3 [ok]
	- Stapler: 1 [ok]
	- PwnLab: init [ok]
- Intermediate:
	- Kioptrix: 2014 [ok]
	- Brainpan: 1 (Part 1 of BO is relevant to OSCP. egghunting is out of scope though)
	- Mr-Robot: 1 [ok] 
	- HackLAB: Vulnix [ok]
 	- Not so sure (Didn't solve them yet):
	- VulnOS: 2
	- SickOs: 1.2
	- /dev/random: scream 
	- pWnOS: 2.0
	- SkyTower: 1 
	- IMF
	- Lord of the Root 1.0.1
	- Tr0ll
	- Pegasus
- Windows 
	- Metasploitable 3
	- /dev/random: Sleepy (Uses VulnInjector, need to provide you own ISO and key.)
	- Bobby: 1 (Uses VulnInjector, need to provide you own ISO and key.)

(credits for **@abatchy**)  
  
Link to download VMs: http://vulnhub.com

## Hackthebox.eu (HTB)

I strongly recommend the boxes on the <a href="http://hackthebox.eu"> hackthebox.eu</a> to study for OSCP cert. HTB have a good set of windows boxes to training: **Devel**, **Optimum**, **Bastard**, **Grandpa** and **Blue**. 

*PS: It's necessary solve a little "challenge" to obtain the invite.*  

## Recommended books:

<a href="https://www.amazon.com.br/Penetration-Testing-Hands-Introduction-Hacking/dp/1593275641">Penetration Testing: A Hands-On Introduction to Hacking</a> (+Highly recommended for beginners)  
<a href="https://www.amazon.com/Hacking-Art-Exploitation-Jon-Erickson/dp/1593271441/ref=sr_1_1?ie=UTF8&qid=1492297164&sr=8-1&keywords=hacking">Hacking: The Art of Exploitation, 2nd Edition</a>  
<a href="https://www.amazon.com/Rtfm-Red-Team-Field-Manual/dp/1494295504/ref=sr_1_2?ie=UTF8&qid=1492297153&sr=8-2&keywords=pentest">Rtfm: Red Team Field Manual</a>  
<a href="https://www.amazon.com/Web-Application-Hackers-Handbook-Exploiting/dp/1118026470/ref=sr_1_1?ie=UTF8&qid=1492297179&sr=8-1&keywords=the+web+application+hacker%27s+handbook">The Web Application Hacker's Handbook: Finding and Exploiting Security Flaws</a>  
<a href="https://www.amazon.com/Hacker-Playbook-Practical-Penetration-Testing-ebook/dp/B00J5S9OPU">The Hacker Playbook: Practical Guide To Penetration Testing</a>

## Links:

https://blog.g0tmi1k.com/2011/08/basic-linux-privilege-escalation/ [Linux privilege escalation]  
http://www.fuzzysecurity.com/tutorials/16.html [Windows privilege escalation]  
http://www.abatchy.com/2017/03/how-to-prepare-for-pwkoscp-noob.html  
https://www.securitysift.com/offsec-pwb-oscp/ [+Scripts]     
http://hackingandsecurity.blogspot.com.br/2016/04/oscp-related-notes.html  
http://rtfm-ctf.org/2017/PWN-PATH-TO-OSCP  
http://www.techexams.net/forums/security-certifications/110760-oscp-jollyfrogs-tale.html [RECOMMENDED reading]  
https://tulpa-security.com/2016/09/19/prep-guide-for-offsecs-pwk/

## About the final exam

**5 Boxes** on the final exam:  

- 1 box - 25 points: Buffer Overflow (BO). Training writing a custom BO.  
- 3 boxes - No msf, focus on local privilege escalation. By the way, limited shells give you some points.  
- 1 box - 10 points. This should be exploited simply with a MS module or just enumerating a exploit-db script.  

... plus 10 points for the laboratory exercises (5 points for the lab box write-ups and 5 points for the writeups to the exercises along the PWK).

**A possible plan**: Focus on the BO and MSF box while testing other 3 boxes with a port scan, fuzzing directories, etc. :D 

*PS: DEP/ASLR/stack canaries are only part of the OSCE, everything it's a basic overflow on OSCP.*

## My write-ups

<a href="https://ferreirasc.github.io/post/kioptrix_level_1/">Kioptrix level 1</a>  
<a href="https://ferreirasc.github.io/post/kioptrix_level_1_1/">Kioptrix level 1.1 </a>  
<a href="https://ferreirasc.github.io/post/kioptrix_level_1_2/">Kioptrix level 1.2 </a>  

