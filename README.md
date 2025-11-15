# CTI_Assignment_Kiranjot_kaur

Cyber Threat Intelligence Assignment Repository for Kiranjot Kaur.

Task 3: - 

Adversary: - A state-sponsored Russian threat actor, tracked by Microsoft as Midnight Blizzard (also referred to as APT29). (CSIAC) |
Infrastructure: - Corporate email accounts within Microsoft’s environment and associated systems; exfiltrated communications and authentication data used to target customer systems. (CISA) |
Capability: - Ability to exfiltrate email content, harvest authentication credentials (tokens, passwords) from compromise of Microsoft corporate accounts, then use those credentials to attempt further compromise of customer systems. (CSIAC) |
Victim: - Microsoft itself (its corporate email system), and by extension Microsoft commercial customers (government agencies, private sector) who use Microsoft corporate email services. (CISA) |


Task 5: - 
Midnight Blizzard, also known as APT29, is a Russian state-sponsored cyber threat actor known for conducting advanced espionage operations. This group was tracked by Microsoft after they successfully breached Microsoft’s internal corporate email systems. The attackers gained access by compromising authentication tokens and credentials, which allowed them to read private communications between Microsoft and its clients.

The targeted sectors include government agencies and large private companies, especially those that rely on Microsoft’s corporate email infrastructure. The initial access vector involved credential theft and abuse of trust relationships within Microsoft’s environment. Once inside, the adversary exfiltrated sensitive email content and authentication data, which they then used to attempt further compromises against downstream customer systems.

Using the Diamond Model of Intrusion Analysis, the adversary is Midnight Blizzard (APT29); the infrastructure includes Microsoft’s corporate email systems and authentication mechanisms; the capability involves credential harvesting, email exfiltration, and lateral movement; and the victims are Microsoft and its commercial clients across various sectors.

Mitigation strategies recommended by CISA include resetting compromised credentials, analyzing exfiltrated content for risk, enforcing strong multifactor authentication (MFA), limiting privileged account access, and applying zero-trust principles. These steps help reduce the impact of the attack and prevent future exploitation.
