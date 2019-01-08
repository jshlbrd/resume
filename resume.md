## Josh Liburdi <br/> liburdi.joshua@gmail.com
#### Professional Experience
##### Lead Engineer - Threat Detection Operations <br/> Target (March 2017 - Present)
- Lead developer for Target's 1,800+ network security monitoring (NSM) sensor deployment
  - Developed 2 custom Docker containers that provided new features/functionality
      - File extraction and upload to the cloud (>120 files/second)
      - Tool-agnostic full packet capture retrieval via custom API and remote procedure calls
  - Developed dozens of custom Bro/Zeek scripts and Suricata rules
      - Detection of attacker tactics, techniques, and procedures (TTPs)
      - Logging additional network metadata from HTTP, SMTP, and TLS
  - Researched and developed Linux-based methods of rate limiting outbound network traffic (for use in bandwidth-limited networks)
- Project and DevOps lead of Strelka, an open-source, detection-oriented file analysis system written in Python 3.6
  - Supports 60+ types of files, designed to scan hundreds of millions of files per day
  - Integration with NSM sensors (Bro/Zeek)
  - DevOps lifecycle maintained via Git, Drone, Docker, SaltStack, OpenStack, Telegraf, and Grafana
- Contributed significant engineering work on a 9-month project to convert NSM applications from bare metal installs to Docker containers
  - Converted 5 applications to containers
  - Developed methodology for maximizing server resources through a combination of application CPU pinning and Docker CPU isolation
- Developed continuous delivery systems that reduced time-to-deploy from days to minutes
  - Docker containers, Suricata rules, and YARA rules
##### Security Technologist (Research and Development) <br/> Sqrrl (May 2016 - February 2017)
- Drove direction of Sqrrl platform by acting as a threat hunting, threat detection, and incident response subject matter expert for startup of ~50 people
- Researched established and emerging attacker TTPs
  - Performed research focused on DNS resolution activity that fully defined a major product release (Sqrrl v2.7.0)
      - DNS data record ingestion of Windows Server logs
      - Domain Generation Algorithm (DGA) detection analytic
      - DNS tunneling detection analytic
  - Led endpoint-focused research on artifacts found in process execution records and file metadata
- Regularly created, tested, and validated new hunting hypotheses and techniques
  - Significant focus on testing effectiveness of new and underutilized visualization techniques
##### Senior Consultant <br/> CrowdStrike Professional Services (June 2014 - April 2016)
- Primary researcher and developer for CrowdStrike Services' NSM platform
  - Expanded metadata collection by creating new protocol analyzers for Bro/Zeek, including the open-source RDP analyzer, and integrating Laika BOSS
  - Increased detection coverage by creating dozens of private and open-source Bro/Zeek scripts
  - Improved analyst workflow by unifying detection data (network alerts/metadata, file alerts/metadata, full packet capture) from four applications into a custom Splunk-based analysis platform
- Performed threat hunting, network monitoring, and incident response for Fortune 500 clients
  - Participated in 10+ engagements across unique industries, including aviation, entertainment, and manufacturing
- Created and taught two threat hunting training courses
  - One privately taught to a Fortune 100 client
  - One publicly taught at Black Hat
##### Analyst, Detection Operations (CIRT) <br/> General Electric (May 2013 – June 2014)
- Threat detection subject matter expert for GE's 450+ Bro/Zeek sensor deployment
- Led research and development of advanced threat detection scenarios using Bro/Zeek
  - Led a 2-month project that determined precise, heuristic detection of attacker TTPs was feasible across GE's global network
- Developed methods of validating, enriching, and scaling tens of thousands of indicators of compromise (IOCs) across the enterprise
- Developed custom Bro/Zeek detection scripts, including heuristic detection for reconnaissance, lateral movement, and data exfiltration

#### Skills and Technology
- Skills: Threat detection engineering, threat hunting, network security monitoring, incident investigation, open-source intelligence collection, malware analysis
- Programming/Scripting Languages: Python, Bash, Go
- DevOps Technology: Docker, Git, ZeroMQ, SaltStack, Redis, Drone, Telegraf, Grafana, OpenStack/Heat
- Industry Technology: Bro/Zeek, Suricata, YARA, PassiveTotal, Shodan, Splunk, Elastic Stack, Elastic Beats, Volatility

#### Community Contributions
##### Presentations
- "Beyond AV: Detection-Oriented File Analysis". BSides San Francisco, Mar. 2019.
- "[Threat Hunting for Command and Control](https://www.slideshare.net/sqrrl/threat-hunting-for-command-and-control-activity)". Sqrrl webinar, Nov. 2016.
- "[Failed Experiments](https://www.bro.org/community/bro4pros2016.html)". Bro4Pros 2016, Mar. 2016.
- "[Beyond IDS: Practical Network Hunting](https://speakerdeck.com/jshlbrd/beyond-ids-practical-network-hunting)". BSides New York, Jan. 2016.
- "[Adversary Hunting and Incident Response: Network Edition](https://www.blackhat.com/eu-15/training/adversary-hunting-and-incident-response-network-edition.html)". Black Hat Europe 2015 Training, Nov. 2015.
- "[Hunting Through RDP Data](https://speakerdeck.com/jshlbrd/hunting-through-rdp-data)". BroCon 2015, Aug. 2015.
- "[Analyzing RDP Traffic with Bro](https://speakerdeck.com/jshlbrd/analyzing-rdp-traffic-with-bro)". Bro4Pros 2015, Feb. 2015.
##### Open-Source Projects
- [Strelka](https://github.com/target/strelka) (Target, Lead)
- [Bro/Zeek](https://github.com/zeek/zeek) (ICSI, Contributor)
- [Laika BOSS](https://github.com/lmco/laikaboss) (Lockheed Martin, Contributor)
##### Writing
- "[Building Distributed, Scalable Python Apps with pyzmq and multiprocessing](https://medium.com/@jshlbrd/building-distributed-scalable-python-apps-with-pyzmq-and-multiprocessing-ae832f75d1f0)". Medium, Jun. 2018.
- "[Laika BOSS + Bro = LaikaBro (?!)](https://medium.com/@jshlbrd/laika-boss-bro-laikabro-d324d99fddae)". Medium, Feb. 2017.
- "[THE HUNTER'S DEN: COMMAND AND CONTROL](https://sqrrl.com/the-hunters-den-command-and-control/)". Sqrrl blog, Feb. 2017.
- "[Hunting for PowerShell Using Heatmaps](https://medium.com/@jshlbrd/hunting-for-powershell-using-heatmaps-69b70151fa5d)". Medium, Jan. 2017.
- "[THE HUNTER'S DEN: INTERNAL RECONNAISSANCE (PART 2)](https://sqrrl.com/the-hunters-den-internal-reconnaissance-part-2/)". Sqrrl blog, Nov. 2016.
- "[THE HUNTER'S DEN: INTERNAL RECONNAISSANCE (PART 1)](https://sqrrl.com/the-hunters-den-internal-reconnaissance-part-1/)". Sqrrl blog, Nov. 2016.
- "[Maximizing Network Threat Intel with Bro](https://www.crowdstrike.com/blog/maximizing-network-threat-intel-bro/)". CrowdStrike blog, Dec. 2014.
