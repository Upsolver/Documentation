---
description: This procedure describes how to configure Okta with SAML sign-on.
---

# Okta with SAML sign-on

## Configure Okta with SAML sign-on

1. In Okta, select **Classic UI**.

2. Select **Applications &gt; Applications** and click **Add Application**.

4. Click **Create New App** and select **SAML 2.0**.

5. Click **Create**.

6. In the **App Name** field, enter **Upsolver**, then click **Next**.

7. Copy the information from Upsolver into the following fields:

* **Single sign on URL** — copy from the **Single Sign On URL** in Upsolver.
* **Audience URI \(Entity ID\)** — copy from the **Audience URI** in Upsolver.

{% hint style="info" %}
The **Single Sign On URL** and the **Audience URI** can both be found by navigating to the **SAML Integration** page \(**More &gt; SAML**\).
{% endhint %}

8. In **Attribute Statements**, enter the following in the **Name** and **Value** fields respectively:

| Name | Value |
| :--- | :--- |
| **email** | **usermail** |
| **firstName** | **userfirstName** |
| **lastName** | **userlastName** |

9. In **Group Attribute Statements**, enter the following in the **Name** and **Value** fields respectively:

| Name | Filter | Value |
| :--- | :---- | :--- |
| **groups** | **Matches regex** | **.\*** |

10. Click **Next**.

11. Select **I'm an Okta customer adding an external app**.

12. Click **Finish**.

13. Click **View Setup Instructions**.

14. In Upsolver, click **Edit Integration** and copy the information from Okta into the following fields:

* **Single Sign On URL** — copy from the **Identity Provider Single Sign-On URL** field in Okta.
* **Identity Provider Issuer** — copy from the **Identity Provider Issuer** field in Okta.
* **X 509 Certificate** — copy from the **X.509 Certificate** field in Okta.

15. Under the **Assignments** tab, and select **Assign &gt; Assign to People**.

16. Next to the required user, click **Assign** and then click **Done**.

17. Click **Save and Go Back**.

18. Click **Done**.

19. Click **My Apps** and then test access to Upsolver.

20. Complete the procedure as described above.

