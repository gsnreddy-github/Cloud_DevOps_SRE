## Shell script interview questions
* how do you delete last 30 days logs in tomcat by using shell script?

Deleting last 30 days logs in Tomcat using shell script
Use find command to locate files older than 30 days
Use xargs command to pass the file names to rm command
Use crontab to schedule the script to run periodically

* what are the stages you regularly write in pipeline job in Jenkins?
* how you can identify which process cause your server got slow?
* how do you configure ssl certification with tomcat?
how to integrate Maven with jenkins
what are the git commands
 explain dynamic inventory in ansible
explain Jenkis pipeline job
How do you configure ssl certification with tomcat
Explain dynamic inventory in ansible
What are the stages you regularly write in pipeline job in Jenkins
Asked some Devops Docker image size related questions.
Asked Kubernetes deployment strategies.
How to run cmd commands using python on windows environment ?
What is difference between deep and shallow copy in python paradigm?


What is namespace in Docker ?
Have you tackled a day to day problem using automation ? If yes then tell the problem and solution.
How to install IIS using powershell ?
How will you setup a microservice architecture application simple testing environment and deployment pipeline using kubernetes, containers, jenkins and available Cloud services.
What is special variable in powershell ?
What is Docker and its advantages . Which is the most secure docker image
App service configuration, security mechanism, CI/CD pipeline, container, how to deploy in azure using Azure devops specially how it authenticate... questions will be based on the tools and technologies which you mentioned in resume.
What is the difference between a disk and an image in VM roles w.r.t MS Azure?
What is disk caching in Azure

1. Explain what DevOps is?
DevOps is the combination of cultural philosophies, practices, and tools that increases an organization's ability to deliver applications and services at high velocity: evolving and improving products at a faster pace than organizations using traditional software development and infrastructure management processes.

2. Mention what the key aspects or principle behind DevOps are?
To fuel a DevOps culture, we have to build robust tooling, also. That means investing up front in five key areas: abstraction, composability, automation, orchestration, and idempotency. Together, these concepts allow sharing work at every level of the pipeline.

3. What are the core operations of DevOps with application development and with infrastructure?
The core operations of DevOps are application development, code developing, code coverage, unit testing, packaging, deployment with infrastructure, provisioning, configuration, orchestration, and deployment.

4. Explain how “Infrastructure code” is processed or executed in AWS?
The code for infrastructure will be in simple JSON format. This JSON code will be organized into files called templates. This templates can be deployed on AWS devops and then managed as stacks.

5. Explain which scripting language is most important for a DevOps engineer?
Python. Most well-known language for programming and the first one that should be learnt, if someone wishes to become a DevOps professional.
JavaScript. While Python is more flexible, JavaScript adds significant value to the DevOps Environment.
Ruby
Perl
6. Explain how DevOps is helpful to developers?
Developer patterns and technologies are very useful in the operations side. Being able to pull in things such as infrastructure as code, version control, static analysis, and code reviews allows DevOps to be more efficient and more effective, often using the same programming languages.

7. List out some popular tools for DevOps?
Developer patterns and technologies are very useful in the operations side. Being able to pull in things such as infrastructure as code, version control, static analysis, and code reviews allows DevOps to be more efficient and more effective, often using the same programming languages.

8. What Is An Ami?
An Amazon Machine Image (AMI) provides the information required to launch an instance. You must specify an AMI when you launch an instance.

9. What is continuous integration?
Continuous integration (CI) is the practice of automating the integration of code changes from multiple contributors into a single software project.

10. What’s the definition of done?
Defining the definition of done. The Definition of Done is an agreed-upon set of items that must be completed before a project or user story can be considered complete. It is applied consistently and serves as an official gate separating things from being “in progress” to “done.”

11. What is DevOps? Why DevOps?
DevOps is the combination of cultural philosophies, practices, and tools that increases an organization's ability to deliver applications and services at high velocity: evolving and improving products at a faster pace than organizations using traditional software development and infrastructure management processes.

12. What are some of the tools you have used in DevOps approach?
The 10 best DevOps tools for 2021 and beyond
Gradle.
Git.
Jenkins.
Bamboo.
Docker.
Kubernetes.
Puppet Enterprise.
Ansible.

13. What is a Docker? Explain its role in DevOps.
Docker tool is basically used to create, deploy, and run the applications by using containers. Through Docker DevOps, developers can pack all parts of an application like libraries and other dependencies easily and ship it out as a single package.


Q1 _ What is Azure Cloud Service?

Cloud service can convey a multiple web application in Azure, characterizing a number of parts to disseminate handling and permit adaptable scaling of your application. A cloud service comprises of a minimum of one web pars as well as specialist parts, each with its own particular application documents and design.The fundamental favourable position of cloud service is the capacity to help more complex multi-level structures.

Q2_What are the roles implemented in Windows Azure?

There are three roles in Windows Azure.
Web Role
Worker Role
Virtual Machine Role
Web Role : It gives a web solution that is front-end. This is like an ASP.NET application. While under facilitating Azure gives IIS and required services.
Worker Role : It gives a solutions of background service. It can run long activities.
Virtual Machine Role : The roles of both web and worker are executed on virtual machines. The Virtual Machine Roles gives the client the capacity to modify the virtual machine on which the web and worker roles are running.

Q3_ What are Fault Domains and Update domains ?

Fault Domains :- A fault domain is a logical group of underlying hardware that share a common power source and network switch, similar to a rack within an on-premise data-centers. As you create VMs within an availability set, the Azure platform automatically distributes your VMs across these fault domains. This approach limits the impact of potential physical hardware failures, network outages, or power interruptions.
Update Domains :- An update domain is a logical group of underlying hardware that can undergo maintenance or can be rebooted at the same time. As you create VMs within an availability set, the Azure platform automatically distributes your VMs across these update domains. This approach ensures that at least one instance of your application always remains running as the Azure platform undergoes periodic maintenance. The order of update domains being rebooted may not proceed sequentially during planned maintenance, but only one update domain is rebooted at a time.

Q4_What is a break-fix issue?

Technical problems are called break-fix issue, it is an industry term which refers to “work involved in supporting a technology when it fails in the normal course of its function, which requires intervention by a support organization to be restored to working order”.

Q5_What Is Cspack?

It is a command-line tool that deploys a packaged application to the Windows Azure compute emulator and manages the running service.

Q6_ What is Azure Service Fabric?

Azure Service Fabric is a distributed systems platform that makes it easy to package, deploy, and manage scalable and reliable micro-services. Service Fabric also addresses the significant challenges in developing and managing cloud applications. Developers and administrators can avoid complex infrastructure problems and focus on implementing mission-critical, demanding workloads that are scalable, reliable, and manageable. Service Fabric represents the next-generation middleware platform for building and managing these enterprise-class, tier-1, cloud-scale applications.

Q7_What are the differences between Subscription Administrator and Directory Administrator?

By default, one is assigned the Subscription Administrator role when he/she signs up for Azure. A subscription admin can use either a Microsoft account or a work or school account from the directory that the Azure subscription is associated with. This role is authorized to manage services in the Azure portal. If others need to sign in and access services by using the same subscription, you can add them as co-admins.
Azure AD has a different set of admin roles to manage the directory and identity-related features. These admins will have access to various features in the Azure portal or the Azure classic portal. The admin’s role determines what they can do, like create or edit users, assign administrative roles to others, reset user passwords, manage user licenses, or manage domains.

Q8_What is the difference between Service Bus Queues and Storage Queues?

The Azure Storage Queue is simple and the developer experience is quite good. It uses the local Azure Storage Emulator and debugging is made quite easy. The tooling for Azure Storage Queues allows you to easily peek at the top 32 messages and if the messages are in XML or Json, you’re able to visualize their contents directly from Visual Studio Furthermore, these queues can be purged of their contents, which is especially useful during development and QA efforts.
The Azure Service Bus Queues are evolved and surrounded by many useful mechanisms that make it enterprise worthy! They are built into the Service Bus and are able to forward messages to other Queues and Topics. They have a built-in dead-letter queue and messages have a time to live that you control, hence messages don’t automatically disappear after 7 days.
Furthermore, Azure Service Bus Queues have the ability of deleting themselves after a configurable amount of idle time. This feature is very practical when you create Queues for each user, because if a user hasn’t interacted with a Queue for the past month, it automatically gets clean it up. Its also a great way to drive costs down. You shouldn’t have to pay for storage that you don’t need. These Queues are limited to a maximum of 80gb. Once you’ve reached this limit your application will start receiving exceptions.

Q9_What Is Web Role In Windows Azure?

