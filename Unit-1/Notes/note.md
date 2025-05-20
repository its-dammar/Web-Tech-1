
1.  # Module 1: Basic Concepts (3 hours)

## 1.1. Introduction to Internet, WWW, Web Browser, Web Servers, URL

### 1.1.1. The Internet
The Internet is a **global network of interconnected computer networks** that use the standard **Internet Protocol Suite (TCP/IP)** to link devices worldwide. It's a "network of networks" that consists of private, public, academic, business, and government networks of local to global scope, linked by a broad array of electronic, wireless, and optical networking technologies.

**Key Characteristics:**
*   **Decentralized:** No single entity owns or controls the Internet.
*   **Packet Switching:** Data is broken down into small packets, sent independently over the network, and reassembled at the destination. This is more efficient and robust than circuit switching.
*   **Scalability:** Designed to grow and accommodate an increasing number of users and devices.
*   **Interoperability:** Based on open standards (like TCP/IP) that allow different types_of networks and devices to communicate.

**Brief History:**
*   Originated from **ARPANET** (Advanced Research Projects Agency Network) in the late 1960s, a US Department of Defense project.
*   Initially for research and military communication.
*   TCP/IP protocols were developed in the 1970s, becoming the standard.
*   The commercialization of the Internet began in the late 1980s and early 1990s.

**Services on the Internet:**
The Internet supports a vast range of information resources and services, such as:
*   World Wide Web (WWW)
*   Email
*   File Transfer (FTP)
*   Online Gaming
*   Voice over IP (VoIP)
*   Streaming Media

### 1.1.2. World Wide Web (WWW)
The World Wide Web (WWW), or simply "the Web," is an **information system** where documents and other web resources are identified by Uniform Resource Locators (URLs), interlinked by hypertext links, and accessible via the Internet.

**Key Differences: Internet vs. WWW**
*   **Internet:** The global network infrastructure (hardware and protocols) that allows computers to connect and exchange data. Think of it as the roads and highways.
*   **WWW:** One of the services that runs *on* the Internet. It's a collection of web pages, images, videos, etc., accessed using protocols like HTTP. Think of it as the content and destinations accessible via those roads.

**Inventor:**
*   Invented by **Sir Tim Berners-Lee** in 1989 while working at CERN.

**Core Components of the WWW:**
*   **HTML (HyperText Markup Language):** The standard language for creating web pages.
*   **HTTP (HyperText Transfer Protocol):** The protocol used to transfer web pages from servers to browsers.
*   **URLs (Uniform Resource Locators):** Addresses used to locate resources on the Web.
*   **Web Browsers:** Software applications used to access and display web pages.
*   **Web Servers:** Computers that store and deliver web content.

### 1.1.3. Web Browser
A **web browser** is a software application used to retrieve, present, and traverse information resources on the World Wide Web. An information resource is identified by a URL and may be a web page, image, video, or other piece of content.

**Key Functions:**
1.  **Requesting Resources:** When you type a URL or click a link, the browser sends an HTTP request to the appropriate web server.
2.  **Rendering Content:** The browser interprets HTML, CSS (Cascading Style Sheets for styling), and JavaScript (for interactivity) to display the web page to the user.
3.  **Navigation:** Allows users to move between web pages using hyperlinks, back/forward buttons, and bookmarks.
4.  **Security:** Implements security features like warning about insecure sites, managing cookies, and handling digital certificates for HTTPS.
5.  **Managing Add-ons/Extensions:** Allows users to extend browser functionality.

**Popular Web Browsers:**
*   Google Chrome
*   Mozilla Firefox
*   Apple Safari
*   Microsoft Edge
*   Opera

### 1.1.4. Web Servers
A **web server** is software and underlying hardware that accepts requests via HTTP (or its secure variant HTTPS) for web content and responds by sending that content back to the client (typically a web browser).

**Key Functions:**
1.  **Storing Web Content:** Hosts website files, including HTML documents, images, CSS stylesheets, JavaScript files, etc.
2.  **Processing HTTP Requests:** Listens for incoming HTTP requests from clients.
3.  **Serving HTTP Responses:** Sends the requested resources (or an error message) back to the client.
4.  **Running Server-Side Scripts:** Can execute scripts (e.g., PHP, Python, Node.js) to generate dynamic content.
5.  **Security:** Manages security through authentication, authorization, and SSL/TLS encryption (for HTTPS).
6.  **Logging:** Keeps logs of requests and errors for monitoring and analysis.

