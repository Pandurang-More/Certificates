
-----

# Cybersecurity Notes 💻

### Table of Contents

- Introduction to Cybersecurity
- The CIA Triad: Core Objectives
- Key Elements of Cybersecurity
- Risk Management
- Common Misconceptions
- Laws and Ethics
- Threat Actor Groups
- Types of Cyberattacks
- The Structure of a Cyberattack
- The Cybercrime Ecosystem
- Social Engineering
- Open-Source Intelligence
- Technical Scanning
- Case Studies
- On the Defense
- About This Course
- Financial Impacts
- Security Strategy
- Prevent Attacks
- Detect Attacks
- Respond to Attacks
- Introducing Cryptography
- Career Paths and Skills

-----

## Introduction to Cybersecurity

The global average total cost of a **data breach** is **$4.35 million USD**, the highest it has ever been. Cybercrime is predicted to cost the world **$8 trillion USD** in 2023. If measured as a country, it would be the world’s third largest economy.

**Cybersecurity** is the practice of protecting and recovering data, networks, devices, and programs from threats. These threats can have **digital**, **human**, or **physical** components.

  * **Digital security** involves safeguarding your data and systems from threats like **malware**, **viruses**, or **ransomware**. Examples include **firewalls** and **encryption software**.
  * **Human security** involves protecting data from threats caused by human behavior, which can be intentional or unintentional. Examples include **employee security training** and **strong password policies**.
  * **Physical security** involves protecting tangible assets that support digital infrastructure, such as workstations and data centers. Examples include **surveillance systems** and **access control measures**.

-----

## The CIA Triad: Core Objectives

The three core objectives of cybersecurity are **Confidentiality**, **Integrity**, and **Availability** (CIA).

  * **Confidentiality**: Keeping data secret, ensuring only authorized people can access it. For example, a software company keeping their application source code private.
  * **Integrity**: Ensuring data is trustworthy and accurate by protecting it from unauthorized modification or destruction. For instance, preventing a financial transaction amount from being altered.
  * **Availability**: Ensuring timely and reliable access to and use of data. For example, expecting 24/7 online access to your bank account.

**Examples of CIA in Context**

  * **Confidentiality** is most crucial for government intelligence agencies to protect sensitive, classified information.
  * **Integrity** is most crucial for banks, where financial transactions rely on data accuracy and consistency.
  * **Availability** is most crucial for an online retailer, where website downtime can lead to lost business and damaged reputation.

### Controls

**Controls** are safeguards or countermeasures to minimize security risks.

**Controls for Confidentiality:**

  * **Encryption**
  * **Access controls** (e.g., password protection, biometrics)
  * **Patch management**

**Controls for Integrity:**

  * **Checksums**
  * **Access controls** and **user permissions**
  * **Data backups**
  * **Audit trails**

**Controls for Availability:**

  * **Redundant systems** and **data backup procedures**
  * **Antimalware software** and **firewalls**
  * **Disaster recovery** and **business continuity plans**

-----

## Key Elements of Cybersecurity

An organization's security approach should consider three key elements: **Education**, **Process**, and **Technology**.

  * **Education**: Builds a "human firewall" by teaching employees the importance of cybersecurity, reducing risky behavior, and encouraging the reporting of suspicious activity.
  * **Process**: A defined set of steps for activities. Good processes are **clear**, **accessible**, and **consistent**, reducing complexity that attackers can exploit.
  * **Technology**: The underlying infrastructure, including controls like device encryption and network defenses. Good technology solves problems without creating new ones for users.

| Technological Leap | Business Benefit | Perceived Drawback | Undesirable User Response |
| :--- | :--- | :--- | :--- |
| Automated patch management | All software is up to date | Interruptions to use of device | User does not power down devices |
| High complexity mandatory passwords | Harder for attackers to guess passwords | Tedious to use | P@ssw0rd\! |
| Mandatory passwords expire after 30 days | Passwords cannot be compromised for long periods | Predictably repetitive | PasswordJan to then PasswordFeb |
| Encrypted emails | Attackers cannot read emails in transit | Additional configuration and complexity | Disable encryption feature |

