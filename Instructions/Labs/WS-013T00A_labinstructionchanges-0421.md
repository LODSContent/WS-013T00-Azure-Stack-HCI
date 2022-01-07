

4/11/2021

Purpose

The purpose of this document is to highlight changes to the lab instructions for WS-013T00A: Azure-Stack-HCI course. Most of the changes are of a typographical nature, but some corrections to update Azure user interface settings.

Update Date – April 2021

April 2021

- Module 2 Lab 02: Using Windows Admin Center in hybrid scenarios.

	- Ex 2, Task 4, Step 2: change in wording – it should now be “Storage Spaces and Pools” I believe.

	- Ex 2, Task 6, Steps 3: Log Analytics Agent is now configured under “Agents Configuration” and adding Performance Counters is different.



- Lab answer key: Module 2 Lab 02: Using Windows Admin Center in hybrid scenarios.

	- Ex 2, Task 4, Step 2: change in wording – it should now be “Storage Spaces and Pools” I believe.

	- Ex 2, Task 6, Steps 5-7: Log Analytics Agent is now configured under “Agents Configuration”.

	- Ex 4, Task 1, Step 2-4: Some of the wording has changed for Cluster-Aware Updating.


 

April 2021

- Module 3: Lab A: Implementing a Storage Spaces Direct cluster by using Windows PowerShell

	- No changes required.

- Lab answer key: Module 3: Lab A: Implementing a Storage Spaces Direct cluster by using Windows PowerShell

	- No changes required.

 

 

April 2021

- Module 3: Lab B: Managing storage of a Storage Spaces Direct cluster by using Windows Admin Center and Windows PowerShell

	- Ex 1, Task 1, Step 8: WAC Storage Spaces and Pools wording has changed.

 

- Lab answer key: Module 3: Lab B: Managing storage of a Storage Spaces Direct cluster by using Windows Admin Center and Windows PowerShell

	- Ex 1, Task 1, Step 13-14: WAC Storage Spaces and Pools wording has changed.

  
‎ 

April 2021

- Module 3: Lab C: Managing and monitoring resiliency of a Storage Spaces Direct cluster

	- No changes required.

- Lab answer key: Module 3: Lab C: Managing and monitoring resiliency of a Storage Spaces Direct cluster

	- No changes required.


April 2021

- Module 3: Lab D: Managing Storage Spaces Direct cluster tiers

	- No changes required.

- Lab answer key: Module 3: Lab D: Managing Storage Spaces Direct cluster tiers

	- No changes required.

 

 

April 2021

- Module 3: Lab E: Identifying and analyzing metadata of a Storage Spaces Direct cluster (optional)

	- No changes required.

- Lab answer key: Module 3: Lab E: Identifying and analyzing metadata of a Storage Spaces Direct cluster (optional)

	- No changes required.

 

April 2021

- Module 04: Lab A: Deploying Software-Defined Networking

	- Ex 1, Task 2: I verified that only the **DC** VM will require you to run `slmgr -rearm` and be restarted. I did not remove the part of the note that says to do slmgr -rearm on all the VMs. This note can simply say “Sign in to the **DC** VM using the CORP\LabAdmin username and LS1setup! password, run `slmgr -rearm` and restart it.”

- Lab answer key: Module 04: Lab A: Deploying Software-Defined Networking

	- Ex 1, Task 2: I verified that only the **DC** VM will require you to run `slmgr -rearm` and be restarted. I did not remove the part of the note that says to do slmgr -rearm on all the VMs. This note can simply say “Sign in to the **DC** VM using the CORP\LabAdmin username and LS1setup! Password, run `slmgr -rearm` and restart it.”


April 2021

- Module 04: Lab B: Managing virtual networks by using Windows Admin Center and PowerShell

	- Ex 1, Task 3, Step 4: I ran into maybe a transient issue where the iso file was not uploading correctly. So, I used a workaround that I added to the note.

	- Ex 1, Task 8, Steps 1-2: updated steps.

- Lab answer key: Module 04: Lab B: Managing virtual networks by using Windows Admin Center and PowerShell

	- Ex 1, Task 3, Step 9: I ran into maybe a transient issue where the iso file was not uploading correctly. So, I used a workaround that I added to the note.

	- Ex 1, Task 5, Step 19: I noticed the static MAC entry won’t save if you select (open) the VM and then go into settings-network. The Static MAC entry will only save if you select the check next to the VM and then go into Settings.

	- Ex 1, Task 8, Steps 1-2: updated steps.

 

April 2021

- Module 04: Lab C: Implementing SDN Access Control List by using Windows Admin Center

	- Ex 1, Task 2, Step 2: moved note to fix syntax.

	- Ex 1, Task 3, Step 1-2: updated steps.

 

- Lab answer key: Module 04: Lab C: Implementing SDN Access Control List by using Windows Admin Center

	- Ex 1, Task 3, Step 1-2: updated steps.

 

 

 

April 2021

- Module 04: Lab D: Implementing SDN Software Load Balancing with private virtual IP by using PowerShell

	- Ex 1, Task 6, Step 5: The Lab VM was on a public network profile so it wasn’t allowing inbound port 80 so I just added a note to verify that inbound port 80 is allowed on Windows Firewall for the lab VM on all network profiles.

- Lab answer key: Module 04: Lab D: Implementing SDN Software Load Balancing with private virtual IP by using PowerShell

	- Ex 1, Task 6, Step 5: The Lab VM was on a public network profile so it wasn’t allowing inbound port 80 so I just added a note to verify that inbound port 80 is allowed on Windows Firewall for the lab VM on all network profiles.
 

 

 
