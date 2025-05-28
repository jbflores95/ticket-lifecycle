<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Ticket Lifecycle: Intake Through Resolution</h1>
This tutorial outlines the lifecycle of a ticket from intake to resolution within the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How to create, work, and resolves tickets within osTicket](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Ticket Lifecycle Stages</h2>

- Intake
- Assignment and Communication
- Working the Issue
- Resolution

<h2>Lifecycle Stages</h2>

<p>

![88](https://github.com/user-attachments/assets/49beedb9-617e-43a4-9d16-0b9d53126d67)

</p>
<p>
- Alright, now we get to the fun stuff. We will create the following ticket as an end user.
</p>
- Following this link (User portal - http://localhost/osTicket) opens up the Support Portal. Click "Open a New Ticket".
<br />

<p>

![89](https://github.com/user-attachments/assets/26bb2914-ffcd-41e7-b7fc-164882a0d516)
![90](https://github.com/user-attachments/assets/cbde7f78-d29d-454e-9fe5-fe28db0d2b69)

</p>
<p>
- Here we enter the following: Email Address: karen@lognpacific.com > Full Name: Karen > Help Topic choose " Report a Problem". 
</p>
- For Issue Summary, we type in "entire mobile/online banking system is down". Click on Create Ticket.
</p>
- Now you should see that we successfully created a Ticket.
<br />

<p>

![Screenshot 2025-05-27 231337](https://github.com/user-attachments/assets/368c9ea6-25ea-491c-a9dc-4632182fb510)
</p>
<p>
- As the Help Desk Agent, log back in as "john", password "Password1". If you created your own, then your information will be different; that is okay.
</p>
<br />

![92](https://github.com/user-attachments/assets/59d787df-87d2-4e26-8059-e0182a1602a3)
![93](https://github.com/user-attachments/assets/517a83ae-b184-4204-b5bc-2b8371089278)

<p>

<p>
- Under Tickets, click open, and you should see the ticket we just created.
</p>
- Now, based on the info you see here, do you think its a serious issue?  I'll give you a hint, look at what karen posted. Looks like her employees are no longer able to access the online banking portal. Huge issue.
</p>
- In cases like these its wise to contact Karen if this were a real life issue or have your internal team reach out for an update.
</p>
<br />


<p>

![94](https://github.com/user-attachments/assets/8fdf372e-ea97-450b-b691-c240ebf078d3)
![Screenshot 2025-05-27 232707](https://github.com/user-attachments/assets/7ac22a54-3e3c-4583-8285-401a5613c88f)
![96](https://github.com/user-attachments/assets/3b9f6b3a-4aa0-413e-bc78-8e59a11422f1)

</p>
<p>
- Click " Default SLA". Select Sev-A and in this case, comment " Wide impact, customers unable to do online banking". Then click Update.
</p>
- Next, click on "Help Topic" and select " Report a Problem/Business Critical Outage". Comment: " No customers are able to access online banking."
</p>
- Lastly, click "Unassigned" and click on Online Banking. Comment: " Customers not able to access online banking portal, assigning to online banking team." Click Assign.
<br />



<p>

![95](https://github.com/user-attachments/assets/d39416a2-4715-4e45-8907-3c788d28dbc0)

</p>
<p>
- Under the Ticket Thread, you can see updates on the ticket. This helps us keep track of everything.
</p>
<br />


<p>

![97](https://github.com/user-attachments/assets/d089e09b-352d-414d-bb5e-8249bc2f0408)
![98](https://github.com/user-attachments/assets/9634f541-df6c-4655-8691-35ee85b4dffc)

</p>
<p>
- To proceed, log out of the current session by selecting Logout in the top-right corner, then log back in using the credentials for Jane (Username: Jane, Password: Password1). Upon successful authentication, you will see a confirmation message displaying "Welcome, Jane" in the top-right corner. Click on the ticket,
</p>
- Next were going to assign the Ticket to Jane. Click on "Online Banking".
<br />



<p>

![99](https://github.com/user-attachments/assets/8ab71e2a-fb84-4292-a99c-919df0902ca7)

</p>
<p>
- The Assignee will be Jane Doe. You  comment, "I'll be taking this ticket. Click Assign. " Online banking should now say " JaneDoe/Online Banking."
</p>

<br />


<p>

![100](https://github.com/user-attachments/assets/8c18f708-e807-43ee-8ea7-6ce60bff6cb1)
![101](https://github.com/user-attachments/assets/bb274994-1999-422c-abcf-4fb61daa4d15)

</p>
<p>
- Scroll down to locate Karen’s ticket, where we will provide her with an update confirming that the root cause of the issue has been identified.
</p>
- Then we will let her know that the fix has been implemented and online banking is up and running again.
<br />


<p>

![102](https://github.com/user-attachments/assets/1538e021-ad94-47c7-81ce-f753bec05ae7)
![103](https://github.com/user-attachments/assets/e0489fdf-5cf7-4791-b638-7806b3191e6a)

</p>
<p>
- Here you see the update under the Ticket Thread. The ticket seems to be resolved.
</p>
- Scroll back up and click on Status, then  click Resolved.
<br />


<p>

![104](https://github.com/user-attachments/assets/d0a16ff1-5f93-4547-ae83-d838dda94879)
![105](https://github.com/user-attachments/assets/17c51a04-5d35-442b-b0f8-9a73126fbc87)

</p>
<p>
- A pop-up window will appear, ensure the Status field is set to "Resolved". In the comments section, you may briefly detail the implementation of the fix and confirm that the system is now operational.
</p>
- Congratulations! You have completed the ticket lifecycle from creation to resolution. Your screen should now display the confirmation message: "Status changed to Resolved." This marks your first fully processed ticket in osTicket, demonstrating your ability to navigate the system and deliver solutions. Well done! 🎉


<br />

<h2>Final Thoughts</h2>

Whew, what a ride! This osTicket lab threw me into the trenches, creating tickets, playing detective to find the root cause, and finally slapping that "Resolved" status on there like a victory stamp. It’s crazy how much goes into even a "simple" support ticket: SLAs breathing down your neck, making sure Karen in Accounting actually gets her answer, and leaving notes so the next person doesn’t lose their mind retracing my steps. Feels good to see the whole lifecycle from chaos to closure.  
</p>
Heads up! Make sure to always stop your VM's or delete it after you're done. You don't want a surprise bill coming around. 😅 💻