-----

## Risk Management

A **risk** is the possibility of something happening with a negative consequence.

### Risk Valuation

The value of a risk can be calculated with this equation:

$$Risk Value = Consequence \times Likelihood$$

  * **Consequence** is the impact and associated damages.
  * **Likelihood** is how often the risk impact occurs.

In cybersecurity, the likelihood of an attack depends on three attributes:

$$Likelihood = Adversary Capability \times Adversary Motivation \times Vulnerability Severity$$

### Responses to a Risk

Organizations can choose from four responses to a risk:

  * **Acceptance**: Acknowledging the risk and being prepared to deal with its consequences.
  * **Reduction**: Taking steps to lower the risk's likelihood or consequence by implementing security controls.
  * **Transference**: Shifting the risk to a third party, such as an insurance company.
  * **Rejection**: Withdrawing from the activity that leads to the risk, which might involve shutting down a site.

### Risk Appetite

A **risk appetite** is the level of risk an organization is willing to accept.

  * A **high** risk appetite might involve using the latest technologies for a competitive edge.
  * A **low** risk appetite prioritizes stability and protective measures.

-----

## Common Misconceptions

  * **"Everyone who works in cybersecurity comes from an IT background."** This field requires a diverse range of skills from many backgrounds, not just IT.
  * **"All hackers are criminals."** The term also refers to "ethical hackers" who legally test and fortify systems.
  * **"Cybersecurity is something I can’t do."** The field is vast and offers roles for everyone, regardless of skill set.
  * **"I’m too old or too young to work in this industry."** Teams with diverse experiences and life views are highly valuable.

-----

## Laws and Ethics

A wide-ranging set of international laws govern the use of computing technologies.

  * **Unapproved use or control of a computer device**: Prohibits unauthorized access.
  * **Preventing others from legitimate use**: Covers actions that degrade or prevent service availability.
  * **Aiding other criminals or designing malware**: Refers to being an accomplice or creating malicious software.
  * **Unauthorized data alteration**: Prevents the modification, deletion, or blocking of personal data.
  * **Prohibited software**: Laws against creating or distributing hacking tools and malware.
  * **Cyberstalking and harassment**: Curbs harmful or threatening online behavior.

**Legality and Ethics in Cybersecurity**

| Legal | Ethical | Legal and Ethical |
| :--- | :--- | :--- |
| • Collecting excessive data on a product or user | • Performing certain scam-baiting activities | • Conducting normal IT system testing |
| • Collating public posts or online information without consent | • Hunting down attackers using active defense | • Reviewing open-source code |
| • Posting deceptive content online | • Placing booby traps for prospective attackers | • Following responsible disclosure policies for vulnerabilities |
| | • Performing certain whistleblowing activities | |

-----

## Threat Actor Groups

A **threat actor** is an entity that poses a cybersecurity threat. The five main groups are:

### Script Kiddie

  * **Who they are**: Novice hackers using basic hacking tools without understanding them.
  * **Objective**: Reputation, entertainment, or settling grudges.
  * **Protection**: An effective patching schedule is a sufficient deterrent.

### Hacktivist

  * **Who they are**: Driven by ideological or political reasons.
  * **Objective**: To bring about change.
  * **Protection**: Have a plan and methods to cope with a sustained, disruptive attack.

### Criminal Gang

  * **Who they are**: Organized groups operating for financial gain.
  * **Objective**: Making money through theft, extortion, or work-for-hire.
  * **Protection**: Effective defenses for critical assets, a trained workforce, and backups.

### Nation-State Hacker

  * **Who they are**: Highly trained specialists employed by a government.
  * **Objective**: Strategic, multi-year plans for political or strategic advantage.
  * **Protection**: Extremely difficult; requires fully coordinated defenses.

