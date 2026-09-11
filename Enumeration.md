# Enumeration

After collecting the subdomains, I moved on to finding accessible endpoints and directories.

# FFUF

I used FFUF to fuzz the discovered subdomains and look for accessible paths and endpoints.

- Tested the discovered subdomains for available endpoints.
- Filtered the results to remove irrelevant responses.
- Prioritised interesting endpoints for further testing.

# What I Found

The enumeration stage helped identify potential areas such as:

- API endpoints
- Authentication pages
- Admin-related paths
- Staging environments
- Other interesting web directories

The results were then used for the manual web testing stage.