Web roles in Windows Azure are special purpose, and provide a dedicated Internet Information Services (IIS) web-server used for hosting front-end web applications. You can quickly and easily deploy web applications to Web Roles and then scale your Compute capabilities up or down to meet demand.

Q10_What Is The Difference Between Public Cloud And Private Cloud?

Public cloud is used as a service via Internet by the users, whereas a private cloud, as the name conveys is deployed within certain boundaries like firewall settings and is completely managed and monitored by the users working on it in an organization.

Q11_What Is Windows Azure Diagnostics?

Windows Azure Diagnostics enables you to collect diagnostic data from an application running in Windows Azure. You can use diagnostic data for debugging and troubleshooting, measuring performance, monitoring resource usage, traffic analysis and capacity planning, and auditing.

Q12_What Is The Difference Between Block Blob Vs Page Blob?

Block blobs are comprised of blocks, each of which is identified by a block ID.
You create or modify a block blob by uploading a set of blocks and committing them by their block IDs.
If you are uploading a block blob that is no more than 64 MB in size, you can also upload it in its entirety with a single Put Blob operation. -Each block can be a maximum of 4 MB in size. The maximum size for a block blob in version 2009-09-19 is 200 GB, or up to 50,000 blocks.
Page blobs are a collection of pages. A page is a range of data that is identified by its offset from the start of the blob.
To create a page blob, you initialize the page blob by calling Put Blob and specifying its maximum size.
The maximum size for a page blob is 1 TB. A page written to a page blob may be up to 1 TB in size.
what to use block blobs for: streaming video. “The application must provide random read/write access” which is supported by Page Blobs

Q13_What is Azure Redis Cache?

Redis is an open source (BSD licensed), in-memory data structure store, used as a database, cache and message broker. Azure Redis Cache is based on the popular open-source Redis cache. It gives you access to a secure, dedicated Redis cache, managed by Microsoft, and accessible from any application within Azure. It supports data structures such as strings, hashes, lists, sets, sorted sets with range queries, bitmaps, hyperloglogs and geospatial indexes with radius queries.
Apart from this Azure Interview Questions Blog, if you want to get trained from professionals on this technology, you can opt for a structured training from edureka! Click below to know more.

Q14_What are Redis databases?

Redis Databases are just a logical separation of data within the same Redis instance. The cache memory is shared between all the databases and actual memory consumption of a given database depends on the keys/values stored in that database. For example, a C6 cache has 53 GB of memory. You can choose to put all 53 GB into one database or you can split it up between multiple databases.

Q15_ Is it possible to add an existing VM to an availability set?

If you want your VM to be part of an availability set, you need to create the VM within the set. There currently no way to add a VM to an availability set after it has been created.

Q16_What are the password requirements when creating a VM?

Passwords must be 12 – 123 characters in length and meet 3 out of the following 4 complexity requirements:
Have lower characters
Have upper characters
Have a digit
Have a special character


Q17_ How much storage can I use with a virtual machine?

Each data disk can be up to 1 TB. The number of data disks which you can use depends on the size of the virtual machine. Azure Managed Disks are the new and recommended disk storage offerings for use with Azure Virtual Machines for persistent storage of data. You can use multiple Managed Disks with each Virtual Machine. Managed Disks offer two types of durable storage options: Premium and Standard Managed Disks.
Azure storage accounts can also provide storage for the operating system disk and any data disks. Each disk is a .vhd file stored as a page blob.

Q18_Why was my client disconnected from the cache?

The following are some common reason for a cache disconnect.
:-Client-side causes
The client application was redeployed.
The client application performed a scaling operation.
In the case of Cloud Services or Web Apps, this may be due to auto-scaling.
The networking layer on the client side changed.
Transient errors occurred in the client or in the network nodes between the client and the server.
The bandwidth threshold limits were reached.
CPU bound operations took too long to complete.
Server-side causes
On the standard cache offering, the Azure Redis Cache service initiated a fail-over from the primary node to the secondary node.
Azure was patching the instance where the cache was deployed
This can be for Redis server updates or general VM maintenance.


Q19_What is Azure Search?

Azure Search is a cloud search-as-a-service solution that delegates server and infrastructure management to Microsoft, leaving you with a ready-to-use service that you can populate with your data and then use to add search to your web or mobile application. Azure Search allows you to easily add a robust search experience to your applications using a simple REST API or .NET SDK without managing search infrastructure or becoming an expert in search.

Q20_What Is Deadletter Queue?

Messages are placed on the deadletter sub-queue by the messaging system in the following scenarios.
When a message expires and deadlettering for expired messages is set to true in a queue or subscription.
When the max delivery count for a message is exceeded on a queue or subscription.
When a filter evaluation exception occurs in a subscription and deadlettering is enabled on filter evaluation exceptions.


Q21_Difference Between Web And Worker Roles In Windows Azure?

The main difference between the two is that an instance of a web role runs IIS, while an instance of a worker role does not. Both are managed in the same way, however, and it’s common for an application to use both.For example, a web role instance might accept requests from users, then pass them to a worker role instance for processing.

Q22_ What Is Autoscaling?

Scaling by adding additional instances is often referred to as scaling out. Windows Azure also supports scaling up by using larger role instances instead of more role instances.
By adding and removing role instances to your Windows Azure application while it is running, you can balance the performance of the application against its running costs.
An autoscaling solution reduces the amount of manual work involved in dynamically scaling an application.

Q23_What is a Storage keys?

Storage keys or Access Keys are utilized as a validation mode for accessing to the storage services account to control data based on our prerequisites. In Windows Azure we have an alternative to give a Primary Access Key and a Secondary Access Key, despite the fact that we will utilize a solitary access key to confirm our application to the storage. The primary reason to give the secondary access key is to avoid downtime to the application.

Q24_What is the concept of the table in Windows Azure?

A table is one kind of Azure Storage, where you can store your information away. Blobs are put away in compartment and Entity in a table.
Following are the key concepts in a table.
Tables allow structure data storage .
There can be 0..n tables in a storage account.
Table store information as an accumulation of elements.
An element has an essential key and properties as a key-value pair.


Q25_What is profiling in Azure?

Rofiling is only a procedure of measuring the performance analysis of an application. It is normally done to guarantee that the application is sufficiently steady and can maintain overwhelming traffic.
Visual Studio gives us different tools to do it by gathering the performance information from the application that likewise helps in the troubleshooting issues.
Once the profiling wizard is run, it sets up the execution session and collects the data of the sample
The profiling reports helps in:
Deciding the longest running strategies inside the application.
Measure the execution time of every strategy in the call stack.
Assess memory allocation.

## Accenture – DevOps Interview Questions

1. What is DevOps?
DevOps is the combination of cultural philosophies, practices, and tools that increases an organization's ability to deliver applications and services at high velocity: evolving and improving products at a faster pace than organizations using traditional software development and infrastructure management processes.

2. In terms of development and infrastructure, mention the core operations of DevOps.
The core operations of DevOps are application development, code developing, code coverage, unit testing, packaging, deployment with infrastructure, provisioning, configuration, orchestration, and deployment.

3. What are some technical and business benefits of DevOps work culture?
The top 7 benefits of DevOps are:
Improved operational support and faster fixes.
Good processes across IT and teams, including automation.
Increased team flexibility and agility.
Happier, more engaged teams.
Cross-skilling and self-improvement.
Collaborative working.
Respect from senior management
4. Name some of the most important DevOps tools?
The important DevOps tools in devops are:
Slack.
Jenkins.
Docker.
Phantom.
Nagios.
Vagrant.
Ansible.
GitHub.
5. What is CI? What is its purpose?
The technical goal of CI is to establish a consistent and automated way to build, package, and test applications. With consistency in the integration process in place, teams are more likely to commit code changes more frequently, which leads to better collaboration and the software quality.

6. Name three important DevOps KPIs.
Key Performance Indicators are metrics widely used to know how good are some practices, products, projects or even initiatives. Well, planning projects define KPIs that are collected from day zero and followed in all the steps.

7. What is the difference between continuous deployment and continuous delivery?
Continuous delivery is a software engineering practice in which teams develop, build, test, and release software in short cycles. Continuous Deployment is the process by which qualified changes in software code or architecture are deployed to production as soon as they are ready and without the human intervention.

8. What is DevOps? Is it a tool?
DevOps Tool is an application that helps automate the software development process. It mainly focuses on the communication and collaboration between product management, software development, and operations professionals.

9. What are the core operations of DevOps in terms of development and infrastructure?
The core operations of DevOps are application development, code developing, code coverage, unit testing, packaging, deployment with the infrastructure, provisioning, configuration, orchestration, and deployment.

