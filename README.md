# Databricks-UI

### Why is this so hard to navigate/unintuitive (or maybe it's me. But it can't be, databricks is wrong)? Therefore...

#### Main Menu
- the Databricks Logo found at the top left side bar.
- the Main menu gives most Databricks functionalities to do what you need to do. Common Tasks include: New Notebook, Create Table, New Cluster, etc. 
- the main menu is also where you can import data from your local machine. Just hold and drag to the middle 'import area'
- under Recents is where you will find which notebooks you have recently worked on

#### Create
Options to create a:
- Notebook
- Table
- Cluster
- Job

#### Work Space
- where you can see your file directory

#### Repos
- where you can connect to github? Will explore later

#### Data
- You can see all your tables and databases here.
- in order to see your saved and exported tables directory (exported as in a table you want to have persistence with), click on 'Create Table' and then DBFS
- under tables, you can see your saved tables 
- your imported csv files are in DBFS > FileStore > tables
- your saved tables can be found in DBFS > hive > warehouse

#### Compute
- where you can create, terminate, or delete clusters

#### Jobs
- where you can create pipelines to schedule jobs

### Additional Info

#### How to delete notebooks or tables or directories
Workspaces 
- in order to copy/delete/create/movea folder or a notebook, go to WorkSpaces > and then hit the drop down option to the upper right of a folder. 
- Deleted items are moved to the trash and are permenantly deleted after 30 days
Tables
- in order to see your exported tables, look under data > tables
- you can delete a table (permenantly) with the drop down button right by the table 

