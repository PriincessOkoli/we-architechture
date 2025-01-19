---

How the web works and web protocols and how popular services are implemented on the web

---

Web architecture is the conceptual structure of the World Wide Web. The WWW or internet is a constantly changing medium that enables communication between different users and the technical interaction (interoperability) between different systems and subsystems. The basis for this is different components and data formats, which are usually arranged in tiers and build on each other. Overall, they form the infrastructure of the internet, which is made possible by the three core components of data transmission protocols (TCP/IP, HTTP, HTTPS), representation formats (HTML, CSS, XML), and addressing standards (URI, URL). The term web architecture should be distinguished from the terms website architecture and information architecture.
Origin of web architecture
The world wide web is a concept that was realized in the 1990s so that people and machines could communicate with each other within a certain space. It is used to exchange, distribute, and share information in a network. At that time, the web consisted predominantly of static websites based on HTML, in other words, hypertexts that can be retrieved by a browser. Dynamic websites and distributed web services were added later.
How Does Web Application Architecture Work?
https://miro.medium.com/v2/resize:fit:4800/format:webp/1*4Uh_egw1TnNkQ71ZuFqpdw.png
All the web applications run on the client-side and the server-side. When a user makes a request there are mainly two programs run on both sides.
Code that runs in the browser and works as per the inputs of the user.
Code in the server which responds to the HTTP requests

While working on the web application, a web developer decides the functions of the code on the server and the functions of the code on the browser. They also define how these two will function in relation to each other. Server-side code can be written using the languages Python, JavaScript, C#, PHP, Ruby on Rails, etc. Any code can have the capability to run on the server if it can respond to HTTP requests. The server-side code is mainly responsible for creating the page which the user has requested. It also stores different types of data such as user profiles, tweets, pages, etc. Server-side code can not be seen by the end-user (except within a rare malfunction)
Client-side languages include the combination of HTML, CSS, and JavaScript. This code is parsed by the browser, and it can be seen as well as edited by the user. Only through HTTP requests, client-side code can communicate with the server. Also, it cannot read files off a server directly.
Web Application Architecture Components
Web application architecture works on various components. These components can be divided into two areas.
1. User Interface App Components: As the name suggests this category is much more related to the user interface/experience. In this category, the role of the web page is related to the display, dashboards, logs, notifications, statistics, configuration settings, etc and it has nothing to do with the functionality or working of the web application.
2. Structural Components: This category is mainly concerned with the functionality of the web application with which a user interacts, the control, and the database storage. As the name suggests it is much more about the structural part of the web application. This structural part comprises…
The web browser or client
The web application server
The database server

What is Internet Protocol?
The word protocol has been mentioned here a few time, but what does it actually mean? Internet Protocol (IP) is a set of rules that allows devices to communicate with each other over the Internet. It is like the address system used for sending data. Every device connected to the internet has a unique IP address that helps data know where to go and where it is coming from. An IP address represents an Internet Protocol address. A unique address that identifies the device over the network. It is almost like a set of rules governing the structure of data sent over the Internet or through a local network. Examples of IP; HTTP/HTTPs, HTML AND DNS
HTTP(Hyper Text Transfer Protocol)
HTTP protocol is used to transfer hypertexts over the internet and it is defined by the www(world wide web) for information transfer. This protocol defines how the information needs to be formatted and transmitted. And, it also defines the various actions the web browsers should take in response to the calls made to access a particular web page. Whenever a user opens their web browser, the user will indirectly use HTTP as this is the protocol that is being used to share text, images, and other multimedia files on the WWW. 
HTTPS is an extension of the Hypertext Transfer Protocol (HTTP). It is used for secure communication over a computer network with the SSL/TLS protocol for encryption and authentication.
https://miro.medium.com/v2/resize:fit:1400/format:webp/0*I72Z43wFsy1VJmDz.gif

DNS(Domain Name System)
The DNS is a core network service that allows devices to communicate much like we do on our smart phones. Generally we don't memorize phone numbers any more, we just save them under names in our Contacts app.
DNS works the same way, where we assign an IP address to a name. If a device doesn't know the IP address or name of a device with which it needs to communicate, it will find that information from DNS servers either on the local network or on the Internet.
HTML
HTML stands for Hypertext Markup Language. It's a text-based language that defines the structure and content of web pages. HTML is the foundation of the World Wide Web.
How HTML works
HTML uses tags to provide instructions to web browsers on how to display content.
Tags are special elements that set off content from other text in a document.
Tags are surrounded by the less than (<) and greater than (>) symbols.
HTML elements can be written in uppercase, lowercase, or a mixture.

HTML code segment/syntax
https://miro.medium.com/v2/resize:fit:996/format:webp/0*TUkinAZ-LjgGXjQa.jpeg

Popular Services and how they are implemented on the internet
E-commerce (Electronic commerce)
Electronic commerce, or e-commerce, is the buying and selling of goods and services over the internet. E-commerce can be conducted on computers, tablets, smartphones, and other smart devices. Nearly every imaginable product and service is now available through e-commerce, and it has upended how many companies and entire industries do business.

https://miro.medium.com/v2/resize:fit:1400/format:webp/0*7AtpprQddtHt_HAG.png

E-commerce, or electronic commerce, is implemented on the internet through a combination of technologies, platforms, and processes that facilitate buying and selling goods or services online. At its core, e-commerce relies on websites or mobile apps as digital storefronts where businesses showcase their products or services to customers. These platforms are powered by backend systems like databases to store product information, user accounts, and order details, while frontend interfaces ensure smooth navigation and user experience.
The process begins when a customer visits an e-commerce site, browses products, and adds items to a virtual shopping cart. Secure payment gateways, such as PayPal or Stripe, enable users to complete transactions using credit cards, digital wallets, or other payment methods, ensuring confidentiality and protection against fraud. Technologies like SSL encryption safeguard sensitive data during transactions, creating a trusted environment for customers. Once a purchase is made, inventory management systems update stock levels, and logistics tools coordinate order fulfillment, including shipping and tracking.
Modern e-commerce also leverages artificial intelligence (AI) and data analytics to enhance the shopping experience. Personalized recommendations, chatbots for customer service, and targeted advertisements are some of the ways businesses use data to engage customers. Additionally, cloud computing ensures scalability, allowing businesses to handle large traffic volumes, especially during sales or promotions. With mobile optimization and omnichannel strategies, e-commerce now seamlessly integrates across devices and platforms, making online shopping more convenient than ever. This blend of innovative technology and user-centric design has revolutionized commerce, enabling businesses to reach global audiences with just a few clicks.

In conclusion, the internet and its protocols serve as the backbone of modern communication, powering technologies and services that shape our daily lives. Web architecture, with its layered structure and foundational protocols like HTTP, HTTPS, and DNS, ensures seamless connectivity and functionality across devices and platforms. Popular services like e-commerce exemplify the internet's transformative impact, combining backend technologies, user-friendly interfaces, and advanced tools like AI to deliver efficient and personalized experiences. As the web continues to evolve, it highlights the importance of understanding its architecture and protocols, enabling developers, businesses, and users to harness its full potential while adapting to an increasingly interconnected world.