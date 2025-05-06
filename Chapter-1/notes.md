
---

## **1.1 Introduction to Internet, WWW, Web Browser, Web Servers, URL**

▶ **Section Title**

    This is the symbolic dropdown content.
    - You can indent it
    - Or use bullet points

▼ **Section Title (Expanded)**

    - This could represent opened dropdowns


<details>
<summary>Dropdown Title</summary>

Content inside the dropdown goes here.  
You can use lists, code, or paragraphs.

- List item
- Another item


</details>

[+] **Internet**

* **Definition:** A global network of interconnected computers that communicate using standardized protocols to share information.
* **History:** Evolved from ARPANET in the 1960s by the U.S. Department of Defense.
 **Functions:**

  * Email communication
  * Browsing websites
  * File transfer
  * Online streaming
  * Cloud computing

### **World Wide Web (WWW)**

* **Definition:** A system of interlinked hypertext documents accessed via the internet using a web browser.
* **Difference from Internet:** The WWW is a service **on top** of the internet; the internet is the infrastructure.
* **Components:**

  * **Web Pages:** HTML documents
  * **Hyperlinks:** Navigation between pages
  * **Web Servers:** Host and serve content

### **Web Browser**

* **Definition:** Software application used to retrieve, display, and interact with content on the World Wide Web.
* **Examples:** Google Chrome, Mozilla Firefox, Safari, Microsoft Edge.
* **Key Functions:**

  * Render HTML, CSS, and JavaScript
  * Manage bookmarks and history
  * Use extensions for additional features
* **Browser Engine:** Handles layout and rendering (e.g., Blink, Gecko)

### **Web Server**

* **Definition:** A computer system that stores, processes, and delivers web pages to clients (browsers) over HTTP/HTTPS.
* **Popular Web Servers:** Apache, Nginx, Microsoft IIS.
* **Functions:**

  * Handle client requests
  * Deliver HTML content and media
  * Run server-side scripts (e.g., PHP, Python)

### **URL (Uniform Resource Locator)**

* **Definition:** The address used to access resources on the web.
* **Structure:**

  ```
  https://www.example.com:443/path/page.html?query=1#section
  └──┬─────┘ └────┬────┘ └──────┬──────┘ └─────┬──────┘ └───┬───┘
  protocol    domain name   port number   path & query     anchor
  ```

---

## **1.2 Overview of Different Protocols**

| Protocol  | Full Form                     | Purpose                                                            | Port   |
| --------- | ----------------------------- | ------------------------------------------------------------------ | ------ |
| **HTTP**  | HyperText Transfer Protocol   | Transfers web data (insecure)                                      | 80     |
| **HTTPS** | HTTP Secure                   | Encrypted version of HTTP using SSL/TLS                            | 443    |
| **POP**   | Post Office Protocol (v3)     | Retrieves emails from server to local device (download and delete) | 110    |
| **SMTP**  | Simple Mail Transfer Protocol | Sends emails from client to server or server to server             | 25     |
| **FTP**   | File Transfer Protocol        | Transfers files between client and server                          | 21     |
| **WAP**   | Wireless Application Protocol | Used to access internet on mobile devices (older tech)             | Varies |

### **Detailed Descriptions:**

* **HTTP vs. HTTPS:**

  * HTTPS uses **SSL/TLS encryption** for secure data transmission.
  * HTTPS is essential for login pages, payment systems, and secure browsing.

* **POP vs. IMAP (Comparison):**

  * POP downloads emails and deletes them from the server.
  * IMAP syncs email with the server; preferred for multi-device access.

* **SMTP (Email Sending):**

  * Used by email clients to send messages.
  * Works alongside POP/IMAP for complete email systems.

* **FTP:**

  * Used by developers and site admins to upload/download files to/from a server.
  * Requires FTP client software (e.g., FileZilla).

* **WAP:**

  * Designed for mobile devices before smartphones became mainstream.
  * Now largely obsolete, replaced by responsive websites and mobile apps.

---

## **1.3 Domain Name and Hierarchy, Domain Name Registration Process, Web Hosting**

### **Domain Name**

* **Definition:** A human-readable address for websites, mapped to IP addresses using DNS.
* **Example:** `www.google.com`
* **Why It Matters:** Easier than remembering numeric IP addresses.

### **Domain Name Hierarchy**

```
www.xdezo.com
└──┬──┘ └───┬──┘ └┬┘
subdomain domain TLD
```

* **TLD (Top-Level Domain):** `.com`, `.org`, `.edu`, `.gov`, `.np`
* **Second-Level Domain:** `xdezo` in `xdezo.com`
* **Subdomain:** `www`, `mail`, or `blog`

### **DNS (Domain Name System):**

* Translates domain names into IP addresses.
* Acts like a phonebook of the internet.

### **Domain Name Registration Process**

1. **Choose a domain name** relevant to your business or identity.
2. **Check availability** via a domain registrar (e.g., GoDaddy, Namecheap).
3. **Register the domain** for 1+ years.
4. **Provide contact and DNS info**.
5. **Point domain to hosting server** via **nameservers (NS records)**.

### **Web Hosting**

* **Definition:** Service that provides storage space and access to websites on the internet.
* **Types of Hosting:**

  * **Shared Hosting:** Multiple sites share the same server (affordable, limited performance).
  * **VPS (Virtual Private Server):** Virtualized server with dedicated resources.
  * **Dedicated Hosting:** Entire server is rented; high performance and cost.
  * **Cloud Hosting:** Scalable and flexible hosting via multiple servers.
* **Popular Providers:** Bluehost, HostGator, SiteGround, AWS, DigitalOcean.

---

Would you like this content formatted in a downloadable **PDF** or **Markdown file** for distribution or classroom use?
