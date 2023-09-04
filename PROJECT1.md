# STEPS FOLLOWED TO ACHIEVE THE ASSESSMENT
#### First you need to Set up the SSMS and download Data migration instance.  
##### To Download the two database instance. click on the link 
####  (https://github.com/Microsoft/sql-server-samples/releases/tag/wide-world-importers-v1.0) and https://learn.microsoft.com/en-us/sql/samples/adventureworks-install-configure?view=sql-server-ver16&tabs=ssms
1. Go to SSMS, connect and restore the database by right clicking on the **DATABASE* to restore the database. ![restore-db-ssms1](https://github.com/kabirmohd/UNDP_RELIANCE_PROGRAM/assets/139928266/9ce3f5f7-d683-4438-99c0-8311b9ebfe9b)

2. Click on Device, locate the device, click add,copy the link and go to file explorer and paste(This pc)
3. Copy the backup file;(Adventurework)
4. To continue in restoring the database,refresh and click ok. It will show restore successful.
5. click on the Adventurework database
6. Go to Data migration instance, click on the + icon to perform the assessement.![new-assessment](https://github.com/kabirmohd/UNDP_RELIANCE_PROGRAM/assets/139928266/75e8a36d-1db7-4a06-9d17-08b14a111e22)

7. Give the project a name e.g Adventurework_DB,check and choose the target server type(Azure SQL database) and click create.
8. Connect to a server by pasting the server name copied frm SSMS and connect.
9. Click on the database been worked on(Adventurework) on the sewrver. Click add, start the assessment and save.
10. Test against Azure SQL managed instance, the Azure VM.
