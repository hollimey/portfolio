# Cybersecurity Project 2
Repository contains the presentation for the following project below. The topic addressed is leading and managing enterprise information security. <br/>

## Risk Management and Cyber Threat Mitigation
The presentation provides a thorough examination of the cybersecurity attack that targeted Schneider Electric, a French multinational energy management company, on November 4, 2024. <br/>

The attack was carried out by the Hellcat ransomware group, formerly known as Grep. Hellcat announced on their blog and social media X, that they infiltrated Schneider Electric’s custom Atlassian Jira server, used for project management, and their Gravatar developer platform by exploiting exposed credentials. Once inside, Hellcat utilized a MiniOrange REST API to scrape 400,000 rows of user data (Abrams). In their posts, Hellcat demanded $125,000 in exchange for 40 gigabytes of stolen data. The compromised data included employee and customer names, email addresses, project files, and plugin information (TheRavenFile; Swain). <br/>

Schneider Electric refused to pay the ransom, and Hellcat released the stolen data sometime between November 8, 2024, and December 29, 2024, on the dark web via a new Onion Domain with direct download capabilities (Okunyte; TheRavenFile). Schneider Electric later issued a statement asserting that the attack only affected its internal project execution tracking platforms, which they claimed are hosted in an isolated environment, thus not impacting their products or services (Greig; Jones; Swain). <br/>

Notably, this was Schneider Electric’s second cybersecurity breach of 2024. Earlier in January, the Cactus ransomware group exfiltrated 1.5 terabytes of data, underscoring the company’s urgent need for enhanced security measures (Vasquez). To address these vulnerabilities, Schneider Electric should strengthen its extended detection and response (XDR) solutions to provide better end-to-end network visibility and eliminate blind spots that could be later exploited; improve training and education programs to prevent exposures related to human error; expand its network detection and response (NDR) solutions to enhance network traffic and suspicious activity monitoring (Sangfor Technologies). As Swain points out, Schneider Electric’s large presence in critical infrastructure sectors, employing over 100,000 individuals and generating nearly $40 billion annually (Abrams), makes it a prime target for cybercriminals seeking valuable data and high-impact vulnerabilities. Active management practices by creative, highly adaptable cybersecurity experts are vital for securing the company’s assets. <br/>

Schneider Electric’s security policies claim alignment with recognized standards such as ISO 27001, NIST, ISA/IEC 62443, and GDPR. The company’s 2022 Universal Registration Document expresses that Schneider’s ISO 27001 certification demonstrates its commitment to securely managing information; the ISA/IEC 62443-4-1 certification outlines the requirements and processes Schneider implements and maintains to secure its industrial systems; the CREST certification confirms Schneider’s ability to conduct penetration tests; the CyberVadis certification reflects Schneiders Gold Rating in its adherence to international information security standards; and the ISO/IEC 30111:2019 and ISO/IEC 29147:2018 certifications highlight Schneider’s commitment to addressing vulnerabilities (122). <br/>

Following the attack, Schneider Electric released five security notifications on November 12, 2024. The ransomware exploited weak user credentials, prompting Schneider to disclose several common vulnerabilities and exposures (CVEs). These include CVE-2021-22763 listed as high (CWE-640: Weak Password Recovery Mechanism for Forgotten Password) and CVE-2021-22764 listed as medium (CWE-287: Improper Authentication) (PowerLogic PM5500 1); CVE-2024-10575 listed as critical (CWE-862: Missing Authorization) (EcoStruxure 1); CVE-2024-8936 medium-high (CWE-20: Improper Input Validation), CVE-2024-8937 high-critical (CWE-119: Improper Restriction of Operations with the Bounds of a Memory Buffer), CVE-2024-8938 high-critical (CWE-119: Improper Restriction of Operations with the Bound of a Memory Buffer) (Modicon, Report no. SEVD-2024-317-03 1-2); CVE-2024-8933 high (CWE-924: Improper Enforcement of Message Integrity During Transmission in a Communication Channel), CVE-2024-8935 high (CWE-290: Authentication Bypass by Spoofing) (Modicon, Report no. SEVD-2024-317-02 1); and CVE-2024-9409 high (CWE-400: An Uncontrolled Resource Consumption) (PowerLogic PM5300 1). <br/>