**Popular Web Server Software:**
*   **Apache HTTP Server:** Open-source, widely used.
*   **Nginx (pronounced "engine-x"):** Open-source, known for performance and scalability, often used as a reverse proxy and load balancer.
*   **Microsoft Internet Information Services (IIS):** Developed by Microsoft, runs on Windows servers.
*   **LiteSpeed Web Server:** Commercial, known for performance.

**Hardware Aspect:** A web server is also the physical computer (or virtual machine) that runs the web server software and stores the website files. It needs to be connected to the internet and have sufficient processing power, memory, and storage.

### 1.1.5. URL (Uniform Resource Locator)
A **URL** is a reference (an address) to a web resource that specifies its location on a computer network and a mechanism for retrieving it. It's a specific type of URI (Uniform Resource Identifier).

**Components of a URL:**
A typical URL has the following structure:
`scheme://[userinfo@]host[:port]/path[?query][#fragment]`

Let's break down an example: `https://www.example.com:443/path/to/myfile.html?key1=value1#section1`

1.  **Scheme (or Protocol):** `https`
    *   Defines the protocol to be used to access the resource (e.g., `http`, `https`, `ftp`, `mailto`).
    *   Ends with a colon and two forward slashes (`://`).

2.  **Userinfo (Optional):** `[userinfo@]` (e.g., `username:password@`)
    *   Username and password for authentication. Rarely used directly in URLs visible to users due to security risks.

3.  **Host (or Domain Name):** `www.example.com`
    *   The domain name or IP address of the server hosting the resource.

4.  **Port (Optional):** `:443`
    *   The port number on the server to connect to.
    *   If omitted, defaults to standard ports (e.g., 80 for HTTP, 443 for HTTPS).

5.  **Path:** `/path/to/myfile.html`
    *   Specifies the location of the resource on the server, often corresponding to a file path.
    *   Starts with a single forward slash (`/`).

6.  **Query String (Optional):** `?key1=value1`
    *   A sequence of key-value pairs, typically used to pass data to the server for dynamic pages or tracking.
    *   Starts with a question mark (`?`). Pairs are separated by ampersands (`&`).

7.  **Fragment (Optional):** `#section1`
    *   Identifies a specific section or part within the resource (e.g., an anchor in an HTML page).
    *   Starts with a hash symbol (`#`). Processed by the client (browser) and not sent to the server.

**Example:**
For `http://www.gandakimyuniversity.edu.np/programs`
*   Scheme: `http`
*   Host: `www.gandakiuniversity.edu.np`
*   Port: `80` (default for http)
*   Path: `/academics/courses.php`
*   Query: `department=cs&level=300`
*   Fragment: `fall`

---

## 1.2. Overview of different protocols: HTTP, HTTPS, POP, SMTP, FTP, WAP

Protocols are sets of rules and conventions that govern how data is transmitted and received over a network.

### 1.2.1. HTTP (HyperText Transfer Protocol)
*   **Purpose:** The foundation of data communication for the World Wide Web. It defines how messages are formatted and transmitted, and what actions web servers and browsers should take in response to various commands.
*   **How it Works:**
    *   A client (e.g., web browser) sends an HTTP **request** to a server.
    *   The server processes the request and sends back an HTTP **response** (e.g., the requested HTML page, an image, or an error message).
*   **Key Features:**
    *   **Stateless:** Each request from a client to a server is treated as an independent transaction. The server does not retain any information about previous requests from the same client. (Mechanisms like cookies are used to create "sessions" on top of HTTP).
    *   **Text-based:** Messages are human-readable (though often compressed).
    *   **Request Methods:**
        *   `GET`: Requests data from a specified resource.
        *   `POST`: Submits data to be processed to a specified resource (e.g., form submission).
        *   `PUT`: Updates a resource or creates it if it doesn't exist.
        *   `DELETE`: Deletes a specified resource.
        *   And others (`HEAD`, `OPTIONS`, `PATCH`, etc.).
*   **Default Port:** TCP port 80.

### 1.2.2. HTTPS (HyperText Transfer Protocol Secure)
*   **Purpose:** The secure version of HTTP. It encrypts the communication between the client and server, providing confidentiality and integrity.
*   **How it Works:**
    *   Uses HTTP over an encrypted connection provided by **SSL (Secure Sockets Layer)** or its successor, **TLS (Transport Layer Security)**.
    *   **Encryption:** Protects data from eavesdropping.
    *   **Authentication:** Often uses digital certificates to verify the identity of the web server (and sometimes the client).
    *   **Integrity:** Ensures that data has not been tampered with during transmission.
*   **Key Features:**
    *   Essential for sensitive transactions like online banking, e-commerce, and login pages.
    *   Browsers display a padlock icon for HTTPS sites.
