# MyDFIR 30-Day SOC Analyst Challenge Task 18
[Link to full briefing](https://www.youtube.com/watch?v=WnOkhGNPmyA) of Task 18 </br>
Creator of Exercise: MyDFIR (Steven)

## Task:
Overview of Command and Control (C2)

## Food for Thought:
After executing a malicious binary, what typically happens? A series of commands would tend to run, because the deployed file would need to get a "sense of its surroundings" in the target system. 

Highly likely, it could run a couple of discovery commands automatically: such as whoami, ipconfig, nslookup, net user and others. 

Or, it might choose to persist in the system: either by creating a scheduled task or service creation. Doing this, it will allow the malware to survive a hard reboot of the system. 

However, there tends to be one action majority of the malware can tend to perform - Command and Control.


### About C2: 
C2, as defined by the MITRE ATT&CK [framework](https://attack.mitre.org/tactics/TA0011/), is when an adversary uses techniques to communicate with systems under their control within a target victim's network. 

Why is it important to establish C2 into a victim's network? Mainly to get closer to their end goals: steal credentials, move laterally in the system, exfiltrate sensitive data or create an impact. 

Essentially, before any damage can be done on a victim's system, connection to it has to be established, and creating a C2 session is a common tactic. 

### Tools that are commonly used to create a C2 session
At the point of writing, there are [18 unique techniques](https://attack.mitre.org/tactics/TA0011/) that may be used to establish a C2 session. 

Some common tools that are used include:
1. Metasploit
2. Cobalt Strike
3. Sliver
4. Mythic

* Mythic will be explored in the 30-day Challenge.

### Credits:
Full credits to MyDFIR (Steven) for putting together this exercise
















