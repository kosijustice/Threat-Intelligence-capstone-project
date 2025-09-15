 # Threat-Intelligence-capstone-project
KORTNIT GROUP-OSINT Driven Threat Intelligence Assessment.

## Project Summary
This project delivers an OSINT-driven cyber threat intelligence assessment on Kortnit (kortnit.com), the world’s largest home improvement retailer. Using reconnaissance tools and the MITRE ATT&CK framework, the assessment identifies digital exposures, evaluates active ransomware groups targeting the retail sector, and provides risk-based recommendations.

## Key Achievements
1. Conducted OSINT Reconnaissance using Recon-NG, theHarvester, Shodan, Maltego, Sublist3r, and Amass.
   ### Discovered:
1. 2000+ domain hosts
2. 10+ exposed IP addresses
3. Publicly available employee emails & personal data
### Profiled two active ransomware groups relevant to retail:
1. Scattered Spider (UNC3944) – High-risk, retail-focused group exploiting MFA fatigue & helpdesk impersonation.
2. ALPHV/BlackCat – Ransomware-as-a-Service group known for large-scale retail and e-commerce extortion.
   ## Findings
1. Kortnit’s broad digital footprint increases its attack surface.
2. Exposure of emails & employee data elevates phishing/social engineering risks.
3. Prior third-party data leaks may enable credential stuffing and identity-based attacks.
4. Ransomware campaigns by Scattered Spider pose the greatest threat to retail operations.
## Recommendations
1. Implement attack surface reduction: regular domain/IP monitoring, asset inventory, and decommissioning unused infrastructure.
2. Strengthen identity security: MFA hardening, employee security training, and phishing-resistant authentication.
3. Deploy threat detection & response mapped to MITRE ATT&CK TTPs of Scattered Spider & BlackCat.
4. Monitor for Indicators of Compromise (IOCs) linked to targeted ransomware campaigns
