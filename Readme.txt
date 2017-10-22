 System Configuration Requirement:
 1.)  Visual Stdio 2015 or 2012
 2.)  SQL Server Management Stdio 2012 or 2014

These are the following steps to run this application:
1.)  Create a blank Database in your SQLServer.
2.)  Restore this database with blog.bak file.
3.)  Unzip the Blog file.
4.)  Open new project in visual stdio.
5.)  Browse the unzip blog folder.
6.)  Open Blog Folder click on Solution File.
7.)  Project will be loaded.
8.)  Click on Solution Explorer then click on UI folder and tham expand the Blog.
9.)  Now Open Web.Config.
10.) Go to connectionStrings segment and than change the data Source with your database engine name, change the userid, password and initial catalog(change with newly created batabase name) and save.
11.) Expand the UI Folder. Right Click on Blog Select 'Set as Startup Project'.
12.) Build the solution.
13.) Press Ctrl + F5
