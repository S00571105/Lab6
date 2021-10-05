## Joyce Stonebraker/10.10.21

## Executive Summary 
Section six explored protocols that support communication of the internet, ICANN, TCP/ICP,client server modules, types of TCP/ICP protocol suite and stacks.  In addition internet security of HTTP, HTTPS, Web Browser and more security was discussed. Along with describing internet programming methodologies,URL  and allowed practice creating a web page with HTML and CSS.

## Internet Architecture
Refers to the internet architecture such as protocol and IP addresses.

### Internet Protocol
IP Address- IP stands for Internet Protocol. An IP address is the unique numbers assigned to every computer or device that is connected to the internet .Currently under the IPv4 all addresses have been allocated that is the reason we need IPv6 that has a bigger space for addresses.  The difference between IPv4 and IPv 6 is: IPv4 adresses are in numbers whereby IPv6 addresses are in hexadecimal and IPv6 with it’s large space is anticipated to last thirty plus years.

#### IP Address
An IP address is the unique numbers assigned to every computer or device that is connected to the internet .Currently under the IPv4 all addresses have been allocated that is the reason we need IPv6 that has a bigger space for addresses.  The difference between IPv4 and IPv 6 is: IPv4 adresses are in numbers whereby IPv6 addresses are in hexadecimal and IPv6 with it’s large space is anticipated to last thirty plus years.

#### ICANN
ICANN stands for Internet Corporation for Assigned Numbers and Names. And the organization contributes to the global internet by ensuring  a stable and unified global Internet. To reach another person on the Internet you have to type an address into your computer—a name or a number. That address has to be unique so computers know where to find each other. ICANN coordinates these unique identifiers across the world. Without that coordination we wouldn’t have one global Internet. ICANN was formed in 1998. It is a not-for-profit public-benefit corporation with participants from around the world dedicated to keeping the Internet secure, stable and interoperable. It promotes competition and develops policy on the Internet’s unique identifiers. ICANN doesn’t control content on the Internet. It cannot stop spam and it doesn’t deal with access to the Internet. But through its coordination role of the Internet’s naming system, it does have an important impact on the expansion and evolution of the Internet. 

### TCP/IP
TCP/IP stands for Transmission Control Protocol/Internet Protocol 

#### Responsibility of TCP/IP
TCP/IP stands for Transmission Control Protocol/Internet Protocol and it basically the network protocol that defines the details of how data is sent and received with the network adapters, hubs, switches, routers and other network communication. The TCP/ICP basically work like a telephone call where someone is initiating a call. Thus the basic responsibility of  TCP/ICP is sending data packets from one computer to another.

#### Client-Server Model and TCP/IP
The client server models that applies to TCP/ICP are that basically the client/server architecture typically that consists of a collection of computers connected by a communication network. The client/server architecture requires clients to communicate with other servers and that is where the TCP/ICP comes in to play it provides standardization ways for the clients and servers to exchange data packets

#### Layers- Application Layer
There are four types of TCP/ICP protocol suite stacks and protocols. These are application, transport, networking and data link and physical. The application layer contains HTTP-the workhorse of the web, FTP, POP3, SMTP and SNMP.After reviewing the “The TCP/ICP Model and Protocol Suite Explained” in reviewing the section of article aligning the post office with protocol stacks, the layers importance to changing technology was noted to be important due to the fact that is the advantage of splitting layers/tasks  into different layers/tasks the layers/tasks can change without affecting the other layers. Even though this example was very simple it illustrated some important points of that are crucial in understanding networking protocols.The type of applications that run on the “application” layer  is basically the application will choose which transmission protocol to use based on their function i.e. HTTP,POP3, IMAP4,SMTP and more use of the TCP. So in summary the TCP/ICP is a collection of protocols that are used on the internet. And it is named after the two main protocols (TCP and ICP) and uses a four layer networking module i.e. application, transport, networking and data link and physical

## Internet Security
Internet security is addressed by HTTP and Client Server Model and protocols for Secure HTP

### HTTP and Client-Server Model
The HTTP (hypertext transfer protocol) is the Web’s application layer protocol works on the Client-Server technology and it supports the client model server. In the client server architecture when the client computer sends a request for data to the server via the internet, the server accepts the requested process and delivers the data packet requested back to the client. HTTP is transferred in clear text to a public network and is available to hackers if they want it. That is why HTTPS (Hypertext Transfer Protocol Secure) was developed. HTTPS encrypts the data being transferred, uses encryption alogorithms.The browser with show the HTTPS and a pad lock to show user the information will be passed securely.

