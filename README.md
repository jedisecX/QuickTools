# QuickTools

Release Notes — JediSecX QuickTools v1.0

> Release Date: April 27, 2025

Perfect —
here's a polished RELEASE-NOTES.md for your GitHub QuickTools v1.0 launch:


---

Release Notes — JediSecX QuickTools v1.0

> Release Date: April 27, 2025




---

What's Included

A lightweight, high-speed cybersecurity and OSINT tool suite developed by Jedi Security.

Tools in this Release:

Mass Subdomain Enumerator
Bruteforce and discover subdomains of any target domain.

URL Unshortener and Redirect Mapper
Trace all URL redirects to their final destination.

Bulk File Metadata Extractor
Pull metadata (EXIF, PDF, DOCX) from a folder of files.

Hash Cracker (Dictionary Attack)
Crack MD5, SHA1, and SHA256 hashes using a wordlist.

Multi-AV + VirusTotal Scanner
Scan files using ClamAV or Windows Defender, and cross-verify with VirusTotal API.



---

New Features

Local & Cloud Scanning with automatic fallback to VirusTotal.

Cross-Platform Ready: Linux & Windows supported.

Self-Contained: No database, no web dependencies, full CLI operation.

MIT Licensed: Free for personal, academic, or commercial use.



---

How to Install

1. Clone or Download the repository.


2. Install dependencies:

pip install requests exifread pypdf2 python-docx


3. Setup ClamAV (Linux) if needed.


4. Insert your free VirusTotal API Key into multi_av_virustotal_scanner.py.




---

Quick Start Example

python3 mass_subdomain_enum.py jedisec.com
python3 url_unshorten_mapper.py urls.txt
python3 bulk_metadata_extractor.py ./downloads/
python3 hash_cracker.py d41d8cd98f00b204e9800998ecf8427e rockyou.txt md5
python3 multi_av_virustotal_scanner.py suspicious_file.exe


---

Known Limitations

VirusTotal uploads may delay by 15-30 seconds for full scan results.

Free VirusTotal API keys have rate limits (4 scans/minute).



---

Credits

Developed by Jedi Security
Domains: jedisec.com | jedisec.us | jedisec.cloud | jedisec.online | jedisec.me


---

Attachments

JediSecX-QuickTools.zip


---

What's Included

A lightweight, high-speed cybersecurity and OSINT tool suite developed by Jedi Security.

Tools in this Release:

Mass Subdomain Enumerator
Bruteforce and discover subdomains of any target domain.

URL Unshortener and Redirect Mapper
Trace all URL redirects to their final destination.

Bulk File Metadata Extractor
Pull metadata (EXIF, PDF, DOCX) from a folder of files.

Hash Cracker (Dictionary Attack)
Crack MD5, SHA1, and SHA256 hashes using a wordlist.

Multi-AV + VirusTotal Scanner
Scan files using ClamAV or Windows Defender, and cross-verify with VirusTotal API.



---

New Features

Local & Cloud Scanning with automatic fallback to VirusTotal.

Cross-Platform Ready: Linux & Windows supported.

Self-Contained: No database, no web dependencies, full CLI operation.

MIT Licensed: Free for personal, academic, or commercial use.



---

How to Install

1. Clone or Download the repository.


2. Install dependencies:

pip install requests exifread pypdf2 python-docx


3. Setup ClamAV (Linux) if needed.


4. Insert your free VirusTotal API Key into multi_av_virustotal_scanner.py.




---

Quick Start Example

python3 mass_subdomain_enum.py jedisec.com
python3 url_unshorten_mapper.py urls.txt
python3 bulk_metadata_extractor.py ./downloads/
python3 hash_cracker.py d41d8cd98f00b204e9800998ecf8427e rockyou.txt md5
python3 multi_av_virustotal_scanner.py suspicious_file.exe


---

Known Limitations

VirusTotal uploads may delay by 15-30 seconds for full scan results.

Free VirusTotal API keys have rate limits (4 scans/minute).



---

Credits

Developed by Jedi Security
