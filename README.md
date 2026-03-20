# AWS Lab: Creating Users and Groups in Active Directory

## 📌 Overview
This lab demonstrates how to create and manage users and security groups in Active Directory using a Windows EC2 instance configured as a domain controller.

---

## 🎯 Objective
- Create a new Active Directory user
- Configure user account settings
- Create a security group
- Understand basic identity and access management in AD

---

## 🎥 Video Walkthrough
[Click here to watch the Loom walkthrough] https://www.loom.com/share/1ff5e4acea4646c7a188006668268732

---

## 🛠️ Technologies Used
- AWS EC2 (Windows Server Domain Controller)
- Active Directory Users and Computers (ADUC)

---

## 🧠 Key Skills Demonstrated
- Active Directory user management
- Group creation and security configuration
- Identity and access management (IAM) fundamentals
- Windows Server administrative tools
- Organizational structure within AD

---

## 📸 Key Visual Highlights

### 1. Active Directory Users and Computers Console
<img width="1896" height="962" alt="ADUC-console" src="https://github.com/user-attachments/assets/b97045b1-66e2-460e-88a1-b4eac085e32a" />

### 2. Creating a New User
<img width="1866" height="954" alt="New-User" src="https://github.com/user-attachments/assets/6b3b6de6-334d-492b-97f7-c20e58927392" />

### 3. User Details Configuration (John Doe)
<img width="1843" height="926" alt="New-user-details" src="https://github.com/user-attachments/assets/b0151aa5-e547-4872-8305-238bffff5a89" />

### 4. Password Configuration Settings
<img width="1844" height="959" alt="new-user-pw" src="https://github.com/user-attachments/assets/0d4e57da-7a21-4929-807b-123dd80a28a8" />

### 5. Created User in Directory
<img width="1894" height="963" alt="User-created" src="https://github.com/user-attachments/assets/643c092e-36e6-44dc-9c75-cae95656ff0e" />

### 6. Creating a New Security Group
<img width="1883" height="945" alt="New-Security-group" src="https://github.com/user-attachments/assets/4d134c24-724a-412e-acc2-814803c3b5fe" />

### 7. Group Successfully Created
<img width="1862" height="932" alt="Group-created" src="https://github.com/user-attachments/assets/524443f6-d995-431c-8dc2-68d086d41c06" />

---

## 🔄 Full Step-by-Step Process

### 1. Open Active Directory Users and Computers
- In the search bar, type **Active Directory Users and Computers**
- Click to open the application

### 2. Navigate to Users Folder
- Expand your domain (**adlab.local**)
- Right-click **Users**
- Hover over **New**, then click **User**

### 3. Create New User
- Enter name: **John Doe**
- Set logon name: **John.Doe**
- Click **Next**

### 4. Set User Password
- Create a password and confirm it
- Click **Next**

### 5. Configure Password Settings
- Uncheck: **User must change password at next logon**
- Check: **Password never expires**
- Click **Next**

### 6. Complete User Creation
- Click **Finish**
- Verify that **John Doe** appears in the Users folder

### 7. Create a New Group
- Right-click inside the **Users** folder pane
- Hover over **New**, then click **Group**

### 8. Configure Group Settings
- Group name: **AD Lab**
- Group scope: **Global**
- Group type: **Security**
- Click **OK**

### 9. Verify Group Creation
- Confirm that the **AD Lab** security group appears in the directory

---

## 🔐 Security Considerations
- Avoid setting passwords to never expire in production environments  
- Enforce strong password policies  
- Use groups to manage permissions instead of assigning directly to users  
- Follow least privilege principles  

---

## 🚀 Outcome
Successfully created a user (**John Doe**) and a security group (**AD Lab**) in Active Directory, demonstrating foundational identity and access management skills.
