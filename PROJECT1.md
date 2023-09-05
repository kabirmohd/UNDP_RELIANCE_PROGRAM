# STEPS FOLLOWED TO ACHIEVED THE ASSESSMENT
#### First you need to Set up the SSMS and download Data migration instance.  
##### To Download the two database instance. click on the link 
####  (https://github.com/Microsoft/sql-server-samples/releases/tag/wide-world-importers-v1.0) and https://learn.microsoft.com/en-us/sql/samples/adventureworks-install-configure?view=sql-server-ver16&tabs=ssms
1. Go to SSMS, connect and restore the database by right clicking on the *DATABASE* to restore the database. ![restore-db-ssms1](https://github.com/kabirmohd/UNDP_RELIANCE_PROGRAM/assets/139928266/9ce3f5f7-d683-4438-99c0-8311b9ebfe9b)

2. Tab on Device and click add copy to the link then go to file explorer and paste to (This pc)
3. Copy the backup file;(Adventurework)
4. To continue in restoring the database,refresh and click ok. It will show restore successful.
5. click on the Adventurework database
6. Go to Data migration instance, click on the + icon to perform the assessement.![new-assessment](https://github.com/kabirmohd/UNDP_RELIANCE_PROGRAM/assets/139928266/75e8a36d-1db7-4a06-9d17-08b14a111e22)

7. Project a name e.g Adventurework_Database,choose the target server type(Azure SQL database) and click create.![{061A5889-9498-404C-81E6-0A3A28CCE284} png](https://github.com/kabirmohd/UNDP_RELIANCE_PROGRAM/assets/139928266/6a227fcc-6188-4136-91aa-711b191085b1)

8. Connect to a server by pasting the server name copied frm SSMS and connect.![{758EB80A-27FA-4047-B65B-F076486D302F}2](https://github.com/kabirmohd/UNDP_RELIANCE_PROGRAM/assets/139928266/ff24a4d2-e87d-40e0-9bc6-aac1e1a0eced)

9. Tab on the database (Adventurework) on the server. Click add to start the assessment and save.![Inked{30056701-53DE-4F2A-9B3E-CADD4B918151}3_LI](https://github.com/kabirmohd/UNDP_RELIANCE_PROGRAM/assets/139928266/f204a02c-b4bc-415a-8f78-fb85679f8153)

10. Test against Azure SQL managed instance, the Azure VM.
