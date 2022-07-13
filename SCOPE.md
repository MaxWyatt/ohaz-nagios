# Scope

This document should define the scope of work around the OHAZ Monitoring system.


## Phase 1 Features

- server deployment
- basic server configuration, including standard IS security posture and managed firewall rules
- OMD installation and base configuration (includes nagios components and some other goodies)
- nsca-ng-server for passive checks (built-in nsca server is bad)
- postfix server configured to relay against smtp.uoregon.edu
- valid SSL certificates (1yr) and CNAME if wanted
    - apache configured for https redirect
- central authentication (2fa) using shibboleth
- templates for host, service, and contact
    - configured with acceptable notification times
- checks configured statically, deployed using ansible



## Potential features for future work

- netdot attributes for SNMP OIDs, ansible uses this as datasource
- ansible inventory build-out for maintaining devices
- <insert more here>


