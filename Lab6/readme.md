## Your Name / Date
Natalie Tirabassi / 11/06/21
## Executive Summary 
This lab allowed me to go more in depth into the structure of the Internet and how it is organized and functions. Internet protocol addresses are important to every device that connects to the internet, and allows for data to be transferred between devices. However, it is important to have secure protocol and a secure web browers, and I was able to learn about the risks that could happen of my browser wasn't secured or if I was using a sketchy website. I was also able to design mock webpage through HTML, and it was exciting to something that is just letters and symbols as a real page on the internet. Finally, I learned all about the components of a URL, and how each of its important parts help the computer navigate to that specific page.

## Internet Architecture
### Internet Protocol
#### IP Address
Internet protocol (IP) addresses are unique numbers assigned to every computer or device that is connected to the Internet. They allow for the identification of the device and allow devices to communicate with one another. There are currently two versions of IP addresses in use - IPv4 and IPv6. IPv4 addresses are written as a string of four numbers separated by dots, while IPv6 are considerably longer and written using hexadecimal, with can fit more information into fewer digits. IPv6 is considered the next generation of IP addresses and will last much longer than IPv4 because it is larger.

#### ICANN
ICANN is the operator of Internet Assigned Numbers Authority (IANA). It contributes to the global internet by allocating IP address blocks to the five Regional Internet Registries (RIR) around the world. The RIRs then allocate smaller IP address blocks to network operators. This helps to distribute the IP addresses to individual internet connections around the globe. 

### TCP/IP
#### Responsibility of TCP/IP
TCP/IP stands for “Transmission Control Protocol / Internet Protocol.” It is a network protocol that defines the details of how data is sent and received through network communications hardware. It was developed for the purpose of connecting government computer systems to each other through a fault-tolerant network. The TCP/IP protocol creates a “virtual IP port,” and the network hardware and software is responsible for routing data in and out of each virtual IP port.

#### Client-Server Model and TCP/IP
In TCP/IP communications, the “client” is the computer that initiates the connection, and the “server” is that the computer listens for the connection. The client needs to know the IP Address of whatever server it wants to connect to, and also the port number that it wants to send and receive data through after a connection has been established. Once a connection though a TCP/IP port has been established between a TCP/IP client and a TCP/IP server, data can be sent in either direction across the network. 

#### Layers
Creating layered protocol stacks is important because each level of the stack performs a particular function and communicates with the levels above and below it, making the program more flexible. As a result, any of the layers can now be changed without affecting the other layers, which means that the entire protocol or application does not have to be changed.

#### Application Layer
The application layer provides protocols that allow software to send and receive information and present meaningful data to users. Some examples of application layer protocols are the Hypertext Transfer Protocol (HTTP), File Transfer Protocol (FTP), Post Office Protocol (POP), Simple Mail Transfer Protocol (SMTP), and Domain Name System (DNS).
## Internet Security
### HTTP and Client-Server Model
HTTP stands for Hypertext Transfer Protocol and is the protocol used for viewing web pages on the Internet. The information that is transferred over the internet is the clear text that is exchanged between the computer and the web server. HTTP supports the client-server model because the computer acts as the client that sends the information to the receiving web server.

### Protocols for Secure HTTP
HTTPS stands for Secure Hypertext Transfer Protocol. It encrypts the data that is being retrieved by HTTP. This ensures that all the data that is being transferred over the internet is secure by using encryption algorithms to scramble the data. SSL is one of the protocols that ensures security on the internet by using public key encryption through a form of certificates. The other protocol is TLS, is the successor to SSL. Like SSL, it authenticates the server, client, and encrypts the data.

## Securing your Web Browser
### Reasons to Secure Browser
Not securing a web browser can lead to many computer problems such as spyware being installed or hackers taking control of the computer. Because web browsers are used so frequently, it is important to configure them securely. There is an increasing threat from software attacks that take advantage of vulnerable web browsers, through the use of compromised or malicious websites, so it is smart to secure your browser before that happens.
### Risk Explained
ActiveX allows applications or parts of applications to be utilized by the web browser. This gives extra functionality to web browsing, but also poses a few risks if not properly implemented. One of the risks is that it greatly increases the attack surface of a system. Installing any Windows application introduces the possibility of new ActiveX controls being installed, which can lead to an attacker taking control of computer. 
## Internet Programming
### World Wide Web Consortium
Tim Berners-Lee invented the World Wide Web in 1989. He is also the director of the World Wide Web Consortium (W3C), which is a Web standards organization that develops specifications, guidelines, software, and tools. Tim Berners-Lee founded the W3C to further the potential of the Web to benefit humanity.
Web Design and Applications is important because it involves the standards for building and rendering Web pages, and without it, there would be no internet interface. It includes HTML and CSS, which are the fundamental technologies for building webpages. It also includes Graphics, such as pngs and svg vector format. Another important standard is Accessibility, which helps authors create content that is accessible to people with disabilities. 
### HTML5 and CSS
HTML5 is the latest HTML standard markup language for creating Web pages. It describes the structure of the page and tells the browser how to display the content. CSS stands for Cascading Style Sheets and is used to format the layout of the webpage. It allows a user to control the color, font, sizing, spacing, positioning, and displays. On my webpage I used HTML5 to create the basic structure of the page - the heading, paragraph, and website link. I then used CSS to add a background color, change the color of the heading, and add a colored border around the paragraph. This helped add more visual appeal to the Web page.
### HTML and XML
XML is a software and hardware independent tool for storing and transporting data. It is a markup language like HTML, but it does not do anything. It was designed to carry data - with focus on what data is, whereas HTML was designed to display data - with focus on how the data looks. XML also does not use predefined taxes like HTML does. With XML, the author must define both the tags and the document structure. 
## Components of a URL
Every URL begins with a scheme. A scheme tells the browser what type of address it is in order for the browser to connect to it correctly. An example of a scheme is http.
The domain name is the next part of a web address. Each segment of the domain name separated by a period is a domain, and you can learn things about the site from the domains. An example would be www.amazon.com, where there are three domains.
The domain on the right is the top-level domain, which gives you more general information on what kind of site it is. An example of this is .edu, which tells you that the site is an education site.
The default page is when no file path is provided, only a domain name. The browser will then load to a default page, which will help you navigate to other pages.
Some URLs include a string of characters after the path called the parameters. This is the result of a search, and can confusing, but it is critical information to the server.
Finally, the anchor loads a specific location on a page. It usually begins with a hashtags and is used to direct your browser to a specific part of a very long page, like a bookmark.
## Conclusion
In conclusion, communication on the Internet is not as simple as it seems. Without safe and secure protocols, data could easily be stolen or tracked. It is important to always make sure to have a secure web browsers and to stay away from sites that are not protected. It was also interesting to learn about Tim-Berners Lee and the World Wide Web Consortium, which develops the guidelines and tools for safe internet access. This lab showed me the different components that go into ensuring that users get the best and safest experience from the Web, and now I will always make sure to be conscious of my internet browsing to protect my data.
