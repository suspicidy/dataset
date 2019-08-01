# Suspicidy Dataset

Right now, this dataset only contains logs from different honeypot instances. 
The hostname (e.g. IP or domain) got replaced by a hash, except for `""` (empty hostname) and `localhost`. 
For domains, the subdomain and TLD got preserved and only the main domain name is hashed.

The honeypots 1-3 run on different servers, on port 80, 4000, 5000 and 7000 and have no domain name assigned to them.
Any domain name that is found in the logs is configured from the caller side.
