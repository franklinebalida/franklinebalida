# Phase 2: Security Core (6–8 weeks)

This phase gives you the vocabulary and mental models of the field, and lines up
with **CompTIA Security+**, the most requested entry-level certification in job
postings (and a baseline for US DoD 8140 roles). Check CompTIA's site for the
current exam code before you buy study material.

## Concepts to master

**Principles**
- CIA triad: Confidentiality, Integrity, Availability
- AAA: Authentication, Authorization, Accounting
- Least privilege, defense in depth, zero trust, separation of duties

**Cryptography**
- Encoding (base64, hex) is **not** encryption: anyone can reverse it
- Symmetric (AES) vs. asymmetric (RSA, ECC); when each is used
- Hashing (SHA-256) vs. encryption; why passwords need *slow, salted* hashes (bcrypt, scrypt, Argon2, PBKDF2)
- PKI, certificates, how TLS works at a high level

**Identity and access**
- MFA factors (know / have / are), SSO, SAML vs. OAuth 2.0 vs. OIDC
- RBAC vs. ABAC, privileged access management

**Threats and attacks**
- Malware types: ransomware, trojans, worms, RATs, rootkits
- Social engineering: phishing, pretexting, BEC
- Network attacks: MitM, DoS/DDoS, ARP/DNS spoofing
- App attacks: injection, XSS, CSRF, buffer overflow (you'll go deeper in Phase 4)
- Threat actors and motivations, **MITRE ATT&CK** (attack.mitre.org): browse the matrix

**Risk and governance**
- Risk = likelihood × impact; accept / mitigate / transfer / avoid
- Frameworks: NIST CSF, ISO 27001, CIS Controls
- Regulations at a glance: GDPR, HIPAA, PCI DSS

## Study plan

| Week | Focus |
|---|---|
| 1–2 | Professor Messer's free Security+ videos, first half; take notes by domain |
| 3–4 | Second half, and do Labs 02 and 04 |
| 5 | Practice exams (e.g. Jason Dion on Udemy); log every miss and why |
| 6 | Review weak domains; book the exam when you're scoring 85%+ consistently |

## Checkpoint

- [ ] Explain the difference between hashing, encryption and encoding to a non-technical friend
- [ ] Explain why a stolen database of MD5 password hashes is a disaster but a bcrypt one is survivable
- [ ] Map a real breach (read any public incident report) to 3+ MITRE ATT&CK techniques
- [ ] Pass Security+
