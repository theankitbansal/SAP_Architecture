# SAP_Architecture
Detailed description of SAP architecture.


SAP architecture is a set of principles, patterns and best practices that outline the architecture of an organization’s SAP environment. By using it, organizations can build a more secure and reliable platform for running business processes across their organization. SAP is a software-as-a-service solution, which means it’s cloud-based. This has implications for your SAP architecture. Your users will be accessing SAP via a web browser; they won’t be installing software on their desktops and laptops like they would with desktop applications.
That means you need to think about your SAP architecture beyond the technical components necessary to run SAP itself. You need to think about how to structure your system so that it is easily managed, supported and updated over time while remaining secure and reliable at the same time. This article covers everything you need to know about SAP architecture

What is SAP?
SAP is a global leader in providing software solutions that enable organizations to process data efficiently and communicate information effectively. SAP was founded in 1972 and has grown from a small, five-person program development firm to a multinational corporation with more than 105,000 employees worldwide since then. Walldorf, Germany is SAP’s headquarters, where it’s run by more than 100,000 employees worldwide. SAP stands for “Systems Application Program.” The SAP acronym is a widely used shorthand term for software, computer programs, and applications that all fall under the umbrella of SAP systems. Some examples of applications that fall under the SAP acronym are accounting software, inventory management software, database management software and web application software. To be more specific, SAP is a business-to-business (B2B) application development platform which allows organizations to manage and optimize their business processes in order to increase productivity and profitability. By providing organizations with real-time access to critical information from multiple sources, such as financial data, inventory records and customer profiles, SAP systems enable them to effectively manage their operations. By streamlining business processes and reducing operational costs, SAP systems can help companies achieve greater growth and profitability.

SAP Architecture and Different SAP Layers
The SAP System Architecture includes Presentation, Application, and Database layers. Each of these programmes operates on its own. In contrast, MiniSAP has all the components in one machine. We may distribute the whole system across diverse machines or it may also be on one machine like ours. The database and the application server can be on the same machine if we want to get an idea of the SAP system architecture in greater depth. In addition to these application servers, other applications are run on separate machines. To better grasp the SAP architecture, let’s look at these three elements in more detail.

The SAP System Architecture consists of the Presentation, Application, and Database layers.

![SAP-Architecture-and-different-SAP-layers-800x682](https://user-images.githubusercontent.com/81725794/178094266-4a92fff8-8f20-4749-8203-9473c705270f.png)

Presentation Layer

The presentation layer is responsible for the user experience and for making sure that the SAP system is responsive and easy to interact with. The presentation layer does not have any knowledge of the underlying data stored in the data layer. The data layer holds all the data that is being stored in the SAP system. The data layer is the realm where all the business rules and processes take place. The data layer exists between the presentation layer and the application server. When you connect to the application server and start to do work, the application server, which is the realm where all the logic happens, knows nothing about the data layer.
![Presentation-Layer](https://user-images.githubusercontent.com/81725794/178094293-b8368eb8-10ea-4363-ac21-9a89bef5a776.png)


Application Layer

This layer of the architecture is responsible for receiving and parsing data, before it can be used by any part of the organization. This layer is also responsible for providing data with in the correct format for each application. The last responsibility of the application layer is to ensure that the data is secure, before it is sent to the next layer. This layer of the architecture is a critical component to the success of your digital transformation. The work process must be carried out by a user who is registered in the system. For this reason, we define the work process as a user of the system. The work process will register itself in the database, and when it is required to create a new record in the system, this is done by the work process. The work process can be created by the system administrator through the SAP system. In the case of the SAP system, this can be done by setting the role of the user to a specific value. What happens when you do this is that the SAP system will create a new user in the database system. This user will register itself in the database, and when the system needs to create a new record, the user can do this. The user will create the work process, and when the system requires the work process to create a new record, the user will create the process.

Database Layer

The system architecture is what defines how your SAP system is set up. If you were setting up a new company, you would choose a system architecture based on the type of business you want to start. For example, a manufacturer of motorcycles and scooters would be best served by a system architecture that focuses on production and inventory. A hotel would do best with a system architecture that focuses on customer relations. Once you have chosen the setting for your new company, you need to choose the SAP system architecture. The application and database layers receive information about actions performed on the presentation layer and then query the results. As a result, you can see the results of processing on the presentation layer.
![Database-Layer-800x800](https://user-images.githubusercontent.com/81725794/178647363-5c59b91f-7b45-4229-845e-bd3cdc5426f9.png)

SAP Architecture Components

The SAP R/3 3-tier Architecture is a popular application server topology for developing large-scale enterprise applications. With the increased use of web-based technologies and the ever-increasing importance of user experience, application servers are being replaced by web-based applications. However, there are certain situations where the usage of web-based applications is not possible, due to the size of the system, regulatory compliance, or other business reasons. In such cases, the usage of 3-tier application servers is unavoidable. The most common application server topology is the SAP R/3 3-tier Architecture.
![SAP-Architecture-Components-800x642](https://user-images.githubusercontent.com/81725794/178647409-65289d62-d70b-4fd1-96eb-10822b8b428d.png)

1. The role of the Message Server is to handle communication between ABAP Dispatchers that are distributed across the system.
2. In this Dispatcher queue, process work of several different types is stored.
3. Work processes are allocated by the dispatcher.
4. Gateway provides access between SAP systems and external systems.
5. Each R/3 dialog step is separately executed by ABAP-Work processes.

The following describes types of work processes:
![SAP-Architecture-Components2-800x485](https://user-images.githubusercontent.com/81725794/178647606-90e33959-120b-4ee7-b13b-05c2dee00665.png)

1. An ICM work process can communicate with an ABAP work process via a memory-pipe.
2. The java dispatcher and server processes are handled by the Message Server. Within the java runtime environment, the Message Server enables communication.
3. A server process is configured by a Java application program to handle logical locks. The queue server handles them.
4. The central services are used to manage locks and transmit messages and data when working in a Java cluster. Java clusters are sets of cooperating processes that create a dependable system. A group of resources, such as memory, work processes, and so on, is known as an instance.
5. The Dispatcher handles the incoming client requests and dispatches them to the correct server process.
6. To install J2EE components using SDM, you must first download and install Software Deployment Manager.
7. A high quantity of requests can be handled by a Java Server Process.
8. Threading refers to the method of processing multiple items at once in the background.
9. SAP can be accessed from a browser by entering the system’s URL. Because of this, ICM can also be used for communication.


When using the ABAP and Java systems, we use another component called a JCO to handle communication with the abap dispatchers. ABP+Java uses Java dispatchers to handle communication.


