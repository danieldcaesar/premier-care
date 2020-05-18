# Connect the Database to the PremierCare application:

**Ensure that you have followed the instructions in DATABASE.md before completing these instructions.**

### Part 1
1. Open Visual Studio solution (.sln) file.
2. Go to Server Explorer --> click 'Connect to Database'.
3. Under Server Name, select your PC.
4. Select your authentication method and enter your login credentials (if required).
5. Under 'Connect to a database', click 'Select or enter a database name.'
6. Select 'PremierCare'.
7. Click OK.

### Part 2
1. Go to Server Explorer
2. Right-click PremierCare.dbo, click 'Properties'.
3. In the Properties pane --> Connection, copy the enitre Connection String.
4. Go to Solution Explorer --> Classes.
5. Right-click GlobalClass.cs --> Select "View Code".
6. Change the connectionString value to your DB's connection string.
7. Save file.