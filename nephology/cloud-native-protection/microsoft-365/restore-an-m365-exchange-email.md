# Restore an M365 Exchange email

To recover an M365 email from Polaris:

In the web UI, click **Exchange inventory card** > **View Users**. The Users page appears, with the list of all the Exchange Users.

![](<../../../.gitbook/assets/M365 Dashboard  View User.png>)

Click on the email account of the User.

![](<../../../.gitbook/assets/Exchage Users (Gold) Highlight.png>)

The **Overview** pane provides information regarding the object’s location, the SLA Domain applied, Oldest and Latest Snapshot, total snapshots, etc. This can vary depending on location and type of object. On the right-hand side there is a **Snapshots** calendar view. The next few steps will guide you on your journey to explore this more.

![](../../../.gitbook/assets/Calendar.png)

Select a date that has a blue dot by hovering over and then clicking on the blue dot (indicating there are recovery points from this day). All available snapshots are listed. An example screenshot below demonstrates all of the snapshots available for the selected mailbox. Note that the date and number of snapshots may differ from the following image.

![](<../../../.gitbook/assets/Email restore.png>)

Select the ellipses icon (`...`) next to one of the snapshots.

Click **Recover**. Next type in the search bar the word `update`. Four emails are shown.

Click on the checkbox in front of the `Weekly digest: Microsoft service update` and then click **Next**.

![](<../../../.gitbook/assets/Selct email.png>)

There are two options shown: **Restore to original user** and **Restore to another user**.

![](../../../.gitbook/assets/Restore.png)

Do not select any of the options at this time and click ![](../../../.gitbook/assets/Cross.png) to exit the dialog.

{% hint style="info" %}
**Trail Map:**

_Restore to original user_ - email restored directly on the original mailbox but in a dedicated folder.

_Restore to another user_  - email restored on a selected mailbox but in a dedicated folder.
{% endhint %}

In the Exchange Recovey UI, browse the content click on the Name.

![](<../../../.gitbook/assets/Exchage Users (Gold) Highlight.png>)

Browse the content of the mailbox.&#x20;



![](<../../../.gitbook/assets/Restore Browse highlight (1).png>)



Go to **Inbox** and Click on the checkbox in front of the `Weekly digest: Microsoft service update` and then click **Next**.

![](<../../../.gitbook/assets/Browse Inbox.png>)

Choose **Restore to original user** and Click on **Recover**.

This may take a few moments. Click on the **Events** icon ![](<../../../.gitbook/assets/Event Icon.png>) in the top left menu of the Rubrik UI to review the notification informing you that the email is restored.

![](<../../../.gitbook/assets/Events Dash.png>)

On your browser access the Office 365 environment.
