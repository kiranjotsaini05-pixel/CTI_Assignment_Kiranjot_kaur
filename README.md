# CTI_Assignment_Kiranjot_kaur

Cyber Threat Intelligence Assignment Repository for Kiranjot Kaur.

Task 3: - 

Diamond Model Vertex Extraction: - Activity attributed to UNC5221
Adversary: - identified in Mandiant investigations as a frequently observed actor in the Americas and linked to exploitation of specific CVEs in late 2023 / early 2024. 
Infrastructure: - Use of externally-hosted exploit infrastructure and temporary VPN/proxy chains to mask origin; activity observed against Internet-facing services (CVE exploitation entry points). Report notes exploitation-driven intrusions and use of proxy/C2 infrastructure patterns.
Capability: - Exploitation of known CVEs (e.g., chain activity around CVE-2023-46805 and CVE-2024-21887 as observed in related investigations), credential harvesting and living-off-the-land persistence techniques. Tooling includes exploit frameworks and post-exploit backdoors. 
Victim: - Targets included organizations in the Americas across sectors vulnerable to Internet-facing CVEs; M-Trends highlights financial, professional services, and high-tech among the most frequently targeted sectors.

Task 5: - Threat Actor: -
UNC5221 is a threat group that Mandiant observed many times in 2024. They usually break into systems by taking advantage of newly discovered software vulnerabilities. In several investigations, this group was seen targeting Internet-facing systems and using known CVEs to get inside a network. After gaining access, they often steal credentials and use normal system tools to hide their activity and move around without being noticed. They also use temporary cloud servers, VPNs, and proxy networks to hide where the attack is really coming from. M-Trends data shows that exploiting software weaknesses was the most common way attackers gained entry in 2024, which matches UNC5221’s behavior.

UNC5221 has targeted many different industries, especially financial services, professional services, and technology companies. These sectors are attractive because they hold valuable data and often have systems that can be exploited.

To defend against this group, the report recommends quickly patching vulnerabilities, especially on Internet-facing systems, using strong multi-factor authentication, limiting account permissions, and improving monitoring for strange login activity or signs of exploitation. These steps make it much harder for attackers like UNC5221 to get in and stay inside a network.

Task 6: - Reflection: -
1. How does the Diamond Model help in understanding threat actors?
The Diamond Model helps break down an attack into four parts: who is attacking, what tools they used, how they attacked, and who they targeted. This makes it easier to understand the full picture of the intrusion instead of looking at random details. For a group like UNC5221, the model helps connect their use of vulnerabilities (capability), the servers they used (infrastructure), and the victims they targeted. This makes it easier to see patterns and know where defenders should focus.

2. What challenges did you face in identifying each vertex?
The biggest challenge is figuring out who the attacker actually is, because reports usually don’t give a confirmed identity. Another difficulty is telling the difference between capability (tools/skills) and infrastructure (servers, domains), since attackers often reuse common tools and switch servers often. Sometimes the report gives limited details, so you have to interpret information based on context.

3. How could this model support proactive defense strategies?
The model helps defenders think ahead by showing how the attacker works. Once you see their tools, servers, and methods, you can watch for those signs in your own environment. This lets you detect suspicious activity earlier. For example, if you know UNC5221 uses certain vulnerabilities and proxy servers, you can patch those CVEs quickly and monitor for unusual login activity or exploit attempts. This can stop an attack before it becomes serious.
