# Progress Report April 25th, 2019
**Capstone:** IoT Forensics  
**University:** University of Nebraska at Omaha  
**Members:** Elisabeth Henderson, Ashley Leedom, Amber Makovicka, Ronald Ramirez, & Nathan Wood   

- [Overview](#overview)
- [Outcomes](#outcomes)
- [Hinderances](#hinderances) 
## Overview
(insert brief overview of efforts made)

## Outcomes
(brief overview of outcomes - what did you achieve?)

##### *just some ideas from two sources i found that we might be able to apply to our project*
Reading 1 - [Security Analysis of the Amazon Echo](https://courses.csail.mit.edu/6.857/2017/project/8.pdf)
* Summary - As the title states, authors of this reading conducted a security analysis on the Amazon Echo.  They defined an ideal security policy which included three main goals, confidentiality, integrity, and availability. This security policy is then used to reference the vulnerabilities they would later attempt. The authors conducted Sound, network, and API attacks. Here are a couple examples that the authors conducted that could be useful to us.   
 
   + Sound-based Attacks – When placing orders, Amazon prevents users from buying stuff by having a user enter a 4-digit PIN. The authors wrote a script to brute-force the 4-digit PIN since Amazon doesn’t limit the number of attempts when ordering
   
   + Network Attacks – The authors used Wireshark to conduct a man-in-the-middle attack, to intercept and record the traffic. They were able to retrieve the MAC address of the device and but weren’t able to decrypt the data portion of the packets.  


Reading 2 - [Digital forensic approaches for Amazon Alexa ecosystem](https://www.sciencedirect.com/science/article/pii/S1742287617301974)

* Summary - In this paper, the authors focused on the digital forensics based on the Intelligent Virtual Assistant (IVA) Alexa’s Ecosystem. One of the points that I thought was interesting was pertaining to the database of the Alexa Mobile App. Using an Android device, the application uses two SQLite files called “map_data_storage.db” and “DataStore.db” where the first database contains the token information about the user who is logged in. And the data is deleted when a user signs out. The other database includes to-do and shopping lists. Nevertheless, the results when examining the database files showed that there was little information stored on the device. 


also list them out like this:
* outcome 1
* outcome 2

## Hinderances
(insert brief discussion of challenges encountered)