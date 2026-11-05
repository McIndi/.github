# McIndi Solutions

**Gateway, PKI and agent security engineering for regulated enterprises.**

We automate and secure IBM DataPower and API Connect estates for banks, insurers, and healthcare organizations: certificate inventory and rotation, post-quantum readiness, and identity for AI agents. McIndi is two senior practitioners, [Clifford Bressette](https://www.linkedin.com/in/cliffbressette/) and [Brian Kearney](https://www.linkedin.com/in/brianpkearney/), and the tools below are the ones our engagements run on.

## Start here

| Repository | What it is | Where it fits |
| --- | --- | --- |
| [mast3](https://github.com/McIndi/mast3) | MAST: fleet automation for IBM DataPower (backups, deployments, configuration promotion, certificate audits) | DataPower operations and the certificate inventory behind our certificate-lifetime sprint |
| [pki_workbench](https://github.com/McIndi/pki_workbench) | Private CA management: root and intermediate CAs, certificate profiles, REST API | PKI and post-quantum readiness work |
| [project-armory](https://github.com/McIndi/project-armory) | Reference security platform on k3s: Keycloak OIDC, OpenBao secrets and PKI, Envoy Gateway, audit search | The base for running AI agents in regulated environments |
| [project-garrison](https://github.com/McIndi/project-garrison) | An audited agent runtime (BeeAI Agent Stack) deployed on Armory | Agent runtime identity and guardrails |
| [SIEMatic](https://github.com/McIndi/SIEMatic) | Security observability: agents, indexer, pipeline search language, dashboards, alerts | Audit trails, including the audit view for Project Catalyst |
| [delve](https://github.com/McIndi/delve) | Data platform for interactive search, dashboards, and alerts | Operational search and analytics |

More: [webutils](https://github.com/McIndi/webutils) (browser-only utilities), [logsieve](https://github.com/McIndi/logsieve) (in-browser log analysis), [adapt](https://github.com/McIndi/adapt) (files to REST APIs), [trailhead](https://github.com/McIndi/trailhead) (local code search).

## Work with us

- **Certificate-lifetime sprint:** inventory every certificate and key on your DataPower and API Connect gateways, and automate rotation before public TLS certificates drop to 100 days on March 15, 2027.
- **Quantum-safe gateway readiness:** a cryptographic bill of materials (CBOM) for the gateway tier and a roadmap to the federal post-quantum dates.
- **Agent runtime identity:** workload identity, just-in-time credentials, and egress control for AI agents moving past pilot.
- **Hands-on engineering:** DataPower, API Connect, OpenShift, Ansible, Vault, and Python by the hour.

Details at **[mcindi.com](https://www.mcindi.com/)** · Read **[When the Agent Had the Keys](https://www.mcindi.com/insights/when-the-agent-had-the-keys/)** · Email **sales@mcindi.com**
