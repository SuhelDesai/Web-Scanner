Web App Security Scanner

Web Scanner is an audit-grade, offline-ready vulnerability assessment tool written in pure Java 8. It performs deep analysis of web applications without requiring login, internet access, or external proxy setup. Perfect for pre-prod hardening, CI pipelines, and secure snapshots—even inside air-gapped environments.

⚙️ Features
No installation required — drop-in .jar ready for CLI or embedded usage
📡 Referrer Policy Audit — Flags potential info leaks from unsafe header configurations

🛡️ Security Header Check — Detects missing CSP, HSTS, X-Frame-Options, and more

🍪 Cookie Flag Scanner — Lists all cookies and flags missing HttpOnly, Secure, or SameSite

❗ Server Name Disclosure Detection — Identifies known server fingerprints from headers

🌍 CORS Risk Assessment — Highlights overly permissive Access-Control-Allow-Origin

🔎 Offline DNS Resolution — Resolves target hostname to IP without relying on external APIs

📄 HTML Report Generation — Exports findings as a color-coded, styled HTML report with embedded tables

🎯 Use Case
Run scans in isolated QA environments, secure VMs, or CI/CD containers. No external libraries, agents, or setup required. Outputs a polished audit report that's both human-readable and presentation-friendly.

Note: Target should be accessible over HTTP/HTTPS
