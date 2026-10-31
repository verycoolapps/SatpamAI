# 🔐 SECURITY POLICY — SatpamAI

## Supported Versions

| Version | Support Status |
|---------|---------------|
| 1.0.x   | ✅ Active security support |

## Reporting a Security Vulnerability

If you discover a security vulnerability in SatpamAI itself — including:
- A bypass technique that evades the security gate
- A prompt injection pattern that defeats the defense engine
- A logic flaw in the risk classification framework
- An audit manipulation vector not yet covered

**Please report it responsibly:**

1. **Do NOT open a public GitHub issue** for security vulnerabilities
2. Open a **GitHub Security Advisory** via the Security tab of this repo
3. Include: description, reproduction steps, potential impact, suggested fix

We will acknowledge within 48 hours and work toward a fix within 14 days for critical issues.

## Security Design Principles

SatpamAI is designed and audited against these principles:

```
1. Zero Trust          — no artifact trusted without verifiable evidence
2. Least Privilege     — minimum access required for declared function only
3. Defense in Depth    — layered controls, no single point of failure
4. Secure by Default   — everything is restricted unless explicitly authorized
5. Fail Closed         — uncertainty results in blocking, not allowing
6. Audit Everything    — every security decision is logged and explainable
7. No Security Theater — every claim backed by mechanism or explicit limitation
8. Verify Explicitly   — evidence demanded, claims alone insufficient
```

## What SatpamAI Does NOT Claim

SatpamAI is built on radical honesty about its limitations:

- ❌ Does NOT claim 100% detection of all malware
- ❌ Does NOT claim all prompt injections are always detected
- ❌ Does NOT claim to replace dedicated security tooling (SAST, DAST, SIEM)
- ❌ Does NOT claim enforcement guarantees beyond what the platform provides
- ❌ Does NOT guarantee dynamic behavior analysis without a proper sandbox

Any version of SatpamAI making these claims has been compromised or incorrectly modified.

## Known Limitations

See [docs/LIMITATIONS.md](docs/LIMITATIONS.md) for the complete, honest list of what
SatpamAI cannot detect, cannot block, and cannot guarantee.