These incidents emphasize the need for Schneider Electric to adopt proactive and comprehensive cybersecurity measures to protect its assets and maintain stakeholder trust. By prioritizing continuous improvement and leveraging emerging technologies, Schneider Electric can rebuild trust and set a benchmark for cybersecurity in the energy management sector. <br/><br/>


### Works Cited

2022 Universal Registration Document. Schneider Electric, Financial and Sustainable Development 
Report, 2022. https://flipbook.se.com/ww/en/998-22385455/2023/#page/125, PDF file.

PowerLogic PM5500 and PowerLogic PM8ECC. Schneider Electric, Security Notification, 12 Nov. 2024. 
Report no. SEVVD-2021-159-02. https://download.schneider-electric.com/files?p_Doc_Ref=SEVD-2021-159-02&p_enDocType=Security+and+Safety+Notice&p_File_Name=SEVD-2021-159-02.pdf, PDF file.

EcoStruxure IT Gateway. Schneider Electric Security Notification, 12 Nov. 2024. Report no. SEVD-2024-
317-04. https://download.schneider-electric.com/files?p_Doc_Ref=SEVD-2024-317-
04&p_enDocType=Security+and+Safety+Notice&p_File_Name=SEVD-2024-317-04.pdf, PDF file.

Modicon Controllers M340 / Momentum / MC80. Schneider Electric Security Notification, 12 Nov. 2024. Report no. SEVD-2024-317-03. https://download.schneider-electric.com/files?p_Doc_Ref=SEVD-2024-317-03&p_enDocType=Security+and+Safety+Notice&p_File_Name=SEVD-2024-317-03.pdf, PDF file.

---. Report no. SEVD-2024-317-02. https://download.schneider-electric.com/files?p_Doc_Ref=SEVD-2024-317-02&p_enDocType=Security+and+Safety+Notice&p_File_Name=SEVD-2024-317-02.pdf, PDF file.

Swain, Gyana. “Schneider Electric suffers data breach, exposing critical project and user data.” CSO, 6 
Nov. 2024, https://www.csoonline.com/article/3599966/schneider-electric-suffers-data-breach-exposing-critical-project-and-user-data.html. Accessed 20 Jan. 2025.

TheRavenFile. “IOC / Hellcat Ransomware.” GitHub, 
https://github.com/TheRavenFile/IOC/blob/main/Hellcat%20Ransomware. Accessed 21 Jan. 2025.

Okunyte, Paulina. “Schneider Electric’s stolen data leaked on dark web.” Cybernews, 30 Dec. 2024, 
https://cybernews.com/security/schneider-electrics-data-breach/. Accessed 21 Jan. 2025.

Sangfor Technologies. “Schneider Electric data breach by Hellcat Ransomware Gang.” Sangfor, 8 Nov. 
2024, www.sangfor.com/blog/cybersecurity/schneider-electric-data-breach-hellcat-
ransomware-gang. Accessed 20 Jan. 2025.

Abrams, Lawrence. “Schneider Electric confirms dev platform breach after hacker steals 
data.” BleepingComputer, 4 Nov. 2024, www.bleepingcomputer.com/news/security/schneider-
electric-confirms-dev-platform-breach-after-hacker-steals-data/. Accessed 20 Jan. 2025.

Vasquez, Christian. “Schneider Electric reports cyberattack, its third incident in 18 months.” CyberScoop, 
5 Nov. 2024, cyberscoop.com/schneider-electric-energy-ransomware-hellcat/. Accessed 20 Jan. 
2025.

Jones, David. “Schneider Electric investigating cyber intrusion after threat actor gains access to 
platform.” Cybersecurity Dive, 5 Nov. 2024, www.cybersecuritydive.com/news/schneider-electric-investigating-cyber/732006/. Accessed 20 Jan. 2025.

Greig, Jonathan. “Schneider Electric says hackers accessed internal project execution tracking platform.” 
The Record, 4 Nov. 2024, https://therecord.media/schneider-electric-hackers-accessed-internal-
project-tracking-platform. Accessed 21 Jan. 2025.