10. How does HTTP work?
HTTP gives users a way to interact with the web resources such as HTML files by transmitting hypertext messages between clients and servers. PUT directly modifies an existing web resource or creates a new URI if need be. DELETE gets rid of a specified resource.

11. Can one consider DevOps as an Agile methodology?
DevOps is an extension of the agile built around the practices that are not in agile's focus. When used together, both practices improve software development and lead to the better products.

12. Can you tell me the advantages of using Git?
Two main advantages of using Git are:
Tracking the changes and updates. We are able to see who made which changes. Git also provides when and why a change was made.
Allowing to work collaboratively. Software development projects usually require many people to work together.
13. Are git fetch and git pull the same?
Git fetch is the command that tells your local git to retrieve the latest meta-data info from the original yet doesn't do any file transferring. git pull on the other hand does that and brings those changes from the remote repository.

14. What are the benefits of using version control?
Version control helps teams solve these kinds of problems, tracking every individual change by each contributor and helping prevent concurrent work from conflicting. Changes made in one part of the software can be incompatible with that those made by another developer working at the same time.

15. How do you handle the merge conflicts in Git?
The merge conflicts in Git are:
The easiest way to resolve a conflicted file is to open it and make any necessary changes.
After editing the file, we can use the git add a command to stage the new merged content.
The final step is to create a new commit with the help of the git commit command.

## TCS – DevOps Interview Questions
1. How do you handle the merge conflicts in Git?
The merge conflicts in Git are:
The easiest way to resolve a conflicted file is to open it and make any necessary changes.
After editing the file, we can use the git add a command to stage the new merged content.
The final step is to create a new commit with the help of the git commit command.
2. Can you tell me some advantages of Forking Workflow over other Git workflows?
The main advantage of the Forking Workflow is that contributions can be integrated without the need for everybody to push to a single central repository. Developers push to their own server-side repositories, and only the project maintainer can push to the official repository.

3. When do you use ‘git rebase’ instead of ‘git merge’?
Git rebase and merge both integrate the changes from one branch into another. Where they differ is how it's done. Git rebase moves a feature branch into a master. Git merge adds a new commit, preserving the history.

4. How to launch a browser using WebDriver?
Launch a browser using WebDriver are:
Download the latest ChromeDriver binary from Chromium.org download page and place the executable on your local machine.
Set the webdriver.chrome.driver property to the chromeDriver.exe's location as- System.setProperty(“webdriver.chrome.driver”, “chromeDriver.exe path”);
5. Are there any technical challenges with Selenium?
One of the top challenges faced in Selenium automation is the handling of dynamic web content. Selenium solves for it using the explicit wait feature, where you specify a pre-defined time for the automation testing process to the wait for new content to load.

6. Describe the difference between driver.close() and driver.quit().
driver. quit() is used to the exit the browser, end the session, tabs, pop-ups etc. But the when you driver. close(), only the window that has focus is closed.

7. How will you secure Jenkins?
To configure Security in Jenkins, follow the steps given below.

Step 1 − Click on Manage Jenkins and choose the 'Configure Global Security' option.

Step 2 − Click on Enable Security option.

Step 3 − You will be prompted to add your first user.

Step 4 − It's now time to setup your users in the system.

8. Can you write the syntax for building a docker image?
With the Dockerfile written, you can build the image using the following command: $ docker build . We can see the image we just built using the command docker images.

9. What is the concept of sudo in Linux?
Sudo stands for either "substitute user do" or "super user do" and it allows you to elevate your current user account to have root privileges temporarily. This is different from the“su” which is not temporary.

10. What is Nagios Log Server?
Log Server is a powerful centralized enterprise-class log monitoring and management application that allows organizations to quickly and easily view, sort, and configure logs from any source on any given network.

11. What Are The Benefits Of The Nosql?
The Benefits Of The Nosql are:
Handle large volumes of data at high speed with a scale-out architecture.
Store unstructured, semi-structured, or structured data.
Enable easy updates to schemas and fields.
Be developer-friendly.
Take full advantage of the cloud to deliver zero downtime.
12. What Are Adoptions Of Devops In Industry?
DevOps is an approach in which traditional software engineering roles are merged and communication is enhanced to improve the production release frequency and maintain software quality. There seem to be benefits in adopting DevOps but the practical industry experiences have seldom been reported.

13. How Would You Explain The Concept Of “infrastructure As Code” (iac) ?
DevOps is an approach in which traditional software engineering roles are merged and communication is enhanced to improve the production release frequency and maintain software quality. There seem to be benefits in the adopting DevOps but practical industry experiences have seldom been reported.

14. How Is Chef Used As A Cm Tool ?
Chef is a configuration management technology used to automate the infrastructure provisioning. It is developed on the basis of Ruby DSL language. It is used to streamline the task of configuration and managing the company's server. It has the capability to get the integrated with any of the cloud technology.

15. Why Are Configuration Management Processes And Tools Important ?
Configuration management helps engineering teams build robust and stable systems through the use of tools that automatically manage and monitor updates to configuration data. Complex software systems are composed of the components that differ in granularity of size and complexity.

## Dell – DevOps Interview Questions 
1. Which Are Some Of The Most Popular Devops Tools ?
The Most Popular Devops Tools are:
Docker.
Ansible.
Git.
Puppet.
Chef.
Jenkins.
Nagios.
Splunk.
2. How We Can Make Sure New Service Is Ready For The Products Launched?
The Product Launch Checklist are:
Learn about your customer.
Write a positioning statement.
Pitch your positioning to stakeholders.
Plan your go-to-market strategy.
Set a goal for the launch.
Create promotional content.
Prepare your team.
Launch the product.
3. What Are The Major Difference Between The Linux And Unix Operating Systems ?
Linux threat detection and the solution are very fast while Unix users require longer wait times to get the proper bug fixing patch. Important versions of Linux are Redhat, Ubuntu, OpenSuse, Solaris, whereas important versions of Unix are HP-UX, AIS, BSD, etc.

4. What Are Vagrant And Its Uses?
Vagrant is a tool for building and managing virtual machine environments in a single workflow. With an easy-to-use workflow and focus on the automation, Vagrant lowers development environment setup time, increases production parity, and makes the "works on my machine" excuse a relic of the past.

5. How Devops Is Helpful To Developers ?
DevOps describes a culture and set of processes that bring development and operations teams together to complete software development. It allows organizations to create and improve products at a faster pace than they can with the traditional software development approaches. And, it's gaining popularity at a rapid rate.

6. Name The Popular Scripting Language Of Devops ?
The Popular Scripting Language Of Devops are:
Python Scripting in DevOps: In IT Infrastructure, Python has become an all-purpose language.
Bash Scripting: Bash is one of the most frequently used Unix Shell Scripting and provides good support.
Ruby: Ruby is another DevOps Scripting language that offers a lot of versatility.
7. List The Agile Methodology Of Devops?
An Agile Approach to DevOps are:
Individuals and interactions over processes and tools.
Working software over comprehensive documentation.
Customer collaboration over contract negotiation.
Responding to change over following a plan.
8. Which Are The Areas Where Devops Are Implemented?
Vizuri experts have grouped DevOps automation processes into four areas of focus for implementing the automation that can each help your organization gain efficiencies and improve your overall IT processes: Build, Deployment, Test, and Infrastructure.

9. The Scope For Ssh ?
SSH is a Secure Shell which provides users with a secure, encrypted mechanism to log into the systems and transfer files.


10. What Are The Advantages Of Devops With Respect To Technical And Business Perspective?
DevOps benefits business by improving office collaboration and communication. The more employees communicate and work together, the better they work together. This improves the employee camaraderie and boosts employee morale, which is why it is one of the most effective team management strategies.

11. What Are The Core Operations Of Devops In Terms Of Development And Infrastructure ?
The core operations of DevOps are application development, code developing, code coverage, unit testing, packaging, deployment with the infrastructure, provisioning, configuration, orchestration, and deployment.

12. What Are The Anti-patterns Of Devops?
An anti-pattern is a pattern that you use to fix a short-term problem at the expense of your long-term goals. The insidious thing about anti-patterns isn't that they don't work or fail outright, but that they work in the short term while causing the long-term failure and pain.

13. Explain With A Use Case Where Devops Can Be Used In Industry/ Real-life?
DevOps is the combination of cultural philosophies, practices, and tools that increases an organization's ability to deliver applications and services at high velocity: evolving and improving products at a faster pace than organizations using traditional software development and the infrastructure management processes.

14. What Is The Most Important Thing Devops Helps Us Achieve?
DevOps is important because it's a software development and operations approach that enables faster development of new products and easier maintenance of theexisting deployments.

