# Deep Dive — Security Engineer

---

## Career levels

=== "Junior (0–2 yrs)"
    **Focus:** Run vulnerability scans, assist with pen tests, monitor alerts, patch known CVEs.

    `Networking (TCP/IP, HTTP, DNS, TLS)` `Linux fundamentals` `Python scripting` `OWASP Top 10` `Burp Suite basics` `Wireshark` `Basic log analysis` `CVE awareness`

=== "Mid-level (2–5 yrs)"
    **Focus:** Lead penetration tests, build security tooling, perform threat modeling, run incident response.

    `Web app pentesting` `Cloud security (AWS IAM, GuardDuty)` `SIEM (Splunk / Sentinel)` `Threat modeling (STRIDE)` `SAST / DAST in CI/CD` `Malware analysis basics` `Security code review` `Compliance (SOC2, GDPR)`

=== "Senior (5–10 yrs)"
    **Focus:** Design secure systems, lead red team operations, own security architecture across products.

    `Red team operations` `Architecture security review` `Zero trust implementation` `AI red teaming & LLM security` `Supply chain security` `ISO 27001 / FedRAMP` `Binary exploitation` `Cryptography design`

=== "Staff / Principal (10+ yrs)"
    **Focus:** Define security culture and strategy, advise engineering on security-by-design, shape AI governance.

    `Enterprise security strategy` `AI governance (EU AI Act)` `Bug bounty program management` `Security M&A due diligence` `CISO advisory` `Cross-org security architecture` `Research leadership`

---

## Tools

=== "Pentesting"
    | Tool | Priority |
    |------|----------|
    | Burp Suite | ⭐ Core |
    | Nmap | ⭐ Core |
    | Metasploit | Useful |
    | SQLmap | Useful |
    | Cobalt Strike | Useful |

=== "SIEM / monitoring"
    | Tool | Priority |
    |------|----------|
    | Splunk | ⭐ Core |
    | Microsoft Sentinel | Useful |
    | Elastic SIEM | Useful |
    | Wazuh | Useful |

=== "Cloud security"
    | Tool | Priority |
    |------|----------|
    | AWS GuardDuty | ⭐ Core |
    | AWS Security Hub | Useful |
    | Prisma Cloud | Useful |
    | Prowler | Useful |

=== "Code scanning"
    | Tool | Priority |
    |------|----------|
    | Semgrep | ⭐ Core |
    | Snyk | ⭐ Core |
    | Trivy | ⭐ Core |
    | SonarQube | Useful |
    | OWASP ZAP | Useful |

=== "Identity & secrets"
    | Tool | Priority |
    |------|----------|
    | HashiCorp Vault | ⭐ Core |
    | AWS Secrets Manager | Useful |
    | Okta / Auth0 | Useful |
    | CyberArk | Useful |

=== "AI security"
    | Tool | Priority |
    |------|----------|
    | Custom red teaming | ⭐ Core |
    | Garak (LLM probe) | Useful |
    | PromptBench | Useful |
    | Rebuff | Useful |

---

## Learning path

1. **Networking fundamentals** *(1–2 months · Free)*
   Professor Messer CompTIA Network+ materials (free on YouTube). Deep understanding of TCP/IP, DNS, TLS.

2. **Linux & scripting** *(1–2 months · Free)*
   OverTheWire Bandit wargame + learn Python for automation. Linux is the foundation of everything.

3. **Web app security (OWASP)** *(2–3 months · Free)*
   PortSwigger Web Security Academy (free) — the best hands-on platform for web app security.

4. **CompTIA Security+ or CEH** *(1–2 months · Paid)*
   Entry-level cert widely recognized. Covers core security concepts and often required for compliance.

5. **Cloud security** *(2–3 months · Paid)*
   AWS Security Specialty cert or GCP Security Engineer. Crucial as everything runs in cloud.

6. **Penetration testing (OSCP)** *(3–6 months · Paid)*
   OSCP by Offensive Security — the gold standard pentesting cert. Challenging but highly valued.

7. **AI/LLM security** *(Ongoing · Free)*
   OWASP LLM Top 10 + build a prompt injection test suite. New and rapidly evolving area.

---

## Interview topics

=== "Networking & protocols"
    - TLS handshake explained
    - Common attack vectors (MITM, replay)
    - DNS security (DNSSEC, DoH)
    - Firewall rules & iptables
    - VPN protocols comparison

=== "Web security"
    - XSS vs CSRF vs SSRF
    - SQL injection mechanics
    - JWT security pitfalls
    - CORS misconfigurations
    - Cookie security attributes

=== "Pentesting / red team"
    - PTES methodology
    - Privilege escalation techniques
    - C2 frameworks overview
    - Lateral movement methods
    - Evidence & reporting standards

=== "AI/LLM security"
    - Prompt injection attacks
    - Model extraction threats
    - RAG data poisoning
    - Jailbreak taxonomy
    - Defense-in-depth for LLM apps

---

## Roles & salary

| Title | Experience | Salary (US) |
|-------|-----------|-------------|
| Security Analyst | 0–2 yrs | $65k–$100k |
| Security Engineer / Pentester | 2–5 yrs | $110k–$155k |
| Senior Security Engineer | 5–8 yrs | $155k–$220k |
| Staff / Principal Security | 8+ yrs | $220k–$340k+ |

---

## Related pages

- [Roadmap — Security](../roadmaps/security.md)
- [AI Era — Security](../ai-era/security.md)
