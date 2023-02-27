### Team 2 - 27 FEB 23
#### Jordan Marshall
#### Justin Tabios
#### Lamin Touray
#### Robert Gregor

### Systems Selection

#### - Review the project guidelines and scenario. Meet as a team and decide what systems, platforms, or tools you’ll be using this project.
#### - Each should represent a clear, logical solution to a problem the client company is facing.
#### - Create a high-level list of systems, platforms, or tools you’ve decided to work with this project. For each, explain:
**- How does it fit into your scenario’s requirements?**
**- What problem or pain point does it solve? In other words, what value does this add to your client? **
**- Minimum Viable Product (MVP) - What is the minimum required for you to present on your demo day?**
  - **DBAN** - Will be used to wipe donated laptops prior to imaging, removing all sensitive info & PII.
    - Keeps costs at minimum using open source software validated by the community.
    - At a minimum we will discuss the DBAN process and verbalize the advantages of using DBAN.
  - **Spiceworks** - Will be used as the organizations help desk tracking environment.
    - We will train new employees how to create tickets in spiceworks to streamline the troubleshooting process.
    - At a minimum we will establish a Spiceworks pre-configured account and discuss the steps used to process an issue.
  - **VM Clients** - We will produce a script that will automate the set-up of standard user work stations, will significantly reduce the time to stand up new users
    - We will establish two images, one to support social media community organizers & researchers, and another for those who handle financial info & PII.
    - Each workstation will utilize Windows 10 OS, MS Office, and the Thunderbird email client.
    - We will establish administrative remote access with the ability to wipe all data if necessary.
    - Will remove bloatware, unnecessary apps, optimize boot time, include apps useful to clients.
    - Will create an ISO image and use it to set up an new endpoint.
    - At a minimum we will provide an overview of client workstation configuration.
  - **VM Server** - We will set up Network Attached Storage (NAS) on a Ubuntu server to support client work stations.
    - Will be utilized as our backup solution.
    - In line with the hybrid solution the organization wants to implement to support remote access.
    - At a minimum we will provide an overview of server configuration.
  - **VM Pfsense** - Pfsense firewall will be utilized at the office location located between the internet and our server & work stations.
    - Pfsense firewall will filter all traffic entering or leaving the organizations network to prevent unauthroized access or malicious activities.
    - At a minumum we will explain the process Pfsense uses to filter traffic to and from the organizations infrastructure.  
  - **Virtual Private Network Server** - VPN server tunnel will be established for all external connections to organizations infrastructure.
    - To maintain secure communications between remote workstations and the organizations network.
    - At a minimum we will explain VPN concepts.
