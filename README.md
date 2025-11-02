# 🛡️ SilentPS Blocklists
Welcome to the official blocklist repository maintained by SilentPS, LLC. This repo contains curated lists of domains used for unsolicited emails, phishing, scams, and other malicious or unwanted activity. These lists are designed for use in email servers, DNS blockers (like Pi-hole), and other security tools.

# 📦 Available Blocklists
+ UEDB (Unsolicited Emailers by Domain) - Intended for email server domain blocking
+ Phishing & Scam Domains (coming soon) - Intended for Pi-hole DNS filtering
+ Malvertising & Tracking Domains (planned) - Intended for Pi-hole DNS filtering

# 📄 License
All blocklists are released under the MIT License unless otherwise noted. You are free to use, modify, and redistribute them with attribution.

# ⚙️ Usage
 - Email Servers: Import .txt lists into your MTA (Postfix, Exim, etc.) to block domains at the SMTP level.
 - Pi-hole / DNS Filtering: Use .hosts or domain-only lists to block malicious domains at the DNS level.

 - # 🤝 Contributing
We welcome contributions! To suggest additions or request removals:
 - Open a Pull Request with supporting evidence (headers, logs, abuse reports).
 - Or file an Issue with details.
 - Allow up to 14 days for review and processing.

# 📬 Contact
For questions, false positives, or partnership inquiries, please open an issue or contact us via the repo.
