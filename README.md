# Repair-Suspect-Database

Repair Suspect Database in SQL Server 2008 to 2016



EXEC sp_resetstatus dbname

ALTER DATABASE dbname SET EMERGENCY

DBCC checkdb (dbname)

ALTER database dbname SET SINGLE_USER with ROLLBACK IMMEDIATE

DBCC CHECKDB (dbname, REPAIR_ALLOW_DATA_LOSS)

ALTER DATABASE dbname SET MULTI_USER
