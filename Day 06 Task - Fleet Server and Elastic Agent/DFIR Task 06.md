# MyDFIR 30-Day SOC Analyst Challenge Task 06
[Link to full briefing](https://www.youtube.com/watch?v=0WklP6ZsP1g) of Task 06 </br>
Creator of Exercise: MyDFIR (Steven)

## Task:
Introduction on Elastic Agent and Fleet Servers

## Summary: 
A recap from Day 02:
In ELK, Logstash is the pipeline that will collect telemetry from various sources. It helps transform, filter and outputs into the Elasticsearch instance. 

To collect telemetry, there are 2 popular ways: Beats and Elastic Agents. 

In order for outputs to appear in our Elasticsearch instance, either the Beats or the Elastic Agents need to be configured appropriately. 

#### The difference between a beat and an agent? Which one should one use? 

1. Beats - There are 6 different types of beats
- File Beat: Logs
- Metric Beat: Metrics
- Packet Beat: Network data
- Winlog Beat: Windows Events
- Audit Beat: Audit data
- Heartbeat Beat: Uptime monitoring

2. Elastic Agent - One unified way to collect various logs or data 

Ultimately, deciding between a beat or an elastic agent is project dependent. For the focus of the 30-day Challenge, it's an agent in this project. 

[Extra Reading](https://www.elastic.co/guide/en/fleet/current/beats-agent-comparison.html#additional-capabilities-beats-and-agent) on the differences between Elastic Agents and Beats.

### More about Elastic Agent
A unified way to add monitoring for logs, metrics and many other different types of data.

There are two different deployment methods for an elastic agent: 

1. Standalone mode (Policies are applied to the Elastic Agent manually as a YAML file)

2. Fleet Managed (The Elastic Agent policies and lifecycle are centrally managed by the Fleet app in Kibana)

### More on Fleet Server
A Fleet server is a component that connects the elastic agent to a fleet - which will allow management of multiple agents in a centralised location. 
Without a fleet server, there would be a need to look into other options if there comes a time an agent's policy needs to get updated. 

### Credits:
Full credits to MyDFIR (Steven) for putting together this exercise
















