## Assign Role to a User
This exercise assumes that the user is already created and able to authenticate on Azure.

Ensure that you have switch back to the default AD, then from the Azure side panel select the **Azure Active Directory**, and from the next panel, select **Users**. From the list of users, select the the respective user and under the user profile, select "Assigned roles" then click "Add assignment" to select a built-in role eg Global Administrator

![Assign Role]()

With the assigned role, the User is now authorized to carry out actions on the Azure resources. However, to start using this access, the user profile would have to be linked to subscription account. ( May not be able to implement this as free tier account due to limitation)

With this exercise, a built-in role has been successfully assigned to a new user, and user can start accessing resource that are authorized by the role if a subscription account is linked to the user.

**Note:** Ideally you want assigned roles to group and add the user in the group to inherit the permissions. Again, assigning roles to a group required an upgrade account and may not be demonstrated with a free tier account.