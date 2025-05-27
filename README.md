## Scanned Domains

- kali.org (scanned with Nmap and theHarvester)
# OSINT-recon-kali
A practical OSINT project using theHarvester and Nmap for domain reconnaissance.
# OSINT Recon Project

## Project Overview
This project leverages open-source tools to perform OSINT (Open Source Intelligence) gathering on target domains. The goal is to conduct comprehensive reconnaissance using tools like **theHarvester** and **Nmap** to collect data useful for security assessments or general information gathering.

---

## Tools Used

### theHarvester
- A tool to gather information from multiple public sources such as search engines, databases, and social media.
- Used for collecting initial data about the target domain like emails, hosts, subdomains, and more.

### Nmap
- A powerful network scanning tool used to discover hosts and open services on a network.
- Used for scanning open ports, service versions, and operating system detection.

---

## How to Use

1. Prepare a file containing the list of target domains (e.g., `domains.txt`).
2. Run theHarvester to collect initial information:
   ```bash
   theHarvester -d example.com -b bing,duckduckgo,crtsh,hunter -l 100 -f data/theHarvester/example_com_results
