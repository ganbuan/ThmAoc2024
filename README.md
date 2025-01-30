# ThmAoc2024
My journal entries while working through THM's Advent of Cyber 2024

## Day 1: Maybe SOC-mas music, he thought, doesn't come from a store?

+ A malicious YouTube-to-Mp3/Mp4 converter
+ Learned about <i>exiftool</i> on bash (needs to be installed). This tool is used to view and edit EXIF metadata.
+ Introduced to Operational Security (OPSEC)

## Day 2: One man's false positive is another man's potpourri.
+ Introduction to TP/FP events in SOC
+ Using <i>Elastic</i> SIEM
+ Utilising <i>Cyberchef</i> for decoding

## Day 3: Even if I wanted to go, their vulnerabilities wouldn't allow it.
+ More <i>Elastic</i> SIEM log analysis
+ Introduction to remote code execution (RCE) vulnerability exploitation via file upload

## Day 4: I’m all atomic inside!
+ Introduced to the <i>MITRE ATT&CK</i> framework
+ Used the <i>Atomic Red Team</i> library test cases
+ Used information from <i>Sysmon</i> event log to create detection rules

## Day 5: SOC-mas XX-what-ee?
+ Introduced to extensible markup language (XML) and XML external entity (XXE)
+ Used <i>Burpsuite</i> for intercepting requests
+ Executed an XXE injection attack

## Day 6: If I can't find a nice malware to use, I'm not going.
+ Introduced to the concept of sandboxing
+ Learned about <i>YARA</i>, a tool used to identify and classify malware based on code patterns
+ Learned about the use of obfuscation as a malware evasion technique
+ Introduced to <i>Floss</i>, a malware analysis tool that reveals concealed details
+ Used YARA rules on Sysmon logs for data gathering and investigation

## Day 7: Oh, no. I'M SPEAKING IN CLOUDTRAIL!
+ Introduced to <i>CloudWatch, CloudTrail,</i> & <i>JQ</i> for AWS log analysis

## Day 8: Shellcodes of the world, unite!
+ Introduced to <i>shellcodes</i>
+ Generated shellcodes using <i>msfvenom</i> tool, while using <i>nc</i> to listen to a port

## Day 9: Nine o'clock, make GRC fun, tell no one. 
+ Introduced to <i>Governance, Risk, and Compliance (GRC)</i>
+ Attempted a third-party risk assessment

## Day 10: Day 10: He had a brain full of macros, and had shells in his soul. 
+ Learned about <i>macros</i> and how they can be used for phishing attacks
+ Used <i>Metasploit Framework</i> to create a document to establish a reverse tcp connection, which is sent via email attachment

## Day 11: If you'd like to WPA, press the star key!
+ Learned about WiFi attacks and executed <i>WPA/WPA2 cracking</i>
+ Used <i>aireplay-ng</i> tool to send deauthentication packets, force a reconnection, capture the WPA 4-way handshake, and performed a dictionary attack to bruteforce the PSK

## Day 12: If I can’t steal their money, I’ll steal their joy!
+ Introduced to <i>web timing attacks</i> such as <i>information disclosures</i> and <i>race conditions</i>
+ Exploited a web application's <i>Time-of-Check to Time-of-Use (TOCTOU)</i> flaw by duplicating packet requests and sending them in parallel using Burp Suite

## Day 13: It came without buffering! It came without lag!
+ Learned about <i>WebSocket</i> and its possible vulnerabilities
+ Exploited a car tracking web application via <i>message manipulation</i> using Burp Suite

## Day 14: Even if we're horribly mismanaged, there'll be no sad faces on SOC-mas! 
+ Learned about <i>certificates</i>, particularly the vulnerabilities posed by <i>self-signed certificates</i>
+ Exploited a web application's certificate vulnerability using a man-in-the-middle attack, routing web traffic to my machine and used Burp Suite to listen in on requests

## Day 15: Be it ever so heinous, there's no place like Domain Controller. 
+ Learned about <i>Active Directory</i> and common attacks such as <i>golden ticket attack, pass-the-hash, kerberoasting, malicious GPOs, </i> and <i>skeleton key attack</i>
+ Got familiar with common event IDs in Windows <i>Event Viewer</i> including 4624 (logon success), 4625 (logon failure), 4672 (SeTcbPrivilege), and 4768 (TGT ticket request)
+ Investigated AD controller, audited users, reviewed PowerShell history and logs

## Day 16: The Wareville’s Key Vault grew three sizes that day.

## Day 17: He analyzed and analyzed till his analyzer was sore!
+ Introduce to <i>Splunk</i>
+ Learned about parsing and manipulating custom log data
+ Investigated CCTV feed logs to identify the adversarial insider

## Day 18: I could use a little AI interaction!
+ Learned about common vulnerabilities with AI models such as <i>data poisoning, sensitive data disclosure, </i>and <i>prompt injection</i>
+ Performed a prompt injection to test for blind RCEs, which led to establishing a reverse shell connection

## Day 19: I merely noticed that you’re improperly stored, my dear secret!
+ Learned about game hacking and the difference between executable and library files (i.e. .so extension files)
+ Introduced to <i>Frida</i> as a tool to analyse, modify, and interact with running applications, such as games
+ Created and edited handler files to manipulate in-game functions

## Day 20: If you utter so much as one packet… 
+ Introduced to <i>Wireshark</i> as a network traffic analysis tool
+ Learned about <i>C2 communication</i>, where a command and control server (C2) deploys a secret agent (payload) that obey instructions such as execute malicious commands, exfiltrate files, etc
+ Learned about <i>beacons</i>, which are packets sent at regular intervals
+ Used Cyberchef again to decrypt exfiltrated data

##  Day 21: HELP ME...I'm REVERSE ENGINEERING! 
+ Learned about <i>binaries</i> and how they can be reverse engineered by <i>disassembly</i> or <i>decompiling</i>
+ Learned that binaries can be multi-stage, meaning multiple binaries that do different actions can be performed instead of one entire attack action
+ Used <i>PEStudio</i> to list important aspects about a file such as hash form, architecture type, signature of language used to compile, and other indicators
+ Used <i>ILSpy</i> to access the code on the binary

## Day 22: It's because I'm kubed, isn't it?
+ Learned about <i>Kubernetes</i>, which is a container orchestration system used to manage microservices
+ Learned about the basics of <i>Digital Forensics and Incident Response (DFIR)</i>
+ Investigated audit logs using K8s

## Day 23: You wanna know what happens to your hashes?
+ Learned about the use of <i>hashing</i> in passwords
+ Used <i>John the Ripper</i> to crack password hashes and gain access to a password-protected document

## Day 24: You can’t hurt SOC-mas, Mayor Malware!
+ Learned about <i>Message Queuing Telemetry Transport (MQTT)</i> protocols used in IoT
+ Used Wireshark to analyse MQTT traffic
