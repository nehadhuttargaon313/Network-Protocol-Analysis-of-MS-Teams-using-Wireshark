# CS558 - Computer Systems Lab
## Group 18

v.subramanian@iitg.ac.in - Subramanian V<br>
r.sri@iitg.ac.in - Sri Harsha R<br>
d.neha@iitg.ac.in - Neha Dhuttargaon

## Assignment 2 : Network Protocol Analysis Using Wireshark

Wireshark is a free and open-source packet sniffer and network protocol analyser tool. It helps to capture
network packets and understand the structure of different networking protocols.
## Instructions:
1. Install Wireshark (download from www.wireshark.org), and learn how to capture packets and filter
the required content.
2. A specific application is assigned to groups (refer to Table 1 below). Each group needs to perform
various activities according to functionalities available in the assigned application and collect the
traces for the application using Wireshark. Application-specific activities, if any, are mentioned in the
table.
3. You should carry out your experiments across different network conditions including different
time(s) of the day and locations (e.g., lab or hostel, etc.).
4. It is advisable to provide only trace-based description while answering the questions. While
answering, provide snapshots of the traces in the report and highlight the content as and when
required.
5. If something is missing/incorrect in a problem description, clearly mention the assumption with your
answer.
6. Be precise with your answers; there is no credit for being unnecessarily verbose (may award you
negativemarks for the same). Unless specified otherwise, do not describe the tool or application or
protocol in general.

## Questions:
1. List out all the protocols used by the application at different layers (only those which you can figure out
from traces). Study and briefly describe their packet formats.
2. Highlight and explain the observed values for various fields of the protocols. Example: Source or
destination IP address and port number, Ethernet address, protocol number, etc.
3. Explain the sequence of messages exchanged by the application for using the available functionalities in
the application. For example: upload, download, play, pause, etc. Check whether there are any
handshaking sequences in the application. Briefly explain the handshaking message sequence, if any.
4. Explain how the particular protocol(s) used by the application is relevant for functioning of the
application.
5. Calculate the following statistics from your traces while performing experiments at different time of the
day: Throughput, RTT, Packet size, Number of packets lost, Number of UDP & TCP packets, Number of
responses received with respect to one request sent. Report the observed values in your answer,
preferably using tables.
6. Check whether the whole content is being sent from same location/source. List out the IP addresses of
content providers if multiple sources exist, and explain the reason behind this.
