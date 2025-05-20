
---

## **1.1 Introduction to Internet, WWW, Web Browser, Web Servers, URL**


### **Internet**

A global network of interconnected computers that communicate using standardized protocols to share information.
* The Internet:
- The Internet is a global network of interconnected computer networks.
- It enables the exchange of data and information between devices.
- It relies on protocols like TCP/IP to ensure reliable and consistent data transmission. 
- OR
- The Internet is a massive network of networks, connecting billions of computers globally. It provides the infrastructure for communication and information sharing. 

- What is the Internet?
The Internet is used to connect the different networks of computers simultaneously. It is a public network therefore anyone can access the internet. On the internet, there are multiple users and it provides unlimited information to the users. 

- What is an Intranet?
Intranet is the type of internet that is used privately. It is a private network therefore anyone can’t access the intranet. On the intranet, there is a limited number of users and it provides a piece of limited information to its users. 

| **Criteria**                 | **Internet**                                                                       | **Intranet**                                                                                      |
| ---------------------------- | ---------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------- |
| **Definition**               | A global public network that connects millions of computers and devices worldwide. | A private network used within an organization for internal communication and information sharing. |
| **Ownership**                | Not owned by any one entity; decentralized and public.                             | Owned and managed by a specific organization.                                                     |
| **Accessibility**            | Open to everyone with an internet connection.                                      | Restricted to authorized users within the organization.                                           |
| **Number of Users**          | Unlimited; millions of global users.                                               | Limited to organization members/employees.                                                        |
| **Purpose**                  | Used for communication, education, entertainment, e-commerce, etc.                 | Used for internal communication, collaboration, and document management.                          |
| **Security**                 | Relatively less secure; vulnerable to cyber threats.                               | More secure due to restricted access and internal firewalls.                                      |
| **Information Availability** | Offers unlimited public information and resources.                                 | Provides limited, organization-specific information.                                              |
| **Examples of Use**          | Browsing websites, using social media, sending emails.                             | Employee portals, internal messaging, company announcements.                                      |
| **Visitors**                 | High number of visitors from all over the world.                                   | Fewer visitors limited to internal staff.                                                         |
| **Location of Access**       | Can be accessed from anywhere in the world.                                        | Usually accessed from within the organization or via VPN.                                         |
| **Security Measures**        | Uses firewalls, encryption, SSL, antivirus, etc.                                   | Uses similar security but is easier to control due to limited users.                              |
| **Examples**                 | Google, Facebook, YouTube, Amazon.                                                 | Company internal HR portal, internal dashboards, SharePoint.                                      |


  
 **Functions:**
  * Email communication
  * Browsing websites
  * File transfer
  * Online streaming
  * Cloud computing

### **World Wide Web (WWW)**

* **Definition:** A system of interlinked hypertext documents accessed via the internet using a web browser.The Web is a specific application built upon the Internet. It uses protocols like HTTP to transmit data and allows users to access web pages via browsers. 
* **Difference from Internet:** The WWW is a service **on top** of the internet; the internet is the infrastructure.
* **Components:**

  * **Web Pages:** HTML documents
  * **Hyperlinks:** Navigation between pages
  * **Web Servers:** Host and serve content

### **Web Browser**

* **Definition:** Software application used to retrieve, display, and interact with content on the World Wide Web.A web browser is a software application that interprets and displays web pages. It enables users to navigate the Web by following hyperlinks and loading resources. Examples include Chrome, Firefox, and Safari. 
* Web Browser is an application software to interact with the World Wide Web. It acts as a User Interface to browse files online. It is basically a client program to render HTML on the client side by making HTML requests. It supports various internet protocols to fetch files and email from the internet. Let us learn more about the world of Web Browsers.
  

Functions of a Web Browser
- Bookmarking and history: Helps to save permanent links and keeps record of visited pages
- Downloading Function: This function helps to save files, applications and images from different URL to the system
- Plugins: These are small pieces of code which help to customize and add extra features to browser
- Cookies and Cache management: These help to enhance user experience and increase webpage loading speed Apart from these functions a browser also provides functions to enhance user security such as Phishing and Malware Protection, Tracking Prevention, SSL/TLS Encryption, Pop-up Blocking, Password managing etc.

* **Examples:** Google Chrome, Mozilla Firefox, Safari, Microsoft Edge.
* **Key Functions:**

  * Render HTML, CSS, and JavaScript
  * Manage bookmarks and history
  * Use extensions for additional features
* **Browser Engine:** Handles layout and rendering (e.g., Blink, Gecko)

### **Web Page**
* A web page is a single document that is displayed through a web browser. It is a part of a website and can include text, images, videos, links, and interactive elements. Web pages are primarily written in HTML (HyperText Markup Language), styled with CSS (Cascading Style Sheets), and have dynamic elements with JavaScript.

- A web page shows text, images, and videos to provide information.
- It includes elements like forms and buttons that users can click or fill out.
- A web page has links that let users move between different pages or sections.

How does a web page render?
https://media.geeksforgeeks.org/wp-content/uploads/20250410153024087959/step_5.webp

### **Web Server**
* **Definition:** A computer system that stores, processes, and delivers web pages to clients (browsers) over HTTP/HTTPS.A web server is a computer program that processes requests from web browsers and delivers the requested web pages. It stores and serves the files (HTML, images, etc.) that make up a website. 
* OR
* A web server is a system—either software, hardware, or both—that stores, processes, and delivers web content to users over the Internet using the HTTP or HTTPS protocol. When a user’s browser sends a request (like visiting a website), the web server responds by delivering the appropriate resources such as HTML pages, images, videos, or data.
  
* **Popular Web Servers:** Apache, Nginx, Microsoft IIS.
* **Functions:**

  * Handle client requests
  * Deliver HTML content and media
  * Run server-side scripts (e.g., PHP, Python)

### **URL (Uniform Resource Locator)**

* **Definition:** The address used to access resources on the web.A URL is the address of a specific resource on the web, such as a web page or an image. It specifies the protocol (e.g., HTTP or HTTPS), the domain name (e.g., google.com), and the path to the resource. For example, https://www.google.com/ is a URL. 
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
