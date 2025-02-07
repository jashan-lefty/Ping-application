# Ping-application
This is a python code that will create custom ICMP packets and send requests to any domain for ping.
In this task, I created my own ping application, where I can ping IP and domain names of different
websites, I used socket programming in Python to develop the code, although there were many
challenges that I had to encounter and I had to take some help to understand the logic of Checksum
calculation. Overall, there was a lot to learn from this task.

![image](https://github.com/user-attachments/assets/bf15faf3-6f45-4402-a9ec-ddd2fcee0618)

In the course of developing a Ping application using Python as outlined in the provided task, several 
fundamental programming concepts were explored and applied.  
Understanding Network Protocols and Socket Programming: 
Developing a Ping application involved a deep dive into network protocols, particularly the ICMP 
protocol, and employing Python's socket module to establish network communication. This provided 
practical insights into how data is exchanged and transmitted over networks. 
Packet Structuring and Checksum Verification: 

To construct and handle ICMP packets, understanding the structure and organization of these 
packets was crucial. This included unpacking and packing data using the struct module. The 
computation and verification of checksums were essential for ensuring data integrity in the packets. 
Error Handling and Timeout Management: 
Implementing features like error handling for cases where ping requests timed out was an important 
aspect of the application. This involved managing socket timeouts effectively, providing a 
comprehensive understanding of error handling strategies in network programming.

Data Extraction and Interpretation: 
Extracting relevant information from received ICMP packets, such as packet type, checksum, and 
sequence number, provided valuable experience in data parsing and interpretation, which is a 
fundamental skill in network programming. 

Real-time Data Processing and Display: 
The Ping application required real-time processing of data, including calculating round-trip times and 
displaying relevant statistics promptly. This highlighted the importance of efficient data processing 
and display for user-friendly applications. 

Future Benefits: 
Networking and Systems Development: Understanding network protocols and socket programming is 
foundational for developing various network-related applications and systems. 
