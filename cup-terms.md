MECH E TERMS: 
- 
Form factor <br>

Baby Yoda Notes: 
6 servos, two for each arm, two for the head
Coding an Arduino, with no built in bluetooth capabilities 
Controlled by an XBox, switch between arm and head 
Controlling servo motors 
Allen has a controller we can use 


ECE TERMS: 
- 
Machine Learning Core <br> 
Data Cable (four wires) vs Charging Cable (two wires) <br>
USB Shield <br> 

Firmware: between software and hardware 

CS TERMS: 
- 
Linux vs MacOS <br>
Robot Operating System (ROS) <br>

Machine Learning Languages: <br>
TensorFlow <br>
PyTorch <br>
OpenCV <br>
Scikit Learn <br>
C/C++ <br>
Generative AI <br>


Software Develpoment Languages: <br>
Frontend: React <br>
Web languages: TypeScript, Javascript <br>
Databases: SQL, NoSQL, MongoDB <br>
Backend: Django, Flask <br>

TESTING: 
-
Robotics: <br>
Line Test <br>
Durability Tests <br>

SERVER PROTOCOL:
The Raspberry Pi connects to the Basestation using UDP and establishes two-way communication using TCP. The Raspberry Pi and the two Arduinos have two-way communication through SPI. 
1) Raspberry Pi -> It will first set up a listening socket on port 5001 then continuously broadcast UDP packets with the message “i_am_a_minibot”
2) GUI will send an HTTP request to the Basestation to listen for broadcasts containing the message “i_am_a_minibot” from a Minibot on the network. If it finds such a broadcast, it will fetch the IP address and port number of the Minibot to create a Bot object

Transmission Control Protocol (TCP):  a communications standard that enables application programs and computing devices to exchange messages over a network.
HOST: A host is a computer or other device that communicates with other hosts on a network. Also known as network hosts, hosts include clients and servers that send or receive data, services and applications.
PORT: is a number assigned to uniquely identify a connection endpoint and to direct data to a specific service

Gantt Charts: Bar chart that illustrates project schedule

Agile Methodology: a project management approach that involves breaking 
the project into phases and emphasizes continous collaboration 
=> Requirements Definition and Analysis of Concepts
=> Planning of Sprints
=> Collaborative Design Development
=> Create and Implement
=> Review and Monitor 
repeat 



