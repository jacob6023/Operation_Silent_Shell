# Operation Silent Shell
### Incident Response Case Study — Hybrid Cloud + Linux Host Compromise

A simulated multi-stage intrusion spanning cloud and on-premises Linux infrastructure, investigated and documented as a full incident response engagement — from initial compromise through persistence to remediation.

## Scenario

Investigated a simulated attack involving valid credential abuse, remote command execution, and the establishment of persistence on a compromised Linux host. The engagement was scoped as a hybrid cloud + Linux environment to reflect a realistic enterprise attack surface.

## MITRE ATT&CK Mapping

| Technique ID | Technique | Role in Attack Chain |
|---|---|---|
| T1078 | Valid Accounts | Initial access via credential abuse |
| T1105 | Ingress Tool Transfer | Attacker tooling brought onto the compromised host |
| T1059 | Command and Scripting Interpreter | Remote command execution |
| T1543.002 | Create or Modify System Process: Systemd Service | Persistence mechanism |

## Methodology

- Built a chronological attack timeline correlating log sources across the affected cloud and Linux systems
- Identified and analyzed attacker tooling used during the intrusion
- Mapped each stage of the attack chain to corresponding MITRE ATT&CK techniques
- Assessed impact and scope of the compromise
- Produced prioritized remediation and detection recommendations for each stage of the attack chain

## Deliverable

The full incident response report — including root cause analysis, attack flow, impact assessment, and prioritized remediation and detection guidance — is included in this repository: [`Operation_Silent_Shell_JJ.pdf`](./Operation_Silent_Shell_JJ.pdf)

## Skills Demonstrated

Log analysis · Attack timeline reconstruction · MITRE ATT&CK mapping · Root cause analysis · Incident response reporting · Detection and remediation planning
