# Apply an SLA Domain

An SLA Domain may be applied at a broad level - such as the entire Microsoft 365 Subscription (e.g. see image below), folder, host, cluster, or tag. This enables newly provisioned workloads to automatically inherit protection from a higher level resource. Alternatively, an SLA Domain may be granularly applied per object to achieve specific data protection objectives.

To do so:

In the web UI, click **Exchange inventory card** > **View Users**. The Users page appears, with the list of all the Exchange Users.

![](<../../../.gitbook/assets/M365 Dashboard  View User.png>)

Select a User.

Notice that the **Manage Protection** button in the upper right-hand corner illuminates and is now clickable. Do not assign an SLA Domain at this time.

![](<../../../.gitbook/assets/Exchage Users.png>)

To place a granular policy on an individual object you can also search for your user. Type in `your user name` in the **Search for email or display name** field to locate it.

![](<../../../.gitbook/assets/Exchange Search.png>)

Select the UserX and click **Manage Protection**.

Find and select the previously created `Camp Rubrik` SLA Domain and press **Next**.

![](<../../../.gitbook/assets/Assign SLA.png>)

Review the retention change caused by changing the SLA Domain.

![](<../../../.gitbook/assets/Manage Protection.png>)

Click **Submit**.

The User will soon update to reflect it is protected by the selected SLA Domain.
