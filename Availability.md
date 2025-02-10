# Avaibility
availability refers to the proportion of time that a system or service is operational and accessible for use.
# How to achive high avaibility
Avaibility is higher in microsevices
Fault Tolerant α Availibity
1. use distributed system
2. replication
3. Redundancy: Use redundant servers or components so that, in the event of a failure, another can take over without any problems. 
Data centers, networking, and hardware redundancy are a few examples of this.

4. Load balancing: Incoming requests are divided among several servers or resources to enhance system performance and fault 
tolerance while avoiding overload on any one part.

# Redundancy
Purpose:
The main goal of redundancy is to increase system reliability and availability. If one component fails, another can immediately take 
its place, minimizing downtime.

How It Works:
In a redundant setup, you might have multiple copies of the same hardware or infrastructure that don’t actively participate
in processing or storage but are ready to be used if the primary component fails.

# Replication
Purpose:
The goal of replication is to ensure data availability, consistency, and sometimes improve read performance. 
It ensures that even if one server goes down, the data is still accessible from other locations.

How It Works:
Data or processes are duplicated across servers. Depending on the system, these replicas might be updated in real-time or at scheduled intervals.

