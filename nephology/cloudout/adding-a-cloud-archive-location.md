# Adding a Cloud Archive Location

Using Amazon S3 as an example, let’s walk through adding an archive location:					 							

1. Click on the gear icon located on the top right bar of the web UI.

   The Settings menu appears.

![alt_text](images/image75.png "image_tooltip")

2. From the **Settings** menu, select **Archival Locations**.					

   The Archival Locations page appears.

3. Click the blue **+** icon.							

The Add Archival Location dialog box appears.

![alt_text](images/image76.png "image_tooltip")

4. In **Archival Type**, select **Amazon S3**.

   The Amazon S3 archival location fields appear.

![alt_text](images/image77.png "image_tooltip")

   Review the different inputs required for Amazon S3 as an archive. Feel free to browse other archive types to view required settings. 

5. Press **Cancel** when finished.

6. On the left pane of the web UI, select **SLA Domains** > **Local Domains**. The Local SLA Domains page appears.
7. Select the Camp Rubrik SLA Domain that you previously created. The SLA Domain page will load. 
8. Click the ellipses (`...`) at the top right corner of the SLA Domain page. Select **Edit**.				 							
9. Click **Configure Remote Settings** at the bottom of the dialog (depending on the resolution of your screen it may be necessary to scroll down).					 							
10. In Archival, click the toggle (if not already done). Notice the **Enable Instant Archive** option. Do not select it at this time although you can click the circled “`i`” to read what it does.

![alt_text](images/image78.png "image_tooltip")

   The Instant Archive feature can be enabled to instruct a Rubrik cluster to immediately queue a task to copy a new snapshot to a specified archival location. 

11. Press **Cancel**.