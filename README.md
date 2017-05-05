# SDN for Secure Video Streaming: CORD Based Secure Video Streaming

Students –
1)	Aman Maldar
2)	Priyanka Murthy

List of Files -
1) Project Report - Includes - Project details + Individual Contribution
2) CORD environement setup -  DIY Instruction
3) Running and Changing HelloWorld Service - DIY Instruction
4) Presentation Slides
-----------------------------------------------------------------------------------------------------------------------------------

The repository consist of the documents which includes detailed steps and screenshots indicating the work progress for the project.
Instructions to setup the project environment are explained in detail.

Read and follow the steps mentioned in the documents below to track the project progress.
1) CORD environement setup
2) Running and Changing HelloWorld Service

Objectives Achieved -
1) Setting up CORD Environment on CloudLab.
2) Running Hello World Service.
3) Making changes in HelloWorld service
4) Creating a new tenant service.

What did not work?
1) Running a python script as a service.
- We made a changes to the ansible script to run the python program as a service. The CORD-POD environment broke everytime we made the changes. So we basically could not deploy it.

2) Running Red5/Mist server
- CORD runs apache server to host/run the service. We tried to install red5 server in place of Apache server. Again, CORD-POD broke evrytime.

Troubleshooting-
- We analysed the logs, understood the sequence of operations for the container after every development loop execution. Did  exeperiemnts to achieve the results.

--------------------------------------------------------------------------------------------------------------------------------
Date - May 5, 2017
Etherpad Links for details -
http://etherpad2-p2plab.rhcloud.com/p/SDN_Project2
http://etherpad2-p2plab.rhcloud.com/p/Session2_SDNProj
