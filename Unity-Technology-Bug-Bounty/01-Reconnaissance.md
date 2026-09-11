# Reconnaissance

The first step was to gather information about Unity's public-facing assets.

## Subdomain Enumeration

I used **Subfinder** to find subdomains associated with **unity.com**.

- 1,623 subdomains were discovered.
- The results were filtered using keywords related to higher-risk areas.
- 371 subdomains were selected for further testing.
- The main areas of interest were APIs, admin panels, staging environments, and authentication endpoints.

## Tool Used 

**Subfinder** - Used to discover subdomains associated with the target domain.

## Command

subfinder -d unity.com -o unity_subs.txt

The filtered subdomains were then used for the next stage of endpoint enumeration and testing.
