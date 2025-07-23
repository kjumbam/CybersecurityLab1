# CybersecurityLabs
Lab activity for Security+ preparation and cybersecurity skills development.

🛠️ DNS Network Traffic Analysis Project

PROJECT OVERVIEW
This project involved investigating why users could not access a client’s website (www.yummyrecipesforme.com). When they tried, they saw an error saying “destination port unreachable.”
As a cybersecurity analyst, I was responsible for finding out what went wrong by analyzing the network traffic.

WHAT WAS THE PROBLEM?
1. Users could not reach the website.
2. The error showed that port 53 (used by DNS servers) was unreachable.
3. DNS (Domain Name System) is what helps browsers find the correct IP address for a website name. If DNS fails, websites do not load.

WHAT I DID
1. Used tcpdump, a network traffic analysis tool, to capture data.
2. Found that when my computer sent a request using UDP protocol to the DNS server, it got an ICMP error message back saying “udp port 53 unreachable”. This means the DNS server was not responding, possibly because:
- The server was down.
- The server was misconfigured.
- Firewall blocked the traffic, Or a Denial of Service attack affected it.

WHAT I LEARNED
1. How to analyze network traffic using tcpdump.
2. How different network protocols (UDP, ICMP, DNS) work together.
3. The importance of DNS for website availability.
4. How to write a clear incident report explaining technical problems.

FILES INCLUDED
- Scenario Document – Describes the incident situation.
- Incident Report PDF – My analysis and explanation of what happened.

🚀 Skills Demonstrated

- Network Traffic Analysis.
- Using tcpdump.
- Problem identification and troubleshooting.
- Writing professional incident reports





