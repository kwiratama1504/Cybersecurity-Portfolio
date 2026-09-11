# Enumeration & Crawling

The next stage focused on discovering accessible directories and endpoints across the filtered subdomains.

## Endpoint Discovery

I used **FFUF (Fuzz Faster U Fool)** to perform endpoint discovery.

Since there were **371 filtered subdomains**, I created a **Bash loop** to automate the process across the targets instead of running each scan manually.

The results were saved and reviewed to identify potentially interesting endpoints and application functionality.

The identified areas included:

* Administrative pages
* Internal tools
* API endpoints
* Login pages
* Application functionality

The interesting results were then manually reviewed and passed to the relevant team members for further security testing.

## Automation

Using Bash automation made it possible to apply the same endpoint discovery process across multiple subdomains and organise the results for later analysis.

## Tools Used

* **FFUF** — Endpoint and directory discovery
* **Bash** — Scan automation
