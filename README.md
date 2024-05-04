# cloud_foundations <a id="top"></a>
Dive into foundational knowledge spanning cloud, data science and web development.

### Table of content 
|chapter|Description|
|:-----:|:----------|
|[ch.01](#ch.01)| Introduction to computing |
|[ch.02](#ch.02)| Basic Computing Concepts |

### <a id="ch.01"></a> ch. 01 - Introduction to Computing 
------------------[to the top ↑](#top)------------------

*"Technology is not just a tool. It's a part of our lives and shapes our digital world every day."* -Jan Koum, co-founder of WhatsApp.
<br>
<br>
In today's world, we can use technology to extend our activities beyond physical, geographical and time limits. 

**Basic computing terminology**
- An application is a set of instructions that runs on a computer to perform a specific task.
- A computer program is written code in a programming language.
- Computer programs are generally called software.

<p align="center"><img src="img/basic_computer_terminology.png"></p>

**Type of applications**
*Application run on different types of devices and are accessed in different ways.*
- Web application; Runs in a `web server` or `application server` and is accessed from a web browser
- Mobile app; Runs in and is accessed from a `mobile device`
- Desktop application; Runs in and is accessed from a `desktop computer`
- Internet of Things (IoT) application; Runs in and is accessed from an appliance or `specialized device that is connected to the internet`

**Components inside a computer**
*Hardware*
- Motherboard
- Central Processing Unit (CPU)
- Memory / Random Access Memory (RAM)
- Storage Drive
- Network Card
- Graphic Card
- Power Supply

*Software*
- Operating System (OS)
- Application

In summary, applications, computer and networks run the digital world. An application is a computer program. It is a set of instruction that a computer runs to perform a specific task. A computer's hardware consits of its physical components (as mentioned above) and the software consists of the program that run on it (as mentioned above).

### <a id="ch.02"></a> ch. 02 - Basic Computing Concepts
------------------[to the top ↑](#top)------------------

#### Servers and data centers
<p>What is a server? A server serves as a specialized computer designed to furnish data or services to other computer across a network. Its fundamental role is to respond to requests initiated by client computers, facilitating seamless communication and data exchange. Distinguished by its hardware specifications, servers typically feature expanded memory capacity and support for multiple CPUs, enabling them to handle substantial workloads efficiently. Moreover, they incorporate redundancy mechanism such as duplicate power supplies and network interfaces to ensure continuous operation. Often compact in design, servers are optimized for rack-mounted deployment in data centers. Examples of servers types span various functions, including web servers for hosting websites, database servers for managing data storage and retrieval, and mail servers for facilitating email communication. These exemplify the divers roles serves fulfill in enabling and enhancing networked computing environments.</p>

<p align="center"><img src="img/Client&Server-Eg.png"></p>

Running a web application is an example use case for servers. A web application is typically deployed to a web server, which is responsible for directing client requests to it. A web application usually stores its application data on a database server. The database server runs a special type of software that’s called a database management system (DBMS). The DBMS controls the organization, security, and access of the data.Examples of a DBMS are MySQL, an open-source relational database management system; and Oracle, a relational DBMS that Oracle Corporation owns and offers. The following list shows the flow of information in the example:

1. The user opens a browser on a client machine and enters the address of the web 
application’s homepage. This address is called its home Uniform Resource Locator 
(URL) (for example, https://anycompanywebapp.com).
2. The web server receives the client request and directs it to the appropriate web 
application.
3. The web application sends a request to the database server to access its 
application data.
4. The database server returns the requested data to the web application.
5. The web application builds the response webpage and passes it to the web server, 
which returns the page to the client browser.

**Where does server reside**

Servers reside in a data center. A data center is a physical location that is used to host computer systems and associated components such as networks, storage devices, and power supplies. Data centers are designed to be secure and to provide an ideal climate for the contained equipment to operate. They must protect the equipment from many types of failures and accidents, including power losses and fire.

**Who owns data center**

**Traditional on-premise model**

Traditionally, organizations owned their data centers. The equipment was on premises at a location that the company owned. If you follow this model, you are the one who buys, installs, configures, and manages all the hardware and software in your own facility. You are responsible for installation, maintenance, and numerous other costs. You also must hire the staff who are responsible for the maintenance of the hardware, software, and the facility itself.

**Cloud model**

The cloud model provides another option: a cloud services provider buys the hardware and infrastructure software in their own facility. They manage and maintain it with their own personnel. You bring your application or workload to run on their servers and pay for the services that they offer.

#### Virtual Machine

**What is virtual machine?**

A virtual machine (VM) is a software-based computer.

<p align="center"><img src="img/virtualization.png"></p>


