##Objective:
Attain more skills on virtualization and aim to be able to automate end to end to make customers life easier.

##Qualification:
•	Master of computer application from NMAMIT, VTU 2009
##Professional Training & Certification
•	VMware vSphere 6.7 Foundations  score 389
•	VMware Certified Professional - Network Virtualization score 480
•	Certified kubernetes Administrator – Score 81


##Skillset/Technologies/Language:
VMware vRealize Orchestrator v8.6
VMWare vRealize Automation v8.6
VMWare NSX-T v3.1
VMWare vSphere v6.7, v7.0
VMWare VCF v3.9, v4.0, v4.1,4.2,4.3.1
Ansible/Python
ESXi v6.7, v7.0
RHEL v8, v8.2
Centos v7.9
CKA(Certified Kubernetes Administrator)

#Current Role:
##System/Software Engineer 5b, 
•	Automating infrastructure deployment for customer requirement through POC and use case development. 
•	Presentation of POC to relevant customers
•	Whitepaper documentation of unique solutions.

#Hewlett Packard Enterprises (Oct-2009 to Current) 
•	Working in presales for 7+ years in HPE, prior in platform modernization and HPE IUM tools.
•	Understanding customer requirements and aid in automation solution.
•	PowerShell automation script for customer to upgrade Mellanox drivers across 2000 ESXi host
•	Automation via script using vRO and vRA for customers and internal codebase aiding in (HPE Oneview) BareMetal deployment Day0 and Day1 activity and storage configuration (HPE Nimble/3PAR/PRIMERA). Define custom object for enabling micro service on the same.
•	Automating vSAN cluster deployment with vMotion on standard switch. Automation to Scaleout cluster using VROPS alert mechanism and VRO in case of threshold breach.
•	Cloud Assembly scripts to automate multi-tier deployment, kubernetes 2 worker node and master node, Hadoop VM’s along with NSX features, configuring security groups, load balancer and segments on demand to create a truly virtual space for end user.
•	vRO automation workflow to deploy windows VM from template attach vGPU selected from host GPU and install the required drivers on windows guest OS and make VM ready for vGPU consumption. The Graphic card on host is NVidia.
•	vRO automation script to schedule repurpose server based on time zone to different OS.
•	VRA Cloud Assembly Single template to deploy in public(AWS)/Private(vCenter)Cloud
•	Automation via Ansible python scripts for capturing infrastructure details of datacenter and deploying it to another datacenter (Internally goes via REST API and HPE Oneview Converged infrastructure management dashboard) and created Docker image (to incorporate libraries and environment)
•	Automation via Ansible python scripts to aid in raid configuration of server local storage and deploy OS and fetch IP.
•	Ansible automation deployment for BareMetal and VM Blueprint generation using Morpheus.
•	Report generation code for customers based on data they perceive important. This helped them to get a report view of performance, backup.
•	Prior to 2015 
o	Worked on automation scripts of Python and PowerShell for customers on need basis.
o	Automating code using HP OpenView Internet Usage Manager(IUM) to help customer capture usage and trigger alert on subscription expiry
o	Re-architecting legacy applications to modern architecture like oracle ADF, SOA, EJB
o	Re-hosting of application from Mainframe environment to LINUX
o	Application transition from Solaris operating system to Windows and UNIX operating system.
o	Internship: Integrate Silverlight technology with C# using WCF and LINQ to SQL to develop user interface which on hover shows storage facility data – used RFID tagging.

###Prominent Project Recognized by Management and Customers
•	Baremetal Service: 
Creating automated end to end server provisioning solution – across datacenter (For RHEL/ESXi attaching storage volumes (across datacenter), patching ESXi OS, and firmware). Responsible for team operations by working on user stories such as new features, enhancement, bug fixes, environment version upgrade, patch update.  

For a customer use case: This was further enhanced, based on network interconnects in input the connection network is to be chosen, finding the server hardware based on internal JBOD storage availability, power consumption on an enclosure , CPU/Memory(Small/Medium/Large), affinity, anti-affinity rule to make enclosure awareness possible for deployment. Raid set creation. Day 2 activity to add/remove JBOD connection, network storage connection. Error handling for failure scenario’s.

•	Capture Datacenter Infrastructure and Redeploy:
Ansible/Python automation to capture details of an infrastructure into JSON files and deploy it to a different datacenter. This handles the URL to name mapping and uses hash map to update JSON before it is stored in files and used for deployment. Based on customer requirement this was made into docker image.

•	Parallel deployment of server Hardware and deploy VCF:
vRO workflows to deploy 4 ESXi nodes, make it VCF ready and deploy VCF. This was initially done using curl commands to validate and deploy VCF stack, network pool creation and workload domain/cluster deployment with 3 nodes. Have recently guided the process to team to convert the same to Ansible scripts using REST API.
