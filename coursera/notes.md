This course is the first of a series that aims to help you learn more about web development and prepares you for using Bootstrap on a biographical page you will create.  By the end of this course, you’ll be able to:   

  ·       Describe the front-end developer role

  ·       Explain the core and underlying technologies that power the internet

  ·       Use HTML to create a simple webpage

  ·       Use CSS to control the appearance of a simple webpage

  ·       Explain what React is

  ·       Describe the applications and characteristics of the most popular UI frameworks

In this course, you will explore the following:

Module 1: Get started with web development 
In this module, you are introduced to web development. You’ll learn about the different types of web developer roles and the responsibilities of front-end, back-end and full-stack developers. You will get a streamlined overview of the core technologies of HTML, CSS and JavaScript and explore the concepts that underpin how the internet works. Furthermore, you will be able to access hands-on exercises to edit a website. 

After completing this module, you will be able to: 
Describe the web developer job role. 
Distinguish between front-end, back-end and full-stack developers.
Explain how data moves through the internet.
Describe the technologies that underpin the internet.  

Module 2: Introduction to HTML5 and CSS  
Here you'll learn about HTML5 and CSS. You'll also examine how to construct HTML documents and add basic styling and layout using CSS. 
After completing this module, you will be able to: 
Use HTML to create a simple webpage.
Use CSS to define the style of a simple webpage. 

Module 3: UI Frameworks
In this module, you'll learn about UI frameworks. In addition, you will learn how to use the Bootstrap framework to build responsive interfaces. You'll explore the benefits of working with UI frameworks. 
After completing this module, you will be able to: 
Outline the concepts that exist in most UI frameworks.
Use the Bootstrap CSS framework to create webpages.
Leverage Bootstrap documentation to reproduce and modify CSS components.
Use Bootstrap themes. 
Describe the basics of React in relation to other frameworks and web technologies.

Webpages vs Websites: 
Webpage is a document that displays images, text, videos and other content 
Website is a collection of webpages put together

HTML/CSS/JS (trio)
HTML: Hyper Text Markup Language
CSS: Cascading Style Sheets
JS: JavaScript
HTML: structures the content you see
CSS: Colors and style
JS: responsible for user interaction
HTML is like the building (structure)
CSS is like the decorations and landscaping
JS is just like business, the services offered and the people coming in and out
Javascript is the powerhouse of webpages
URL: Uniform Resource Locator

IP Addresses: function like addresses in the postal system
IP address: 
data transmission: 
when you send data across the internet, computers are the destination that send and receive data and the networks are the roots that the data travels across
ip version 4 and ip version 6 are the most used standards of internet protocol
every computer on a network is assigned an ip address
IP protocol version 4 example: 192.0.2.235
IP protocol version 6 example: 4527:0a00:1567:0200:ff00:0042:8329 (uses hexadecimal values)
when you send data across a network it is sent as a series of messages called IP packets also known as data grounds
IP packets contain a IP header and a payload which is the IP data
whehn you send data you are not only sending to the receipients address, but you are showing your own address as well incase a return is needed

introduction to HTTP: Hyper Text Transfer Protocol
HTTP is a core operational protocol of the world wide web, it is what allows your web browser to communicate with the webserver that hosts a website
HTTP is a request response based profile:
HTTP request consists of a method: 
example: GET /(PATH) HTTP/1.1 (VERSION) + (HEADERS) HOST: developer.google.org  Accept-Language: en
Primary or most commonly used HTTP methods are: GET, POST, PUT, DELETE
GET: retrieve information from a given server
POST: used to send data to the server
PUT: update whatever currently exists on the webserver
DELETE: removes the resource
HTTP RESPONSE: follow a format similar to the request format
following the header a response will optionally contain a message body consisting of the response content
example 
<html> 
<body> 
<p> hello world</p>
</body>
</html> 
HTTP RESPONSE CODES: 
100 - 599
100 - 199: informational
200 - 299: successful
300 - 399: redirection
400 - 499: client error
500 - 599: server error

Other Internet Protocols: 

Dynamic Host Configuration Protocol (DHCP)
You've learned that computers need IP addresses to communicate with each other. When your computer connects to a network, the Dynamic Host Configuration Protocol or DHCP as it is commonly known, is used to assign your computer an IP address.
Your computer communicates over User Datagram Protocol (UDP) using the protocol with a type of server called a DHCP server. The server keeps track of computers on the network and their IP addresses. It will assign your computer an IP address and respond over the protocol to let it know which IP address to use. Once your computer has an IP address, it can communicate with other computers on the network.

Domain Name System (DNS)
Your computer needs a way to know with which IP address to communicate when you visit a website in your web browser, for example, meta.com. The Domain Name System Protocol, commonly known as DNS, provides this function. Your computer then checks with the DNS server associated with the domain name and then returns the correct IP address.

Internet Message Access Protocol (IMAP) 
Do you check your emails on your mobile or tablet device? Or maybe you use an email application on your computer?
Your device needs a way to download emails and manage your mailbox on the server storing your emails. This is the purpose of the Internet Message Access Protocol or IMAP.

Simple Mail Transfer Protocol (SMTP)
Now that your emails are on your device, you need a way to send emails. The Simple Mail Transfer Protocol, or SMTP, is used. It allows email clients to submit emails for sending via an SMTP server. You can also use it to receive emails from an email client, but IMAP is more commonly used.

Post Office Protocol (POP)
The Post Office Protocol (POP) is an older protocol used to download emails to an email client. The main difference in using POP instead of IMAP is that POP will delete the emails on the server once they have been downloaded to your local device. Although it is no longer commonly used in email clients, developers often use it to implement email automation as it is a more straightforward protocol than IMAP.

File Transfer Protocol (FTP) 
When running your websites and web applications on the Internet, you'll need a way to transfer the files from your local computer to the server they'll run on. The standard protocol used for this is the File Transfer Protocol or FTP. FTP allows you to list, send, receive and delete files on a server. Your server must run an FTP Server and you will need an FTP Client on your local machine. You'll learn more about these in a later course.

Secure Shell Protocol (SSH)
When you start working with servers, you'll also need a way to log in and interact with the computer remotely. The most common method of doing this is using the Secure Shell Protocol, commonly referred to as SSH. Using an SSH client allows you to connect to an SSH server running on a server to perform commands on the remote computer.
All data sent over SSH is encrypted. This means that third parties cannot understand the data transmitted. Only the sending and receiving computers can understand the data.

SSH File Transfer Protocol (SFTP) 
The data is transmitted insecurely when using the File Transfer Protocol. This means that third parties may understand the data that you are sending. This is not right if you transmit company files such as software and databases. To solve this, the SSH File Transfer Protocol, alternatively called the Secure File Transfer Protocol, can be used to transfer files over the SSH protocol. This ensures that the data is transmitted securely. Most FTP clients also support the SFTP protocol.

REST APIs: 
A REST API is an application programming interface (API) that conforms to the design principles of the representational state transfer (REST) architectural style.

IDE: An integrated development environment, or IDE, is software for building applications. This kinda of software application has many different features to help you as a developer.


