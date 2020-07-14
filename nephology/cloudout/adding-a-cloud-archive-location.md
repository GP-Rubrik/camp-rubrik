# Adding a Cloud Archive Location

Using Amazon S3 as an example, let’s walk through adding an archive location:

1. Click on the gear icon located on the top right bar of the web UI.

   The Settings menu appears.

![](https://lh4.googleusercontent.com/08KEhZ0Zetym-uy2L-_qqJn2PPrxZFBfyciZf0fLO6b36GSiENyhrIrDovsV54TTCQ_-iD7fsY2VIXChk5_N-b1XYotEGfzesEpZ5ZTyRaxd9t0cu4UFk3rjtr7lwZzGxx7_Stpb)

1. From the **Settings** menu, select **Archival Locations**.

   The Archival Locations page appears.

2. Click the blue **+** icon.

![](https://lh6.googleusercontent.com/LVrv2jjcLhIB5kZ54eQFWECbWn3Rdo5u9mVSWHgbIOW4Ls1j0Ze1NztRtPQ9-i9KczbJosyw2MWT8pvlfHYI20Amks1jbfe9LSuYhjXG_Xp-JGakLHyiVZMoOh3hJk_CmNmbWx9d)

The Add Archival Location dialog box appears.

1. In **Archival Type**, select **Amazon S3**.

   The Amazon S3 archival location fields appear.

![](https://lh4.googleusercontent.com/Ak9OJxHytOrnOnP_Ezrx3JRB0yo2xlGMduc_bYIf1uL-vvdwTmIN54tHeis-JTgpomEgEsFiMyhlbR6q48u6PjgrGlQIJs-Nvd3GWZtxJo3e3wvgSYauRoTPLauG3FiCgu-pQIKP)

Review the different inputs required for Amazon S3 as an archive. Feel free to browse other archive types to view required settings.

1. Press **Cancel** when finished.
2. On the left pane of the web UI, select **SLA Domains** &gt; **Local Domains**. The Local SLA Domains page appears.
3. Select the Camp Rubrik SLA Domain that you previously created. The SLA Domain page will load. 
4. Click the ellipses \(`...`\) at the top right corner of the SLA Domain page. Select **Edit**.                                             
5. Click **Configure Remote Settings** at the bottom of the dialog \(depending on the resolution of your screen it may be necessary to scroll down\).                                                 
6. In Archival, click the toggle \(if not already done\). Notice the **Enable Instant Archive** option. Do not select it at this time although you can click the circled “`i`” to read what it does.

![](https://lh5.googleusercontent.com/5cNsnDgGkE20DeySY-B7DA389b9CTQEBgJSAHrUShLgAiFmCIu5hGE4wWXAOCcDO9_cFx9dKMXaNAWF4wWau7hEXjUcPlAaxuinMvMIasqXTTXS8SY1YhEyy0ycxFHaLR9-Wzquc)

The Instant Archive feature can be enabled to instruct a Rubrik cluster to immediately queue a task to copy a new snapshot to a specified archival location.

1. Press **Cancel**.