*   **Default Port:** TCP port 443.

### 1.2.3. POP (Post Office Protocol)
*   **Purpose:** Used by email clients to retrieve emails from a mail server. The current version is POP3.
*   **How it Works:**
    1.  Email client connects to the mail server.
    2.  Client authenticates (username/password).
    3.  Client downloads emails to the local device.
    4.  **Typically, emails are deleted from the server after download** (though some clients allow an option to "leave a copy on the server").
*   **Key Features:**
    *   Simple protocol for email retrieval.
    *   Best suited for users who access email from a single device.
    *   Less ideal for multi-device access, as emails are stored locally.
*   **Default Ports:**
    *   TCP port 110 (unencrypted POP3)
    *   TCP port 995 (POP3S - POP3 over SSL/TLS)

*   **Contrast with IMAP (Internet Message Access Protocol):** IMAP is another email retrieval protocol that keeps emails on the server, synchronizing them across multiple devices. This is generally preferred for modern usage.

### 1.2.4. SMTP (Simple Mail Transfer Protocol)
*   **Purpose:** The standard protocol for **sending** email messages between servers and from email clients to mail servers.
*   **How it Works:**
    1.  When you send an email, your email client (or webmail interface) connects to an SMTP server (often called an outgoing mail server or Mail Submission Agent - MSA).
    2.  The client authenticates and transfers the email to this SMTP server.
    3.  This SMTP server then relays the email to the recipient's mail server (Mail Transfer Agent - MTA) using SMTP.
    4.  The recipient's mail server stores the email until the recipient retrieves it (using POP3 or IMAP).
*   **Key Features:**
    *   "Push" protocol: Initiates the sending of messages.
    *   Reliable but can have delays.
*   **Default Ports:**
    *   TCP port 25 (server-to-server email transfer)
    *   TCP port 587 (email submission from clients, often requires authentication and uses STARTTLS for encryption)
    *   TCP port 465 (SMTPS - SMTP over SSL/TLS, older but still used for client submission)

### 1.2.5. FTP (File Transfer Protocol)
*   **Purpose:** Used to transfer computer files between a client and a server on a computer network.
*   **How it Works:**
    *   Uses two separate TCP connections:
        1.  **Control Connection (Port 21):** For sending commands (e.g., `LIST`, `RETR`, `STOR`) and receiving responses. Stays open for the duration of the session.
        2.  **Data Connection (Port 20 in Active mode, or a dynamic port in Passive mode):** For actual file transfer. Opens and closes for each file transferred.
    *   **Modes:**
        *   **Active Mode:** Client tells the server its IP and port; server initiates the data connection back to the client. Can be problematic with firewalls.
        *   **Passive Mode:** Client initiates both control and data connections to the server. More firewall-friendly.
*   **Key Features:**
    *   Supports user authentication (username/password).
    *   Can transfer files in binary or ASCII mode.
    *   **Security Concern:** Standard FTP transmits data (including credentials) in plaintext. It's highly recommended to use secure alternatives:
        *   **FTPS (FTP over SSL/TLS):** Adds SSL/TLS encryption to FTP.
        *   **SFTP (SSH File Transfer Protocol):** Not related to FTP, but provides file transfer functionality over a secure SSH connection.
*   **Default Ports:**
    *   TCP port 21 (Control Connection)
    *   TCP port 20 (Data Connection, Active Mode)

### 1.2.6. WAP (Wireless Application Protocol)
*   **Purpose:** An older standard for accessing information services (like simplified web pages) over a mobile wireless network. Primarily designed for feature phones with limited browsers, low bandwidth, and small screens.
*   **How it Works:**
    *   Used **WML (Wireless Markup Language)** instead of HTML, which was simpler and designed for small displays.
    *   Often involved a **WAP Gateway** that acted as an intermediary between the mobile device and the web server. The gateway would translate WML requests to HTTP and HTML responses back to WML.
*   **Key Features:**
    *   Enabled early mobile internet access.
    *   Included protocols like WTP (Wireless Transaction Protocol) and WTLS (Wireless Transport Layer Security).
*   **Relevance Today:** Largely obsolete. Modern smartphones have full-fledged web browsers that can render standard HTML, CSS, and JavaScript, and mobile networks offer much higher bandwidth. The need for WAP has diminished significantly.

---

## 1.3. Domain name and hierarchy, domain name registration process, web hosting

### 1.3.1. Domain Name and Hierarchy

