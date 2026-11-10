# FishGuard

FishGuard — Dive Into Safer Browsing

FishGuard is an ocean-themed website interface for a proposed intelligent platform that helps users identify potentially phishing and malicious websites. The project brings together four security concepts: threat analysis, web security assessment, certificate validation, and collaborative threat intelligence.

Project status: Frontend demo. The current scanner performs basic URL-format checks in the browser. It does not determine whether a website is safe or malicious.

 Features
Ocean-inspired interface: Dark underwater colours, fish and bubble animations, and responsive layouts.

URL scanner demo: Accepts a URL and checks its basic format.

HTTPS indicator: Displays whether the submitted URL uses HTTPS or HTTP.

Threat analysis concept: A section describing how suspicious URL patterns and threat indicators could be assessed.

Web security assessment concept: A section describing potential website security checks.

Certificate validation concept: A section describing HTTPS/TLS certificate checks.

Collaborative threat intelligence concept: A section describing how community reports could help identify emerging threats.
Responsive design: Adapts to desktop, tablet, and mobile screens.

Technologies Used
HTML5 — page structure and content
CSS3 — layout, colours, animations, and responsive design
JavaScript — URL input handling and the frontend scanner demonstration



🔍 How to Try the Scanner
Open the URL Safety Scanner section.
Enter a URL, for example https://example.com.
Select Scan website.
The demo displays the submitted domain and whether the URL uses HTTP or HTTPS.

Planned Full-System Architecture
The following capabilities are proposed for a future backend implementation:
Component
Planned responsibility
URL threat analysis
Inspect URL and domain indicators for suspicious patterns
Web security assessment
Evaluate selected website security signals
Certificate validation
Validate TLS certificate details and trust information on the server
Threat intelligence
Query trusted threat feeds and reputation services
Community reports
Collect, review, and share user-submitted threat indicators
Risk reporting
Combine available evidence into an understandable result


⚠️ Limitations and Safety Notes
The current demo does not contact or crawl the submitted website.
It does not inspect redirects, page content, DNS records, or server configuration.
It does not perform real TLS certificate-chain validation.
It does not connect to threat-intelligence databases or community reports.
It must not be used to make real-world security decisions.
Do not enter passwords, private tokens, or other sensitive information into untrusted websites.
A production scanner should validate URLs on the backend, protect against server-side request forgery (SSRF), restrict private and internal network destinations, apply timeouts and response-size limits, and avoid exposing submitted URLs or sensitive data in logs.

👥 Project Information
Project name: FishGuard
Project type: Cybersecurity awareness / phishing-detection website demo
Current deliverable: Frontend prototype

📄 License
No license has been specified yet. 

FishGuard — Dive Deep. Stay Safe. Browse Safely 🐠