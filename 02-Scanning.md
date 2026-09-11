# Scanning

After reconnaissance, I performed technology identification on selected web applications to better understand the technologies and infrastructure involved.

## Technology Stack Identification

I used **WhatWeb** to identify technologies and security controls used by the web applications.

The assessment identified technologies including:

* React.js
* Next.js
* Express.js / Node.js
* Nginx
* Cloudflare
* HSTS
* X-Frame-Options
* X-Content-Type-Options

The results helped the team understand the application's structure and identify areas that could be prioritised for further testing.

## Tech Stack Diagram

I created a high-level technology stack diagram based on the WhatWeb results.

The architecture was represented as:

**Frontend → Web Server / Reverse Proxy → Backend / APIs**

The diagram helped visualise the communication between the frontend, web infrastructure and backend services.

> Target-specific infrastructure details have been removed from this public portfolio version.
