{
  "Status": "Completed",
  "AssessmentId": "c3a7b6ed-df3b-4aac-869e-756ae26ce170",
  "Servers": [
    {
      "ServerAssessments": [
        {
          "ServerName": "DESKTOP-UHK11PS",
          "DatabaseName": "",
          "DatabaseRestoreFails": false,
          "FeatureId": "WindowsAuthentication",
          "IssueCategory": "Warning",
          "ImpactedObjects": [
            {
              "Name": "DESKTOP-UHK11PS",
              "ObjectType": "Instance",
              "ImpactDetail": "",
              "DatabaseObjectType": "Instance"
            }
          ],
          "MoreInformation": "An overview of Azure SQL Database and SQL Managed Instance security capabilities",
          "RuleMetadata": {
            "Description": "Azure SQL Database  supports two types of authentication 1) SQL Authentication, which uses a username and password 2) Azure Active Directory Authentication, which uses identities managed by Azure Active Directory and is supported for managed and integrated domains. Database users mapped with Windows authentication (integrated security) are not supported in Azure SQL Database.",
            "Id": "Database users mapped with Windows authentication (integrated security) are not supported in Azure SQL Database.",
            "HelpLink": "https://docs.microsoft.com/en-us/azure/azure-sql/database/security-overview#authentication",
            "Probes": [],
            "Enabled": true,
            "Level": 2,
            "Tags": [],
            "Message": "Federate the local Active Directory with Azure Active Directory. The Windows identity can then be replaced with the equivalent Azure Active Directory identities. Alternatively, migrate to SQL Server on Azure Virtual Machine.",
            "Parameters": {}
          },
          "RuleScope": "Server",
          "AppliesToMigrationTargetPlatform": "AzureSqlDatabase",
          "Timestamp": "2023-08-28T15:47:08.6367402+01:00"
        },
        {
          "ServerName": "DESKTOP-UHK11PS",
          "DatabaseName": "",
          "DatabaseRestoreFails": false,
          "FeatureId": "WindowsAuthentication",
          "IssueCategory": "Warning",
          "ImpactedObjects": [
            {
              "Name": "DESKTOP-UHK11PS",
              "ObjectType": "Instance",
              "ImpactDetail": "",
              "DatabaseObjectType": "Instance"
            }
          ],
          "MoreInformation": "An overview of Azure SQL Database and SQL Managed Instance security capabilities",
          "RuleMetadata": {
            "Description": "Azure SQL Managed Instance supports three types of authentication 1) SQL Authentication, which uses a username and password 2) Azure Active Directory Authentication and 3) Windows Authentication, which both use identities managed by Azure Active Directory and is supported for managed and integrated domains. Windows logins and users not in Azure Active Directory are not supported in Azure SQL Managed Instance.",
            "Id": "Database users mapped with Windows authentication (integrated security) should be remapped to equivalent Azure AD identities.",
            "HelpLink": "https://docs.microsoft.com/en-us/azure/azure-sql/database/security-overview#authentication",
            "Probes": [],
            "Enabled": true,
            "Level": 2,
            "Tags": [],
            "Message": "Synchronize the local Active Directory with Azure Active Directory. The Windows identity can then be replaced with the equivalent Azure Active Directory identities. Alternatively, migrate to SQL Server on Azure Virtual Machine.",
            "Parameters": {}
          },
          "RuleScope": "Server",
          "AppliesToMigrationTargetPlatform": "AzureSqlManagedInstance",
          "Timestamp": "2023-08-28T15:47:08.6368422+01:00"
        }
      ],
      "TargetReadinesses": {
        "AzureSqlDatabase": {
          "DatabasesListReadyForMigration": [
            "AdventureWorks2022",
            "WideWorldImporters"
          ],
          "DatabasesListNoSelectionForMigration": [],
          "DatabasesListWithUnhandledErrors": [],
          "AppliesToMigrationTargetPlatform": "AzureSqlDatabase",
          "NumberOfDatabasesReadyForMigration": 2,
          "NumberOfSecondaryAGDatabasesWithError": 0,
          "NumberOfServerBlockerIssues": 0,
          "NumberOfNonOnlineDatabases": 0,
          "TotalNumberOfDatabases": 2,
          "Errors": [],
          "RecommendationStatus": "Ready",
          "ServiceTiers": []
        },
        "AzureSqlManagedInstance": {
          "DatabasesListReadyForMigration": [
            "AdventureWorks2022",
            "WideWorldImporters"
          ],
          "DatabasesListNoSelectionForMigration": [],
          "DatabasesListWithUnhandledErrors": [],
          "AppliesToMigrationTargetPlatform": "AzureSqlManagedInstance",
          "NumberOfDatabasesReadyForMigration": 2,
          "NumberOfSecondaryAGDatabasesWithError": 0,
          "NumberOfServerBlockerIssues": 0,
          "NumberOfNonOnlineDatabases": 0,
          "TotalNumberOfDatabases": 2,
          "Errors": [],
          "RecommendationStatus": "Ready",
          "ServiceTiers": [
            "GeneralPurpose",
            "BusinessCritical"
          ]
        }
      },
      "Properties": {
        "ServerName": "DESKTOP-UHK11PS",
        "ProductName": "UNKNOWN",
        "FQDN": "DESKTOP-UHK11PS",
        "InstallId": "072968cf-3242-4390-885e-4dd2ccf90e5d",
        "ServerVersion": "16.0.1000.6",
        "ServerEdition": "Developer Edition (64-bit)",
        "ServerHostPlatform": "Windows",
        "ServerLevel": "RTM",
        "ServerDefaultBackupPath": "C:\\Program Files\\Microsoft SQL Server\\MSSQL16.MSSQLSERVER\\MSSQL\\Backup",
        "ServerDefaultDataPath": "C:\\Program Files\\Microsoft SQL Server\\MSSQL16.MSSQLSERVER\\MSSQL\\DATA\\",
        "ServerDefaultLogPath": "C:\\Program Files\\Microsoft SQL Server\\MSSQL16.MSSQLSERVER\\MSSQL\\DATA\\",
        "ServerCoreCount": 4,
        "ServerCollation": "SQL_Latin1_General_CP1_CI_AS",
        "ServerVisibleOnlineCoreCount": 4,
        "IsHadrEnabled": false,
        "IsBufferPoolExtensionEnabled": false,
        "IsClustered": false,
        "IsIntegratedSecurityOnly": true,
        "IsPolyBaseInstalled": false,
        "IsServerCaseSensitive": false,
        "LogicalCpuCount": 4,
        "HyperthreadRatio": 4,
        "PhysicalCpuCount": 1.0,
        "SqlStartTime": "2023-08-26T17:39:37.507",
        "MaxServerMemoryInUse": 2147483647.0,
        "NumberOfUserDatabases": 2,
        "SumOfUserDatabasesSize": 3444.0,
        "TempDbSize": 40.0,
        "NumOfLogins": 16,
        "TotalNumOfUserDefinedObjects": 26,
        "ServerPermissionsLevel": "MemberSysadmin",
        "LinkedServers": [],
        "AgentJobs": [],
        "AGInfo": {
          "AGs": [],
          "SyncReplicasCount": 0,
          "AsyncReplicasCount": 0,
          "AsyncReadReplicasCount": 0,
          "TotalAGDatabasesCount": 0
        },
        "IsRds": false
      },
      "Errors": [],
      "Status": "Completed",
      "XeventsFilesFolderPath": "",
      "Databases": [
        {
          "DatabaseAssessments": [],
          "TargetReadinesses": {
            "AzureSqlDatabase": {
              "AppliesToMigrationTargetPlatform": "AzureSqlDatabase",
              "State": "Online",
              "RecommendationStatus": "Ready",
              "NoSelectionForMigration": false,
              "NumOfBlockerIssues": 0,
              "Errors": [],
              "ServiceTiers": [
                "GeneralPurpose",
                "BusinessCritical",
                "Hyperscale"
              ]
            },
            "AzureSqlManagedInstance": {
              "AppliesToMigrationTargetPlatform": "AzureSqlManagedInstance",
              "State": "Online",
              "RecommendationStatus": "Ready",
              "NoSelectionForMigration": false,
              "NumOfBlockerIssues": 0,
              "Errors": [],
              "ServiceTiers": [
                "GeneralPurpose",
                "BusinessCritical"
              ]
            }
          },
          "Properties": {
            "Id": "d2793c50-4e71-42d0-b7d4-e235c7ed7997",
            "ServerDatabaseId": "5",
            "Name": "AdventureWorks2022",
            "CompatibilityLevel": "CompatLevel160",
            "Collation": "SQL_Latin1_General_CP1_CI_AS",
            "DatabaseState": "Online",
            "SizeMB": 272.0,
            "DatabaseFileLocationDrive": "\u0000",
            "DatabaseFiles": [
              {
                "LogicalName": "AdventureWorks2022",
                "PhysicalFullName": "C:\\Program Files\\Microsoft SQL Server\\MSSQL16.MSSQLSERVER\\MSSQL\\DATA\\AdventureWorks2022.mdf",
                "FileType": "Rows",
                "SizeMB": 200.0,
                "IsMemoryOptimizedDataOptionEnabled": false,
                "FilegroupName": "PRIMARY",
                "FilegroupType": "FG",
                "HasErrors": false,
                "ReportedErrors": {},
                "ReportedExceptions": []
              },
              {
                "LogicalName": "AdventureWorks2022_log",
                "PhysicalFullName": "C:\\Program Files\\Microsoft SQL Server\\MSSQL16.MSSQLSERVER\\MSSQL\\DATA\\AdventureWorks2022_log.ldf",
                "FileType": "Log",
                "SizeMB": 72.0,
                "IsMemoryOptimizedDataOptionEnabled": false,
                "FilegroupType": "NotApplicable",
                "HasErrors": false,
                "ReportedErrors": {},
                "ReportedExceptions": []
              }
            ],
            "IsServiceBrokerEnabled": false,
            "IsCdcEnabled": false,
            "IsReplicationEnabled": false,
            "NumOfUserDefinedObjects": 26,
            "TSqlScriptAnalysisTimeElapse": "00:00:00.0480408",
            "IsFullRecoveryModelSelected": true,
            "IsRdsAdmin": false,
            "IsTdeEnabled": false,
            "AGDatabaseInfo": {
              "AGDbSyncSecondaryReplicaCount": 0,
              "AGDbAsyncSecondaryReplicaCount": 0,
              "AGDbReadAsyncSecondaryReplicaCount": 0
            }
          },
          "Errors": [],
          "Status": "Completed",
          "FeatureDiscoveryTimeElapse": "00:00:01.0964268"
        },
        {
          "DatabaseAssessments": [
            {
              "ServerName": "DESKTOP-UHK11PS",
              "DatabaseName": "WideWorldImporters",
              "DatabaseRestoreFails": false,
              "FeatureId": "MemoryOptimizedTables",
              "IssueCategory": "Warning",
              "ImpactedObjects": [
                {
                  "Name": "[Warehouse].[ColdRoomTemperatures]",
                  "ObjectType": "Table",
                  "ImpactDetail": "",
                  "DatabaseObjectType": "Table"
                },
                {
                  "Name": "[Warehouse].[VehicleTemperatures]",
                  "ObjectType": "Table",
                  "ImpactDetail": "",
                  "DatabaseObjectType": "Table"
                },
                {
                  "Name": "[Website].[OrderIDList]",
                  "ObjectType": "UserDefinedTableType",
                  "ImpactDetail": "",
                  "DatabaseObjectType": "UserDefinedTableType"
                },
                {
                  "Name": "[Website].[OrderList]",
                  "ObjectType": "UserDefinedTableType",
                  "ImpactDetail": "",
                  "DatabaseObjectType": "UserDefinedTableType"
                },
                {
                  "Name": "[Website].[OrderLineList]",
                  "ObjectType": "UserDefinedTableType",
                  "ImpactDetail": "",
                  "DatabaseObjectType": "UserDefinedTableType"
                },
                {
                  "Name": "[Website].[SensorDataList]",
                  "ObjectType": "UserDefinedTableType",
                  "ImpactDetail": "",
                  "DatabaseObjectType": "UserDefinedTableType"
                }
              ],
              "MoreInformation": "Azure SQL Database unsupported feature for General Purpose tier.",
              "RuleMetadata": {
                "Description": "SQL Server provides an In-Memory OLTP capability. It allows usage of memory-optimized tables, memory-optimized table types, and natively compiled SQL modules to run workloads that have high-throughput and low-latency requirements for transactional processing. Azure SQL Database General Purpose service tier does not support in-memory OLTP (memory optimized tables). This feature is only supported in Azure SQL Database Business Critical service tier.",
                "Id": "Azure SQL Database General Purpose service tier does not support in-memory OLTP (memory optimized tables).",
                "HelpLink": "https://docs.microsoft.com/en-us/azure/azure-sql/in-memory-oltp-overview",
                "Probes": [],
                "Enabled": true,
                "Level": 2,
                "Tags": [],
                "Message": "If you have memory-optimized tables or memory-optimized table types in your on-premises SQL Server instance and you want to migrate to Azure SQL Database, you should either choose the Business Critical tier for your target Azure SQL database that supports In-Memory OLTP (OR) if you want to migrate to the General Purpose tier, remove memory-optimized tables, memory-optimized table types, and natively compiled SQL modules that interact with memory-optimized objects before migrating your databases. You can use the following T-SQL query to identify all objects that need to be removed before migration to the General Purpose tier: SELECT * FROM sys.tables WHERE is_memory_optimized=1, SELECT * FROM sys.table_types WHERE is_memory_optimized=1, SELECT * FROM sys.sql_modules WHERE uses_native_compilation=1",
                "Parameters": {}
              },
              "RuleScope": "Database",
              "AppliesToMigrationTargetPlatform": "AzureSqlDatabase",
              "Timestamp": "2023-08-28T15:47:08.6368917+01:00"
            },
            {
              "ServerName": "DESKTOP-UHK11PS",
              "DatabaseName": "WideWorldImporters",
              "DatabaseRestoreFails": false,
              "FeatureId": "MemoryOptimizedTables",
              "IssueCategory": "Warning",
              "ImpactedObjects": [
                {
                  "Name": "[Warehouse].[ColdRoomTemperatures]",
                  "ObjectType": "Table",
                  "ImpactDetail": "",
                  "DatabaseObjectType": "Table"
                },
                {
                  "Name": "[Warehouse].[VehicleTemperatures]",
                  "ObjectType": "Table",
                  "ImpactDetail": "",
                  "DatabaseObjectType": "Table"
                },
                {
                  "Name": "[Website].[OrderIDList]",
                  "ObjectType": "UserDefinedTableType",
                  "ImpactDetail": "",
                  "DatabaseObjectType": "UserDefinedTableType"
                },
                {
                  "Name": "[Website].[OrderList]",
                  "ObjectType": "UserDefinedTableType",
                  "ImpactDetail": "",
                  "DatabaseObjectType": "UserDefinedTableType"
                },
                {
                  "Name": "[Website].[OrderLineList]",
                  "ObjectType": "UserDefinedTableType",
                  "ImpactDetail": "",
                  "DatabaseObjectType": "UserDefinedTableType"
                },
                {
                  "Name": "[Website].[SensorDataList]",
                  "ObjectType": "UserDefinedTableType",
                  "ImpactDetail": "",
                  "DatabaseObjectType": "UserDefinedTableType"
                }
              ],
              "MoreInformation": "Azure SQL Managed Instance unsupported feature for General Purpose tier.",
              "RuleMetadata": {
                "Description": "SQL Server provides an In-Memory OLTP capability. It allows usage of memory-optimized tables, memory-optimized table types, and natively compiled SQL modules to run workloads that have high-throughput and low-latency requirements for transactional processing. Azure SQL Managed Instance General Purpose service tier does not support in-memory OLTP (memory optimized tables). This feature is only supported in Azure SQL Managed Instance Business Critical service tier.",
                "Id": "Azure SQL Managed Instance General Purpose service tier does not support in-memory OLTP (memory optimized tables).",
                "HelpLink": "https://docs.microsoft.com/en-us/azure/azure-sql/migration-guides/managed-instance/sql-server-to-managed-instance-overview#in-memory-oltp-memory-optimized-tables",
                "Probes": [],
                "Enabled": true,
                "Level": 2,
                "Tags": [],
                "Message": "If you have memory-optimized tables or memory-optimized table types in your on-premises SQL Server instance and you want to migrate to Azure SQL Database, you should either choose the Business Critical tier for your target Azure SQL database that supports In-Memory OLTP (OR) if you want to migrate to the General Purpose tier, remove memory-optimized tables, memory-optimized table types, and natively compiled SQL modules that interact with memory-optimized objects before migrating your databases. You can use the following T-SQL query to identify all objects that need to be removed before migration to the General Purpose tier: SELECT * FROM sys.tables WHERE is_memory_optimized=1, SELECT * FROM sys.table_types WHERE is_memory_optimized=1, SELECT * FROM sys.sql_modules WHERE uses_native_compilation=1",
                "Parameters": {}
              },
              "RuleScope": "Database",
              "AppliesToMigrationTargetPlatform": "AzureSqlManagedInstance",
              "Timestamp": "2023-08-28T15:47:08.6369118+01:00"
            }
          ],
          "TargetReadinesses": {
            "AzureSqlDatabase": {
              "AppliesToMigrationTargetPlatform": "AzureSqlDatabase",
              "State": "Online",
              "RecommendationStatus": "Ready",
              "NoSelectionForMigration": false,
              "NumOfBlockerIssues": 0,
              "Errors": [],
              "ServiceTiers": [
                "GeneralPurpose",
                "BusinessCritical",
                "Hyperscale"
              ]
            },
            "AzureSqlManagedInstance": {
              "AppliesToMigrationTargetPlatform": "AzureSqlManagedInstance",
              "State": "Online",
              "RecommendationStatus": "Ready",
              "NoSelectionForMigration": false,
              "NumOfBlockerIssues": 0,
              "Errors": [],
              "ServiceTiers": [
                "GeneralPurpose",
                "BusinessCritical"
              ]
            }
          },
          "Properties": {
            "Id": "c73db044-b812-438f-b03d-620fbbe1aea5",
            "ServerDatabaseId": "6",
            "Name": "WideWorldImporters",
            "CompatibilityLevel": "CompatLevel130",
            "Collation": "Latin1_General_100_CI_AS",
            "DatabaseState": "Online",
            "SizeMB": 3172.0,
            "DatabaseFileLocationDrive": "\u0000",
            "DatabaseFiles": [
              {
                "LogicalName": "WWI_Primary",
                "PhysicalFullName": "C:\\Program Files\\Microsoft SQL Server\\MSSQL16.MSSQLSERVER\\MSSQL\\DATA\\WideWorldImporters.mdf",
                "FileType": "Rows",
                "SizeMB": 1024.0,
                "IsMemoryOptimizedDataOptionEnabled": false,
                "FilegroupName": "PRIMARY",
                "FilegroupType": "FG",
                "HasErrors": false,
                "ReportedErrors": {},
                "ReportedExceptions": []
              },
              {
                "LogicalName": "WWI_Log",
                "PhysicalFullName": "C:\\Program Files\\Microsoft SQL Server\\MSSQL16.MSSQLSERVER\\MSSQL\\DATA\\WideWorldImporters.ldf",
                "FileType": "Log",
                "SizeMB": 100.0,
                "IsMemoryOptimizedDataOptionEnabled": false,
                "FilegroupType": "NotApplicable",
                "HasErrors": false,
                "ReportedErrors": {},
                "ReportedExceptions": []
              },
              {
                "LogicalName": "WWI_UserData",
                "PhysicalFullName": "C:\\Program Files\\Microsoft SQL Server\\MSSQL16.MSSQLSERVER\\MSSQL\\DATA\\WideWorldImporters_UserData.ndf",
                "FileType": "Rows",
                "SizeMB": 2048.0,
                "IsMemoryOptimizedDataOptionEnabled": false,
                "FilegroupType": "NotApplicable",
                "HasErrors": false,
                "ReportedErrors": {},
                "ReportedExceptions": []
              },
              {
                "LogicalName": "WWI_InMemory_Data_1",
                "PhysicalFullName": "C:\\Program Files\\Microsoft SQL Server\\MSSQL16.MSSQLSERVER\\MSSQL\\DATA\\WideWorldImporters_InMemory_Data_1",
                "FileType": "Filestream",
                "SizeMB": 0.0,
                "IsMemoryOptimizedDataOptionEnabled": false,
                "FilegroupType": "NotApplicable",
                "HasErrors": false,
                "ReportedErrors": {},
                "ReportedExceptions": []
              }
            ],
            "IsServiceBrokerEnabled": false,
            "IsCdcEnabled": false,
            "IsReplicationEnabled": false,
            "NumOfUserDefinedObjects": 0,
            "TSqlScriptAnalysisTimeElapse": "00:00:00",
            "IsFullRecoveryModelSelected": true,
            "IsRdsAdmin": false,
            "IsTdeEnabled": false,
            "AGDatabaseInfo": {
              "AGDbSyncSecondaryReplicaCount": 0,
              "AGDbAsyncSecondaryReplicaCount": 0,
              "AGDbReadAsyncSecondaryReplicaCount": 0
            }
          },
          "Errors": [],
          "Status": "Completed",
          "FeatureDiscoveryTimeElapse": "00:00:01.1854986"
        }
      ]
    }
  ],
  "Errors": [],
  "StartedOn": "2023-08-28T15:47:04.3526915+01:00",
  "EndedOn": "2023-08-28T15:47:08.6383716+01:00",
  "XeventsFilesFolderPath": ""
}
