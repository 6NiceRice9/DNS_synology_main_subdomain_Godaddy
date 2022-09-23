# This script renew your Wildcard SSL certificates for main AND subdomains based on GoDaddy DNS provider.
coarse procedure:
- login via SSH to your Synology DS
- modify in each step declared changes & copy/paste separtly commands into DSM-SSH terminal
- Step 2,3,4,5 have to be done only once
  - because synology gives each domain family specific folder name, it will be generated once we import our domain certificate
