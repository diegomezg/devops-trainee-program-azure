## Creating  Azure User & Group
For the exercise, the task would be completed under the default Azure Active Directory (due to limitations with subscriptions for a free tier account)

- **Step 1:** Ensure that you have switched back to the default AD, then from the Azure side panel select the **Azure Active Directory**, and from the next panel, select **Groups**

![Group Panel]()

- **Step 2:** Click on the **New Group** button to begin creating a new group. Leave the group type as **Security** and enter a **Group name** then create.  

![Group Config]()

- **Step 3:** To create a new user, navigate back to the AD page, select **Users** from the side panel, then click on “New user”. Fill out the information as required. you may want to select “let me create password” option and enter a password of your choice.

![User Config]()

- **Step 4:** Under the "Groups and roles" section, click on the "0 groups seleted" and select the group created in the previous steps, then create the user.

![Assign group]()

- **Step 5:** On a seperate browser (preferable private window), go to [portal.azure.com](portal.azure.com) and sign in with newly created user (may be required to change password). From the side panel, select AD (confirm the default AD is selected, otherwise switch to the default AD). Select “Users” from the side panel, and from the list of users select the new user that is logged in. Under the User profile, click on **Groups** to confirm the group that the user is assigned to, then also click on the **Assigned roles** to check select assigned roles. Notice that user has no roles so although new user has authenticated successfully user is not authorized to carry out any actions.

Good job! In a seperate exercise, roles will be assigned to the new user