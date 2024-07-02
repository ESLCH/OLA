# OLA
All scripts from OLA Hallengren
Solution/Ola_Maintenance_Solution
SQL Server Backup, Integrity Check, and Index and Statistics Maintenance
Source link: ola.hallengren.com

The SQL Server Maintenance Solution comprises scripts for running backups, integrity checks, and index and statistics maintenance on all editions of Microsoft SQL Server 2005, SQL Server 2008, SQL Server 2008 R2, SQL Server 2012, SQL Server 2014 and SQL Server 2016. The solution is based on stored procedures, the sqlcmd utility, and SQL Server Agent jobs. Ola Hallengren designed the solution for the most mission-critical environments, and it is used in many organizations around the world. Numerous SQL Server community experts recommend the SQL Server Maintenance Solution, which has been a Gold winner in the 2013, 2012, 2011, and 2010 SQL Server Magazine Awards. The SQL Server Maintenance Solution is free.

Getting Started
Download MaintenanceSolution.sql. This script creates all the objects and jobs that you need. Learn more about using the SQL Server Maintenance Solution.

You can also download the objects as separate scripts:

DatabaseBackup: SQL Server Backup
DatabaseIntegrityCheck: SQL Server Integrity Check
IndexOptimize: SQL Server Index and Statistics Maintenance
CommandExecute: Stored procedure to execute and log commands
CommandLog: Table to log commands
Note that you always need CommandExecute, DatabaseBackup, DatabaseIntegrityCheck, and IndexOptimize are using it. You need CommandLog if you are going to use the option to log commands to a table.
