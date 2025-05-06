🌐 Web Technology Course Notes
📚 Course Overview
This course introduces Web Technology, exploring the Internet, World Wide Web (WWW), and related systems. It covers web browsers, web servers, URLs, protocols, domain names, and web hosting, providing a foundation for web development. Tailored for bachelor-level students, these notes include clear definitions, practical examples, and additional topics to ensure a deep understanding.

📖 Module 1: Introduction to Internet, WWW, Web Browser, Web Servers, and URL

1.1 Internet 🌍

Definition: The Internet is a global network of interconnected computers and devices that communicate using standardized protocols like TCP/IP.

Explanation:

Uses packet-switching to send data in small chunks, reassembled at the destination.
Supports services like WWW, email, and streaming.
Managed by organizations like ICANN for IP addresses and domains.


Key Features ✅:

Scalable to billions of devices.
Decentralized for resilience.
Interoperable via universal protocols.


Example 📌:

Video chatting on WhatsApp sends audio/video packets over the Internet to WhatsApp’s servers, which relay them to your friend.


Real-World Application:

E-commerce (e.g., Flipkart), cloud storage (e.g., Dropbox), and remote work (e.g., Microsoft Teams) rely on the Internet.


Additional Content:

Internet Backbone: High-speed fiber-optic cables connecting global hubs.
ISPs: Companies like AT&T or Airtel provide Internet access.






1.2 World Wide Web (WWW) 🕸️

Definition: The WWW is an Internet service for accessing and sharing hypertext documents (web pages) via browsers, using HTTP/HTTPS.

Explanation:

Web pages use HTML (structure), CSS (styling), and JavaScript (interactivity).
Hypertext links pages (e.g., clicking a link navigates to another page).
Operates on a client-server model.


Key Features ✅:

Globally accessible.
Supports dynamic content (e.g., forms).
Cross-platform (desktops, mobiles).


Example 📌:

Visiting www.bbc.com loads a news page with articles and links to related stories.


Real-World Application:

Online learning platforms like Khan Academy deliver interactive content via the WWW.


Additional Content:

Web 2.0: User-generated content (e.g., YouTube, Twitter).
Web 3.0: Semantic web for machine-readable data (e.g., AI-driven searches).






1.3 Web Browser 🖥️

Definition: A web browser is software that retrieves, interprets, and displays web content (HTML, CSS, JavaScript) from servers.

Explanation:

Sends HTTP/HTTPS requests and renders responses.
Executes JavaScript for interactivity (e.g., buttons, animations).
Manages cookies (user data), cache (faster loading), and bookmarks.


Popular Browsers: Chrome, Firefox, Safari, Edge.

Key Features ✅:

Rendering engine (e.g., Blink in Chrome).
Security (e.g., anti-phishing).
Extensions (e.g., Grammarly).


Example 📌:

Typing www.netflix.com in Safari fetches HTML/CSS/JavaScript, displaying a streaming interface.


Real-World Application:

Browsers enable online shopping, banking, and education.


Additional Content:

Developer Tools: Chrome DevTools for inspecting HTML and debugging.
PWAs: Websites functioning like apps (e.g., Twitter mobile).






1.4 Web Servers 🖧

Definition: A web server is a computer or software that stores and delivers web content to browsers using HTTP/HTTPS.

Explanation:

Hosts files (HTML, images) and responds to requests.
Supports static (pre-built) and dynamic (script-generated) content.
Handles multiple requests for scalability.


Popular Servers: Apache, Nginx, IIS.

Key Features ✅:

Load balancing for high traffic.
Security via SSL/TLS.
Logging for analytics.


Example 📌:

Visiting www.example.com triggers an Apache server to send index.html.


Real-World Application:

Amazon’s servers handle millions of requests for product pages.


Additional Content:

Server-Side Scripting: PHP, Python (Flask), Node.js for dynamic pages.
CMS: WordPress runs on servers for easy site management.






1.5 URL (Uniform Resource Locator) 🔗

Definition: A URL is a standardized address specifying a resource’s location and access method.

Explanation:

Parsed by browsers to locate servers and resources.
Includes protocol, domain, path, and optional parameters.


Structure:

Protocol: http:// or https://.
Domain: www.example.com.
Port (optional): :8080.
Path: /blog/post1.
Query (optional): ?id=123.
Fragment (optional): #section1.
Example: https://www.example.com/blog/post1?id=123#details


