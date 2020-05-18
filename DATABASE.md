# To import Database to SQL Server:

1. Download and install SQL Management Studio 17.9 or later (https://docs.microsoft.com/en-us/sql/ssms/release-notes-ssms?view=sql-server-2017#previous-ssms-releases)

**NOTE** *SSMS 17.9 or later is required to resolve any compatibility issues with older versions.*

2. Extract PremierCare.bacpac from the Zip file.
3. Open Microsoft SQL Server Management Studio.
4. Click connect.

**NOTE** *If you have issues connecting to SQL Server, be sure to check your Services (services.msc) and verify that both 'SQL Server (MSSQLSERVER)' and 'SQL Server Browser' are running. If not, right-click on those services and select 'Start'.*

5. In Object Explorer, right-click on 'Databases', then select 'Import Data-tier Application'.
6. Click Next.
7. Select 'Import from Local Disk'. Click Browse.
8. Navigate to the directory where you extracted the PremierCare.bacpac file and select it, then press Open.
9. Click Next.
10. Click Next again.
11. Click Finish.
12. Once complete, click Close.
