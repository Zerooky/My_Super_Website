value
# REPORTINGS
  | Property | Value |
| --- | --- |
| SQL Server Version | 14.0.2027.2 |
| Compatibility Level | 130 |
| Collation | French_CI_AS |
----
  ## Schemas
  <details><summary>Click to expand</summary>  
* [dbo](#dbo)
  ### dbo
  </details>
  ## Tables
  <details><summary>Click to expand</summary>  
* [dbo.partners_smile_angels_hresa_cars](#dbopartners_smile_angels_hresa_cars)
* [dbo.partners_smile_angels_hresa_hotels](#dbopartners_smile_angels_hresa_hotels)
* [dbo.partners_smile_angels_misterfly_cars](#dbopartners_smile_angels_misterfly_cars)
* [dbo.partners_smile_angels_misterfly_flights](#dbopartners_smile_angels_misterfly_flights)
* [dbo.partners_smile_angels_misterfly_hotels](#dbopartners_smile_angels_misterfly_hotels)
* [dbo.partners_smile_angels_misterfly_transfers](#dbopartners_smile_angels_misterfly_transfers)
  ### dbo.partners_smile_angels_hresa_cars
  #### Columns
  | Column | Type | Null | Foreign Key | Default | Description |
| --- | --- | --- | --- | --- | --- |
| UserCode | VARCHAR(MAX) | no |  |  |  |
| CriterionCode | VARCHAR(MAX) | yes |  |  |  |
| Value | NUMERIC(18,0) | no |  |  |  |
| SaleDate | VARCHAR(MAX) | yes |  |  |  |
| CompletionDate | VARCHAR(MAX) | yes |  |  |  |
| Comment | VARCHAR(MAX) | no |  |  |  |
| Reference | VARCHAR(MAX) | yes |  |  |  |
| Active | INT | yes |  |  |  |
| Status | INT | no |  |  |  |
| BeingSent | INT | no |  |  |  |
| Sent | INT | no |  |  |  |
| TimeStamp_Added | DATETIME | no |  |  |  |
| TimeStamp_Sent | DATETIME | yes |  |  |  |
  [Back to top](#reportings)
  ### dbo.partners_smile_angels_hresa_hotels
  #### Columns
  | Column | Type | Null | Foreign Key | Default | Description |
| --- | --- | --- | --- | --- | --- |
| UserCode | VARCHAR(MAX) | no |  |  |  |
| CriterionCode | VARCHAR(MAX) | yes |  |  |  |
| Value | NUMERIC(18,0) | no |  |  |  |
| SaleDate | VARCHAR(MAX) | yes |  |  |  |
| CompletionDate | VARCHAR(MAX) | yes |  |  |  |
| Comment | VARCHAR(MAX) | no |  |  |  |
| Reference | VARCHAR(MAX) | yes |  |  |  |
| Active | INT | yes |  |  |  |
| Status | INT | no |  |  |  |
| BeingSent | INT | no |  |  |  |
| Sent | INT | no |  |  |  |
| TimeStamp_Added | DATETIME | no |  |  |  |
| TimeStamp_Sent | DATETIME | yes |  |  |  |
  [Back to top](#reportings)
  ### dbo.partners_smile_angels_misterfly_cars
  #### Columns
  | Column | Type | Null | Foreign Key | Default | Description |
| --- | --- | --- | --- | --- | --- |
| UserCode | VARCHAR(MAX) | no |  |  |  |
| CriterionCode | VARCHAR(MAX) | yes |  |  |  |
| Value | NUMERIC(18,0) | no |  |  |  |
| SaleDate | VARCHAR(MAX) | yes |  |  |  |
| CompletionDate | VARCHAR(MAX) | yes |  |  |  |
| Comment | VARCHAR(MAX) | no |  |  |  |
| Reference | VARCHAR(MAX) | yes |  |  |  |
| Active | INT | yes |  |  |  |
| Status | INT | no |  |  |  |
| BeingSent | INT | no |  |  |  |
| Sent | INT | no |  |  |  |
| TimeStamp_Added | DATETIME | no |  |  |  |
| TimeStamp_Sent | DATETIME | yes |  |  |  |
  [Back to top](#reportings)
  ### dbo.partners_smile_angels_misterfly_flights
  #### Columns
  | Column | Type | Null | Foreign Key | Default | Description |
| --- | --- | --- | --- | --- | --- |
| UserCode | VARCHAR(MAX) | no |  |  |  |
| CriterionCode | VARCHAR(MAX) | yes |  |  |  |
| Value | NUMERIC(18,0) | no |  |  |  |
| SaleDate | VARCHAR(MAX) | yes |  |  |  |
| CompletionDate | VARCHAR(MAX) | yes |  |  |  |
| Comment | VARCHAR(MAX) | no |  |  |  |
| Reference | VARCHAR(MAX) | yes |  |  |  |
| Active | INT | yes |  |  |  |
| Status | INT | no |  |  |  |
| BeingSent | INT | no |  |  |  |
| Sent | INT | no |  |  |  |
| TimeStamp_Added | DATETIME | no |  |  |  |
| TimeStamp_Sent | DATETIME | yes |  |  |  |
  [Back to top](#reportings)
  ### dbo.partners_smile_angels_misterfly_hotels
  #### Columns
  | Column | Type | Null | Foreign Key | Default | Description |
| --- | --- | --- | --- | --- | --- |
| UserCode | VARCHAR(MAX) | no |  |  |  |
| CriterionCode | VARCHAR(MAX) | yes |  |  |  |
| Value | NUMERIC(18,0) | no |  |  |  |
| SaleDate | VARCHAR(MAX) | yes |  |  |  |
| CompletionDate | VARCHAR(MAX) | yes |  |  |  |
| Comment | VARCHAR(MAX) | no |  |  |  |
| Reference | VARCHAR(MAX) | yes |  |  |  |
| Active | INT | yes |  |  |  |
| Status | INT | no |  |  |  |
| BeingSent | INT | no |  |  |  |
| Sent | INT | no |  |  |  |
| TimeStamp_Added | DATETIME | no |  |  |  |
| TimeStamp_Sent | DATETIME | yes |  |  |  |
  [Back to top](#reportings)
  ### dbo.partners_smile_angels_misterfly_transfers
  #### Columns
  | Column | Type | Null | Foreign Key | Default | Description |
| --- | --- | --- | --- | --- | --- |
| UserCode | VARCHAR(MAX) | no |  |  |  |
| CriterionCode | VARCHAR(MAX) | yes |  |  |  |
| Value | NUMERIC(18,0) | no |  |  |  |
| SaleDate | VARCHAR(MAX) | yes |  |  |  |
| CompletionDate | VARCHAR(MAX) | yes |  |  |  |
| Comment | VARCHAR(MAX) | no |  |  |  |
| Reference | VARCHAR(MAX) | yes |  |  |  |
| Active | INT | yes |  |  |  |
| Status | INT | no |  |  |  |
| BeingSent | INT | no |  |  |  |
| Sent | INT | no |  |  |  |
| TimeStamp_Added | DATETIME | no |  |  |  |
| TimeStamp_Sent | DATETIME | yes |  |  |  |
  [Back to top](#reportings)
  </details>
  ## Stored Procedures
  <details><summary>Click to expand</summary>  
* [dbo.sp_doc](#dbosp_doc)
* [dbo.sp_estindex](#dbosp_estindex)
* [dbo.sp_help_revlogin](#dbosp_help_revlogin)
* [dbo.sp_helpme](#dbosp_helpme)
* [dbo.sp_hexadecimal](#dbosp_hexadecimal)
* [dbo.sp_sizeoptimiser](#dbosp_sizeoptimiser)
  ### dbo.sp_doc
  | Description |
| --- |
| Generate on the fly database documentation in markdown. Documentation at https://expresssql.lowlydba.com |
  #### Parameters
  | Parameter | Type | Output | Description |
| --- | --- | --- | --- |
| @DatabaseName | SYSNAME(128) | no | Target database to document. Default is the stored procedure's database. |
| @ExtendedPropertyName | SYSNAME(128) | no | Key for extended properties on objects. Default is 'Description'. |
| @AllExtendedProperties | BIT | no | Include all extended properties for each object, not just @ExtendedPropertyName. |
| @LimitStoredProcLength | BIT | no | Limit stored procedure contents to 8000 characters, to avoid memory issues with some IDEs. Default is 1. |
| @Emojis | BIT | no | Use emojis when generating documentation. Default is 0. |
| @Verbose | BIT | no | Whether or not to print additional information during the script run. Default is 0. |
| @SqlMajorVersion | TINYINT | no | Used for unit testing purposes only. |
| @SqlMinorVersion | SMALLINT | no | Used for unit testing purposes only. |
  #### Definition
  <details><summary>Click to expand</summary>
  ```sql   CREATE PROCEDURE [dbo].[sp_doc]  @DatabaseName SYSNAME = NULL  ,@ExtendedPropertyName SYSNAME = 'Description'  ,@AllExtendedProperties BIT = 0  ,@LimitStoredProcLength BIT = 1  ,@Emojis BIT = 0  ,@Verbose BIT = 1  /* Parameters defined here for testing only */  ,@SqlMajorVersion TINYINT = 0  ,@SqlMinorVersion SMALLINT = 0 WITH RECOMPILE AS  /* sp_doc - Always have current documentation by generating it on the fly in markdown.  Part of the DBA MultiTool https://dba-multitool.org  Version: 20211223  MIT License  Copyright (c) 2023 John McCall  Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:  The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.  THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.  =========  Example:   EXEC sp_doc @DatabaseName = 'WideWorldImporters';  */  BEGIN   SET NOCOUNT ON;   DECLARE @Sql NVARCHAR(MAX)   ,@ParmDefinition NVARCHAR(500)   ,@QuotedDatabaseName SYSNAME   ,@Msg NVARCHAR(MAX)   ,@SensitivityClassification BIT   -- Escaping markdown inside EP via HTML codes since   -- we can't traditionally escape unknown content easily   ,@PipeHTMLCode CHAR(6) = '&#124;'   ,@TickHTMLCode CHAR(5) = '&#96;'   ,@RightBracketHTMLCode CHAR(5) = '&#93;'   ,@BreakHTMLCode CHAR(5) = '<br/>'   -- Variables for Emoji mode   ,@Yes VARCHAR(20) = 'yes'   ,@No VARCHAR(20) = 'no'   ,@PK VARCHAR(20) = NULL   ,@FK VARCHAR(20) = NULL   ,@Column VARCHAR(20) = NULL;   -- Find Version  IF (@SqlMajorVersion = 0)   BEGIN;    SET @SqlMajorVersion = CAST(SERVERPROPERTY('ProductMajorVersion') AS TINYINT);   END;  IF (@SqlMinorVersion = 0)   BEGIN;    SET @SqlMinorVersion = CAST(SERVERPROPERTY('ProductMinorVersion') AS TINYINT);   END;   -- Validate Version  IF (@SqlMajorVersion < 11)   BEGIN;    SET @Msg = 'SQL Server versions below 2012 are not supported, sorry!';    RAISERROR(@Msg, 16, 1);   END;   -- Check database name  IF (@DatabaseName IS NULL)   BEGIN    SET @DatabaseName = DB_NAME();    IF (@Verbose = 1)     BEGIN;      SET @Msg = 'No database provided, assuming current database.';      RAISERROR(@Msg, 10, 1) WITH NOWAIT;     END;   END  ELSE IF (DB_ID(@DatabaseName) IS NULL)   BEGIN;    SET @Msg = 'Database not available.';    RAISERROR(@Msg, 16, 1);   END;   SET @QuotedDatabaseName = QUOTENAME(@DatabaseName); --Avoid injections   -- Check Emoji Mode  IF (@Emojis = 1)   BEGIN;    SET @Yes = ':heavy_check_mark:';    SET @No = ':x:';    SET @PK = ':key: ';    SET @FK = ':old_key: ';    SET @Column = ':page_facing_up: ';   END;   -- Check for Sensitivity Classifications  IF EXISTS (SELECT 1 FROM [sys].[system_views] WHERE [name] = 'sensitivity_classifications')   BEGIN    SET @Sql = N'USE ' + @QuotedDatabaseName + ';     IF EXISTS (SELECT 1 FROM [sys].[sensitivity_classifications])      BEGIN       SET @SensitivityClassification = 1;      END;     ELSE      BEGIN       SET @SensitivityClassification = 0;      END;';    SET @ParmDefinition = N'@SensitivityClassification BIT OUTPUT';    EXEC sp_executesql @Sql     ,@ParmDefinition     ,@SensitivityClassification OUTPUT;   END;   --Create table to hold EP data  SET @Sql = N'USE ' + @QuotedDatabaseName + ';  CREATE TABLE #markdown (     [id] INT IDENTITY(1,1),     [value] NVARCHAR(MAX));';   /******************************  Generate markdown for database  ******************************/  --Database Name  SET @Sql = @Sql + N'  INSERT INTO #markdown (value)  VALUES (CONCAT(''# '', @DatabaseName) COLLATE DATABASE_DEFAULT);' +   --Database extended properties  + N'INSERT INTO #markdown (value)   SELECT CONCAT(CHAR(13), CHAR(10), CAST([value] AS VARCHAR(8000)))   FROM [sys].[extended_properties] AS [ep]   WHERE [ep].[class] = 0    AND [ep].[name] = @ExtendedPropertyName;' +   --Database metadata  + N'INSERT INTO #markdown (value)   VALUES (CONCAT(CHAR(13), CHAR(10), ''| Property | Value |''))   ,(''| --- | --- |'');    INSERT INTO #markdown   SELECT CONCAT(''| '', ''SQL Server Version'', '' | '', CAST(SERVERPROPERTY(''ProductVersion'') AS SYSNAME), '' |'')   UNION ALL   SELECT CONCAT(''| '', ''Compatibility Level'', '' | '', [compatibility_level], '' |'')   FROM [sys].[databases]   WHERE [name] = DB_NAME()   UNION ALL   SELECT CONCAT(''| '', ''Collation'', '' | '', [collation_name], '' |'')   FROM [sys].[databases]   WHERE [name] = DB_NAME();    INSERT INTO #markdown (value)   VALUES (''----'');' +   --Variables  + N'DECLARE @ObjectId INT,   @IndexObjectId INT,   @TrigObjectId INT,   @CheckConstObjectId INT,   @DefaultConstObjectId INT;    DECLARE @KeyColumns NVARCHAR(MAX),   @IncludeColumns NVARCHAR(MAX);';   /*****************************  Generate markdown for schemas  *****************************/  --Build table of contents  SET @Sql = @Sql + N'  INSERT INTO #markdown (value)  VALUES (CONCAT(CHAR(13), CHAR(10), ''## Schemas''))   ,(CONCAT(CHAR(13), CHAR(10), ''<details><summary>Click to expand</summary>'', CHAR(13), CHAR(10)));' +   + N'INSERT INTO #markdown (value)  SELECT CONCAT(''* ['', [name], ''](#'', REPLACE(LOWER([name]), '' '', ''-''), '')'')  FROM [sys].[schemas]  WHERE [schema_id] < 16384   AND [name] NOT IN (''sys'', ''guest'', ''INFORMATION_SCHEMA'')  ORDER BY [name] ASC;' +   --Object details  + N'DECLARE [obj_cursor] CURSOR  LOCAL STATIC READ_ONLY FORWARD_ONLY  FOR  SELECT [schema_id]  FROM [sys].[schemas]  WHERE [schema_id] < 16384   AND [name] NOT IN (''sys'', ''guest'', ''INFORMATION_SCHEMA'')  ORDER BY [name] ASC;   OPEN [obj_cursor]  FETCH NEXT FROM [obj_cursor] INTO @ObjectId  WHILE @@FETCH_STATUS = 0  BEGIN;    INSERT INTO #markdown   SELECT CONCAT(CHAR(13), CHAR(10), ''### '', SCHEMA_NAME(@ObjectId));' +    --Main Extended Property (@ExtendedProperty)   + N'   IF EXISTS (SELECT * FROM [sys].[schemas] AS [s] WITH(NOLOCK)       INNER JOIN [sys].[extended_properties] AS [ep] WITH(NOLOCK) ON [s].[schema_id] = [ep].[major_id]       WHERE [s].[schema_id] = @ObjectId        AND [ep].[minor_id] = 0 --On the object        AND [ep].[class] = 3 --Schema        AND [ep].[name] = @ExtendedPropertyName)     BEGIN;      INSERT INTO #markdown (value)      VALUES (CONCAT(CHAR(13), CHAR(10), ''| '', @ExtendedPropertyName COLLATE DATABASE_DEFAULT, '' |''))      ,(''| --- |'');       INSERT INTO #markdown (value)      SELECT CONCAT(''| '', REPLACE(REPLACE(REPLACE(REPLACE(CAST([ep].[value] AS NVARCHAR(4000)), ''|'', @PipeHTMLCode COLLATE DATABASE_DEFAULT), CHAR(13) + CHAR(10), @BreakHTMLCode COLLATE DATABASE_DEFAULT), ''`'', @TickHTMLCode COLLATE DATABASE_DEFAULT), '']'', @RightBracketHTMLCode COLLATE DATABASE_DEFAULT) COLLATE DATABASE_DEFAULT, '' |'')      FROM [sys].[schemas] AS [s] WITH(NOLOCK)       INNER JOIN [sys].[extended_properties] AS [ep] WITH(NOLOCK) ON [s].[schema_id] = [ep].[major_id]      WHERE [s].[schema_id] = @ObjectId       AND [ep].[minor_id] = 0 --On the object       AND [ep].[class] = 3 --Schema       AND [ep].[name] = @ExtendedPropertyName;     END;';    --All Extended Properties (non-@ExtendedProperty)   IF @AllExtendedProperties = 1    BEGIN;     SET @Sql = @Sql + N'     IF EXISTS (SELECT * FROM [sys].[schemas] AS [s] WITH(NOLOCK)       INNER JOIN [sys].[extended_properties] AS [ep] WITH(NOLOCK) ON [s].[schema_id] = [ep]
/************************************************************************************************/
/* sp_doc: Max 8000 characters reached. Set @LimitStoredProcLength = 0 to show full definition. */
/************************************************************************************************/
```
  </details>
  [Back to top](#reportings)
  ### dbo.sp_estindex
  | Description |
| --- |
| Estimate a new index's size and statistics. |
  #### Parameters
  | Parameter | Type | Output | Description |
| --- | --- | --- | --- |
| @SchemaName | SYSNAME(128) | no | Target schema of the index's table. Default is 'dbo'. |
| @TableName | SYSNAME(128) | no | Target table for the index. Default is current database. |
| @DatabaseName | SYSNAME(128) | no | Target database of the index's table. |
| @IndexColumns | NVARCHAR(2048) | no | Comma separated list of key columns. |
| @IncludeColumns | NVARCHAR(2048) | no | Optional comma separated list of include columns. |
| @IsUnique | BIT | no | Whether or not the index is UNIQUE. Default is 0. |
| @Filter | NVARCHAR(2048) | no | Optional filter for the index. |
| @FillFactor | TINYINT | no | Optional fill factor for the index. Default is 100. |
| @VarcharFillPercent | TINYINT | no | Optional estimated fill percent of data in variable length columns. Default is 100. |
| @Verbose | BIT | no | Show intermediate variables used in size calculations. Default is 0. |
| @SqlMajorVersion | TINYINT | no | For unit testing only. |
  #### Definition
  <details><summary>Click to expand</summary>
  ```sql   CREATE PROCEDURE [dbo].[sp_estindex]     @SchemaName SYSNAME = NULL     ,@TableName SYSNAME     ,@DatabaseName SYSNAME = NULL     ,@IndexColumns NVARCHAR(2048)     ,@IncludeColumns NVARCHAR(2048) = NULL     ,@IsUnique BIT = 0     ,@Filter NVARCHAR(2048) = ''     ,@FillFactor TINYINT = 100     ,@VarcharFillPercent TINYINT = 100     ,@Verbose BIT = 0     -- Unit testing only     ,@SqlMajorVersion TINYINT = 0 AS BEGIN  SET NOCOUNT ON;  /* sp_estindex - Estimate a new index's size and statistics.  Part of the DBA MultiTool http://dba-multitool.org  Version: 20220124  MIT License  Copyright (c) 2023 John McCall  Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:  The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.  THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.  -- TODO:     -- Handle clustered indexes - https://docs.microsoft.com/en-us/sql/relational-databases/databases/estimate-the-size-of-a-clustered-index?view=sql-server-ver15  =========  Example:      EXEC dbo.sp_estindex @SchemaName = 'dbo', @tableName = 'Marathon', @IndexColumns = 'racer_id, finish_time, is_disqualified';      EXEC dbo.sp_estindex @tableName = 'Marathon', @IndexColumns = 'racer_id, finish_time, is_disqualified', @Filter = 'WHERE racer_id IS NOT NULL', @FillFactor = 90;  */  DECLARE @Sql NVARCHAR(MAX) = N''     ,@QualifiedTable NVARCHAR(257)     ,@IndexName SYSNAME = CONCAT('sp_estindex_hypothetical_idx_', DATEDIFF(SECOND,'1970-01-01 00:08:46', GETUTCDATE()))     ,@DropIndexSql NVARCHAR(MAX)     ,@Msg NVARCHAR(MAX) = N''     ,@IndexType SYSNAME = 'NONCLUSTERED'     ,@IsHeap BIT     ,@IsClusterUnique BIT     ,@ObjectID INT     ,@IndexID INT     ,@ParmDefinition NVARCHAR(MAX) = N''     ,@NumRows BIGINT     ,@UseDatabase NVARCHAR(200)     ,@UniqueSql VARCHAR(10)     ,@IncludeSql VARCHAR(2048)     ,@PageSize BIGINT = 8192     ,@FreeBytesPerPage BIGINT = 8096;  BEGIN TRY     -- Find Version  IF (@SqlMajorVersion = 0)   BEGIN;    SET @SqlMajorVersion = CAST(SERVERPROPERTY('ProductMajorVersion') AS TINYINT);   END;      /* Validate Version */  IF (@SqlMajorVersion < 11)   BEGIN;    SET @Msg = 'SQL Server versions below 2012 are not supported, sorry!';    RAISERROR(@Msg, 16, 1);   END;      /* Validate Fill Factor */     IF (@FillFactor > 100 OR @FillFactor < 1)         BEGIN;             SET @Msg = 'Fill factor must be between 1 and 100.';             THROW 51000, @Msg, 1;         END;      /* Validate Varchar Fill Percent */     IF (@VarcharFillPercent > 100 OR @VarcharFillPercent < 1)         BEGIN;             SET @Msg = 'Varchar fill percent must be between 1 and 100.';             THROW 51000, @Msg, 1;         END;      /* Validate Filter */     IF (@Filter <> '' AND LEFT(@Filter, 5) <> 'WHERE')         BEGIN;             SET @Msg = 'Filter must start with ''WHERE''.';             THROW 51000, @Msg, 1;         END;      /* Validate Database */     IF (@DatabaseName IS NULL)         BEGIN;             SET @DatabaseName = DB_NAME();             IF (@Verbose = 1)                 BEGIN;                     SET @Msg = 'No database provided, assuming current database.';                     RAISERROR(@Msg, 10, 1) WITH NOWAIT;                 END;         END;     ELSE IF (DB_ID(@DatabaseName) IS NULL)         BEGIN;             SET @DatabaseName = DB_NAME();             SET @Msg = 'Database does not exist.';             RAISERROR(@Msg, 16, 1);         END;      /* Validate Schema */     IF (@SchemaName IS NULL)         BEGIN;             SET @SchemaName = 'dbo';             IF (@Verbose = 1)                 BEGIN;                     SET @Msg = 'No schema provided, assuming dbo.';                     RAISERROR(@Msg, 10, 1) WITH NOWAIT;                 END;         END;      -- Set variables with validated params     SET @QualifiedTable = CONCAT(QUOTENAME(@SchemaName), '.', QUOTENAME(@TableName));     SET @UseDatabase = N'USE ' + QUOTENAME(@DatabaseName) + '; ';     IF (@IsUnique = 1)         BEGIN;             SET @UniqueSql = ' UNIQUE ';         END;     IF (@IncludeColumns IS NOT NULL)         BEGIN;             SET @IncludeSql = CONCAT(' INCLUDE(', @IncludeColumns, ') ');         END;      -- Find object id     SET @Sql = CONCAT(@UseDatabase,         N'SELECT @ObjectID = [object_id]         FROM [sys].[all_objects]         WHERE [object_id] = OBJECT_ID(@QualifiedTable)');  SET @ParmDefinition = N'@QualifiedTable NVARCHAR(257)       ,@ObjectID INT OUTPUT';     EXEC sp_executesql @Sql     ,@ParmDefinition     ,@QualifiedTable     ,@ObjectID OUTPUT;      -- Determine Heap or Clustered     SET @Sql = CONCAT(@UseDatabase,         N'SELECT @IsHeap = CASE [type] WHEN 0 THEN 1 ELSE 0 END             ,@IsClusterUnique = [is_unique]          FROM [sys].[indexes]          WHERE [object_id] = OBJECT_ID(@QualifiedTable)          AND [type] IN (1, 0)');  SET @ParmDefinition = N'@QualifiedTable NVARCHAR(257), @IsHeap BIT OUTPUT, @IsClusterUnique BIT OUTPUT';  EXEC sp_executesql @Sql   ,@ParmDefinition   ,@QualifiedTable   ,@IsHeap OUTPUT         ,@IsClusterUnique OUTPUT;      -- Safety check for leftover index from previous run     SET @DropIndexSql = CONCAT(@UseDatabase,     N'IF EXISTS (SELECT 1 FROM [sys].[indexes] WHERE [object_id] = OBJECT_ID(''',@QualifiedTable,''') AND [name] = ''',@IndexName,''')         DROP INDEX ', QUOTENAME(@IndexName), ' ON ', @QualifiedTable);     EXEC sp_executesql @DropIndexSql;      -- Fetch missing index stats before creation     IF OBJECT_ID('tempdb..##TempMissingIndex') IS NOT NULL         BEGIN;             DROP TABLE ##TempMissingIndex;         END;      SET @Sql = CONCAT(@UseDatabase,     N'SELECT [id].[statement]         ,[id].[equality_columns]         ,[id].[inequality_columns]         ,[id].[included_columns]         ,[gs].[unique_compiles]         ,[gs].[user_seeks]         ,[gs].[user_scans]         ,[gs].[avg_total_user_cost] -- Average cost of the user queries that could be reduced         ,[gs].[avg_user_impact]  -- %     INTO ##TempMissingIndex     FROM [sys].[dm_db_missing_index_group_stats] [gs]     INNER JOIN [sys].[dm_db_missing_index_groups] [ig] ON [gs].[group_handle] = [ig].[index_group_handle]     INNER JOIN [sys].[dm_db_missing_index_details] [id] ON [ig].[index_handle] = [id].[index_handle]     WHERE [id].[database_id] = DB_ID()         AND [id].[object_id] = @ObjectID     OPTION (RECOMPILE);');     SET @ParmDefinition = N'@ObjectID INT';  EXEC sp_executesql @Sql   ,@ParmDefinition         ,@ObjectID;      -- Create the hypothetical index     SET @Sql = CONCAT(@UseDatabase, 'CREATE ', @UniqueSql, @IndexType, ' INDEX ', QUOTENAME(@IndexName), ' ON ', @QualifiedTable, ' (', @IndexColumns, ') ',@IncludeSql, @Filter, ' WITH (STATISTICS_ONLY = -1)');     EXEC sp_executesql @Sql;      /*******************/     /* Get index stats */     /*******************/     -- Use DBCC to avoid various inconsistencies     -- in equivalent DMVs between 2012-2016     SET @Sql = CONCAT(@UseDatabase, 'DBCC SHOW_STATISTICS ("', @QualifiedTable,'", ', QUOTENAME(@IndexName), ')');     EXEC sp_executesql @Sql;      /***************************/     /* Get missing index stats */     /*********************
/************************************************************************************************/
/* sp_doc: Max 8000 characters reached. Set @LimitStoredProcLength = 0 to show full definition. */
/************************************************************************************************/
```
  </details>
  [Back to top](#reportings)
  ### dbo.sp_help_revlogin
  #### Parameters
  | Parameter | Type | Output | Description |
| --- | --- | --- | --- |
| @login_name | SYSNAME(128) | no |  |
  #### Definition
  <details><summary>Click to expand</summary>
  ```sql  CREATE PROCEDURE [dbo].[sp_help_revlogin] (     @login_name sysname = NULL ) AS BEGIN     DECLARE @name                     SYSNAME     DECLARE @type                     VARCHAR (1)     DECLARE @hasaccess                INT     DECLARE @denylogin                INT     DECLARE @is_disabled              INT     DECLARE @PWD_varbinary            VARBINARY (256)     DECLARE @PWD_string               VARCHAR (514)     DECLARE @SID_varbinary            VARBINARY (85)     DECLARE @SID_string               VARCHAR (514)     DECLARE @tmpstr                   VARCHAR (1024)     DECLARE @is_policy_checked        VARCHAR (3)     DECLARE @is_expiration_checked    VARCHAR (3)     Declare @Prefix                   VARCHAR(255)     DECLARE @defaultdb                SYSNAME     DECLARE @defaultlanguage          SYSNAME     DECLARE @tmpstrRole               VARCHAR (1024)  IF (@login_name IS NULL) BEGIN     DECLARE login_curs CURSOR     FOR         SELECT p.sid, p.name, p.type, p.is_disabled, p.default_database_name, l.hasaccess, l.denylogin, p.default_language_name         FROM  sys.server_principals p         LEFT JOIN sys.syslogins     l ON ( l.name = p.name )         WHERE p.type IN ( 'S', 'G', 'U' )         AND p.name <> 'sa'         ORDER BY p.name END ELSE         DECLARE login_curs CURSOR         FOR             SELECT p.sid, p.name, p.type, p.is_disabled, p.default_database_name, l.hasaccess, l.denylogin, p.default_language_name             FROM  sys.server_principals p             LEFT JOIN sys.syslogins        l ON ( l.name = p.name )             WHERE p.type IN ( 'S', 'G', 'U' )             AND p.name = @login_name             ORDER BY p.name          OPEN login_curs         FETCH NEXT FROM login_curs INTO @SID_varbinary, @name, @type, @is_disabled, @defaultdb, @hasaccess, @denylogin, @defaultlanguage         IF (@@fetch_status = -1)         BEGIN             PRINT 'No login(s) found.'             CLOSE login_curs             DEALLOCATE login_curs             RETURN -1         END          SET @tmpstr = '/* sp_help_revlogin script '         PRINT @tmpstr          SET @tmpstr = '** Generated ' + CONVERT (varchar, GETDATE()) + ' on ' + @@SERVERNAME + ' */'          PRINT @tmpstr         PRINT ''          WHILE (@@fetch_status <> -1)         BEGIN         IF (@@fetch_status <> -2)         BEGIN                 PRINT ''                  SET @tmpstr = '-- Login: ' + @name                  PRINT @tmpstr                  SET @tmpstr='IF NOT EXISTS (SELECT * FROM sys.server_principals WHERE name = N'''+@name+''')                 BEGIN'                 Print @tmpstr                  IF (@type IN ( 'G', 'U'))                 BEGIN -- NT authenticated account/group                 SET @tmpstr = 'CREATE LOGIN ' + QUOTENAME( @name ) + ' FROM WINDOWS WITH DEFAULT_DATABASE = [' + @defaultdb + ']' + ', DEFAULT_LANGUAGE = [' + @defaultlanguage + ']'                 END                 ELSE                 BEGIN -- SQL Server authentication                         -- obtain password and sid                         SET @PWD_varbinary = CAST( LOGINPROPERTY( @name, 'PasswordHash' ) AS varbinary (256) )                          EXEC sp_hexadecimal @PWD_varbinary, @PWD_string OUT                         EXEC sp_hexadecimal @SID_varbinary,@SID_string OUT                          -- obtain password policy state                         SELECT @is_policy_checked     = CASE is_policy_checked WHEN 1 THEN 'ON' WHEN 0 THEN 'OFF' ELSE NULL END                         FROM sys.sql_logins                         WHERE name = @name                          SELECT @is_expiration_checked = CASE is_expiration_checked WHEN 1 THEN 'ON' WHEN 0 THEN 'OFF' ELSE NULL END                         FROM sys.sql_logins                         WHERE name = @name                          SET @tmpstr = 'CREATE LOGIN ' + QUOTENAME( @name ) + ' WITH PASSWORD = ' + @PWD_string + ' HASHED, SID = '                                         + @SID_string + ', DEFAULT_DATABASE = [' + @defaultdb + ']' + ', DEFAULT_LANGUAGE = [' + @defaultlanguage + ']'                          IF ( @is_policy_checked IS NOT NULL )                         BEGIN                         SET @tmpstr = @tmpstr + ', CHECK_POLICY = ' + @is_policy_checked                         END                          IF ( @is_expiration_checked IS NOT NULL )                         BEGIN                         SET @tmpstr = @tmpstr + ', CHECK_EXPIRATION = ' + @is_expiration_checked                         END         END          IF (@denylogin = 1)         BEGIN -- login is denied access             SET @tmpstr = @tmpstr + '; DENY CONNECT SQL TO ' + QUOTENAME( @name )         END         ELSE IF (@hasaccess = 0)         BEGIN -- login exists but does not have access             SET @tmpstr = @tmpstr + '; REVOKE CONNECT SQL TO ' + QUOTENAME( @name )         END         IF (@is_disabled = 1)         BEGIN -- login is disabled             SET @tmpstr = @tmpstr + '; ALTER LOGIN ' + QUOTENAME( @name ) + ' DISABLE'         END          SET @Prefix = '         EXEC master.dbo.sp_addsrvrolemember @loginame='''          SET @tmpstrRole=''          SELECT @tmpstrRole = @tmpstrRole             + CASE WHEN sysadmin        = 1 THEN @Prefix + [LoginName] + ''', @rolename=''sysadmin'''        ELSE '' END             + CASE WHEN securityadmin   = 1 THEN @Prefix + [LoginName] + ''', @rolename=''securityadmin'''   ELSE '' END             + CASE WHEN serveradmin     = 1 THEN @Prefix + [LoginName] + ''', @rolename=''serveradmin'''     ELSE '' END             + CASE WHEN setupadmin      = 1 THEN @Prefix + [LoginName] + ''', @rolename=''setupadmin'''      ELSE '' END             + CASE WHEN processadmin    = 1 THEN @Prefix + [LoginName] + ''', @rolename=''processadmin'''    ELSE '' END             + CASE WHEN diskadmin       = 1 THEN @Prefix + [LoginName] + ''', @rolename=''diskadmin'''       ELSE '' END             + CASE WHEN dbcreator       = 1 THEN @Prefix + [LoginName] + ''', @rolename=''dbcreator'''       ELSE '' END             + CASE WHEN bulkadmin       = 1 THEN @Prefix + [LoginName] + ''', @rolename=''bulkadmin'''       ELSE '' END         FROM (                     SELECT CONVERT(VARCHAR(100),SUSER_SNAME(sid)) AS [LoginName],                             sysadmin,                             securityadmin,                             serveradmin,                             setupadmin,                             processadmin,                             diskadmin,                             dbcreator,                             bulkadmin                     FROM sys.syslogins                     WHERE (       sysadmin<>0                             OR    securityadmin<>0                             OR    serveradmin<>0                             OR    setupadmin <>0                             OR    processadmin <>0                             OR    diskadmin<>0                             OR    dbcreator<>0                             OR    bulkadmin<>0                         )                         AND name=@name             ) L              PRINT @tmpstr             PRINT @tmpstrRole             PRINT 'END'         END         FETCH NEXT FROM login_curs INTO @SID_varbinary, @name, @type, @is_disabled, @defaultdb, @hasaccess, @denylogin, @defaultlanguage     END     CLOSE login_curs     DEALLOCATE login_curs     RETURN 0 END SET ANSI_NULLS ON; 
```
  </details>
  [Back to top](#reportings)
  ### dbo.sp_helpme
  | Description |
| --- |
| Drop-in alternative to sp_help. Documentation at https://expresssql.lowlydba.com |
  #### Parameters
  | Parameter | Type | Output | Description |
| --- | --- | --- | --- |
| @ObjectName | SYSNAME(128) | no | Target object. Default is all objects. |
| @ExtendedPropertyName | SYSNAME(128) | no | Key for extended properties on objects. Default is 'Description'. |
| @SqlMajorVersion | TINYINT | no | Used for unit testing purposes only. |
| @SqlMinorVersion | SMALLINT | no | Used for unit testing purposes only. |
  #### Definition
  <details><summary>Click to expand</summary>
  ```sql   CREATE PROCEDURE [dbo].[sp_helpme]  @ObjectName SYSNAME = NULL  ,@ExtendedPropertyName SYSNAME = 'Description'  /* Parameters defined here for testing only */  ,@SqlMajorVersion TINYINT = 0  ,@SqlMinorVersion SMALLINT = 0 AS  /* sp_helpme - A drop-in modern alternative to sp_help.  Part of the DBA MultiTool http://dba-multitool.org  Version: 20230108  MIT License  Copyright (c) 2023 John McCall  Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:  The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.  THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.  =========  Example:   EXEC sp_helpme 'dbo.Sales';  */  BEGIN  SET NOCOUNT ON;   DECLARE @DbName SYSNAME   ,@ObjShortName SYSNAME = N''   ,@No VARCHAR(5) = 'no'   ,@Yes VARCHAR(5) = 'yes'   ,@None VARCHAR(5) = 'none'   ,@SysObj_Type CHAR(2)   ,@ObjID INT   ,@HasParam INT = 0   ,@HasDepen BIT = 0   ,@HasHidden BIT = 0   ,@HasMasked BIT = 0   ,@SQLString NVARCHAR(MAX) = N''   ,@Msg NVARCHAR(MAX) = N''   ,@ParmDefinition NVARCHAR(500);   /* Find Version */  IF (@SqlMajorVersion = 0)   BEGIN;    SET @SqlMajorVersion = CAST(SERVERPROPERTY('ProductMajorVersion') AS TINYINT);   END;  IF (@SqlMinorVersion = 0)   BEGIN;    SET @SqlMinorVersion = CAST(SERVERPROPERTY('ProductMinorVersion') AS TINYINT);   END;   /* Validate Version */  IF (@SqlMajorVersion < 11)   BEGIN;    SET @Msg = 'SQL Server versions below 2012 are not supported, sorry!';    RAISERROR(@Msg, 16, 1);   END;   /* Check for Hidden Columns feature */  IF 1 = (SELECT COUNT(1) FROM sys.all_columns AS ac WHERE ac.name = 'is_hidden' AND OBJECT_NAME(ac.object_id) = 'all_columns')   BEGIN    SET @HasHidden = 1;   END;   /* Check for Masked Columns feature */  IF 1 = (SELECT COUNT(1) FROM sys.all_columns AS ac WHERE ac.name = 'is_masked' AND OBJECT_NAME(ac.object_id) = 'all_columns')   BEGIN    SET @HasMasked = 1;   END;   -- If no @ObjectName given, give a little info about all objects.  IF (@ObjectName IS NULL)  BEGIN;   SET @SQLString = N'SELECT     [Name] = [o].[name],     [Owner] = USER_NAME(OBJECTPROPERTY([object_id], ''ownerid'')),     [Object_type] = LOWER(REPLACE([o].[type_desc], ''_'', '' '')),     [Create_datetime] = [o].[create_date],     [Modify_datetime] = [o].[modify_date],     [ExtendedProperty] = [ep].[value]    FROM [sys].[all_objects] [o]     LEFT JOIN [sys].[extended_properties] [ep] ON [ep].[major_id] = [o].[object_id]      and [ep].[name] = @ExtendedPropertyName      AND [ep].[minor_id] = 0      AND [ep].[class] = 1    ORDER BY [Owner] ASC, [Object_type] DESC, [Name] ASC;';   SET @ParmDefinition = N'@ExtendedPropertyName SYSNAME';    EXEC sp_executesql @SQLString    ,@ParmDefinition    ,@ExtendedPropertyName;    -- Display all user types   SET @SQLString = N'SELECT    [User_type]  = [name],    [Storage_type] = TYPE_NAME(system_type_id),    [Length]  = max_length,    [Prec]   = [precision],    [Scale]   = [scale],    [Nullable]  = CASE WHEN is_nullable = 1 THEN @Yes ELSE @No END,    [Default_name] = ISNULL(OBJECT_NAME(default_object_id), @None),    [Rule_name]  = ISNULL(OBJECT_NAME(rule_object_id), @None),    [Collation]  = collation_name   FROM sys.types   WHERE user_type_id > 256   ORDER BY [name];';   SET @ParmDefinition = N'@Yes VARCHAR(5), @No VARCHAR(5), @None VARCHAR(5)';    EXEC sp_executesql @SQLString    ,@ParmDefinition    ,@Yes    ,@No    ,@None;    RETURN(0);  END -- End all Sysobjects   -- Make sure the @ObjectName is local to the current database.  SELECT @ObjShortName = PARSENAME(@ObjectName,1);  SELECT @DbName = PARSENAME(@ObjectName,3);  IF @DbName IS NULL   SELECT @DbName = DB_NAME();  ELSE IF @DbName <> DB_NAME()   BEGIN    RAISERROR(15250,-1,-1);   END   -- @ObjectName must be either sysobjects or systypes: first look in sysobjects  SET @SQLString = N'SELECT @ObjID   = object_id        , @SysObj_Type  = type       FROM sys.all_objects       WHERE object_id = OBJECT_ID(@ObjectName);';  SET @ParmDefinition = N'@ObjectName SYSNAME       ,@ObjID INT OUTPUT       ,@SysObj_Type VARCHAR(5) OUTPUT';   EXEC sp_executesql @SQLString   ,@ParmDefinition   ,@ObjectName   ,@ObjID OUTPUT   ,@SysObj_Type OUTPUT;   -- If @ObjectName not in sysobjects, try systypes  IF @ObjID IS NULL  BEGIN   SET @SQLString = N'SELECT @ObjID = user_type_id        FROM sys.types        WHERE name = PARSENAME(@ObjectName,1);';   SET @ParmDefinition = N'@ObjectName SYSNAME        ,@ObjID INT OUTPUT';    EXEC sp_executesql @SQLString    ,@ParmDefinition    ,@ObjectName    ,@ObjID OUTPUT;    -- If not in systypes, return   IF @ObjID IS NULL   BEGIN    RAISERROR(15009,-1,-1,@ObjectName,@DbName);   END    -- Data Type help (prec/scale only valid for numerics)   SET @SQLString = N'SELECT       [Type_name]   = t.name,       [Storage_type]  = type_name(system_type_id),       [Length]   = max_length,       [Prec]    = [precision],       [Scale]    = [scale],       [Nullable]   = case when is_nullable=1 then @Yes else @No end,       [Default_name]  = isnull(object_name(default_object_id), @None),       [Rule_name]   = isnull(object_name(rule_object_id), @None),       [Collation]   = collation_name,       [ExtendedProperty] = ep.[value]      FROM [sys].[types] AS [t]       LEFT JOIN [sys].[extended_properties] AS [ep] ON [ep].[major_id] = [t].[user_type_id]        AND [ep].[name] = @ExtendedPropertyName        AND [ep].[minor_id] = 0        AND [ep].[class] = 6      WHERE [user_type_id] = @ObjID';   SET @ParmDefinition = N'@ObjID INT, @Yes VARCHAR(5), @No VARCHAR(5), @None VARCHAR(5), @ExtendedPropertyName SYSNAME';    EXECUTE sp_executesql @SQLString    ,@ParmDefinition    ,@ObjID    ,@Yes    ,@No    ,@None    ,@ExtendedPropertyName;    RETURN(0);  END --Systypes   -- FOUND IT IN SYSOBJECT, SO GIVE OBJECT INFO  SET @SQLString = N'SELECT   [Name]     = [o].[name],   [Owner]     = USER_NAME(ObjectProperty([o].[object_id], ''ownerid'')),   [Type]     = LOWER(REPLACE([o].[type_desc], ''_'', '' '')),   [Created_datetime]  = [o].[create_date],   [Modify_datetime]  = [o].[modify_date],   [ExtendedProperty]  = [ep].[value]  FROM [sys].[all_objects] [o]   LEFT JOIN [sys].[extended_properties] [ep] ON [ep].[major_id] = [o].[object_id]    AND [ep].[name] = @ExtendedPropertyName    AND [ep].[minor_id] = 0    AND [ep].[class] = 1  WHERE [o].[object_id] = @ObjID;';   SET @ParmDefinition = N'@ObjID INT, @ExtendedPropertyName SYSNAME';   EXEC sp_executesql @SQLString   ,@ParmDefinition   ,@ObjID   ,@ExtendedPropertyName;   -- Display column metadata if table / view  SET @SQLString = N'  IF EXISTS (SELECT * FROM [sys].[all_columns] WHERE [object_id] = @ObjID)  BEGIN;    -- SET UP NUMERIC TYPES: THESE WILL HAVE NON-BLANK PREC/SCALE   -- There must be a '','' immediately after each type name (including last one),   -- because that''s what we''ll search for in charindex later.   DECLARE @precscaletypes NVARCHAR(150);   SELECT @precscaletypes = N''tinyint,smallint,decimal,int,bigint,real,money,float,numeric,smallmoney,date,time,datetime2,datetimeoffset,''    -- INFO FOR EACH COLUMN   SELECT    [Column_name]   = [ac].[name],    [Type]     = TYPE_NAME([ac].[user_type_id]),    [Computed]    = CASE WHEN ColumnProperty([objec
/************************************************************************************************/
/* sp_doc: Max 8000 characters reached. Set @LimitStoredProcLength = 0 to show full definition. */
/************************************************************************************************/
```
  </details>
  [Back to top](#reportings)
  ### dbo.sp_hexadecimal
  #### Parameters
  | Parameter | Type | Output | Description |
| --- | --- | --- | --- |
| @binvalue | VARBINARY(256) | no |  |
| @hexvalue | VARCHAR(514) | yes |  |
  #### Definition
  <details><summary>Click to expand</summary>
  ```sql  CREATE PROCEDURE [dbo].[sp_hexadecimal] (     @binvalue varbinary(256),     @hexvalue varchar (514) OUTPUT ) AS BEGIN     DECLARE @charvalue varchar (514)     DECLARE @i int     DECLARE @length int     DECLARE @hexstring char(16)     SELECT @charvalue = '0x'     SELECT @i = 1     SELECT @length = DATALENGTH (@binvalue)     SELECT @hexstring = '0123456789ABCDEF'      WHILE (@i <= @length)     BEGIN         DECLARE @tempint int         DECLARE @firstint int         DECLARE @secondint int          SELECT @tempint = CONVERT(int, SUBSTRING(@binvalue,@i,1))         SELECT @firstint = FLOOR(@tempint/16)         SELECT @secondint = @tempint - (@firstint*16)         SELECT @charvalue = @charvalue + SUBSTRING(@hexstring, @firstint+1, 1) + SUBSTRING(@hexstring, @secondint+1, 1)          SELECT @i = @i + 1     END     SELECT @hexvalue = @charvalue END 
```
  </details>
  #### Referenced By
  | Object | Type |
| --- | --- |
| [[dbo].[sp_help_revlogin]](#dbosp_help_revlogin) | sql stored procedure |
  [Back to top](#reportings)
  ### dbo.sp_sizeoptimiser
  | Description |
| --- |
| Recommends space saving and corrective data type measures based on SQL Server database schemas. Documentation at https://expresssql.lowlydba.com |
  #### Parameters
  | Parameter | Type | Output | Description |
| --- | --- | --- | --- |
| @IndexNumThreshold | SMALLINT | no | Number of indexes to classify a table as having too many indexes on it. Default value is 10. |
| @IncludeDatabases | SIZEOPTIMISERTABLETYPE | no | Which databases to run the script on in the form of a user defined table type. If not supplied, all accessible user databases are targeted. Cannot be used in conjunction with @ExcludeDatabases. |
| @ExcludeDatabases | SIZEOPTIMISERTABLETYPE | no | Which databases to exclude in the form of a user defined table type. Cannot be used in conjunction with @IncludeDatabases. |
| @IncludeSysDatabases | BIT | no | Whether or not to include system databases in the script's analysis. Default is 0. |
| @IncludeSSRSDatabases | BIT | no | Whether or not to include SQL Server Reporting Services databases in the script's analysis. Default is 0. |
| @Verbose | BIT | no | Whether or not to print additional information during the script run. Default is 0. |
| @IsExpress | BIT | no | Used for unit testing purposes only. |
| @SqlMajorVersion | TINYINT | no | Used for unit testing purposes only. |
| @SqlMinorVersion | SMALLINT | no | Used for unit testing purposes only. |
  #### Definition
  <details><summary>Click to expand</summary>
  ```sql   CREATE PROCEDURE [dbo].[sp_sizeoptimiser]  @IndexNumThreshold SMALLINT = 10  ,@IncludeDatabases [dbo].[SizeOptimiserTableType] READONLY  ,@ExcludeDatabases [dbo].[SizeOptimiserTableType] READONLY  ,@IncludeSysDatabases BIT = 0  ,@IncludeSSRSDatabases BIT = 0  ,@Verbose BIT = 1  /* Parameters defined here for testing only */  ,@IsExpress BIT = NULL  ,@SqlMajorVersion TINYINT = NULL  ,@SqlMinorVersion SMALLINT = NULL  WITH RECOMPILE AS  /* sp_sizeoptimiser - Recommends space saving measures for data footprints.  Part of the DBA MultiTool http://dba-multitool.org  Version: 20220818  MIT License  Copyright (c) 2023 John McCall  Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:  The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.  THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.  =========  Example:   DECLARE @include SizeOptimiserTableType;   INSERT INTO @include ([database_name])  VALUES (N'WideWorldImporters');   EXEC [dbo].[sp_sizeoptimiser] @IncludeDatabases = @include */  BEGIN  SET NOCOUNT ON;   BEGIN TRY    DECLARE @HasTempStat BIT = 0    ,@HasPersistedSamplePercent BIT = 0    ,@CheckNumber TINYINT = 0             ,@EngineEdition TINYINT    ,@CheckSQL NVARCHAR(MAX) = N''    ,@Msg NVARCHAR(MAX) = N''    ,@DbName SYSNAME = N''    ,@TempCheckSQL NVARCHAR(MAX) = N''    ,@BaseURL VARCHAR(1000) = 'http://dba-multitool.org/';    /* Validate @IndexNumThreshold */   IF (@IndexNumThreshold < 1 OR @IndexNumThreshold > 999)    BEGIN     SET @Msg = '@IndexNumThreshold must be between 1 and 999.';     RAISERROR(@Msg, 16, 1);    END    /* Validate database list */   IF (SELECT COUNT(1) FROM @IncludeDatabases) >= 1 AND (SELECT COUNT(1) FROM @ExcludeDatabases) >= 1    BEGIN     SET @Msg = 'Both @IncludeDatabases and @ExcludeDatabases cannot be specified.';     RAISERROR(@Msg, 16, 1);    END    CREATE TABLE #Databases (    [database_name] SYSNAME NOT NULL);    /* Build database list if no parameters set */   IF (SELECT COUNT(1) FROM @IncludeDatabases) = 0 AND (SELECT COUNT(1) FROM @ExcludeDatabases) = 0    BEGIN     INSERT INTO #Databases     SELECT [sd].[name]     FROM [sys].[databases] AS [sd]     WHERE ([sd].[database_id] > 4 OR @IncludeSysDatabases = 1)      AND ([sd].[name] NOT IN ('ReportServer', 'ReportServerTempDB') OR @IncludeSSRSDatabases = 1)      AND DATABASEPROPERTYEX([sd].[name], 'UPDATEABILITY') = N'READ_WRITE'      AND DATABASEPROPERTYEX([sd].[name], 'USERACCESS') = N'MULTI_USER'      AND DATABASEPROPERTYEX([sd].[name], 'STATUS') = N'ONLINE';    END;   /* Build database list from @IncludeDatabases */   ELSE IF (SELECT COUNT(1) FROM @IncludeDatabases) >= 1    BEGIN     INSERT INTO #Databases     SELECT [sd].[name]     FROM @IncludeDatabases AS [d]      INNER JOIN [sys].[databases] AS [sd] ON [sd].[name] COLLATE database_default = REPLACE(REPLACE([d].[database_name], '[', ''), ']', '')     WHERE DATABASEPROPERTYEX([sd].[name], 'UPDATEABILITY') = N'READ_WRITE'      AND DATABASEPROPERTYEX([sd].[name], 'USERACCESS') = N'MULTI_USER'      AND DATABASEPROPERTYEX([sd].[name], 'STATUS') = N'ONLINE';      IF (SELECT COUNT(1) FROM @IncludeDatabases) > (SELECT COUNT(1) FROM #Databases)      BEGIN       DECLARE @ErrorDatabaseList NVARCHAR(MAX);        WITH ErrorDatabase AS(        SELECT [database_name]        FROM @IncludeDatabases        EXCEPT        SELECT [database_name]        FROM #Databases)        SELECT @ErrorDatabaseList = ISNULL(@ErrorDatabaseList + N', ' + [database_name], [database_name])       FROM ErrorDatabase;        SET @Msg = 'Supplied databases do not exist or are not accessible: ' + @ErrorDatabaseList + '.';       RAISERROR(@Msg, 16, 1);      END;    END;   /* Build database list from @ExcludeDatabases */   ELSE IF (SELECT COUNT(1) FROM @ExcludeDatabases) >= 1    BEGIN     INSERT INTO #Databases     SELECT [sd].[name]     FROM [sys].[databases] AS [sd]     WHERE NOT EXISTS (SELECT [d].[database_name]          FROM @IncludeDatabases AS [d]          WHERE [sd].[name] COLLATE database_default = REPLACE(REPLACE([d].[database_name], '[', ''), ']', ''))      AND DATABASEPROPERTYEX([sd].[name], 'UPDATEABILITY') = N'READ_WRITE'      AND DATABASEPROPERTYEX([sd].[name], 'USERACCESS') = N'MULTI_USER'      AND DATABASEPROPERTYEX([sd].[name], 'STATUS') = N'ONLINE'     AND [sd].[name] <> 'tempdb';    END    /* Find edition */   IF (@IsExpress IS NULL AND CAST(SERVERPROPERTY('Edition') AS VARCHAR(50)) LIKE 'Express%')    BEGIN     SET @IsExpress = 1;    END;   ELSE IF (@IsExpress IS NULL)    BEGIN;     SET @IsExpress = 0;    END;          /* Find engine edition */   IF (@EngineEdition IS NULL)    BEGIN     SET @EngineEdition = CAST(SERVERPROPERTY('EditionEdition') AS TINYINT);    END;    /* Find Version */   IF (@SqlMajorVersion IS NULL)          BEGIN;              SET @SqlMajorVersion = CAST(SERVERPROPERTY('ProductMajorVersion') AS TINYINT);          END;   IF (@SqlMinorVersion IS NULL)          BEGIN;              SET @SqlMinorVersion = CAST(SERVERPROPERTY('ProductMinorVersion') AS SMALLINT);          END;    /* Validate Version */   IF (@SqlMajorVersion < 11)    BEGIN;     SET @Msg = 'SQL Server versions below 2012 are not supported, sorry!';     RAISERROR(@Msg, 16, 1);    END;    /* Check for is_temp value on statistics */   IF 1 = (SELECT 1 FROM [sys].[all_columns] AS [ac] WHERE [ac].[name] = 'is_temporary' AND OBJECT_NAME([ac].[object_id]) = 'all_columns')     BEGIN;      SET @HasTempStat = 1;     END;    /* Check for Persisted Sample Percent update */   IF 1 = (SELECT 1 FROM [sys].[all_columns] AS [ac] WHERE [ac].[name] = 'persisted_sample_percent' AND OBJECT_NAME([ac].[object_id]) = 'dm_db_stats_properties')    BEGIN;     SET @HasPersistedSamplePercent = 1;    END;    IF (@Verbose = 1)    BEGIN;     /* Print info */     SET @Msg = 'sp_sizeoptimiser';     RAISERROR(@Msg, 10, 1) WITH NOWAIT;     SET @Msg = '------------';     RAISERROR(@Msg, 10, 1) WITH NOWAIT;     SET @Msg = CONCAT('Time: ', GETDATE());     RAISERROR(@Msg, 10, 1) WITH NOWAIT;     SET @Msg = CONCAT('SQL Major Version: ', @SqlMajorVersion);     RAISERROR(@Msg, 10, 1) WITH NOWAIT;     SET @Msg = CONCAT('SQL Minor Version: ', @SqlMinorVersion);     RAISERROR(@Msg, 10, 1) WITH NOWAIT;     SET @Msg = CONCAT('Is Express Edition: ', @IsExpress);     RAISERROR(@Msg, 10, 1) WITH NOWAIT;     SET @Msg = CONCAT('Is feature "persisted sample percent" available: ', @HasPersistedSamplePercent);     RAISERROR(@Msg, 10, 1) WITH NOWAIT;     SET @Msg = CONCAT(CHAR(13), CHAR(10));     RAISERROR(@Msg, 10, 1) WITH NOWAIT;    END;    /* Build temp tables */   IF OBJECT_ID(N'tempdb..#results') IS NOT NULL    BEGIN;     DROP TABLE #results;    END;    CREATE TABLE #results    ([check_num] INT NOT NULL,    [check_type] NVARCHAR(50) NOT NULL,    [db_name]  SYSNAME NOT NULL,    [obj_type]  SYSNAME NOT NULL,    [obj_name]  NVARCHAR(400) NOT NULL,    [col_name]  SYSNAME NULL,    [message]  NVARCHAR(500) NULL,    [ref_link]  NVARCHAR(500) NULL);    IF OBJECT_ID('tempdb..#DuplicateIndex') IS NOT NULL    BEGIN;     DROP TABLE #DuplicateIndex;    END;    CREATE TABLE #DuplicateIndex    ([check_type] NVARCHAR(50) NOT NULL    ,[obj_type]  SYSNAME NOT N
/************************************************************************************************/
/* sp_doc: Max 8000 characters reached. Set @LimitStoredProcLength = 0 to show full definition. */
/************************************************************************************************/
```
  </details>
  [Back to top](#reportings)
  </details>
  ## User Defined Table Types
  <details><summary>Click to expand</summary>  
* [dbo.SizeOptimiserTableType](#dbosizeoptimisertabletype)
  ### dbo.SizeOptimiserTableType
  | Description |
| --- |
| Required table type for sp_sizeoptimiser. |
  #### Columns
  | Column | Type | Null | Default | Description |
| --- | ---| --- | --- | --- |
| **database_name** | SYSNAME(128) | no |  |  |
  #### Referenced By
  | Object | Type |
| --- | --- |
| [[dbo].[sp_sizeoptimiser]](#dbosp_sizeoptimiser) | sql stored procedure |
  [Back to top](#reportings)
  </details>
  ----
  *Markdown generated by [sp_doc](https://dba-multitool.org)
 at 2023-05-10 14:28:22.5177741 +02:00.*
