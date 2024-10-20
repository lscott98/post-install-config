<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Installation Configuration</h1>
This project focuses on configuring osTicket to function effectively as a ticketing system. It involves setting up multiple agents, assigning them to departments, and defining their roles and permissions. Additionally, it includes configuring SLAs (Service Level Agreements), help topics, and user management.



<h2>Environments and Technologies Used</h2>

- Microsoft Azure 
- Remote Desktop Connection
- Virtual Machines
- osTicket
<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Installation Steps</h2>
<p>
With osTicket open, access the Admin Panel by clicking the "Admin Panel" button, located in orange at the top right corner of the page. To begin configuring roles, go to the Agents tab and click on Roles beneath it. Then, enter a name for the role.</p>
<br />









![image](https://github.com/user-attachments/assets/dbd30a75-9112-4b3d-b14b-2a626ebf70f8)









<p>
To set up departments, remain in the Agents tab and click on Departments located just below it. Name the department "System Administrators" and create the department.</p>
<br />







![image](https://github.com/user-attachments/assets/a4404ff8-674a-4cd1-a7b3-e43889f253fb)














<p>
Next, create a team by selecting the Teams option within the Agents tab. Name the team "Level II Support" and proceed to create the team.


</p>
<br />


![image](https://github.com/user-attachments/assets/1b7b8a14-6bcf-4693-8e21-2a564011f303)





<p>

To allow anyone to create tickets, navigate to the Settings tab and, under Authentication Settings, ensure that "Require registration and login to create tickets" is unchecked.
  
<br />



![image](https://github.com/user-attachments/assets/a3354bdc-a2ce-4a33-b421-0cccac513cfd)

















<p>To add agents (help desk staff), go back to the Agents tab, click on Agents, and enter the name, email, and username for each agent.<br />





![image](https://github.com/user-attachments/assets/df83f20f-1816-44e8-8dcc-a22a25ee2c28)



<p>On the "Access" tab for this user select the "System Administrators" department and the "Supreme Admin" role created earlier:<br />



![image](https://github.com/user-attachments/assets/a83a71c2-15aa-4bdb-8b74-b86ee76028e7)



<p>Under the "Teams" tab select "Level II Support" for this agent:<br />




![image](https://github.com/user-attachments/assets/0896dfec-c27c-450a-95a2-d11151f5579a)





<p>
Create another agent following the same steps as before, but this time, in the Access tab, select "Support" for the department.<br />



![image](https://github.com/user-attachments/assets/ed8cafda-acb6-4f70-929f-72f4c92de4b7)






![image](https://github.com/user-attachments/assets/b37cb072-2c08-4148-adb9-424f0da06c71)


<p>
  To configure an SLA plan, return to the Admin Panel, go to Manage, and select SLA. Create three SLAs with varying severities, grace periods, and schedules as follows:
<br />





![image](https://github.com/user-attachments/assets/335fbc75-0e87-4267-8de0-412227526a16)






![image](https://github.com/user-attachments/assets/6d1691ae-78cb-4b9f-8237-a5cd820cad1e)




![image](https://github.com/user-attachments/assets/f137e634-80fb-4a0f-8e19-1d9386d64850)



<p>
Under the same "Manage" tab go to the "Help Topics" tab and create four help topics named, "Business Critical Outage", "Personal Computer Issues", "Equipment Request", and "Password Reset" all with the same settings like so:/p>
<br />






![image](https://github.com/user-attachments/assets/b51f244d-1901-4235-963a-ec6f94a73563)