**What is a Domain Name?**
A **domain name** is a human-readable, easy-to-remember address used to identify and access websites and other resources on the Internet. It's a user-friendly substitute for an IP address (e.g., `172.217.160.142`), which is a numerical label assigned to each device connected to a computer network.
*   Example: `www.google.com` is a domain name.

**The Domain Name System (DNS):**
DNS is a hierarchical and decentralized naming system for computers, services, or other resources connected to the Internet or a private network. It translates human-readable domain names into machine-readable IP addresses. Think of it as the "phonebook of the Internet."

*   **Domain Name Definition:** A human-readable, easy-to-remember address used to identify and access websites and resources on the Internet (e.g., `www.google.com`), translating to an IP address.
*   **DNS (Domain Name System):** A hierarchical, decentralized naming system that translates domain names into IP addresses. "The phonebook of the Internet."

*   **Domain Name Hierarchy:** (Right to Left)
    ```
              . (root)
              |
      ---------------------
      |         |         |
     com       org       net       uk        (Top-Level Domains - TLDs)
      |         |                   |
    google    wikipedia           co.uk     (Second-Level Domains - SLDs)
      |                             |
     www                         bbc.co.uk  (Subdomains / Hostnames)
    ```
    1.  **Root Domain (`.`):** Highest level, often implied. Managed by ICANN/IANA.
    2.  **Top-Level Domains (TLDs):**
        *   **gTLDs (Generic):** `.com`, `.org`, `.net`, `.edu`, `.app`, `.blog`.
        *   **ccTLDs (Country Code):** `.uk`, `.us`, `.ca`, `.in`.
    3.  **Second-Level Domains (SLDs):** The unique name chosen by registrant (e.g., `google` in `google.com`).
    4.  **Subdomains:** Further divisions to the left of the SLD (e.g., `www`, `mail`, `blog`).
*   **FQDN (Fully Qualified Domain Name):** The complete domain name for a specific host, including the trailing dot (e.g., `www.example.com.`).
*   
2.  **Root Domain (`.`):**
    *   The highest level in the DNS hierarchy. It is often implied and not explicitly typed in browsers.
    *   Managed by ICANN (Internet Corporation for Assigned Names and Numbers) through IANA (Internet Assigned Numbers Authority).

3.  **Top-Level Domains (TLDs):**
    *   The last part of a domain name (e.g., `.com`, `.org`, `.net`, `.gov`, `.edu`).
    *   **Generic TLDs (gTLDs):**
        *   Original: `.com` (commercial), `.org` (organization), `.net` (network), `.edu` (education), `.gov` (government), `.mil` (military).
        *   Newer: `.app`, `.blog`, `.shop`, etc.
    *   **Country Code TLDs (ccTLDs):**
        *   Two-letter domains representing specific countries or territories (e.g., `.uk` (United Kingdom), `.us` (United States), `.ca` (Canada), `.in` (India)).

4.  **Second-Level Domains (SLDs):**
    *   The part of the domain name directly to the left of the TLD (e.g., `google` in `google.com`, `example` in `example.co.uk`).
    *   This is the unique name typically chosen by an individual or organization.

5.  **Subdomains:**
    *   Parts to the left of the SLD (e.g., `www` in `www.google.com`, `mail` in `mail.google.com`, `blog` in `blog.example.com`).
    *   Organizations can create subdomains to organize different sections or services of their website. `www` is a common subdomain traditionally used for the main website.

**Fully Qualified Domain Name (FQDN):**
An FQDN is a complete domain name for a specific computer, or host, on the Internet. It consists of the hostname and the domain name. For example, `www.example.com.` (note the trailing dot representing the root) is an FQDN.

### 1.3.2. Domain Name Registration Process

Registering a domain name involves reserving a specific name with an accredited organization called a **domain name registrar**.

**Key Players:**
*   **ICANN (Internet Corporation for Assigned Names and Numbers):** A non-profit organization responsible for coordinating the maintenance and procedures of several databases related to the namespaces of the Internet, ensuring the network's stable and secure operation. ICANN accredits registrars.
*   **Registries:** Organizations that manage TLDs (e.g., Verisign manages `.com`). They maintain the authoritative database of all domain names registered under their TLDs.
*   **Registrars:** ICANN-accredited companies that individuals and organizations can use to register domain names. They act as intermediaries between users and registries (e.g., GoDaddy, Namecheap, Google Domains).
*   **Registrant:** The individual or organization registering the domain name.

