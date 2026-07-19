# Incident Response Playbooks

Structured IR playbooks mapping each major attack type to concrete detection, containment, and recovery procedures — built around the preparation → detection → containment → eradication → recovery → lessons-learned framework.

## What's in here

| Playbook | Attack Type |
|---|---|
| phishing-attack-playbook | Phishing |
| mitm-attack-playbook | Man-in-the-Middle (MITM) |
| ddos-attack-playbook | Distributed Denial of Service (DDoS) |
| ransomware-playbook | Ransomware Infection |

Each playbook follows the same structure: incident overview, incident identification, preparation procedures, detection procedures, containment procedures, eradication procedures, recovery procedures, roles and responsibilities, communication strategy, and metrics for success.


## Framework

Every playbook follows the standard IR lifecycle:

1. **Preparation** — tools, training, and readiness ahead of an incident
2. **Detection & Analysis** — identifying and scoping the incident
3. **Containment** — limiting the blast radius
4. **Eradication** — removing the root cause
5. **Recovery** — restoring normal operations
6. **Lessons Learned** — post-incident review and process improvement

## Usage

These playbooks are written to be adapted, not used verbatim — swap in your own tooling, escalation paths, and communication channels where the scenarios reference example environments.
