Creator: ParzivalHack (DEADSEC)
Written code by: Alexander [AlphaX]
Publishers: Pixel Rosee & NightmareAwakes [Pixel- Bravo-0, NightmareAwakes- CPI684]

Users that use it: Bravo-0, CPI684, Skullpredators, ParzivalHack.

SHARING IS NOT ALLOWED THIS IS AN PRVATE TOOL
SHARING IS NOT ALLOWED THIS IS AN PRVATE TOOL
SHARING IS NOT ALLOWED THIS IS AN PRVATE TOOL
SHARING IS NOT ALLOWED THIS IS AN PRVATE TOOL




# TechDos
T-DoS Attack Tool
------------------
What's a DoS/DDoS attack?
------------------------------------
Distributed Denial Of Service (DDoS) attacks are a subclass of denial of service (DoS) attacks. A DDoS attack involves multiple connected online devices, collectively known as a botnet, which are used to overwhelm a target website with fake traffic.

As you can see from the image below, there are 14 different types of DoS/DDoS attacks; the tool i developed, T-DoS, is able to do TCP SYN Flood Attack (Number 3), HTTP Flood (Number 6), Slowloris Ping Attack (Number 14), Ping Flood Attack, Ping Of Death Attack (Number 13), ICMP Flood Attack (Number 2) and IP Fragmentation Flood (Number 5).

![image](https://github.com/AEXGroup/TechDos/assets/156357682/6f11f7aa-1c1c-45f4-92fe-d9455952eac6)

My goal is to slowly add, to T-DoS, all 14 types of attacks.

What's T-DoS?
T-DoS is a Multi-Purpose DoS Tool, written in Python 3, right now capable of doing "only" 7 out of 14 types of DoS Attacks. It's meant to be used for Pentesting, but can also be used for testing of your own network (like your own router, website or webserver) and researching. It has an easy-to-use cli wizard interface, perfect for beginners, and right now it works on Termux, Kali Linux and ParrotOS.
![image](https://github.com/AEXGroup/TechDos/assets/156357682/2459cf86-4b22-45ed-9299-4cf8a35aabec)


Installation of T-DoS
---------------------------------
----   "apt update && apt upgrade"
----   "pip install python" 
----   "pip install git" 
----   "pip install scapy" 
----   "git clone https://github.com/AEXGroup/TechDos" 

Usage
----------------
Disclaimer: Illecit use of this tool could lead to a violation of federal and local laws. Use this tool only on your own network or on networks from which you have obtained permission. The creator of this tool, CANNOT be held liable for any misuse of it.
-----------------------------------------------------------------------------------------------------
----   "cd T-DoS" 
----   "python T-DoS.py"
---------------------------------

Update
-------------
----   "cd T-DoS" 
----   "0bash update.sh"

