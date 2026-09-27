# Security Portfolio

Software engineer (Go, Kubernetes, cloud) transitioning into offensive security. This repo collects lab and CTF work with an emphasis on **methodology and clear reporting**, not flag counts — every flagship engagement is documented the way a real client deliverable would be.

**Background that carries over:** I build and operate production Go services on Kubernetes (ArgoCD, DynamoDB/S3/Postgres, Datadog/Splunk) on a 24x7 on-call rotation. That means I read application logic, understand cloud/container internals, and write remediation a developer can actually act on.

**Certifications / path:** CompTIA A+, Network+ → (in progress: Security+ → hands-on cert e.g. eJPTv2 / PNPT / OSCP).

> ⚠️ Everything here is scoped to **my own isolated labs, intentionally-vulnerable VMs, or retired/sanctioned CTF targets**. No activity against systems I don't own or lack authorization to test. Active-machine writeups are never published.

<!-----

## Flagship engagements

Full professional reports (executive summary → CVSS-scored findings → remediation).

| Engagement | Platform | Type | Key findings | Report |
|---|---|---|---|---|
| Metasploitable 2 | Local lab | Network / host | _e.g. vsftpd backdoor, Samba RCE, weak creds_ | [report](engagements/metasploitable2/report.md) |
| _TBD_ | VulnHub | Network / host | | |
| _TBD_ | HTB (retired) | Network / host | | |
| _TBD_ | Local lab | Container / IaC | | |
| _TBD_ | Web app lab | Web (OWASP) | | |

## CTF writeups

Concept-focused writeups for **retired / publishable** targets only.

| Challenge | Platform | Category | Writeup |
|---|---|---|---|
| _TBD_ | picoCTF | Web / crypto / rev | |
| _TBD_ | OverTheWire (Bandit) | Linux fundamentals | |

## Practice log

The volume grind lives here — every box worked, not every box written up. See **[progress-log.md](progress-log.md)**.

----->

## Repo layout

```
├── README.md                     # this page
├── progress-log.md               # running log of all boxes/challenges
├── methodology/
│   └── my-pentest-process.md     # PTES-based repeatable checklist
├── templates/
│   └── pentest-report-template.md
├── engagements/                  # full reports + sanitized evidence
└── ctf-writeups/                 # publishable CTF writeups
```

## Contact

- [GitHub](https://github.com/danny-oneal)
- [LinkedIn](https://linkedin.com/danny-oneal)
