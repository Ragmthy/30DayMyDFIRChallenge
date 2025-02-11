# MyDFIR 30-Day SOC Analyst Challenge Task 03
[Link to full briefing](https://www.youtube.com/watch?v=ypXARA5Uk4I) of Task 03 </br>
Creator of Exercise: MyDFIR (Steven)

## Task:
Set-up of Elasticsearch Server

## Summary: 
Based on the Logical Diagram designed in Day 1: </br>

![image](DFIR_Day_03_Focus.jpg)

With Vultr, a Virtual Private Cloud needs to be designed for the focus of the five servers.
And alongside that, the first one to design in this task is the Elastic & Kibana one

#### More about Elasticsearch
**A recap from Day 2:** </br>
A database that is used to store logs (from Windows Event Logs, SysLogs, Firewall Logs amongst a few). 
Search across data, and uses ESQL as a query lang. 
Uses Restful API and JSON to interact with various application. 

#### Installation 
As per video - https://www.youtube.com/watch?v=ypXARA5Uk4I

#### Some technical things to take note of:
1. Ensure all virtual machines have the same location selected as the Virtual Private Cloud
2. To ensure secure connection to the virtual machine, its Public IP address, username and password are essential
3. Ensure apt-get update and apt-get upgrade are always executed after the connection is established
4. Recollect commands like `nano`, `cd`, or for file executions in the same directory
5. Command of `systemctl` to ensure elasticsearch services are running

Extra content to look up for [systemctl command service:](https://linuxhandbook.com/systemctl-commands/) </br>
6. After whatever work is completed for the day within the connection to a remote server, enter `exit` and close the connection. </br>

Repeat Step 2 as needed for the next installation

### Credits:
Full credits to MyDFIR (Steven) for putting together this exercise
















