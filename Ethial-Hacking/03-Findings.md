# Findings

The vulnerability assessment identified security weaknesses across multiple systems and services.

## Key Findings

### Unsupported Windows OS

An unsupported Windows operating system was identified.

**Severity:** Critical

**Recommendation:** Upgrade to a supported operating system and maintain regular security updates.

### Apache Vulnerabilities

An outdated Apache HTTP Server version was identified with multiple known vulnerabilities.

**Severity:** Critical

**Recommendation:** Upgrade Apache to a supported version and maintain regular patching.

### OpenSSH Vulnerabilities

An outdated OpenSSH version was identified with multiple known vulnerabilities.

**Severity:** Critical

**Recommendation:** Upgrade OpenSSH to a supported version.

### SSL/TLS Weaknesses

The assessment identified several SSL/TLS security weaknesses involving outdated protocols, certificates and cryptographic configurations.

**Severity:** Critical to Low depending on the finding.

**Recommendation:** Disable obsolete protocols and weak cryptographic configurations and use modern supported TLS settings.

### Other Findings

Additional findings included:

- SMB signing not required
- HTTP TRACE/TRACK methods enabled
- Weak SSH MAC algorithms
- SSH CBC mode ciphers enabled
- Weak Diffie-Hellman parameters
- Weak export cipher suites

The findings were reviewed and prioritised according to their severity.

> Specific lab IP addresses and detailed exploitation information have been excluded from this public portfolio.
methodology.md
# Methodology

## 1. Vulnerability Scanning

I used **Nessus Advanced Scan** to scan the systems within the defined lab scope.

## 2. Result Analysis

After completing the scan, I reviewed the identified vulnerabilities and grouped them according to their severity.

## 3. Vulnerability Analysis

I analysed the findings to understand:

- What the vulnerability was
- Which service or system was affected
- The potential security impact
- How the issue could be remediated

## 4. Risk Prioritisation

I used **CVSS severity levels** to help prioritise the findings.

## 5. Remediation

For the identified vulnerabilities, I provided recommendations such as:

- Updating outdated software
- Replacing unsupported systems
- Disabling insecure protocols
- Improving security configurations
- Removing weak cryptographic settings

## Tools Used

- Nessus
- CVSS
- NIST National Vulnerability Database (NVD)
