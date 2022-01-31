# Restore a file from Onedrive

To recover a Onedrive file from Polaris:

In the web UI, click **Onedrive inventory card** > **View Users**. The Users page appears, with the list of all the Exchange Users.

![](<../../../.gitbook/assets/Polaris Dash Protected OneDrive.png>)

Click the radio button **OneDrive** in the **Data Sources** listed on the left. Select the User on the list in the right pane.

![](<../../../.gitbook/assets/OneDrive Browse.png>)

The **Overview** pane provides information regarding the object’s location, the SLA Domain applied, Oldest and Latest Snapshot, total snapshots, etc. This can vary depending on location and type of object. On the right-hand side there is a **Snapshots** calendar view. The next few steps will guide you on your journey to explore this more.

![](<../../../.gitbook/assets/OneDrive Calendar.png>)

Select a date that has a green dot by hovering over and then clicking on the blue dot (indicating there are recovery points from this day). All available snapshots are listed. An example screenshot below demonstrates all of the snapshots available for the selected mailbox. Note that the date and number of snapshots may differ from the following image.

![](<../../../.gitbook/assets/OneDriveSnap List.png>)

Next type in the search bar the word `365`. One file are shown.

Click on the checkbox in front of the `Microsoft 365 - The 201 Pith Deck (Jan 2022).pptx` and **Recover**.&#x20;

![](<../../../.gitbook/assets/Select pptx.png>)

There are two options shown: **Restore to original user** and **Restore to another user**.

![](<../../../.gitbook/assets/Restore File.png>)

Choose **Restore to original user** and Click on **Recover**.

This may take a few moments. Click on the **Events** icon ![](<../../../.gitbook/assets/Events Ico.png>) in the top left menu of the Rubrik UI to review the notification informing you that the file is restored.

![](<../../../.gitbook/assets/Screenshot 2022-01-31 at 18.49.09.png>)

On your browser access the Office 365 test environment, [https://www.office.com](https://www.office.com/?auth=2). Use the credential provided by the Rubrik instructor.

Go to **OneDrive**, localize the recover folder in **My Files**.

![](<../../../.gitbook/assets/Screenshot 2022-01-31 at 18.50.00.png>)
