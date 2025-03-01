Logical clocks are a concept used in distributed systems to order events without relying on physical time synchronization. They provide a way to establish a partial ordering of events based on causality rather than real-time clock values.

By assigning logical timestamps to events, logical clocks allow distributed systems to maintain consistency and coherence across different nodes, despite varying clock speeds and network delays.
This ensures that events can be correctly ordered and coordinated, facilitating fault tolerance and reliable operation in distributed computing environments.

![image](https://github.com/user-attachments/assets/c16ed5d2-86b3-42f1-89db-b874f4de2e1b)

# Algorithm of Lamport Clocks:
Initialization: Each node initializes its clock LLL to 0.
Internal Event: When a node performs an internal event, it increments its clock LLL.
Send Message: When a node sends a message, it increments its clock LLL and includes this value in the message.
Receive Message: When a node receives a message with timestamp T: It sets L=max⁡(L,T)+1
