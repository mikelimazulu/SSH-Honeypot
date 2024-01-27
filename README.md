# SSH Honeypot Data Analysis
This repository is dedicated to the analysis and insights derived from data collected by our SSH Honeypot. It includes comprehensive analysis of IP addresses, usernames, passwords, login combinations, traffic patterns, and downloaded payloads by potential attackers. Our goal is to understand attack vectors, peak attack times, common credentials used by attackers, and overall trends in SSH-based threats.

## Scenario
Our SSH honeypot is a software designed to simulate an SSH server. It's purposefully engineered to attract and interact with unauthorized users, typically cyber attackers or automated bots, who attempt to access SSH services on a network. This honeypot acts as a decoy, mimicking vulnerabilities to lure attackers, thereby protecting real servers by diverting attacks away from them.

### Key Features
Data Capture: It meticulously logs various types of data from each interaction, including:
- IP Addresses: Records the IP addresses of all entities that attempt to connect, providing insights into the geographic distribution and potential sources of attacks.
- Username and Password Attempts: Captures all username and password combinations tried by the attackers. This data is crucial for understanding common brute-force techniques and frequently guessed credentials.
- Frequency and Timing Analysis: Monitors and logs the number of hits, along with detailed timestamps. This allows for analysis of attack patterns over time, identifying peak attack hours and days.
- Payload Downloads: Keeps track of any payloads that attackers attempt to download onto the honeypot system. This helps in understanding the types of malware or tools attackers are using.
- Interaction Simulation: The honeypot simulates various SSH server responses, tricking attackers into believing they are interacting with a real system. This includes fake shell environments and simulated file systems, providing insights into the attackers' intentions and methods.

## Data Collection
Data is collected by an SSH Honeypot system that logs:
- IP addresses
- Usernames and passwords
- User/pass combinations
- Number of hits
- Traffic analysis (hours and days)
- Payloads downloaded by attackers

## Analysis
The analysis focuses on various aspects:
- IP address distribution and geo-location analysis
- Most common usernames and passwords used
- Daily and hourly traffic patterns
- Correlation between different types of attacks
- Analysis of downloaded payloads

## Repository Structure
- `/data`: Contains anonymized raw data collected from the honeypot.
- `/analysis`: Jupyter notebooks or scripts for data analysis.
- `/reports`: Generated analysis reports and insights.
- `/visualization`: Graphs, charts, and other visual aids.
- `README.md`: Overview and instructions.

## DISCLAIMER
Usage of the data in this repository for attacking targets without prior mutual consent is illegal. It's your responsibility to obey applicable local, state and federal laws.
We group assume no liability and are not responsible for any misuse or damage caused by using the data.
