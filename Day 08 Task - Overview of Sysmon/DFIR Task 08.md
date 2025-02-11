# MyDFIR 30-Day SOC Analyst Challenge Task 08
[Link to full briefing](https://www.youtube.com/watch?v=hpUnKjEFCoU) of Task 08 </br>
Creator of Exercise: MyDFIR (Steven)

## Task:
Overview of Sysmon

## Summary: 
Sysmon is a free MS tool that's part of the Sysinternals suite, and provides an ability to monitor and log system activity to the Windows event log.

More about it [here](https://learn.microsoft.com/en-us/sysinternals/downloads/sysmon). 

#### Some Important Event IDs:
Event ID 1: Information about a newly created processes. For instance, should an attacker execute an unknown .exe file, it will have a ProcessGUID attached to the process, and can make event correlation easier. 

Event ID 3: Logs TCP/UDP connections on the machine. Event will also contain source and destination IP addresses, for any connection happening with unusual hosts. 

Event ID 6/7/8: These IDs will come in handy in detecting defense evastion techniques. 

Event ID 10: When looking for potential activity to read Lsass.exe. Processes like LSASS enforce security policies on a system. Attempting to read it, will provide a threat actor credential material.

### Credits:
Full credits to MyDFIR (Steven) for putting together this exercise
