Key Features ✅:

Universal format.
Supports dynamic data via queries.


Example 📌:

https://www.google.com/search?q=web+technology searches for “web technology.”


Real-World Application:

Short URLs (e.g., bit.ly) simplify marketing links.


Additional Content:

URL Encoding: Spaces become %20.
RESTful URLs: Structured for APIs (e.g., api.example.com/users/123).






📖 Module 2: Overview of Different Protocols

2.1 HTTP (Hypertext Transfer Protocol) 📤

Definition: HTTP is a protocol for transferring web pages between clients and servers.

Explanation:

Stateless: Each request is independent.
Uses methods: GET (retrieve), POST (send), PUT (update), DELETE.
Includes headers (e.g., content-type).


Key Features ✅:

Operates on port 80.
Supports caching.
Handles multiple media types.


Example 📌:

Clicking a link on http://example.com/news sends a GET request for the news page.


Real-World Application:

HTTP delivers most website content.


Additional Content:

Status Codes: 200 (OK), 404 (Not Found), 500 (Error).
HTTP/2: Faster with multiplexing.






2.2 HTTPS (Hypertext Transfer Protocol Secure) 🔒

Definition: HTTPS is HTTP with SSL/TLS encryption for secure data transfer.

Explanation:

Encrypts data (e.g., passwords) to prevent eavesdropping.
Uses certificates from CAs (e.g., Let’s Encrypt).
Standard for modern websites.


Key Features ✅:

Operates on port 443.
Boosts SEO and trust (padlock icon).
Prevents man-in-the-middle attacks.


Example 📌:

Logging into https://www.paypal.com encrypts your credentials.


Real-World Application:

Mandatory for banking and e-commerce.


Additional Content:

SSL Handshake: Establishes secure connections.
HSTS: Forces HTTPS usage.






2.3 POP (Post Office Protocol) 📥

Definition: POP retrieves emails from a mail server to a client device.

Explanation:

POP3 is the standard version.
Downloads emails, optionally deleting them from the server.
Best for single-device access.


Key Features ✅:

Operates on port 110 (995 for secure POP3).
Lightweight protocol.
Limited multi-device sync.


Example 📌:

Outlook downloads emails from mail.example.com via POP3.


Real-World Application:

Used in small offices for offline email.


Additional Content:

IMAP: Syncs emails across devices, unlike POP.
Security Risks: Non-encrypted POP3 is vulnerable.






2.4 SMTP (Simple Mail Transfer Protocol) 📧

Definition: SMTP sends emails from clients to servers or between servers.

Explanation:

Handles outgoing emails, paired with POP/IMAP for receiving.
Requires authentication to prevent spam.
Supports attachments.


Key Features ✅:

Operates on port 25 (587 for secure SMTP).
Reliable delivery.
Integrates with mail servers.


Example 📌:

Sending an email via Gmail uses SMTP to reach smtp.gmail.com.


Real-World Application:

Powers automated emails (e.g., order confirmations).


Additional Content:

SPF/DKIM: Prevent email spoofing.
Email Relays: Servers like Postfix forward emails.






2.5 FTP (File Transfer Protocol) 📂

Definition: FTP transfers files between clients and servers.

Explanation:

Supports uploading/downloading files.
Uses control (commands) and data (files) channels.
FTPS adds SSL/TLS security.


Key Features ✅:

Operates on ports 21 (control), 20 (data).
Supports anonymous access.
Ideal for website management.


Example 📌:

FileZilla uploads index.html to a server for www.mywebsite.com.


Real-World Application:

Used for software downloads and site updates.


Additional Content:

SFTP: Secure alternative using SSH.
FTP Clients: FileZilla, WinSCP.






2.6 WAP (Wireless Application Protocol) 📱

Definition: WAP delivers simplified web content to mobile devices with limited capabilities.

Explanation:

Uses WML (Wireless Markup Language).
Designed for slow networks and small screens.
Obsolete due to HTML5 and smartphones.


Key Features ✅:

Lightweight protocol.
Supports text and basic images.
Uses WAP gateways.


Example 📌:

A 2000s Nokia phone accessed a text-only news page via wap.bbc.com.


Real-World Application:

Enabled early mobile banking.


Additional Content:

WAP 2.0: Supported basic HTML.
Modern Mobile Web: HTML5, CSS3 for rich apps.






