# MyDFIR 30-Day SOC Analyst Challenge Task 02
[Link to full briefing](https://www.youtube.com/watch?v=4AwBhXAW90Q) of Task 02 </br>
Creator of Exercise: MyDFIR (Steven)


## Task:
Introduction to ELK Stack. 

## Summary: 
ELK, shorthand for Elasticsearch, Logstash and Kibana. 

#### More about Elasticsearch
A database that is used to store logs (from Windows Event Logs, SysLogs, Firewall Logs amongst a few). 
Search across data, and uses ESQL as a query lang. 
Uses Restful API and JSON to interact with various application. 

#### More about Logstash
A pipeline that collects telemetry from various sources. 
It helps transform, filter and outputs into the Elasticsearch instance. 

To collect telemetry, there are 2 popular ways: Beats and Elastic Agents. 

1. File Beat: Logs
Metric Beat: Metrics
Packet Beat: Network data
Winlog Beat: Windows Events
Audit Beat: Audit data
Heartbeat Beat: Uptime monitoring

~ Depending on what the project will require, the appropriate beat should be installed at the endpoint.


2. Elastic Agent
Helps to collect various types of data using one unifying agent per host. 

Being a pipeline, after collecting the various data, Logstash will then transform all this data and push it into the Elasticsearch instance.

#### More about Kibana
A data visualisation and exploration tool used for log data analysis. Uses a web console to query for logs stored within the Elasticsearch instance. 
Has various visualisation capabilities also. 

### Few Benefits of ELK:
1. Centralized Logging - To meet compliance reqs and sift though data in case a incident occurs
2. Flexibility - with installed beats or agents, there's opportunity for custom ingestion
3. Visualisations - Important info in a glance
4. Scalability - easy to configure to large environments
5. Ecosystem - Lots of integrations available

Most SIEMs are built on ELK stack. So getting familiar with ELK stack is beneficial.

### Credits:
Full credits to MyDFIR (Steven) for putting together this exercise
















