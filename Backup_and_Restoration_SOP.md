# Standard Operating Procedure

**Purpose**: to lay down a procedure for the backup/restoration of electronic data of all computerized systems on the network(s) of a given client. 

Performing Backup and Restoration of User Data, Critical Infrastructure, Configurations, and Hosted Data:


1. Create two scripts using the command, robocopy.exe with correct source and destination 
Examples: 
   - User profile data script 
   - OS data script 

2. Set action and trigger accordingly using Windows Task Scheduler 
    - User profile data: Daily 
    - OS data: Every week
3. Mass deploy with PXE boot

For more information, contact the Blue Steele Helpdesk by phone or email. 

~Emily Lee

