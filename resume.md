## Josh Liburdi
#### Summary and Key Accomplishments
- 5+ years hands-on experience in threat detection and incident response
  - Investigating targeted attacks in large networks
  - Researching new threat detection tools and techniques
  - Developing tools and scripts for detecting attacker tools and
behaviors in diverse environments
- Lead/Contributor to multiple open-source threat detection projects and communities
  - [Strelka](https://github.com/target/strelka) (Target)
  - [Bro](https://github.com/bro/bro) (ICSI)
  - [Laika BOSS](https://github.com/lmco/laikaboss) (Lockheed Martin)
- Presenter/trainer at regional, national, and global information
security conferences
  - BSides, BroCon, Black Hat
- Passionate about threat detection and analysis
#### Presentations
- "Threat Hunting for Command and Control". Sqrrl webinar, 30
Nov. 2016.
- "Failed Experiments". Bro4Pros 2016, 15 Mar. 2016.
- "Beyond IDS: Practical Network Hunting". BSides New York, 16
Jan. 2016.
- "Adversary Hunting and Incident Response: Network Edition".
Black Hat Europe 2015 Training, 10-11 Nov. 2015.
- "Hunting Through RDP Data". BroCon 2015, 4 Aug. 2015.
- "Analyzing RDP Traffic with Bro". Bro4Pros 2015, 19 Feb. 2015.
#### Professional Experience
##### Lead Engineer - Threat Detection Operations
##### Target (March 2017 - Present)
- Acts as lead developer for Target's 1,800+ network security monitoring (NSM) sensor deployment
  - Led the on-boarding of 4 new NSM applications
  - Develops custom Bro scripts and Suricata rules
    - Identify attacker tactics, techniques, and procedures (TTPs)
    - Logging additional network metadata from HTTP, SMTP, and TLS
    - Perform reliable, high-volume file extraction (>100million files per day)
  - Developed continuous integration / continuous delivery system for updating Suricata rules
  - Developed system that utilizes ZeroMQ to enable centralized, authenticated packet capture retrieval from distributed sensors
  - Developed Linux-based methods of rate limiting outbound network traffic (for use in bandwidth-limited networks)
- Provides technical guidance to 3-person NSM engineering team
  - Application tuning
  - Metrics collection and monitoring
  - System and Git repository layout
- Contributed significant engineering work on a 9-month project to convert NSM applications from bare metal installs to Docker containers
  - Converted 10 software packages to Docker containers
  - Designed methodology for maximizing system resources through a combination of application CPU pinning and Docker CPU isolation
  - Developed methods of achieving continuous integration and continuous delivery using Git, Drone, and SaltStack
  - Achieved full-stack, automated deployment through use of docker-compose
- Project lead of Strelka, an open-source file scanning system written in Python 3
  - Used for gathering intelligence and threat hunting/detection
  - Supports 60+ unique types of files
  - Designed to scan 100s of millions of files per day
  - Integration with NSM sensors
- Works with Target's threat intelligence and red teams to improve detection across multiple data platforms (network, endpoint, authentication)
##### Security Technologist (Product Development)
##### Sqrrl (May 2016 - February 2017)
- Drove direction of Sqrrl platform by acting as a threat hunting, threat detection, and incident response subject matter expert for startup of 50+ people
- Researched established and emerging attacker tactics, techniques, and procedures
  - Performed research focused on DNS resolution activity that fully defined a major product release (Sqrrl v2.7.0)
    - DNS data record ingestion of Windows Server logs
    - Domain Generation Algorithm detection analytic
    - DNS tunneling detection analytic
  - Lead endpoint-centric research focused on artifacts found in process execution records and file metadata
- Regularly created, tested, and validated new hunting hypotheses and techniques
  - Significant focus on testing effectiveness of new and underutilized visualization techniques
- Publicly presented technical material related to the practice of threat hunting and threat detection through blogs and webinars
##### Senior Consultant
##### CrowdStrike Professional Services (June 2014 - April 2016)
- Performed threat hunting, network forensics, and incident response for Fortune 500 clients
  - Handled 15+ engagements across unique industries, including aviation, entertainment, and manufacturing
- Primary researcher and developer for CrowdStrike Services' network security monitoring and analysis platform
  - Expanded metadata collection by creating new protocol analyzers for Bro, including the open-source RDP analyzer, and integrating Laika BOSS
  - Boosted threat detection coverage by creating dozens of private and open-source Bro scripts
  - Improved analyst workflow by unifying multiple detection capabilities (network alerts/metadata, file alerts/metadata, full packet capture) into a custom Splunk-based analysis platform
- Created and taught two threat hunting training courses
  - One privately taught to a Fortune 100 client
  - One publicly taught at Black Hat Europe 2015
##### Analyst, Detection Operations (CIRT)
##### General Electric (May 2013 – June 2014)
- Acted as the threat detection subject matter expert for GE's 450+ sensor Bro deployment
- Lead developer of scalable, advanced threat detection scenarios using the Bro platform, including heuristic detection of attacker tools and behaviors
  - Led a project that determined heuristic threat detection was feasible across GE's global network
- Developed and implemented methods of validating, enriching, and scaling tens of thousands of indicators of compromise across the enterprise
- Developed custom threat detection scripts, including heuristic detection for reconnaissance, lateral movement, and data exfiltration

#### Skills and Technology
- Skills: Threat detection engineering, threat hunting, incident investigation, network security monitoring, open-source intelligence collection, malware analysis
- Languages: Python, Bash, Bro, Go
- Technology: Docker, Git, SaltStack, ZeroMQ, Elastic Beats, Telegraf, Bro, Suricata, Splunk/Kibana, PassiveTotal, CrowdStrike Falcon Endpoint, Volatility
