<h1>IAM Identity and access management </h1>

<h2>👨‍💻What is user account in microsoft entra ID
A user account in Microsoft Entra ID is a digital identity that represents a person (or sometimes a service) within an organization’s cloud environment:</h2>

<p> 🔑 In simple terms:
It’s what allows someone to sign in and access resources like:
<b> - Microsoft 365 (Outlook, Teams, SharePoint) </b>
<b> - Azure services</b>
<b> - Company apps and systemsr </b>
   

<h2> What a user account includes </h2>
A typical Entra ID user account has:

- Username (UPN) → e.g. user@company.com
- Password / authentication methods (MFA, biometrics, etc.)
- Profile info → name, job title, department
- Permissions & roles → what the user is allowed to access
- Group memberships → used to assign access to apps/reso

  <h2>🔐 What it’s used for</h2>
- Authorization → controlling what you can access
- Single Sign-On (SSO) → one login for multiple apps
- Authentication → proving who you are (login)

    <h2>🔐 Types of Account</h2>
- Member users → employees in the organization
- Guest users → external users (e.g., partners) invited to access resources

 <h2>🔐How to create single user and multi user in Entra id </h2>

 🧑 💻
Method 1: Using the Entra Admin Center (most common)
1. Go to the Entra Admin Center 👉 https://entra.microsoft.com
2. Sign in with an admin account
3. In the left menu:
○ Click Users
○ Then click + New user
4. Choose:
○ Create new user
5. Fill in the details:
○ User name (UPN) → e.g. john@yourcompany.com
○ Name → John Smith
○ Password → auto-generate or create manually
○ Option to require password change at first login
6. (Optional but recommended):
○ Assign Groups
○ Assign Roles (e.g., User, Admin roles)
○ Add job info (department, title)
7. Click Create

<h2> Setting up Entra ID account</h2>
<img width="1383" height="727" alt="Image" src="https://github.com/user-attachments/assets/9144c456-fe51-4de8-915b-db0f5cf081f8" />

<h2> Creating users </h2>
<img width="1902" height="937" alt="Image" src="https://github.com/user-attachments/assets/4f1f2ebd-da6d-45c0-89ef-226326598ef6" />

<h3> Following through the steps, we can  </h3>
- We can uncheck the 'Derive from userpreincipal name' to allow you customise your 'Nick name'
<p> - We can also uncheck 'Autogenrated password box' to allow us manually set our password </p>
<img width="1909" height="831" alt="Image" src="https://github.com/user-attachments/assets/731404a9-9844-4888-a7c7-a86aee853cb7" />
