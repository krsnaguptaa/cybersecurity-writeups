# DNS
DNS = converts domain names to IP addresses

HIERARCHY:
TLD = top level domain (.com .in .org)
Second level = main domain name
Subdomain = prefix before main domain

RECORDS:
A = domain → IPv4
AAAA = domain → IPv6
CNAME = domain → another domain
MX = where to deliver emails for domain
TXT = domain verification, spam prevention

DNS REQUEST FLOW:
Local cache → Recursive DNS (ISP provided)
→ Root server (points to TLD server)
→ TLD server (points to Authoritative server)
→ Authoritative server (gives actual IP)
→ Recursive caches result → browser opens site ✅

Recursive DNS caches results = faster future visits
