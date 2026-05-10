# PRODIGY_CS_07
A network packet analyser (or packet sniffer) is a software program or hardware device that captures, decodes, and inspects traffic passing over a network, acting like a digital voltmeter for network data. It captures packets, breaks down their contents (source/destination IPs, ports, protocol) and logs them, allowing for network troubleshooting, security monitoring, and capacity planning.



The core workflow is:
•	Capture packets from a network interface 
•	Parse protocol headers (Ethernet → IP → TCP/UDP/ICMP) 
•	Extract metadata (IP addresses, protocol, ports) 
•	Optionally decode payload data 
•	Display/log results in a structured format


Usage:
•	Troubleshooting Network Issues: Identifying latency, packet loss, misconfigured applications, or connection failures.
•	Security Investigations: Detecting malicious traffic, unauthorized intrusion attempts, and malware behaviour.
•	Performance Optimization: Analysing traffic bottlenecks, monitoring bandwidth utilization, and planning capacity.
•	Protocol Analysis & Debugging: Developers use these tools to debug applications and verify that protocol implementations match specifications.
•	Regulatory Compliance: Inspecting data to ensure sensitive information is not being sent in clear text.




Install:
sudo apt update
sudo apt install python3-scapy
python3 -m pip install scapy
python3 -m venv venv
source venv/bin/activate
