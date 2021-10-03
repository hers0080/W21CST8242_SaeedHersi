# W21CST8242_SaeedHersi

# S21CST8248_Group 12



<center> <h2> Project Timeline </h2 </center>

  
#### **Brainstorming phase:** 
- Which Operating systems will be used for certain services
- How will we implement services
  

#### **Research time and dates**: 
  - How to implement services (weeks 5-6)
  - Research iSCSi/WAC/Spiceworks(week 7-8)
  - Run Azure (weeks 8-10)
  - Research for added values (weeks 7-11)
  - Adding everything together/value added (weeks 10-12)
  - Technical report, prepare demo (weeks 12-14)
  
#### **Project start and end date:**
  - Start Date: Wednesday May 12, 2021
  - End Date : Thursday August 13, 2021
  
  
#### **Detailed Task breakdown:**
 - Week 3-4 Research how to implement services/value addded services (All)
 
  - Weeks 4-5: Start deploying 1 linux and 1 windows machine. Ensure accounts have file share mapped, firewalls enabled, service connectivity, and no access to admin tools. Setup backups in case of emergency.

  - Weeks 5-6 : Create DNS, HTTP, WAC, AD and File server. Connect WAC to your domain using admin credentials, client machines should have access to file shares, network connectivity to all devices. Use PowerCLI to control power operations of machines within your vApp. Collected inventory information using WAC and Spiceworks

  - Weeks 7: iSCSI Target and Initiator: ISCI traffic should be isolated from user generated traffic.

  - Weeks 8: Veeam Server: Connect your Veeam Server to vcsa.et.lab using your ET domain credentials, Backup your Web server using Veeam

  - Weeks 9-10: Azure : Connect to azure interface, deploy a vm, create a web server to your database vm, secure connection between front end and backend, use powershell to determine status of vms within your subscription

  - Weeks 10-11: Value added

  - Week 12-14 : Technical report, Prepare demo


  
 #### **Communication plan**
  - Where will meetings occur:
    - Meetings we occur on MS teams
  - When will meetings occur
    - Meetings will occur every Thursday at 5:00pm
  - Who will record the meeting minutes?
    - Carlos will record the meeting minutes
  



<center> <h4 Communication/Meeting Plans /h5> </center>
  
  
  #### **Testing plan:**
  
First testing to Occur after services are deployed in weeks 5-6.
After weekly testing to occur by group members whenever a service is deployed to ensure smooth process till project demo.
  
#### **Quality Assurance plan:**
  
Start backups once 2 machines are created.
Setup scheduled backups, scans every 2-3 weeks
Testing will occur every week after weeks 5-6 to ensure connectivity
Designation of new member weekly to check firewall and security.
  
  #### **Hardware Plan:**
  
● 2 gb 1 core 1 processor : File Server 
  
● 8 gb 1 cores 2 processors : Active directory
  
● 4 gb 1 core 2 processors : DNS Server 1
  
● 4 gb 1 core 2 processors : DNS Server 2
  
● 8 gb1 core 2 processor : HTTP server
  
● 4 gb 1 core 2 processor :ISCSI Target
  
● 4 gb 1 core 2 processor :ISCSI i nitiator
  
● 4 gb 1 core 2 processor: Veeam
  
● 8 gb : WAC
  
● 8 gb 1 core 2 processors : Windows client
  
● 4 gb 1 core 2 processos : Linux client
  
#### **Test Plan**
| Source | Destination |Connectivity | Service | Test Command | Result | Comment | Test Date |                              
| --- | --- | --- | --- | --- | --- | --- | --- |
| Linux/Windows Client | Linux/Windows Server |    |HTTP | HTTP:// IPadd  |     |  |   |
| Linux/Windows Client | Linux/Windows Server  |     | NFS/SMB | testparm  |     |  |   | 
| Windows Client | Windows Server  |     | DNS | Show file  |  ping   |  |   | 
| iSCSI Initiator | iSCSI Target  |     | iSCSI | Show file  | dir    |  |   | 
|  |   |     |  |   |     |  |   | 
   
  
  #### **Network Plan**
| Service | IP Address  |
  |:--------| :----------:|
  | HTTP    | 172.20.61.2 |
  | DNS1    | 172.20.61.3 |
  | DNS2    | 172.20.61.4 |
  | AD      | 172.20.61.5 |
  | File server | 172.20.61.6 |
  | Windows client | 172.20.61.100 |
  | Linux client | 172.20.61.101 |
  | Spiceworks | 172.30.61.2 |
  | WAC | 172.30.61.3 |
  | ISCl Target | 172.50.61.2 |
  | iSCi initiator | 172.50.61.3 |
  | Veeam | 172.50.61.4 |
  
![image](https://user-images.githubusercontent.com/84108163/120875203-b0546380-c578-11eb-87bf-8f8c87fe5607.png)
#### **Documentation: All documentation are recorded and stored in the shared Github/Google docs** 