15. What Are The Advantages Of Devops?
Reduce the implementation time of new services from months to minutes. Increase productivity of business and IT teams. Save costs on maintenance and upgrades, and eliminate unnecessary the capital expenditure. Standardize processes for easy replication and faster delivery.

16. How Do All These Tools Work Together?
Build - Continuous integration tools, build status. Test - Test and results determine performance. Package - Artifact repository, application pre-deployment staging. Release - Change management, release approvals, release automation.

17. Which Are The Top Devops Tools?
The Top DevOps Tools are:
Slack.
Jenkins
Docker.
Phantom.
Nagios.
Vagrant.
Ansible.
GitHub.

## Hexaware – DevOps Interview Questions
1. Which Are The Top Devops Tools?
The Top Devops Tools are:
Slack.
Jenkins.
Docker.
Phantom.
Nagios.
Vagrant.
Ansible.
GitHub.
Sentry.
BitBucket.
2. How Is Devops Different From Agile / Sdlc?
DevOps is a practice of bringing development and operations teams together whereas Agile is an iterative approach that focuses on collaboration, customer feedback and the small rapid releases. DevOps focuses on the constant testing and delivery while the Agile process focuses on constant changes.

3. What Is The Need For Devops?
DevOps is important because it's a software development and operations approach that enables the faster development of new products and easier maintenance of existing deployments.

4. What Are Adoptions Of Devops In Industry?
DevOps is an approach in which traditional software engineering roles are merged and communication is enhanced to improve the production release frequency and maintain the software quality. There seem to be benefits in adopting DevOps but practical industry experiences have seldom been reported.

5. How Is Chef Used As A Cm Tool ?
Chef is a configuration management technology used to automate the infrastructure provisioning. It is developed on the basis of the Ruby DSL language. It is used to streamline the task of configuration and managing the company's server. It has the capability to get integrated with any of the cloud technology.

6. Why Are Configuration Management Processes And Tools Important ?
Configuration management helps the engineering teams build robust and stable systems through the use of tools that automatically manage and monitor updates to configuration data. Complex software systems are composed of components that differ in granularity of size and complexity.

7. Which Are Some Of The Most Popular Devops Tools ?
The Most Popular DevOps Tools are:
Version Control tools.
Container Management tools.
Application Performance Monitoring tools.
Deployment & Server Monitoring tools.
Configuration Management tools.
CI / Deployment Automation tools.
Test Automation tools.
Artifact Management tools.
Free PDF : Get our updated DevOps Course Content pdfDOWNLOAD NOW
8. How Devops Is Helpful To Developers ?
Developer patterns and technologies are very useful in the operations side. Being able to pull in things such as the infrastructure as code, version control, static analysis, and code reviews allows DevOps to be more efficient and more the effective, often using the same programming languages.

9. Name The Popular Scripting Language Of Devops ?
JavaScript is used as DevOps Scripting to create the network-centric applications. It is a lightweight and Interpreted DevOps Scripting Language.

10. List The Agile Methodology Of Devops?
The Agile Methodology Of DevOps are:
Individuals and interactions over processes and tools.
Working software over comprehensive documentation.
Customer collaboration over contract negotiation.
Responding to change over following a plan.
11. Which Are The Areas Where Devops Are Implemented?
Vizuri experts have grouped DevOps automation processes into the four areas of focus for implementing automation that can each help your organization gain efficiencies and improve your overall IT processes: Build, Deployment, Test, and Infrastructure.

12. The Scope For Ssh ?
SSH is a Secure Shell which provides users with a secure, encrypted mechanism to log into systems and transfer files.
To log out a remote machine and work on the command line.
To secure encrypted communications between two hosts over an insecure network.
13. What Are The Advantages Of Devops With Respect To Technical And Business Perspective?
Benefits of DevOps can bring the consistent improvements in maintaining software quality, scale and predictability, reduce the cost of designing, testing, writing and deploying software, and satisfy customer requirements faster.

14. What Are The Core Operations Of Devops In Terms Of Development And Infrastructure ?
The core operations of DevOps are the application development, code developing, code coverage, unit testing, packaging, deployment with infrastructure, provisioning, configuration, orchestration, and deployment.

15. What Are The Anti-patterns Of Devops?
Twelve DevOps Anti-Patterns are:
DevOps is a process. Not exactly.
Agile equals DevOps?
Rebrand your ops/dev/any team as the DevOps.
Start a separate DevOps group.
The hostile takeover.
DevOps is a buzzword.
Sell DevOps as a silver bullet.
DevOps means Developers Managing Production.

## Amazon – DevOps Interview Questions
1. What are the fundamental differences between DevOps & Agile?
DevOps is a practice of bringing development and operations teams together whereas Agile is an iterative approach that focuses on collaboration, customer feedback and small rapid releases. DevOps focuses on constant testing and delivery while the Agile process focuses on the constant changes.

2. What is the need for DevOps?
DevOps is important because it's a software development and operations approach that enables faster development of new products and easier maintenance of the existing deployments.

3. How is DevOps different from Agile / SDLC?
DevOps is a practice of bringing development and operations teams together whereas Agile is an iterative approach that the focuses on collaboration, customer feedback and small rapid releases. DevOps focuses on constant testing and delivery while the Agile process focuses on constant changes.

4. Which are the top DevOps tools? Which tools have you worked on?
To help you to refine your DevOps strategy, we mention 10 top DevOps tools which you should use in the year 2020. Slack. Launched in the year 2013, Slack is still one of the top communication tools used by teams for effective collaboration on projects.
Jenkins.
Docker.
Phantom.
Nagios.
Vagrant.
Ansible.
GitHub.
5. What are the advantages of DevOps?
The advantage of DevOps are:
Reduce the implementation time of new services from months to minutes.
Increase productivity of business and IT teams.
Save costs on maintenance and upgrades, and eliminate unnecessary capital expenditure.
Standardize processes for easy replication and faster delivery.
6. What is the most important thing DevOps helps us achieve?
DevOps is the combination of the tools, social strategies that help to expand the company to provide the services and application at the high speed. It is the important thing that helps you achieve to get changes into the production. It helps to good working relationships and communication between the teams.

7. Explain with a use case where DevOps can be used in industry/ real-life.
Real-life Applications of DevOps are:
Application of DevOps in the Online Financial Trading Company.
Use of DevOps in Network cycling.
Application in Car Manufacturing Industries.
Benefits to Airlines Industries.
Application to GM Financial.
Bug Reduction Benefit of DevOps.
Less Time for Integration.
8. What are the anti-patterns of DevOps?
Anti-patterns of DevOps are:
DevOps is a process. Not exactly.
Agile equals DevOps?
Rebrand your ops/dev/any team as the DevOps.
Start a separate DevOps group.
The hostile takeover.
DevOps is a buzzword.
Sell DevOps as a silver bullet.
DevOps means Developers Managing Production.
Free PDF : Get our updated DevOps Course Content pdfDOWNLOAD NOW
9. Explain some basic Git commands?
Basic Git Commands are:
git init.
git add.
git commit.
git status.
git config.
git branch.
git checkout.
git merge.
10. What is meant by Continuous Integration?
Continuous integration is the practice of automating the integration of code changes from multiple contributors into a single software project. The version control system is also supplemented with the other checks like automated code quality tests, syntax style review tools, and more.

11. Why do you need a Continuous Integration of Dev & Testing?
Continuous testing is key to unlocking this culture change because it weaves testing activities into every part of the software design, development, and deployment processes, which helps everyone involved the communicate more, collaborate better, and innovate faster.

12. What are the success factors for Continuous Integration?
The success factors for Continuous Integration are:
Compilation.
Unit Tests.
Code Quality Gates.
Integration Tests.
Deployment.
Chain Tests.
13. How to automate Testing in DevOps lifecycle?
In order to implement automated testing into your DevOps lifecycle, you must first map out your release pipeline. This can be done by following four steps: Identify all the stages of your release. Identify the gates and requirements necessary in a build's journey to the production.

14. Why is Continuous Testing important for DevOps?
Continuous Testing encourages automating tests wherever possible throughout the development cycle. Doing so ensures that teams evaluate the code validity and overall quality of the software at each stage. These insights can help organizations identify whether the software is ready to go through the delivery pipeline.

15. What are the key elements of Continuous Testing tools?
The Key Elements of a Successful Continuous Testing Process are:
A Continuous Integration Tool. A basic continuous integration tool allows the team to integrate new code that has been deposited into a central repository to produce a new build of a software solution.
Environment Provisioning.
End-To-End Testing.
Teamwork.
16. How to launch Browser using WebDriver?
Launch a browser using WebDriver are:
Download the latest ChromeDriver binary from Chromium.org download page and place the executable on your local machine.
Set the webdriver.chrome.driver property to the chromeDriver.exe's location as- System.setProperty“webdriver.chrome.driver”, “chromeDriver.exe path.

