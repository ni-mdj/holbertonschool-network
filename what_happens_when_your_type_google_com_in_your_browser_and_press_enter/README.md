# What happens when you type https://www.google.com in your browser and press Enter

This project explains the famous interview question:  
**"What happens when you type https://www.google.com in your browser and press Enter?"**

It covers how the web stack works on top of the Internet, from the moment you hit **Enter** in your browser until the requested web page is displayed.

---

## 📌 Requirements

### 0. Blog Post (mandatory)
- Write a **blog post** explaining the workflow.  
- Your post **must cover** the following steps:
  1. **DNS request** – how the domain name is resolved into an IP address  
  2. **TCP/IP** – how the browser connects to the server using the IP and port 443  
  3. **Firewall** – how traffic passes through firewalls  
  4. **HTTPS/SSL** – how the SSL/TLS handshake encrypts traffic  
  5. **Load-balancer** – how the request is distributed across servers  
  6. **Web server** – how it serves static content or forwards to the app server  
  7. **Application server** – how it executes application logic  
  8. **Database** – how data is queried and returned  

- Publish your blog post on **Medium** or **LinkedIn**.  
- Share the URL of your blog post in:  
  - The answer file `0-blog_post`  
  - The submission field  


---

### 1. Everything’s better with a pretty diagram (mandatory)
- Add a **diagram** to your blog post illustrating the flow of the request.
- The diagram must show:
  - DNS resolution  
  - The request hitting the server IP on the right port  
  - That traffic is **encrypted**  
  - That traffic goes through a **firewall**  
  - The request is distributed via a **load balancer**  
  - The **web server** serving the web page  
  - The **application server** generating the page  
  - The **application server** querying the **database**  

- Tools you can use: **Gliffy**, **Lucidchart**, **Draw.io**, or any equivalent.  

- Share the URL of your diagram image in:
  - The answer file `1-what_happen_when_diagram`  
  - The submission field  

## Diagram ideas : 

User (Browser)
   |
   v
DNS (resolves www.google.com → IP)
   |
   v
TCP/IP (port 443)
   |
   v
Firewall (filters traffic)
   |
   v
Load Balancer (distributes traffic)
   |
   v
Web Server (serves static content or forwards)
   |
   v
Application Server (runs logic, requests data)
   |
   v
Database (returns results)
   |
   v
Response back to Browser (encrypted HTML page)
