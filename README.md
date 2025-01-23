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

