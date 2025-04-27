# DrSudo

DrSudo is an automation pentesting tool to perform scanning, enumeration, and exploitation.


# Documentation
**Tested version:** ```3.8.18```

This script is currently capable of the following:

1. Nmap scanning  
2. CVE lookup based on scan results

**Usage:**

```python sudo.py <target> e.g. python sudo.py google.com``` basic usage, does everything.

```python sudo.py <target> -inf``` this flag will enable infinite web crawling & scraping, it will take the target domain and search for any links within the source code, it will crawl through those links and repeat the process for every link found. 
# Future updates:

- [ ] AI implementation
- [ ] Web crawling - in progress
- [ ] Brute forcing
- [ ] CVE exploitation
- [ ] auto CVE PoC crafting (related to the CVE exploitation feature).
- [ ] post-exploitation data dumping.
- [ ] Google Dorks lookup of vulnerable websites.
- [ ] Shodan lookup of vulnerable websites.
- [ ] server-side exploitation (the inital attack focus of the tool).
- [ ] client-side exploitation (the soon-to-be update of the additional attack focus e.g. XSS, SQLI, etc).
- [ ] file upload form detection, auto shell upload.
- [ ] client-side static code analysis.
- [ ] publicly accesible web interface of Drsudo.

---
