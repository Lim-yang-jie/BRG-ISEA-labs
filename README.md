

# BRG-ISEA-labs
Module repository
## Session 1a 

- Practised commands: pwd, ls, ls -l, ls -a, cd, mkdir, touch
- Practised system directories: /etc, /var, /home
- Used man to view manual
- Added screenshots for each lab step

## Session 1b

- linux services
- linux permissions
- searching Filesystem 

## Session 2a – Total Cost of Ownership (TCO)

- Created a TCO spreadsheet comparing Prem, Cloud A and Cloud B.
- Calculated monthly and yearly costs for each option.
- Used formulas to find total cost for On-Prem, Cloud A and Cloud B.
- Calculated break-even point
- Calculated ROI for Cloud A 
- Attached spreadsheet and screenshots

## Session 2b – Cloud VM & Bash Scripting

- Launched Ubuntu EC2 instance and connected via SSH.
- Updated server packages using apt.
- Created ~/scripts directory and wrote bash scripts:
  - hello.sh – echo example
  - check_user.sh – if statement
  - loop.sh – for loop
- Made scripts executable with chmod +x.
- Created a cron job that logs a timestamp.
- Added screenshots of commands and outputs.

## Session 3a – DNS

- Installed DNS tools using dnsutils package.
- Queried DNS records with dig:
  - A, AAAA, MX, and NS records.
- Compared DNS results using different resolvers:
  - Cloudflare (1.1.1.1)
  - Google DNS (8.8.8.8)
- Observed DNS caching by comparing first vs repeated query times.
- Performed reverse lookup with dig -x.
- Used nslookup to verify DNS configuration.
- Added all screenshots from commands.

## Session 3b – Certificates (TLS/SSL)

- Installed OpenSSL tools on the Ubuntu EC2 instance.
- Fetched live certificates from websites:
- Identified key certificate fields:
  - Issuer, Subject, Expiry dates, SAN (Subject Alternative Names)
- Viewed full certificate chains (server → intermediate → root).
- Extracted certificate expiry and subject fields using OpenSSL.
- Added screenshots of certificate details and chain output.

## Session 4a – Web Server (Nginx)

- Installed Nginx on my Ubuntu EC2 instance.
- Started and enabled the nginx service using systemctl.
- Located the web root at /var/www/html.
- Created a custom page.
- Viewed the webpage using the browser to IP.
- Added screenshots of installation, service status, index.html editing, and webpage output.


## Session 5a – Server Automation
- Created automation scripts folder.
- Wrote two automation scripts:
 - update.sh – runs apt update/upgrade and logs output.
 - backup.sh – copies /var/www/html to ~/backup and logs output.
- Made scripts executable.
- Tested scripts manually and verified logging in `/var/log/task.log`.
- Added scheduled cron jobs to run scripts every 6 hours.
- Added screenshots of scripts, cron entry, and task.log output.


## Video Demonstration Requirements

- Recorded a full narrated demonstration showing:
  - Linux VM
  - Cloud VM and SSH access
  - DNS and HTTPS validation
  - Bash scripts and cron jobs
  - Additional server service setup
- Provided webcam view and verbal explanation of decisions.