## Oracle – DevOps Interview Questions

1. Explain DevOps.
DevOps is the combination of cultural philosophies, practices, and tools that the increases an organization's ability to deliver applications and services at high velocity evolving and improving products at a faster pace than organizations using traditional software development and infrastructure management processes.

2. Explain a few prerequisites that are useful for DevOps implementation.
DevOps implementation defines the strategic outcome of a software development cycle.Aspire's DevOps implementation services includes the processes of end-to-end delivery pipeline, infrastructure management, automation, deployment, orchestration, etc.

3. What are the best practices for DevOps implementation?
The best practices for DevOps implementation are:
Take a 'security first approach' .
Assess your organization's readiness to utilize a microservices architecture.
Implement tracking and version control tools.
Commit daily, reduce branching.
Build only once.
Decide which processes and tests to automate first.
Release often.
4. What are the key components of DevOps?
Key Components of DevOps are:
The Most Critical Components of DevOps.
An Agile Framework.
Automated Testing.
Configuration Management.
Regular Integration.
Infrastructure as Code.
5. Explain Continuous Integration.
Continuous integration is the practice of automating the integration of code changes from the multiple contributors into a single software project. It's a primary DevOps best practice, allowing developers to frequently merge code changes into a central repository where builds and tests then run.

6. Explain Continuous Delivery.
Continuous Delivery is the ability to get the changes of all types—including new features, configuration changes, bug fixes and experiments into production, or into the hands of users, safely and quickly in a sustainable way.

7. Explain Continuous Testing.
Continuous Testing is the process of executing automated tests as part of the software delivery pipeline in the order to obtain feedback on the business risks associated with a software release candidate as rapidly as possible.

8. Explain Continuous Monitoring.
Continuous monitoring is the process and technology used to detect compliance and risk issues associated with an organizations financial and operational activities. A by-product of continuous monitoring is it highlights opportunities to the improve operational processes.

Free PDF : Get our updated DevOps Course Content pdfDOWNLOAD NOW
9. How will you approach when a project needs to implement devops?
DevOps methodology of is based on the idea of eliminating the main issues of development and maintenance processes, which will allow your business to work with the innovative ideas, change and grow faster, more efficiently and reliably, along with risks reduction.

10. Can DevOps be applied to a Waterfall process? Explain the significance of the Agile process in DevOps implementation.
DevOps is considered a practice of bringing development and operations teams together. Agile helps to manage the complex projects. DevOps central concept is to manage end-to-end engineering processes. Agile method can be implemented within a range of tactical frameworks like a sprint, safe and scrum.

11. What is the difference between Continuous Delivery and Continuous Deployment?
Continuous delivery is a software engineering practice in which teams develop, build, test, and release software in short cycles. Continuous Deployment is the process by which qualified the changes in software code or architecture are deployed to production as soon as they are ready and without human intervention.

12. What is your expertise on the DevOps projects?
DevOps is the combination of cultural philosophies, practices, and tools that increases an organization's ability to deliver applications and services at high velocity evolving and improving products at a faster pace than organizations using traditional software development and the infrastructure management processes.

13. What are the top 10 devops tools that are used in the industry today?
Top 10 DevOps Tools
Git. Code, Build.
Gradle. Build.
Selenium. Test.
Jenkins. Build, Test, Deploy.
Puppet. Deploy, Operate.
Chef. Deploy, Operate.
Docker. Build, Deploy, Operate.
Kubernetes. Build, Deploy, Operate.
Ansible Deploy, Operate
eG Enterprise Monitor
14. Which scripting tools are used in DevOps?
scripting tools are used in DevOps are:
Microsoft PowerShell.
Puppet.
Chef.
Bash.
Ruby.
Ansible.
Perl.
Python.
15. Explain the typical roles involved in DevOps.
The seven critical roles involved in DevOps are:
The DevOps evangelist.
The release manager.
The automation architect.
The software developer/tester.
The experience assurance (XA) professional.
The security engineer.
The utility technology player.
16. Have you been involved in DevOps implementation in the cloud? If yes which cloud computing platform?
The centralized nature of cloud computing provides DevOps automation with a standard and centralized the platform for testing, deployment, and production. Cloud-based DevOps lessens the need to account for resources leveraged.

17. Explain some of the metrics that were followed for DevOps success.
The researchers have determined that only four key metrics differentiate between the low, medium, and high performers: lead time, deployment frequency, mean time to restore , and change failure percentage.

## Infosys – DevOps Interview Questions
  1. What is DevOps?
DevOps is the combination of cultural philosophies, practices, and tools that increases an organization's ability to deliver the applications and services at high velocity: evolving and improving products at a faster pace than organizations using traditional software development and infrastructure management processes.

2. Why do we need DevOps?
DevOps promotes a culture of trust and risk-sharing between team members. It encourages teams to continuously experiment with the aim of improving the company's products and services. That way, both development and the operations teams are enabled to research new customer needs and develop innovations to address them.

3. Mention the key aspects or principle behind DevOps?
To fuel a DevOps culture, we have to build robust tooling, also. That means investing up front in five key areas: abstraction, composability, automation, orchestration, and idempotency. Together, these concepts allow the sharing work at every level of the pipeline.

4. List out some of the popular tools for DevOps?
The popular tools for DevOps are:
Git. Code, Build.
Gradle. Build.
Selenium. Test.
Jenkins. Build, Test, Deploy.
Puppet. Deploy, Operate.
Chef. Deploy, Operate.
Docker. Build, Deploy, Operate.
Kubernetes. Build, Deploy, Operate.
5. What is a version control system?
Version control, also known as source control, is the practice of tracking and managing changes to software code. Version control systems are software tools that the help software teams manage changes to source code over time.

6. What is Git and explain the difference between Git and SVN?
The difference between Git and SVN version control systems is that Git is a distributed version control system, whereas SVN is a centralized version control system. Git uses multiple repositories including a centralized the repository and server, as well as some local repositories.

7. What language is used in Git?
JavaScript continues to be the most popular programming language on GitHub, while Python is now the second most popular, followed by Java and the fast-growing the TypeScript community.

8. What is SubGit?
SubGit is stress-free tool for migrating from SVN to Git. It can be used with any Git server whether it is Github, Gitlab, Gerrit, or Bitbucket.It is developed by Tmate software. Answered by devquora. It is software for the migrating SVN to GIT.

Free PDF : Get our updated DevOps Course Content pdfDOWNLOAD NOW
9. How can you clone a Git repository via Jenkins?
There are two ways to clone the project from the Github. Create a new Jenkins job called 'Clone-with-https', move to the “Source Control Management” setting and choose “Git” options if you can't see the Git options that mean 'GitHub' plugin wasn't installed in the Jenkins machine.

10. What are the Advantages of Ansible?
The primary benefit of Ansible is it allows IT administrators to automate away the drudgery from their daily tasks. That frees them to focus on the efforts that help deliver more value to the business by spending time on more important tasks.

11. What’s the difference between Ansible Playbook and Roles?
Ansible, the role is the primary mechanism for the breaking a playbook into multiple files. This simplifies writing complex playbooks, and it makes them easier to reuse. The breaking of playbook allows you to logically break the playbook into reusable components.

12. How do I see a list of all the ansible_ variables?
There are Three sources of variables in Ansible are:
Variables gathered from facts.
You can get them by running command: ansible -m setup hostname.
But obviously you know what they are.
13. What is Docker?
Docker is an open platform for developing, shipping, and running applications. Docker enables you to separate your applications from your infrastructure so you can deliver software quickly. With Docker, you can manage your infrastructure within the same ways you manage your applications.

14. What is Docker image?
A Docker image is a file used to execute code in a Docker container. Docker is used to create, run and deploy applications in containers. A Docker image contains application code, libraries, tools, dependencies and other files needed to make an application run.

15. What is Docker Container?
Docker streamlines the development lifecycle by allowing developers to work in the standardized environments using local containers which provide your applications and services. Containers are great for continuous integration and continuous delivery workflows.

## IBM – DevOps Interview Questions

1. What is Docker Container?
Docker is an open source containerization platform. It enables developers to package the applications into containers standardized executable components combining application source code with the operating system libraries and dependencies required to run that code in any environment.

2. Can we consider DevOps as Agile methodology?
DevOps is an extension of agile built around the practices that are not in agile's focus. When used together, both practices improve the software development and lead to better products.