**Steps in the Registration Process:**
1.  **Choose a Domain Name:** Select a unique and relevant name. Consider branding, memorability, and TLD choice.
2.  **Check Availability:** Use a registrar's website (or a WHOIS lookup tool) to see if the desired domain name is available.
3.  **Choose a Registrar:** Select an ICANN-accredited registrar. Compare pricing, customer support, user interface, and additional services (e.g., privacy protection, email hosting).
4.  **Provide Registration Information (WHOIS Data):**
    *   The registrant must provide accurate contact information (name, address, email, phone number). This information is stored in the WHOIS database, which is publicly accessible (unless WHOIS privacy is enabled).
    *   Administrative Contact, Technical Contact, Billing Contact.
5.  **Choose Registration Period & Pay:**
    *   Domain names are typically registered for a period of 1 to 10 years.
    *   Pay the registration fee to the registrar.
6.  **Configure DNS Settings (Name Servers):**
    *   After registration, you need to specify the **name servers** for your domain. Name servers tell the DNS where to find your website's IP address (i.e., where your website is hosted).
    *   Your web hosting provider will typically give you the name server addresses to use.
7.  **Manage and Renew:**
    *   Keep track of the expiration date and renew the domain name to maintain ownership. Most registrars offer auto-renewal.

**WHOIS Privacy:**
Many registrars offer a WHOIS privacy service (sometimes called Domain Privacy Protection). This service replaces your personal contact information in the public WHOIS database with the registrar's information, helping to protect against spam and identity theft.

### 1.3.3. Web Hosting

**What is Web Hosting?**
Web hosting is a service that allows individuals and organizations to make their website accessible via the World Wide Web. Web hosting service providers own and maintain servers where website files (HTML, CSS, images, databases, etc.) are stored. When someone types your domain name into their browser, DNS directs them to the server where your website is hosted, and the server delivers the website content to their browser.

**Types of Web Hosting:**

1.  **Shared Hosting:**
    *   **Concept:** Multiple websites share resources (CPU, RAM, disk space, bandwidth) on a single physical server.
    *   **Pros:** Most affordable option, easy to manage (often comes with a control panel like cPanel or Plesk), good for beginners and small websites with low traffic.
    *   **Cons:** Limited resources, performance can be affected by other sites on the same server ("noisy neighbor" effect), less security and customization options.

2.  **VPS (Virtual Private Server) Hosting:**
    *   **Concept:** A physical server is divided into multiple virtual servers. Each VPS has its own dedicated share of resources (CPU, RAM) and operates independently with its own operating system.
    *   **Pros:** More resources and control than shared hosting, better performance and security, root access allows for more customization, scalable.
    *   **Cons:** More expensive than shared hosting, requires more technical knowledge to manage (unless you opt for managed VPS hosting).

3.  **Dedicated Server Hosting:**
    *   **Concept:** An entire physical server is rented exclusively by one client. The client has full control over the server's hardware, operating system, and software.
    *   **Pros:** Maximum performance, resources, security, and customization. Ideal for very high-traffic websites, large businesses, and applications with specific needs.
    *   **Cons:** Most expensive option, requires significant technical expertise for server management (unless managed services are purchased).

4.  **Cloud Hosting:**
    *   **Concept:** Websites are hosted on a cluster of interconnected servers (the "cloud"). Resources are pooled and can be scaled up or down on demand.
    *   **Pros:** High reliability and uptime (if one server fails, others take over), scalability (pay for what you use), flexible resource allocation.
    *   **Cons:** Pricing can be complex and sometimes unpredictable, can be more expensive than shared/VPS for consistent high usage, some find it less intuitive than traditional hosting.

5.  **Managed WordPress Hosting (Specialized):**
    *   **Concept:** Hosting specifically optimized for WordPress websites. Providers handle technical aspects like security, updates, backups, and performance tuning.
    *   **Pros:** Excellent performance and security for WordPress, expert support, automatic updates and backups.
    *   **Cons:** Can be more expensive than general shared hosting, typically limited to WordPress sites only.

**Key Factors When Choosing a Web Host:**
*   **Reliability/Uptime:** Look for guarantees (e.g., 99.9% uptime).
*   **Speed/Performance:** Server hardware, network connectivity, caching technologies.
*   **Scalability:** Ability to upgrade resources as your website grows.
*   **Support:** Availability and quality of customer/technical support (24/7, chat, phone, email).
*   **Security:** Firewalls, malware scanning, DDoS protection, SSL certificates.
*   **Control Panel:** Ease of use (cPanel, Plesk, custom).
*   **Backup Services:** Regular automatic backups and easy restoration.
*   **Price:** Consider value for money, not just the cheapest option.
*   **Features:** Disk space, bandwidth, email accounts, database support, one-click installers.
*   **Location of Servers:** Can impact website speed for your target audience.

---

