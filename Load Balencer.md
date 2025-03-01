a crucial component in system design that distributes incoming network traffic across multiple servers. Its main purpose is to ensure that no single server is overburdened with too many requests,
# Roles
- load distribution is equeal
- healt check - request is passes to another
- high scalabiity, high through put, high availibility.

- Types of Static Load Balancing Algorithms

1. Round Robin (rotation Fashion)
2. Weighted Round-Robin (servers are of different capacities)
3. Source IP hash (client's source & distribution IP address to produce a hash key)

-Types of Dynamic Load Balancing Algorithms

Least Connection Method ( checks who has less active members)
Least Response Time Method