3. What are the advantages of using Git?
One of the biggest advantages of Git is its branching capabilities. Unlike centralized version control systems, Git branches are cheap and easy to merge. This facilitates the feature branch workflow popular with many Git users. Feature branches provide an isolated environment for every change to the your codebase.

4. What is kernel?
The kernel performs its tasks, such as running processes, managing hardware devices such as the hard disk, and handling interrupts, in this protected kernel space. In contrast, application programs like browsers, word processors, or audio or video players use a separate area of memory, user space.

5. What is difference between grep -i and grep -v?
The grep command is used to find the specified string in the file. The execution effect of egrep is similar to "grep-E", the syntax and parameters used can refer to the grep command,The difference with grep is the method of interpreting strings.

6. How can you define particular space to the file
The df command gets file system space statistics from that the statfs system call. statistics from the virtual file system specific file system helper.

7. What is Scrum?
Scrum is a lightweight framework that the helps people, teams and organizations generate value through adaptive solutions for complex problems.

8. Explain what DevOps is?
DevOps is the combination of cultural philosophies, practices, and tools that increases an organization's ability to deliver applications and services at high velocity: evolving and improving products at a faster pace than the organizations using traditional software development and infrastructure management processes.

9. Mention what the key aspects or principle behind DevOps are?
To fuel a DevOps culture, we have to build robust tooling, also. That means investing up front in the five key areas: abstraction, composability, automation, orchestration, and idempotency. Together, these concepts allow sharing work at every level of the pipeline.

Free PDF : Get our updated DevOps Course Content pdfDOWNLOAD NOW
10. What are the core operations of DevOps with application development and with infrastructure?
The core operations of DevOps are application development, code developing, code coverage, unit testing, packaging, deployment with the infrastructure, provisioning, configuration, orchestration, and deployment.

11. Explain how “Infrastructure code” is processed or executed in AWS?
The code for infrastructure will be in simple JSON format. This JSON code will be organized into files called templates. This templates can be deployed on AWS devops and then managed as stacks.

12. Explain which scripting language is most important for a DevOps engineer?
Python. Most well-known language for programming and the first one that should be learnt, if someone wishes to become a DevOps professional.
JavaScript. While Python is more flexible, JavaScript adds significant value to the DevOps Environment.
Ruby.
Perl.
13. Explain how DevOps is helpful to developers?
DevOps is helpful to developers are:
Python. Most well-known language for programming and the first one that should be learnt, if someone wishes to become a DevOps professional.
JavaScript. While Python is more flexible, JavaScript adds significant value to the DevOps Environment.
Ruby.
Perl.
14. List out some popular tools for DevOps?
The popular tools for Devops are:
Git. Code, Build.
Gradle. Build.
Selenium. Test.
Jenkins. Build, Test, Deploy.
Puppet. Deploy, Operate.
Chef. Deploy, Operate.
Docker. Build, Deploy, Operate.
Kubernetes. Build, Deploy, Operate.
15. Mention at what instance have you used the SSH?
SSH or Secure Shell is a network communication the protocol that enables two computers to communicate and share data.

16. Explain how you would handle revision (version) control?
In the software development process, revision control, also known as version control or source control, is the management of the changes made over time. These changes can be to source code, project assets, or any other information that goes into the finished product.

17. What are the types of Http requests?
The types of Http requests are:
Sent when URL is submitted in the browser location bar or a user clicks a link.
Send data in the URL and query string.
Reloadable.
Can bookmark.
Used for read-only operations. View, search, sort, or filter data. Data does not change.
18. What are the key components of DevOps?
The Most Critical key Components of DevOps are:
An Agile Framework.
Automated Testing.
Configuration Management.
Regular Integration.
Infrastructure as Code.

## Blackboard – DevOps Interview Questions

1. What are the key components of DevOps?
The Key Components of DevOps are:
The Most Critical Components of DevOps.
An Agile Framework.
Automated Testing.
An Agile Framework.
Configuration Management.
Regular Integration.
Infrastructure as Code.
2. Name a few cloud platform which are used for DevOps Implementation
The Popular Cloud computing platform used for DevOps implementation are:
Google Cloud.
Amazon Web Services.
Microsoft Azure.
3. Give some benefits of using Version Control system
Version control software is a best practice for the high performing software and DevOps teams. Version control also helps developers move faster and allows software teams to preserve efficiency and agility as the team scales to include more developers.

4. Explain Git Bisect
Git bisect is like a wizard: it guides you step by step through a process of elimination until you find the commit that broke your code. Once you type git bisect start , you have started the wizard and it won't end until you type git bisect reset .

5. What is the build?
The build in devops are:
Write the code.
Commit code to a shared, centralized repository — such as Perforce Helix Core.
Scan the code using tools such as static analysis.
Start a code review.
Compile code and files.
Run automated testing.
Notify contributors to resolve issues.
6. What is Puppet?
Puppet discovers information about a system by using a utility called Facter, which is installed when you install the Puppet software package. Puppet works by using a pull mode, where agents poll the master at regular intervals to retrieve site-specific and node-specific configurations.

7. What is Vagrant?
A vagrant is a tool that uses virtualization to build complete development environments. Vagrant automates the infrastructure tasks that developers waste so much time on. Vagrant has an easy-to-use workflow and it focuses mainly on automation.

8. What are the prerequisites for the implementation of DevOps?
The implementation of DevOps are:
Containers Understanding.
Understanding the DevOps Tools and Technologies.
Knowledge of Scripting Languages.
DevOps Training and Certification.
Knowledge of Automation Tools.
Testing.
Excellent Collaboration and Communication Skills.
Knowledge of Networking fundamentals.
Free PDF : Get our updated DevOps Course Content pdfDOWNLOAD NOW
9. Name some best practices which should be followed for DevOps success.
Best practices which should be followed for DevOps success are:
Have a Centralized Unit for DevOps.
Shift Left With CI/CD.
Implement Test Automation.
Implement Continuous Deployment.
Keep All Teams on the Same Page.
Exercise Patience.
Implement Automation in Dashboards.
10. Explain SubGIt tool
It is a software tool to migrate from SVN to Git.SubGit is stress-free tool for migrating from SVN to Git. It can be used with any Git server whether it is Github, Gitlab, Gerrit, or Bitbucket.It is developed by Tmate software.

11. Name some important network monitoring tools
The Top Network Monitoring Tools are:
SolarWinds Network Performance Monitor
Datadog Network Monitoring
ManageEngine OpManager
PRTG Network Monitor from Paessler
Site24x7 Network Monitoring
Nagios XI.
Zabbix.
Icinga.
12. Why do we need DevOps?
DevOps is important because it's a software development and operations approach that enables faster development of new products and easier maintenance of existing deployments.

13. Mention the key aspects or principle behind DevOps?
The key aspects or principle behind DevOps are: abstraction, composability, automation, orchestration, and idempotency. Together, these concepts allow sharing work at every level of the pipeline.

14. List out some of the popular tools for DevOps?
The popular tools for DevOps are:
Git. Code, Build.
Gradle. Build.
Selenium. Test.
Jenkins. Build, Test, Deploy.
Puppet. Deploy, Operate.
Chef. Deploy, Operate.
Docker. Build, Deploy, Operate.
Kubernetes. Build, Deploy, Operate.
15. What is a version control system?
Version control, also known as source control, is the practice of tracking and managing changes to software code. Version control systems are software tools that help software teams manage changes to source code over time.

16. What is Git and explain the difference between Git and SVN?
Git uses the history of the repository to identify the common base between the merged branches and only needs to merge from where they diverged thereby completing a three-way merge. SVN is also improving and has supported the three-way merging since 1.5.

17. What language is used in Git?
C language is used in Git.h files contain the information to be shared among multiple source files using the #include preprocessing directive. The . c files contain the actual code that makes Git tick. However, analyzing this current version of Git's codebase would get unwieldy fast, simply because there are so many files and folders to go through.

## Temenos – DevOps Interview Questions
1. Can you tell us the fundamental differences between DevOps & Agile?
Agile focuses on making the developers and development cycles more efficient, while DevOps brings the operations team into play to enable continuous integration and continuous delivery.

2. Why do we need DevOps?
DevOps is important because it's a software development and operations approach that enables the faster development of new products and easier maintenance of existing deployments.

3. What are the important business and technical benefits of using DevOps?
DevOps engineers can exploit real-time data into the performance of their systems to quickly understand that the impact of application changes. And resolution times are faster because team members don't need to wait for a different team to troubleshoot and fix the problem.

4. Can you name some of the most-used DevOps tools?
The most-used DevOps tools are:
Jenkins.
Docker.
Phantom.
Nagios.
Vagrant.
Ansible.
GitHub.
5. What is Selenium used for?
Selenium is basically used to automate the testing across various web browsers. It supports various browsers like the Chrome, Mozilla, Firefox, Safari, and IE, and you can very easily automate browser testing across these browsers using Selenium WebDriver.

