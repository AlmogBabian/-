Group Members: Almog Babian

Link to the Source CTI Report: https://blog.talosintelligence.com/phishing-as-a-service-2-furious/

The report describes the evolution of Phishing-as-a-Service (PhaaS) ecosystems targeting users through highly scalable and automated phishing infrastructures. 
Attackers provide ready-made phishing kits, enabling even low-skilled actors to launch credential theft campaigns. 
These kits often include fake login pages, SMS phishing (smishing), and real-time credential harvesting capabilities. 
Victims are typically tricked into entering sensitive information such as passwords and OTP codes.
The infrastructure is highly dynamic, using frequently changing domains to evade detection. 
Unlike traditional APT groups, this ecosystem is decentralized and financially motivated.
The significance of this trend lies in the democratization of cybercrime, lowering the barrier for launching advanced phishing attacks.


Attacker
      │
      ▼

Send SMS/phishing link

      │
      ▼

Victim receives phishing link

      │
      ▼


The victim enters credentials into fake page
      │

 Credentials + OTP are captured in real time

      |
      ▼


Attacker uses stolen data for account takeover (ATO)
      │
      ▼
Data may be sold or reused for financial fraud


Tactic: Initial Access
Technique: Phishing (T1566)
Behavior from Report: Victims receive phishing links via SMS/email
Link:https://attack.mitre.org/techniques/T1566/

Tactic: Credential Access
Technique: Input Capture (T1056)
Behavior from Report:Fake login pages capture credentials.
Link:https://attack.mitre.org/techniques/T1056/

Tactic: Initial Access
Technique: Spearphishing Link (T1566.002) 
Behavior from Report: Fake login links sent to targets
Link: https://attack.mitre.org/techniques/T1566/002/

Tactic: Credential Access
Technique: Web Credentials (T1555.003)
Behavior from Report:Theft of credentials via browser input
Link: https://attack.mitre.org/techniques/T1555/003/

Tactic: Collection
Technique: Automated Collection (T1119)
Behavior from Report:Automated harvesting of credentials/OTP
Link: https://attack.mitre.org/techniques/T1119/

Tactic: Command&Control
Technique: Web Protocols (T1071.001)
Behavior from Report:Data sent to phishing backend servers
Link:https://attack.mitre.org/techniques/T1071/001/

Tactic: Defense Evasion
Technique: Masquerading (T1036)
Behavior from Report:Fake domains mimic legitimate services
Link: https://attack.mitre.org/techniques/T1036/


Insights: 
This report shows how cybercrime is becoming industrialized through Phishing-as-a-Service platforms. 
Instead of advanced attackers, even low-skill actors can now execute sophisticated credential theft campaigns. 
This significantly increases the scale and frequency of phishing attacks worldwide.

The Attacks groups:
APT41 ID: G0096
Tonto Team ID: G0131
Confucius ID: G0142