### Malicious Insider

  * **Who they are**: Staff members who use their authorized access to harm the organization.
  * **Objective**: Revenge or financial gain.
  * **Protection**: No budget or resources required; they use their granted access.
  * **Protection**: Monitor staff carefully, vet employees, and maintain an effective culture.

-----

## Types of Cyberattacks

  * **Denial-of-service (DoS) attack**: Floods a website with traffic, causing an outage.
  * **Distributed denial-of-service (DDoS) attack**: A DoS attack from multiple sources, forming a **botnet**.
  * **Phishing**: Tricks users into taking an action by sending messages that appear to be from a trusted source.
  * **Spear phishing**: A targeted phishing attack on a specific person or organization.
  * **Malware**: Malicious software designed to harm data or systems. Examples include **keyloggers** and **ransomware**.
  * **Man-in-the-middle (MitM) attack**: An attacker intercepts communications between a client and server.
  * **Domain Name System (DNS) attack**: Manipulates the DNS to redirect users to a malicious website.
  * **Structured query language (SQL) injection**: Placing malicious code in web page inputs to access a database.

**AI in Cyberattacks**
Attackers are using AI to enhance attacks through **task automation**, **detection evasion**, **target identification**, and **social engineering** (e.g., deepfakes).

-----

## The Structure of a Cyberattack

### Lockheed Martin Cyber Kill Chain®

This framework breaks down an attack into seven steps:

1.  **Reconnaissance**: Gathering information about the target.
2.  **Weaponization**: Designing malware to exploit a vulnerability.
3.  **Delivery**: Sending the malware to the target (e.g., email, USB drive).
4.  **Exploitation**: The malware activates and takes advantage of a vulnerability.
5.  **Installation**: The malware gets persistence by creating **backdoors**.
6.  **Command and control (C2)**: The attacker establishes communication with the compromised systems.
7.  **Actions on objectives**: The attacker accomplishes their goals.

### MITRE ATT\&CK Matrix

This knowledge base helps professionals identify an attacker's tactics and techniques to anticipate their next move. You can explore it at [https://attack.mitre.org](https://attack.mitre.org).

-----

## The Cybercrime Ecosystem

Making money is the biggest motivator for cybercriminals.

  * **Theft**: Stealing money from targets directly.
  * **Work for hire**: Offering criminal services to others for a fee.
  * **Extortion**: Gaining the ability to disrupt a victim and demanding a ransom, especially with **ransomware**.

**Cryptocurrency**
Cybercriminals prefer cryptocurrencies like **Bitcoin** because they are **anonymous** and **decentralized**, making transactions difficult for law enforcement to trace.

-----

## Social Engineering

**Social engineering** is the use of deception to manipulate individuals into divulging confidential information.

  * A social engineering attack is typically **well-researched**, **delivered confidently**, and **plausible and realistic**.
  * **Phishing emails** are a common form of social engineering. Red flags include generic greetings, poor grammar, and suspicious links.

-----

## Open-Source Intelligence

**Open-source intelligence (OSINT)** is intelligence gathered from publicly available sources like blogs, news sites, and social media. It is often free, easy to acquire, and **undetectable to the target**. Attackers use it during the reconnaissance phase.

-----

## Technical Scanning

