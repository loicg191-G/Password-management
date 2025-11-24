<h1>Password policy configuration</h1>
This tutorial shows how to configure account lockout policy in Active Directory using Group Policy.
<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Active Directory

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Account Lockout Policy Settings</h2>
<p>
<img width="520" height="276" alt="image" src="https://github.com/user-attachments/assets/c0e8fa29-a9b2-4e54-bf54-d71db034abe3" />
<img width="1553" height="1044" alt="image" src="https://github.com/user-attachments/assets/1c7b6435-c5ee-48d3-8efc-bb94bdd90bc7" />
<p>
In the Domain Controller machine, in the "Run" section, type "gpmc.msc". This will open the "Group Policy Management". From there, right-click the group policy object and select "edit" to modify it.
<p>
<img width="2005" height="791" alt="image" src="https://github.com/user-attachments/assets/d398bc9c-674d-401f-bec9-f66d06141465" />
<img width="553" height="669" alt="image" src="https://github.com/user-attachments/assets/b23a4f44-e98e-476f-9087-de08944bda54" />
</p>
Once the "Group Policy Management Editor" window appears, expand the sections as shown in the image, up to "Account Lockout Policy". Finally double-click the setting(s) that needs to be configured (in this instance it is "Account Lockout Duration"). Click "Apply" and "OK" to confirm.
</p>
<br />
