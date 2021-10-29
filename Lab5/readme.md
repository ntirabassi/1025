## Your Name / Date

## Executive Summary 
Include your executive summary here...

## Lucidchart
Lucidchart is designed in order for users to create flowcharts to specific steps in a process. I found the website inviting and easy to use. The editing tools are extremely user-friendly with options for colors, sizes, fonts, and many different types of shapes to use in your flowchart. There is also many templates from users to choose from if they don’t want to create one from scratch. I especially liked how i was able to click and drag arrows out from the different shapes to connect with others. Their tutorials are short and straight to point, and overall my experience with Lucidchart was positive.
## Introduction to Networking

### Data Transmission
#### Packet:
A packet is the fundamental unit of data transmitted over the Internet. When a host intends to send a message to another host, the message is broken down into smaller pieces called packets.
#### Packet-Switching:
Packet switching is technology that allows packets of data to be routed based on destination address. When a message’s packets are sent on the Internet, routers try to find the optimal route for each packet. After the packets arrive they are re-assembled into the original message for the recipient.
#### IP Address:
IP Address is the unique identifying number that every device on the internet is assigned. IP stands for Internet Protocol, and an example of an IP address might be 54.239.26.214 for amazon.com.
#### DNS:
DNS stand for “domain name server or system.” It is the directory of IP addresses (websites) on the Internet. A request to access a host with a domain name is given, and a DNS server returns the IP address, allowing for proper routing.
#### Protocol:
Protocol is the set of rules that allow devices to communicate. For example, File Transfer Protocol are the communication rules for transferring files from one host to another.
### Networking Hardware
#### Switch vs. Hub
The purpose of a hub is to connect all of the devices together on a internal network by means of multiple ports. A hub is considered to be unintelligent because it doesn’t filter any data or has any intelligence about where the data is supposed to be sent. Because of this, a hub creates security concerns and unnecessary traffic on the network. A switch also has multiple ports like a hub, but a switch is intelligent because it can learn the physical address of the devices that are connected to it. When a data packet is sent to a switch, it’s only directed to the intended port, and the intended device. Switches are preferred over hubs because they reduce unnecessary traffic.
#### Router vs. Switch and Hub
Hubs and switches are used to exchange data within a local area network, not an outside network. A router is more beneficial because it is able to read IP addresses, which allows for data exchange with an outside network. It routes the data from one network to another based on the IP addresses. Hubs and switches are used to create networks, while routers are used to connect networks.
### Network Topologies
#### Single point of Failure
A single point of failure is when a specific area on a network fails, which results in the entire network going down. In a star topology, all computers are connected to a central wiring point, like a hub or switch. If the central hub or switch fails, all the computers on that central point would be affected. In a ring topology, each computer is connected to each other a closed loop. If just one of the computers fails or if there was a break in the data, the entire data flow would be broken. The bus topology is where each device is connected to a single cable using special connectors and terminators. If a computer or terminator is removed, there would be an open end and the data flow would be disrupted. 
#### Infrastrucutre vs. Wireless Mesh
Infrastructure topology uses a combination of wired and wireless devices. The computers are connected by wires to a switch, which is then connected by a wire to a wireless access point for tablets, phones, and laptops. Infrastructure topology is not limited to a single wireless access point, but rather it can have multiple access point depending on the needs of the network.
A wireless mesh is where devices are wireless interconnected with each other. I think it is better than infrastructure topology because it allows for multiple wireless access points throughout a building, because the access points can be connected to each other wirelessly. 

### Network Design
The topology I have created in my network design is the infrastructure topology, in which the two computers and the wireless router are connected to the access gateway by wires. The printer then connects to the wireless router through its signal. 
### NSA/CSS
NSA Cybersecurity prevents and eliminates threat to U.S. National Security by focusing on the Defense Industrial Base, improving weapons’ security, and partnering with allies, private industries, academics, and researchers to strengthen awareness to advance cybersecurity. It leads the U.S. Government in cryptology and enables computer network operations to gain an advantage. It provides foreign signals intelligence to the nation’s policymakers and military - critical information our leaders need to defend our country. 
## Cybersecurity and Encryption

### Information Systems Security

#### Security Triad
Amazon’s online chat is a live chat that is meant for a customer service representative to help customers with any questions they might have. Customers need to trust that Amazon is able to keep the chat private and protect their information from outsiders, especially if they need to enter their shipping address or payment information into the chat. Integrity of the information is also important, such as when the representative says they have deposited a refund into the customer’s account, and the customer is able to trust them to do that. Finally, Amazon’s online chat must be available, meaning that it must be present to people all over the world at all hours of the day, and work on all kinds of devices and be accessible from anywhere. 
#### Authentication
Three daily tasks that require authentication are putting in your password into your computer, using your key to get into your apartment, and entering your pin to unlock your phone. These ways can all be strengthen by conversion to multi-factor authentication. For example, when you go to log into your computer, you can put in your password and also an additional PIN number. At your apartment, there could be one key for the main entrance, and then a separate key for your apartment. Your phone could ask for your PIN number and also scan your face or fingerprint for extra security.
#### ACL and RBAC
Access control determines which users are authorized to read, modify, add, and/or delete information. An ACL (Access Control List) is a list of users that have specific permissions assigned to them such as  read, write, delete, or add. ACLs are simple to understand and maintain, but each information resource is managed separately, so it would be difficult to add or remove a user to large set of resources. As the number of users and resources increase, they become harder to maintain. Role-based access control, or RBAC, is an improved method that assigns user to roles and then those roles are assigned the access, rather than giving specific users right to an information resource. This simplifies administration and improves security.
#### Ciphertext, Public Key and Private Key
In public key encryption, two keys are used, a public key and a private key. To send an encrypted message, you obtain the public key, encode the message, and send it. The ciphered text is transmitted through the communication channel and the receiver of the message uses their private key to decode it. The private key is necessary in order to decrypt a message sent with the public key.
#### Public Key Cryptography
Public key encryption is important because it ensures security and confidentiality. Users have private communication through exchanging encryption keys. Two users start with a public key that is easy to decipher in one direction and hard in the opposite, which allows only the users with the private key access to the information.
### Cryptography
#### Encryption
A Caesar cipher is a simple method of encoding messages by using a substation method of shifting over letters of the alphabet. The message “cryptology is a growing field” is encoded into “dszqupmphz jt b hspxjoh gifme” because each letter has been shifted over once. 
#### Frequency Fingerprint
As I type a message, the frequency fingerprint encoder shows the most to the least common letters in the message. This is helpful because it shows me what letters I tend to type the most. The chart shows what the most common letters are in the English language, so in a different language it would show a different chart of the common letters from that language, such as x in Mandarin beingT much more common that it is in English.
#### Polyalphabetic Cipher
A polyalphabetic cipher uses a flatter distribution of letters, or a lighter fingerprint. This cipher is based on substitution, and uses a secret shift word to allow for only the parties that have the word to decipher it.
#### Polyalphabetic Example
The phrase “good morning” using the shift word “peanut” turns in to the phrase “qjnp rubihzl” The shift word and the message is converted into numbers according to their place in the alphabet. Each letter is then shifted according to the number below. This process uses multiple shifts instead of a single shift in order to confuse a code interceptor.
#### Brute-Force
A brute-force attack tries every possible decryption key for a cipher. A cryptoanalyst is able to guess one key, decrypt the cipher text with that key, and then move on to the next key if they haven’t found the secret message. These type of attacks use trial and error to crack codes by testing a wide variety of combinations until they find the right one.
## Conclusion
Include your professional conclusion here...