### Protocols for Secure HTTP
The HTTPS uses an encryption protocol to encrypt communications. The protocol is called Transport Layer Security (TLS), although formerly it was known as Secure Sockets Layer (SSL). This protocol secures communications by using what's known as an asymmetric public key infrastructure. Many organizations automatically have https instead of standard.

## Securing your Web Browser
Due to the explosion of the Internet, attacking the vulnerabilities in Web browsers has become one of the most popular ways for intruders to take over your computer, steal your identity and passwords, spy on your surfing habits, and in the worst cases, destroy your computer altogether.

### Reasons to Secure Browser
The reason to secure are A Web browser is because it is one of the most frequently used software components on your PC. Therefore, it makes perfect sense to practice good Web browser security. As a general rule, most Web browsers that accompany your PC's operating system come without the security features set up. It is left to the user to set up the configuration to create a secure Web surfing environment.Failing to secure your Web browser can encourage unscrupulous hackers to easily take control of your PC. By not securing your Web browser, you are opening up your PC to spyware and adware programs, viruses, and other attacks with malicious intent.

### Risk Explained
The risks identified in the article are: ActiveX extra functionality may introduce more severe vulnerabilities, Java due with its JVM with Java applelets that   excecute code may also increase vulnerabilities, Plug-ins may contain programming flaws that increase vulnerability and Cookies may identify users that are not cleared are just some of the risks explained in the article. So with all these risks such as the Cookies risk identified in the article it is important to understand about Cookies such as date of cleared, information about sites, persistent Cookies that remain on computer for a longer period. So with that said it is important to regularly clear Cookies from your computer.

## Internet Programming
Internet programming with the World Web consortium has assisted in making the web more standardized.

### World Wide Web Consortium
The World Wide Web Consortium mission is to lead the World Wide Web to its full potential by developing protocols and guidelines that ensure the long-term growth of  the Web.Tim Berners-Lee, inventor of the World Wide Web, he leads the World Wide Web Consortium with key individuals and staff. This group invited experts form the public to write standards for the W3C to ensure standardization of the Web technologies. The following standard Web of Devices is important due to the fact it enables Web access anywhere, anytime, using any devices. This standard includes the use of the Web from mobile phones and other mobile devices as well as use of Web technology in consumer electronics, printers, interactive television, and even automobiles.

### HTML5 and CSS
The purpose of CSS is to provide Web developers with a standard way to define, apply, and manage sets of style characteristics. CSS provides these capabilities through a technical model based on a hierarchical scope of effect, the separation of style from content, and a well-defined set of published standards. And the purpose of CSS is the language for describing the presentation of Web pages, including colors, layout, and fonts. It allows one to adapt the presentation to different types of devices, such as large screens, small screens, or printers. CSS is independent of HTML and can be used with any XML-based markup language. HTML and CSS work together by making use of the CSS capabilities it needs to be linked within the HTML content so that style can be added to the website. CSS will tell the browser how to display the existing HTML. CSS can be compared to adding personal style to the body. When you link CSS to HTML, it's like dressing up the body.

### HTML and XML
XML stands for eXtensible Markup language. XML is a markup language like HTML, XML is designed to store and transport data, to be self-descriptive and is one of W3C recommendations. (XML became a W3C Recommendation as early as in February 1998). XML differs from HTML by the fact XML was designed to carry data-with a focus on what data is, HTML was designed to display data-with the focus on how data looks and XML tags are not predefined like HTML tags are.XML also simplifies: data sharing, data transport, platform changes and data availability.

## Components of a URL
The components of URL for HTTP or HTTPS is made up of three or four  or five components: a scheme-that identifies the protocol to be used to access the resource on the Internet, a domain name - identifies the domain that holds the resource (top level domain is the org), a path- identifies the specific resource in the domain that the web client wants to access. In addition some URL’s include a string of characters called the parameter string that is a critical piece of information for the server. And some have an anchor that directs your browser to go to a special part of a page. The top level domain may also give you additional information for example .gov says it is a government site.

## Conclusion
Section six was very interesting it  explored protocols that support communication of the internet, ICANN, TCP/ICP, client server modules, types of TCP/ICP protocol suite and stacks.  In addition internet security of HTTP, HTTPS, Web Browser and more security was discussed. Along with describing internet programming methodologies, URL  and allowed practice creating a web page with HTML and CSS.