6. What do you understand by Puppet in DevOps?
Puppet is a cross-platform client-server based application used for configuration management. It works on both the Linux and Windows platforms. It uses a declarative approach to automate updates, installations, and other tasks. This feature allows the software to configure those systems using files called manifests.

7. What do you understand by anti-patterns of DevOps?
An anti-pattern is a pattern that you use to fix a short-term problem at the expense of your long-term goals. The insidious thing about anti-patterns isn't that they don't work or fail outright, but that they work in the short term while causing the long-term failure and pain.

8. DevOps has something called CI. What is it and what is its purpose?
Continuous integration is the practice of automating the integration of code changes from multiple contributors into a single software project. It's a primary DevOps best practice, allowing developers to frequently merge code changes into a central repository where builds and tests then run.

9. More often than not we hear shift left in DevOps. What is it?
Shift Left is a practice intended to find and prevent defects early in the software delivery process. The idea is to improve quality by moving tasks to the left as early in the lifecycle as possible. Shift Left testing means testing earlier in the software development process.

10. What does CAMS in DevOps stand for?
CALMS is a framework that assesses a company's ability to adopt the DevOps processes, as well as a way of measuring success during a DevOps transformation. The acronym was coined by Jez Humble, co-author of “The DevOps Handbook,” and stands for Culture, Automation, Lean, Measurement, and Sharing.

11. What are the several KPIs used to gauge DevOps success?
The several KPIs used to gauge DevOps success are:
Deployment frequency.
Change failure rate.
Mean Time to Recovery
Lead time.
Change volume.
Defect escape rate.
Customer tickets.
DevOps Resources.
12. In your opinion, what are the major benefits of implementing DevOps automation?
The major benefits of implementing DevOps automation are:
Elimination of recurring action items enabling staff to focus on value addition.
Increased deployment rate for new software releases.
Reduction of ongoing operational cost.
Establishment of standard 'error-free' work environments.
Free PDF : Get our updated DevOps Course Content pdfDOWNLOAD NOW
13. What do you understand by containers?
A container is a standard unit of software that packages up code and all its dependencies so the application runs quickly and reliably from one computing environment to another. Available for both the Linux and Windows-based applications, containerized software will always run the same, regardless of the infrastructure.

14. What are the core operations of DevOps with application development and with infrastructure?
The core operations of DevOps are application development, code developing, code coverage, unit testing, packaging, deployment with the infrastructure, provisioning, configuration, orchestration, and deployment.

15. Explain which scripting language is most important for a DevOps engineer?
Python. Most well-known language for programming and the first one that should be learnt, if someone wishes to become a DevOps professional.
JavaScript. While Python is more flexible, JavaScript adds significant value to the DevOps Environment.
Ruby.
Perl.
16. Explain how DevOps is helpful to developers?
Developer patterns and technologies are very useful in the operations side. Being able to pull in things such as the infrastructure as code, version control, static analysis, and code reviews allows DevOps to be more efficient and more effective, often using the same programming languages.

17. List out some popular tools for DevOps?
The popular tools for DevOps are:
Git. Code, Build.
Gradle. Build.
Selenium. Test.
Jenkins. Build, Test, Deploy.
Puppet. Deploy, Operate.
Chef. Deploy, Operate.
Docker. Build, Deploy, Operate.
Kubernetes. Build, Deploy, Operate.
18. Mention at what instance have you used the SSH?
I utilized SSH to switch into a virtual computer and operate on the manual board Besides this, in addition to promoting protected the authenticated correspondence between two unauthenticated servers across an unreliable infrastructure, I have utilized it to funnel into the device.

19. What are the types of Http requests?
The types of Http requests are:
Sent when URL is submitted in the browser location bar or a user clicks a link.
Send data in the URL and query string.
Reloadable.
Can bookmark.
Used for read-only operations. View, search, sort, or filter data. Data does not change.
20. Explain what you would check If a Linux-build-server suddenly starts getting slow?
System Level troubleshooting. a. RAM related issues.
Application Level troubleshooting. a. Application is not behaving properly.
Dependent Services troubleshooting.
21. What are the key components of DevOps?
The Key Components of DevOps are
The Most Critical Components of DevOps.
An Agile Framework.
Automated Testing.
Configuration Management.
Regular Integration.
Infrastructure as Code.
22. Name a few cloud platform which are used for DevOps Implementation
DevOps implementation defines the strategic outcome of a software development cycle. Aspire's DevOps implementation services includes the processes of end-to-end delivery pipeline, infrastructure management, automation, deployment, orchestration, etc.

## Capgemini – DevOps Interview Questions
1. Explain what DevOps is?
DevOps is the combination of cultural philosophies, practices, and tools that increases an organization's ability to deliver applications and services at high velocity: evolving and improving products at a faster pace than organizations using traditional software development and infrastructure management processes.

2. Mention what the key aspects or principle behind DevOps are?
To fuel a DevOps culture, we have to build robust tooling, also. That means investing up front in five key areas: abstraction, composability, automation, orchestration, and idempotency. Together, these concepts allow sharing work at every level of the pipeline.

3. What are the core operations of DevOps with application development and with infrastructure?
The core operations of DevOps are application development, code developing, code coverage, unit testing, packaging, deployment with infrastructure, provisioning, configuration, orchestration, and deployment.

4. Explain how “Infrastructure code” is processed or executed in AWS?
The code for infrastructure will be in simple JSON format. This JSON code will be organized into files called templates. This templates can be deployed on AWS devops and then managed as stacks.

5. Explain which scripting language is most important for a DevOps engineer?
Python. Most well-known language for programming and the first one that should be learnt, if someone wishes to become a DevOps professional.
JavaScript. While Python is more flexible, JavaScript adds significant value to the DevOps Environment.
Ruby
Perl
6. Explain how DevOps is helpful to developers?
Developer patterns and technologies are very useful in the operations side. Being able to pull in things such as infrastructure as code, version control, static analysis, and code reviews allows DevOps to be more efficient and more effective, often using the same programming languages.

7. List out some popular tools for DevOps?
Developer patterns and technologies are very useful in the operations side. Being able to pull in things such as infrastructure as code, version control, static analysis, and code reviews allows DevOps to be more efficient and more effective, often using the same programming languages.

Free PDF : Get our updated DevOps Course Content pdfDOWNLOAD NOW
8. What Is An Ami?
An Amazon Machine Image (AMI) provides the information required to launch an instance. You must specify an AMI when you launch an instance.

9. What is continuous integration?
Continuous integration (CI) is the practice of automating the integration of code changes from multiple contributors into a single software project.

10. What’s the definition of done?
Defining the definition of done. The Definition of Done is an agreed-upon set of items that must be completed before a project or user story can be considered complete. It is applied consistently and serves as an official gate separating things from being “in progress” to “done.”

11. What is DevOps? Why DevOps?
DevOps is the combination of cultural philosophies, practices, and tools that increases an organization's ability to deliver applications and services at high velocity: evolving and improving products at a faster pace than organizations using traditional software development and infrastructure management processes.

12. What are some of the tools you have used in DevOps approach?
The 10 best DevOps tools for 2021 and beyond
Gradle.
Git.
Jenkins.
Bamboo.
Docker.
Kubernetes.
Puppet Enterprise.
Ansible.
13. What is a Docker? Explain its role in DevOps.
Docker tool is basically used to create, deploy, and run the applications by using containers. Through Docker DevOps, developers can pack all parts of an application like libraries and other dependencies easily and ship it out as a single package.

## cOGNIZANT DEVOPS INTERVIEW QUESTIONS
1. What Is Amazon Web Services In Devops?
AWS provides services that help you the practice DevOps at your company and that are built first for use with AWS. These tools automate manual tasks, help teams manage complex environments at scale, and keep engineers in control of the high velocity that is enabled by DevOps.

2. What Is The Role Of A Devops Engineer?
DevOps Engineers are responsible for the supporting the users of the infrastructure they develop, and the first line of defense is protecting the cloud against hackers and viruses. They do this with code, of course, building secure software from the start.

3. What Is Devops With Cloud Computing?
AWS DevOps is Amazon's answer to implementing the DevOps philosophy using its cloud platform and the dedicated tools and services.AWS DevOps provides application developer teams with the means to efficiently implement continuous integration and continuous delivery.

4. Why Do We Use Aws For Devops?
AWS provides services that help you practice DevOps at your company and that are built first for use with AWS. These tools automate the manual tasks, help teams manage complex environments at scale, and keep engineers in control of the high velocity that is enabled by DevOps.

