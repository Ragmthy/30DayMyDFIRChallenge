# MyDFIR 30-Day SOC Analyst Challenge Task 15
[Link to full briefing](https://www.youtube.com/watch?v=tNhGxtKZo7c) of Task 15 </br>
Creator of Exercise: MyDFIR (Steven)

## Task:
Overview of Remote Desktop Protocol (RDP)

## Summary: 
RDP is a proprietary protocol developed by Microsoft. Allows users to connect to a remote computer over a network, providing a graphical interface for users to interact with that machine as if they were sitting right in front of it. 

It works within TCP, and has a default port of 3389. 

### RDP's original purpose
It's used to access and control another computer remotely. The protocol transmits the graphical display of the remote machine and sends the user's inputs back to that machine. Essentially, one will require the credentials of the target machine to enable any transmission of action over to it.

Useful in IT Support, System Admin, accessing resources from distant locations. 

Although designed by Microsoft, the protocol can be used on Apple, Linux and mobile phones. There are versions of it for the desired system one's keen to install it into. 

That way, it can enable connections such as MacOS-to-Windows too. 

### But, there's a catch...
Due to this protocol providing such flexbility, it's also become the most widely abused in 90% of cyber attacks against Windows machines, according to [Sophos in 2023](https://www.sophos.com/en-us/press/press-releases/2024/04/cybercriminals-abuse-remote-desktop-protocol-rdp-90-attacks-handled).

But the question is, how do attackers know that who to attack with the RDP protocol? There are sources available that reveal exposed RDP services - these might be exposed due to production or a development server. 

However, while it's possible to connect, there's still a need to "login" with credentials into that RDP service (whether it's a device or a server). These credentials could've come from a phishing campaign of valid accounts or brute forcing in default passwords, hoping they've not been altered. 

Based on whatever level of access they're in (provided they've successfully logged in), they can laterally move across the target's systems, and even deploy ransomware or execute data exfiltration. 

### Sources to show RDP being exposed

[Shodan.io](https://www.shodan.io/) </br>
[Censys](https://search.censys.io/)

##Recommendations to prevent RDP from getting exposed
1. Turn RDP off on machines used.
2. Multi-Factor Authentication
3. Restricting Access (By implementing a Firewall rule - certain IP addresses can RDP into the machine)
4. Better Passwords or a Privileged Access Management tool
5. Change the default local accounts 

### Credits:
Full credits to MyDFIR (Steven) for putting together this exercise
















