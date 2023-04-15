<p align="center">
<img src="https://imgur.com/Vxvq35v.png" height="60%" width="40%" alt="Microsoft Azure Logo"/>
</p>

<h1>Creating a Virtual Machine in Microsoft Azure</h1>
In this project, I created a virtual machine on Microsoft's cloud platform and observed the network topology generated by Azure.<br />

<h2>Requirements</h2>

- Computer with internet connection
- Microsoft Azure account
  - Credit card to set up the account

<h2>High-Level Steps</h2>

- Step 1: Create a virtual machine ("VM").
- Step 2: Verify validation and successful deployment of the VM.
- Step 3: Observe the VM's network topology.

<h2>Specific Steps</h2>

<p>
<img src="https://imgur.com/RHHpI1S.png" height="80%" width="80%" alt="Azure VM Details"/>
</p>
<p>
1. I filled out the above form. First, I created a resource group (like a folder for organizing and managing resources, such as VMs) and named my VM. Then I selected a region, image (base operating system), and size for the VM. 
</p>
<br />

<p>
<img src= "https://imgur.com/EVLBzEV.png" height="80%" width="80%" alt="Admin Credentials"/>
</p>
<p>
2. Further down the form, I entered credentials for my administrator account and confirmed I had an eligible license.
</p>
<br />

<p>
<img src="https://imgur.com/idZw1Uu.png" height="80%" width="80%" alt="VM Deployed"/>
</p>
<p>
3. Azure showed my VM had passed the validation check. I noted the VM's cost per hour and then clicked on "Create." 
</p>
<br />

<p>
<img src="https://imgur.com/eWHbAuX.png" height="80%" width="80%" alt="VM Deployed"/>
</p>
<p>
4. My VM was successfully deployed! I then clicked on "Go to resource."
</p>
<br />

<p>
<img src="https://imgur.com/Wyfkugs.png" height="80%" width="80%" alt="VM Deployed"/>
</p>
<p>
5. The resource page (titled "vm1" after my VM) provided key information about my VM, including its location, operating system, size, and public IP address.
</p>
<br />

<p>
<img src="https://imgur.com/2aGMJJ5.png" height="80%" width="80%" alt="VM Deployed"/>
</p>
<p>
6. The Network Watcher | Topology page indicated Azure had set up a virtual network (vm1-vnet), subnet (default), network interface card (vm1278), network security group (similar to a firewall), and IP address (vm1-ip) for my VM. </p>
<p>Thanks for checking out my first Azure lab!
</p>


</p>
<br />
