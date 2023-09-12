#steps to create a backup account

login into azure portal 

goto resources to create a storage account creating storage account

after creating the storage account goto container

create new container creating container

generate SAS key generating sas token

goto access key and shared access tokens to configure the permission on what acttion to perform on the container, and generate tokens and select the validity of the access, then generate SAS Token which contain the URL, that will grant you read and write grant access using shared access

CREATE credentials

then use the querry to create backup using the url generate. backup database

go to azure container to confirm the backup confirming Database in azure

to try restoring the database you have to delete it, but make sure the Backup was successfully

after successfully restoring a deleted database 
