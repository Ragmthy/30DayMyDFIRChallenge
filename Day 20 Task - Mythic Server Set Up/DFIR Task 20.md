# MyDFIR 30-Day SOC Analyst Challenge Task 20
[Link to full briefing](https://www.youtube.com/watch?v=JKO1pZ45_5I) of Task 20 </br>
Creator of Exercise: MyDFIR (Steven)

## Task:
Set Up of Mythic Server in Vultr, download and installation of Kali Linux into the workstation laptop. 

Referring back to the Logical Diagram: </br>

![image](DFIR_Day_005_Updated_Logical_Diagram.jpg)

The goals of this day is to emulate the C2 Mythic Server and the attack Laptop as a threat actor's infrastructure. 

After setting a Ubuntu server via Vultr, installation of Mythic is from this [source on GitHub](https://github.com/its-a-feature/Mythic). For Mythic to work, two other prerequisites are needed, mainly Docker-compose and Make packages. 

As for the Attack Laptop, install the Kali Linux package from its [website](https://www.kali.org/). And to utilize the vmx file after, a virtual machine (like VMWare) would need to be in the work station. 

### Firewall settings
For this exercise, it's best to make sure the Mythic server is only open to talking to our target machines (the Windows Server, Ubuntu Server) and our workstartion machine (in case there are extra commands or packages to install to the Mythic Server). One extra firewall will be configured for that for our "attacker" infrastructure. 


### Installation
As per [video](https://www.youtube.com/watch?v=JKO1pZ45_5I)


### Credits:
Full credits to MyDFIR (Steven) for putting together this exercise
















