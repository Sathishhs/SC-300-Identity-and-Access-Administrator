---
lab:
    title: '14 - Enable sign in and user risk policies'
    learning path: '02'
    module: 'Module 02 - Implement an Authentication and Access Management Solution'
---

# Lab 14 - Enable sign in and user risk policies

## Lab scenario

As an additional layer of security, you need to enable and configure your Azure AD organization's sign in and user risk policies.

#### Estimated time: 10 minutes


### Exercise 1 - Enable User risk policy

#### Task 1 - Configure the policy

1. Sign in to the [https://portal.azure.com]( https://portal.azure.com) using a conditional access administrator account.

3. Open the portal menu and then select **Azure Active Directory**.

4. On the Azure Active Directory page, under **Manage**, select **Security**.

5. On the Security page, in the left navigation, select **Identity protection**.

6. In the Identity protection page, in the left navigation, select **User risk policy**.

    ![Screen image displaying the User risk policy page and highlighted browsing path](./media/lp2-mod4-browse-to-identity-protection.png)

7. Under **Assignments**, select **All users** and review the available options.

8. You can select from **All users** or **Select individuals and groups** if limiting your rollout.

9. Additionally, you can choose to exclude users from the policy.

10. Under **User risk**, select **Low and above**.

11. In the User risk pane, select **High** and then select **Done**.

12. Under **Controls** > **Access**, select **Block access**.

13. In the Access pane, review the available options.

    **Tip** - Microsoft's recommendation is to Allow access and Require password change.

14. Select the **Require password change** check box and then select **Done**.

15. Under **Policy enforcement**, select **On** and then select **Save**.

#### Task 2 - Enable Sign-in risk policy

1. On the Identity protection page, in the left navigation, select **Sign-in risk policy**.

2. As with the User risk policy, the Sign-in risk policy can be assigned to users and groups and allows you to exclude users from the policy.

3. Under **Sign-in risk**, select **Low and above**.

4. In the Sign-in risk pane, select **High** and then select **Done**.

5. Under **Controls** > **Access**, select **Block access**.

6. Select the **Require multi-factor authentication** check box and then select **Done**.

7. Under **Policy enforcement**, select **On** and then select **Save**.
