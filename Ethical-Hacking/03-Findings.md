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

