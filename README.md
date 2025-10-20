This repo documents a Kali Linux network discovery and risk assessment of IP using Nmap.
Performed a TCP SYN scan (sudo nmap -sS -sV -O --script=default) and captured packets to nmap_scan_capture.pcap.
Found host IP with open ports 135, 139, 445, 902, 912, 3306 and produced brief risk + mitigation notes.
All testing was performed on a controlled lab network — only scan systems you own or have explicit authorization to test.