Technical scanning techniques help both IT professionals and attackers collect information about networks.

  * **Ping test**: Measures the time for a packet to travel to a device to see if it's active.
  * **Traceroute**: Maps the path of a network connection between two devices.
  * **Port scanning**: Identifies a host's open ports to see what network services are running.
  * **Vulnerability scanning**: Simulates hacking techniques to discover vulnerabilities.
  * **Search engine for the internet**: Tools like [Shodan](https://www.shodan.io/) catalog internet-connected devices.
  * **Network scanning**: Tools like **Nmap** collect information about a network's hosts and services.

-----

## Case Studies

  * **Stuxnet (2010)**: An advanced cyberweapon that targeted centrifuges in Iranian uranium processing. It demonstrated the power of a highly-targeted attack exploiting **zero-day vulnerabilities** and spreading via USB drives.
  * **LAUSD Ransomware Attack (2022)**: A Russian criminal group, Vice Society, launched a ransomware attack on the Los Angeles Unified School District. The district's refusal to pay the ransom led to the attackers releasing a great deal of critical data on the dark web, highlighting the need for robust security in public services.

-----

## On the Defense

### Financial Impacts

The average cost of a data breach is **$4.45 million USD**.

  * The largest contributors to this cost are **detection and escalation**, **lost business**, and **regulatory fines**.
  * The **Hiscox Cyber Readiness Report 2023** found that while attacks are rising, businesses spending more on security are seeing the cost of those attacks decrease.

### Security Strategy

A **security strategy** is a plan to protect digital and physical assets, including **risk assessment**, **policies**, **training**, and **incident response**. **Security maturity** is how well an organization can protect itself. The **Cybersecurity Capability Maturity Model (C2M2)** helps organizations assess their maturity.

### Prevent Attacks

The goal is to make attacks more difficult to achieve.

  * **Reduce the attack surface**: Minimize all points where an attacker can try to enter a system.
  * **Create a demilitarized zone (DMZ)**: A buffer network between an organization's private network and the internet.
  * **Follow the principle of least privilege**: Grant a user the fewest permissions needed to do their job, limiting the "blast radius" of an attack.
  * **Manage software vulnerabilities**: Regularly update and patch software.
  * **Use defense in depth**: Apply multiple layers of controls (e.g., firewalls, antimalware, encryption).

### Detect Attacks

  * **Antimalware software**: Detects malware by scanning for **malware signatures**.
  * **Logging**: Accurately records actions to provide an audit trail.
  * **Network monitoring**: Identifies network activity and anomalies.
  * **Security information and event management (SIEM) tools**: Aggregates data for analysis by a **security operations center (SOC)**.
  * **Artificial intelligence (AI)**: Enhances detection by automating tasks and reducing **false positives**.

### Respond to Attacks

The SANS Institute's six-phase incident response framework:

1.  **Preparation**: Planning and preparing resources.
2.  **Identification**: Detecting and confirming an incident.
3.  **Containment**: Preventing the situation from worsening.
4.  **Eradication**: Removing the malware or attackers.
5.  **Recovery**: Restoring standard operations.
6.  **Reflection**: Learning from the incident to improve future responses.

-----

## Introducing Cryptography

**Cryptography** is the practice of transforming data to conceal its content.

  * **Encryption**: Converts **plaintext** into unreadable **ciphertext** using a **cipher** and **key**.
  * **Symmetric encryption**: Uses the same key for both encryption and decryption.
  * **Asymmetric encryption**: Uses a **public key** to encrypt and a separate, secret **private key** to decrypt.
  * **Quantum-safe encryption**: Security methods resistant to potential attacks from quantum computers.

-----

## Career Paths and Skills

### Roles in Cybersecurity

  * **Cybersecurity Analyst**
  * **Cybersecurity Engineer**
  * **Network Security Architect**
  * **Penetration Tester**
  * **Malware Analyst**
  * **Digital Forensics Investigator**

### Skills to Build

  * **Baseline Skills**: Information security, threat analysis, cryptography, and risk management.
  * **Workplace Skills**: Critical thinking, problem-solving, communication, and adaptability.
  * **Specialized Skills**: Malware analysis, cloud security, and programming languages like Python.

### Resources to Explore

  * **Free Learning**: The Linux Foundation, IBM Security Learning Academy, and NIST.
  * **Certifications**: CompTIA, (ISC)², and EC-Council.
  * **Professional Organizations**: NIST, NCSC, and OWASP.
  * **News and Blogs**: Security Intelligence, Cybercrime Magazine, and Krebs on Security.
