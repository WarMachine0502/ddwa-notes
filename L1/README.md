# **L1 - Introduction**

### **An Explanation of the Web with relation to the Internet**


- The Internet is a network of connected computers.

- Internet is governed by a system of standards and rules and not by any single company.

- Basic Purposes of Internet is to share information

- Standardized methods (for e.g. Emails, FTP) for transferring data or documents over a network are known as protocols.

- The Web was originally called the World Wide Web, thus the `www` in site addresses.

- The Web is regarded as a subset of the internet.

- It is just one of many ways information can be transferred over networked computers.

- It is unique in that it allows documents to be linked to one another using hypertext links - thus forming a huge "web" of connected information.

- The Web uses a protocol called `HTTP(Hypertext Transfer Protocol)`.

<br>

### **Role of Browser and Server**

**A Server**

- is the software(not the computer itself).

- allows the computer to communicate with other computers.

- The role of server software is to wait for a request for information, then retrieve and send that information as quickly as possible.

In order for a computer to be part of the Web, it must be running special web server software that allows it to handle Hypertext Transfer Protocol transactions.

Web Servers are also called "HTTP Servers."

<br>

**DNS Server**

- Every computer and device (modem, router, smartphone, cars, etc.) connected to the Internet is assigned a unique numeric Internet Protocol (IP) address.

- For example, the computer that hosts [oreilly.com](oreilly.com) has the IP address [64:ff9b::c71b:9140](http://[64:ff9b::c71b:9140]/).

- The numeric IP address is useful computer software, while the domain name is more accessible to humans.

- Matching the text domain names to their respective numeric IP addresses is the job of a seperate DNS (Domain Name System) server.

<br>

**Browser**

- The software that request server is called the client.

- The requests and responses on web are handled via the HTTP Protocol.

- HTTP can be used to transfer images, movies, audio files, data, scripts, and all the other web resources that commonly make up web sites and applications.

- Server returns the documents to the browser (also referred to as the `user agent` in technical circles) to display.

- Commonly used browsers are: Internet Explorer for Windows, Chrome, Firefox, and Safari, Opera.

<br>

### **Introduction to URL and its Components**

Every page and resource on the Web has its own special address called an `URL`, which stands for Uniform Resource Locator.

- **Protocol:** The letters HTTP let the server know to use Hypertext Transfer Protocol, or get into "web mode".

- **Name of the Site:** 
The name of the website is built out of
    - Hostname: The host name `www` has become a convention, but it is not a rule. For eg, `development.example.com`, `clients.example.com`, and so on.
    - Domain Name: the domain name is `example.com`

    <br>

- **Default files**
    - The `index.html` page is the most common name used for the default page shown on a website if no other page is specified when a visitor requests the site.
    - In other words, index.html is the name used for the homepage of the website.

    <br>
    
    So when someone types `http://www.oreilly.com`, what they actually see is `http://www.oreilly.com/index.html`.

    <br>

    Besides `index.html`, there are other default page names that some sites use, including
    - index.htm
    - default.htm
    - default.html
    - home.htm
    - home.html

<br>

### **Anatomy of a Web Page**

<br>

![anatomy](https://lh5.googleusercontent.com/5NsdccIgCR23hUlsmicjei4WYwd7qk0daohNpllO3YWls9f4RY9vmq5LFaC-1Ot96gk=w2400)