📖 Module 3: Domain Name and Hierarchy, Domain Name Registration Process, Web Hosting

3.1 Domain Name and Hierarchy 🏷️

Definition: A domain name is a human-readable address (e.g., www.example.com) mapped to an IP address via DNS.

Explanation:

DNS translates domains to IP addresses (e.g., 192.0.2.1).
Hierarchical structure ensures uniqueness.


Hierarchy:

Root: Top level (.).
TLDs: .com, .org, .in.
Second-Level: example in example.com.
Subdomains: shop in shop.example.com.


Key Features ✅:

User-friendly addressing.
Scalable via DNS.


Example 📌:

mail.google.com: TLD (.com), Second-Level (google), Subdomain (mail).


Real-World Application:

Branded domains (e.g., nike.com) build trust.


Additional Content:

DNS Resolution: Queries DNS servers for IP addresses.
WHOIS: Checks domain ownership.






3.2 Domain Name Registration Process 📝

Definition: Domain name registration reserves a unique domain for a period (e.g., 1 year).

Explanation:

Managed by ICANN-accredited registrars.
Involves selecting a name, paying fees, and linking to hosting.


Steps:

Choose Name: Check availability (e.g., myblog.com).
Select Registrar: Namecheap, GoDaddy.
Enter Details: Name, email, address.
Pay Fees: $10–$50/year.
Configure DNS: Link to nameservers (e.g., ns1.hostinger.com).
Renew: Pay annually.


Key Features ✅:

Ensures unique ownership.
Supports custom branding.


Example 📌:

Register myportfolio.com on Namecheap for $12/year, link to Hostinger.


Real-World Application:

Businesses register domains for websites (e.g., joescafe.com).


Additional Content:

Domain Privacy: Hides registrant details.
Domain Transfer: Moves domains between registrars.






3.3 Web Hosting 🖴

Definition: Web hosting stores website files on servers for Internet access.

Explanation:

Providers offer space, bandwidth, and tools (e.g., email, databases).
Types vary by scale and needs.


Types:

Shared: Multiple sites on one server (e.g., Bluehost).
VPS: Dedicated resources (e.g., DigitalOcean).
Dedicated: One server per site (e.g., for BBC).
Cloud: Scalable across servers (e.g., AWS).


Key Features ✅:

Storage for files.
Bandwidth for traffic.
Security (SSL, backups).


Example 📌:

Host myportfolio.com on Hostinger, upload files via FTP.


Real-World Application:

Universities host sites (e.g., www.mit.edu) on dedicated servers.


Additional Content:

CDN: Cloudflare for faster delivery.
Uptime: 99.9% guarantees.






🛠️ Practical Example: Building a Website
Create a portfolio website:

Register Domain: Buy myportfolio.com (Namecheap, $12/year).
Choose Hosting: Hostinger shared plan ($3/month).
Upload Files: Use FileZilla to upload index.html, style.css.
Configure DNS: Point to Hostinger’s nameservers.
Enable HTTPS: Use Hostinger’s free SSL.
Set Up Email: Create contact@myportfolio.com (SMTP/POP3).
Access: Visit https://myportfolio.com to view the site.


🎯 Learning Outcomes
Students will:

Define Internet, WWW, browsers, servers, URLs, and protocols.
Explain HTTP, HTTPS, POP, SMTP, FTP, WAP functionalities.
Register domains and host websites.
Build a basic website.
Explore advanced topics (e.g., APIs, SEO).


📝 Assessment

Assignments:
Compare HTTP vs. HTTPS (500 words).
Document domain registration steps.


Practical:
Host an HTML page on GitHub Pages.
Analyze HTTP requests with Chrome DevTools.


Quiz:
Define protocols, DNS, hosting types.
Explain URL structure.




📚 Resources

Books:
Web Technology by Gopalan & Akilandeswari.
HTTP: The Definitive Guide by Gourley.


Online:
MDN Web Docs (developer.mozilla.org).
W3Schools (www.w3schools.com).
Namecheap/Hostinger blogs.


Tools:
FileZilla (FTP).
Chrome DevTools.
Pingdom (performance).




➕ Additional Topics

APIs: Fetch data (e.g., api.weather.com).
Web Security: Prevent SQL injection, XSS.
SEO: Optimize for Google rankings.
Accessibility: Support screen readers.

