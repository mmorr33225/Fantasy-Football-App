# Fantasy-Football-App
CSC 4402 Project
----------------------------------------------------------------------------------------

The FantasyFootballAppProjectFile.zip is the full Visual Studios project file. If you want to look at the code you can run the .sln file.

HOWEVER 

You don't need that file I just included it just in case.

To actually run the app everything you need is in the FantasyFootballAppV1.0.zip 

The app is the FantasyFootballApp.exe found in the FantasyFootballAppV1.0.zip and the config file mentioned below is also in that folder.



Before running the FantasyFootballApp.exe:
-----------------------------------------------------------------------
1) The 2 SQL database files are included. Attach them to your database first.

2) Make sure to replace the sql connection string with the connection string for your SQL database

Open the FantasyFootballApp.dll.config file with any text editor and make the change to the line below:

connectionString="Data Source=(LocalDB)\MSSQLLocalDB;MultipleActiveResultSets=True;Initial Catalog=FantasyFootballApp;Integrated Security=True"providerName="System.Data.SqlClient" />

Replace "(LocalDB)\MSSQLLocalDB" with the name of your database
----------------------------------------------------------------------------------------------------------------------------------------------



Additional Comments:

When looking at the Play Tournament Tab or Tournament table in SQL one team will have a Null match up and get a free win as there is an odd number of teams. This is intended. 
