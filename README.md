# Car_Security

## The Cyber physical surveillance system for smart cars 

1.	The OBD-II port which is an open port in the smart cars is easily accessed by the hackers. These are the internal automotive network hack. The port is the only way to get into the ECU of the cars and there are 100’s of ECU connected to the CAN. This hack can be prevented by avoiding the port from being detected and will be done with the help of the DBSCAN (Density-based spatial clustering of applications with noise) and SOM (Self Organizing Maps) algorithms. Firstly the anomaly detection will identify the unusual patterns and behaviors and the link analysis to trace self-propagating malicious code. Further, we can classify this to detect an attack when it occurs. The IDS will be improved by including this and prevent the port from getting scanned. The application firewall will also be configured to prevent the port scans.
2.	The IDS will detect when someone is trying to attack, in response the system will attack back, like the DOS attack, So that the attacker will temporarily shut down and the attack fails.  
3.	The Uconnect which is responsible for the communication among the cars, the hacker will access the IP address of the car and reprogram the firmware which poses serious problems related to adaptive cruise control, collision prevention and others. The IP address can be hidden with the help of Tortunnel, port security, Cuckoo Sandbox. This is less maintenance, broader detection and it will be a better protection for the users.   
4.	The remote attack surface is the Bluetooth, which will be of two types i.e. paired and unpaired. They are prevented by avoiding the connections with the unknown devices. The GPS is the necessary objective for the smart cars, there is a ransomware threat for the cars. The Disk Writes are being constantly monitored by the HMM, if the noisy activity is being identified the data will not be encrypted by the hacker and the car data will be locked.



## Requirements

Python2.0,
             scipy, 
             numpy,
             matlib,
             pandas,
             nmap,
             Hping3,
             BRO (base/protocols/conn/main.bro),
             WEKA,
             DVWA
             
             

## Use cases

The smart cars have various cyber physical controlled features like park assist, lane keep assist, and prevention of collision, steering control and others. If a car on a highway is being hacked then there may be serious issues such as the lane discipline might not be followed, the car might stop all of a sudden in the middle of the road, the steering will go out of control and other serious issues which is not only dangerous for the car but also for the other vehicles around. The sharing of the car data may also cost someone’s life, so it’s very important to keep the data safe.

### Project is in the development stage, will update soon
