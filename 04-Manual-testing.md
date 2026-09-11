# Manual Testing

After reconnaissance, scanning and endpoint enumeration, I moved on to initial manual testing of the identified web applications.

## Access Control and HTTPS Behaviour

I used **Burp Suite Community Edition**, including its embedded Chromium browser and Repeater, to inspect and analyse HTTP requests and responses.

The testing focused on:

* Access control behaviour
* HTTP and HTTPS handling
* Request and response analysis
* Security headers
* Application behaviour

One observation was that the tested application enforced **HTTPS through 301 redirects**.

I also observed that requests to protected areas without authentication returned **403 Forbidden**, showing that server-side access controls were being applied.

The testing helped me understand how the application handled normal user requests and how security controls affected unauthorised traffic.

## Tool Used

**Burp Suite Community Edition** — Used to inspect HTTP traffic and manually analyse application behaviour.
