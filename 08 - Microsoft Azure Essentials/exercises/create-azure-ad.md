## Creating an Azure Acctive Directory
A newly created Azure Account usually comes with a default Azure AD. This exercise is to create a different Azure AD within same account.

**Step 1:** From the Azure side panel select the **Azure Active Directory**, this will display the details of the default AD

![Default AD]()

**Step 2:** Click on the **Manage tenants** tab; then click the **Create** button to begin creating a new AD. Ubder **Basic** select **Azure Active Directory** as the tenant type. For the configuration tab, fill out the form with required information  

![AD Config]()

**Step 3:** To switch to newly created Azure AD, go to the “Manage Tenants” and select the newly created tenants, then click the “Switch” button.  

Bravo! You have successfully created a new AD and can now create other IAM object under this AD if you want to (Users, Groups, Servcie Principals etc)