5. What Is Devops Tooling By Aws?
DevOps Tool is an application that helps automate the software development process.DevOps tool also enables teams to automate most of the software development processes like build, conflict management, dependency management, deployment, etc. and helps reduce the manual efforts.

6. How Do You Handle Continuous Integration And Continuous Delivery In Aws Devops?
Continuous integration is a step in which all code is merged as developers complete code in order to run the automated builds and tests.Continuous delivery is an approach which incorporates the concepts of continuous integration, automated testing and continuous deployment.

7. What Is Aws Code Pipeline In Aws Devops?
AWS CodePipeline is a fully managed continuous delivery service that helps you automate your release pipelines for fast and the reliable application and infrastructure updates. With AWS CodePipeline, you only pay for what you use. There are no upfront fees or long-term commitments.

8. What Is Aws Code Build In Aws Devops?
AWS CodeBuild is a fully managed continuous integration service that compiles source code, runs tests, and produces the software packages that are ready to deploy. With CodeBuild, you don't need to provision, manage, and scale your own build servers.

9. What Is Aws Code Deploy In Aws Devops?
AWS CodeDeploy is a service that the automates application deployments to your compute infrastructure, including fleets of Amazon EC2 instances. AWS CodeDeploy can automatically deploy the latest app version to any new EC2 instance launched due to a scaling event.

10. What Is Aws Code Star In Aws Devops?
AWS CodeStar is a cloud based development service that provides the tools you need to quickly develop, build, and deploy the applications on AWS. With AWS CodeStar, you can set up your entire continuous delivery toolchain in minutes, allowing you to start releasing code faster.

Free PDF : Get our updated DevOps Course Content pdfDOWNLOAD NOW
11. How Lulu Lemon Athletic Uses Aws Devops?
ululemon uses a variety of AWS services to engineer a fully automated, continuous integration and the delivery system. The company uses AWS CloudFormation templates to define its complete development environment.lululemon deploys immutable artifacts distributed via Amazon Simple Storage Service .

12. What Is Amazon Elastic Container Service In Aws Devops?
Amazon Elastic Container Service is a fully managed container orchestration service that makes it easy to operate the containerized workloads at scale. It also integrates with other core AWS services, such as Amazon Route 53, AWS Identity and Access Management , and Amazon CloudWatch.

13. What Is Aws Lambda In Aws Devops?
AWS Lambda is a serverless compute service that can run code in response to predetermined events or conditions and automatically manage all the computing resources required for those processes. It also enables the devops teams to connect to any number of AWS services or run their own functions.

14. What Are Aws Developer Tools?
AWS Developer Tools are:
AWS CodeArtifact. AWS CodeCommit. AWS CodePipeline. AWS CodeBuild.
AWS X-Ray.
AWS CLI. PowerShell Tools. Amazon EC2 AMI Tools. AWS Elastic Beanstalk CLI.
AWS Serverless Application Model (SAM) CLI. AWS Copilot.
AWS Cloud9. Eclipse. IntelliJ. PyCharm.
Azure DevOps. Rider.
JavaScript. Python. PHP. .NET.
Go. Node.js. C++
15. What Is Code Commit In Aws Devops?
AWS CodeCommit is a secure, highly scalable, managed source control service that hosts private Git repositories. It makes it easy for teams to securely collaborate on the code with contributions encrypted in transit and at rest.

16. What Are The Benefits Of Aws Code Build In Aws Devops?
Benefits of AWS Code Build are:
Eliminates the need to set up, patch, update, and manage build servers and software.
Scales up and down automatically to meet your build volume.
Never pay for idle build server capacity.
Create complete, automated software release workflows for continuous integration and delivery.
17. What Is Amazon Ec2 In Aws Devops?
Amazon Ec2 In Aws Devops access the AWS Elastic Computing Power. Industry Leading Security. Agile, Reliable Service. Sign Up for 1 Free Year of 750 Hours/Month on Amazon EC2. Monthly Uptime of Up to 99.99% Highly Scalable. Quickly Scale Capacity.

18. What Is Amazon S3 In Aws Devops?
Amazon S3 is object storage built to store and retrieve any amount of data from anywhere. It's a simple storage service that offers industry leading durability, availability, performance, security, and virtually unlimited scalability at the very low costs.

19.What Is Amazon Rds In Aws Devops?
Amazon Relational Database Service is a web service that makes it easier to set up, operate, and scale a relational database in the AWS Cloud. It provides the cost-efficient, resizable capacity for an industry-standard relational database and manages common database administration tasks.

## Siemens – DevOps Interview Questions
1. What Is Amazon Quick Sight In Aws Devops?
Amazon QuickSight is a scalable, serverless, embeddable, machine learning-powered business intelligence service built for the cloud. QuickSight lets you easily create and publish the interactive BI dashboards that include Machine Learning-powered insights.

2. What Is Aws Iot In Aws Devops?
AWS IoT Greengrass is an Internet of Things open source edge runtime and cloud service that helps you build, deploy, and manage device software. Customers use AWS IoT Greengrass for their IoT applications on the millions of devices in homes, factories, vehicles, and businesses.

3. What Are The Benefits Of Aws Code Deploy In Aws Devops?
Benefits DevOps Teams are:
Scalability. AWS environments are provisioned with scalability in mind, enabling DevOps teams to support a single instance or quickly and easily expand to thousands of instances.
Automation.
Better Collaboration.
AWS Developer-Specific Tools: CodePipeline and CodeBuild
4. What Is Vpc?
A virtual private cloud is the logical division of a service provider's public cloud multi-tenant architecture to support the private cloud computing.

5. What Is Vpc Peering?
A VPC peering connection is a networking connection between two VPCs that enables you to route traffic between them using private IP addresses. VPC peering allows you to deploy the cloud resources in a virtual network that you have defined.

6. Explain how you would handle revision (version) control?
In the software development process, revision control, also known as version control or source control, is the management of changes the made over time. These changes can be to source code, project assets, or any other information that goes into the finished product.

7. What are the types of Http requests?
HTTP Request Types are:
Sent when URL is submitted in the browser location bar or a user clicks a link.
Send data in the URL and query string.
Reloadable.
Can bookmark.
Used for read-only operations. View, search, sort, or filter data. Data does not change.
Free PDF : Get our updated DevOps Course Content pdfDOWNLOAD NOW
8. What are the key components of DevOps?
The Most Critical Components of DevOps.
An Agile Framework.
Automated Testing.
Configuration Management.
Regular Integration.
Infrastructure as Code.
9. Name a few cloud platform which are used for DevOps Implementation
Popular Cloud computing platform used for the DevOps implementation are: Google Cloud. Amazon Web Services. Microsoft Azure.

10. Give some benefits of using Version Control system
Version control systems allow you to compare files, identify differences, and merge the changes if needed prior to committing any code. Versioning is also a great way to keep track of the application builds by being able to identify which version is currently in development, QA, and production.

11. What is Jenkins used for in DevOps?
Jenkins is used to build and test your software projects continuously making it easier for developers to integrate the changes to the project, and making it easier for users to obtain a fresh build. Jenkins achieves Continuous Integration with the help of plugins. Plugins allow the integration of Various DevOps stages.

12. How do you implement CI/CD using Jenkins?
To implement CI/CD using Jenkins are:
We will create a git repository or use an existing one.
Dev team have the responsibility to commit the code to Dev-Branch.
Jenkins will fetch the code from Github and will map with the job enabled for a specific task.
13. Mention some post condition pipelines options that you used in Jenkinsfile?
Jenkins Pipeline is a suite of plugins which supports implementing and integrating continuous delivery pipelines into Jenkins. A continuous delivery pipeline is an automated expression of your process for getting the software from version control right through to your users and customers.



## Fidelity – DevOps Interview Questions
Name a few branching strategies used in DevOps
What is the motive of GIT tools in DevOps?
Explain what the major components of DevOps are?
What steps should be taken when Linux-based-server suddenly gets slow?
Which cloud platforms can be used for the successful DevOps implementation?
What is a Version Control System (VCS)?
What are the significant benefits of VCS(Version Control System)?
What is a Git Bisect?
What do you understand by the term build?
Free PDF : Get our updated DevOps Course Content pdfDOWNLOAD NOW
As per your experience, what is the most important thing that DevOps helps to achieve?
Discuss one use case where DevOps can be implemented in the real-life.
What are the anti-patterns in DevOps?
What is a Git Repository?
What is continuous integration in DevOps?
How to create a file and take backups in Jenkins?
Name a few useful plugins in Jenkins.
How will you secure Jenkins?
What is continuous testing in DevOps?





