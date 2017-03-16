# MonoAGS
AGS (Adventure Game Studio) reimagined in Mono

Builds:

| Windows            | Android            | Linux            | Mac            |
|--------------------|--------------------|------------------|----------------|
| [![Windows][1]][3] | [![Android][2]][3] | [![Linux][4]][6] | [![Mac][5]][6] |

[1]: https://appveyor-matrix-badges.herokuapp.com/repos/tzachshabtay/MonoAGS/branch/master/2
[2]: https://appveyor-matrix-badges.herokuapp.com/repos/tzachshabtay/MonoAGS/branch/master/3
[3]: https://ci.appveyor.com/project/tzachshabtay/monoags
[4]: https://travis-matrix-badges.herokuapp.com/repos/tzachshabtay/MonoAGS/branches/master/1
[5]: https://travis-matrix-badges.herokuapp.com/repos/tzachshabtay/MonoAGS/branches/master/2
[6]: https://travis-ci.org/tzachshabtay/MonoAGS


Code Coverage:

[![Coverage Status](https://coveralls.io/repos/tzachshabtay/MonoAGS/badge.svg?branch=master&service=github)](https://coveralls.io/github/tzachshabtay/MonoAGS?branch=master)

# Microsoft SQL Server Articles

Articles types:
 - **[AZ]** Azure Articles
 - **[B]** Backup Articles
 - **[COR]** Corruption Articles
 - **[DBA]** DBA Articles
 - **[DEV]** Developers Articles
 - **[DM]** Database Mail
 - **[DBCC]** DBCC commands
 - **[DS]** Dynamic SQL
 - **[MG]** Migration Articles
 - **[J]** Jobs Articles
 - **[P]** Performance Articles
 - **[PS]** Powershell Articles
 - **[R]** R Language
 - **[SSIS]** [SQL Server Integration Services](https://msdn.microsoft.com/en-us/library/ms141026.aspx)
 - **[V]** Visualization Articles

| Title                                                                                                                   | Author                                   | Modified   | Type        |
|-------------------------------------------------------------------------------------------------------------------------|------------------------------------------|------------|-------------|
| [SQL Server Index Design Guide]                                                                                         | Microsoft                                | ?          |             |
| [SQL Server 2012 Security Best Practices - Microsoft]                                                                   | Bob Beauchemin                           | 2012-01-15 |             |
| [Help, my database is corrupt. Now what?]                                                                               | Gail Shaw                                | 2010-04-23 | [COR]       |
| [Understanding how SQL Server executes a query]                                                                         | Remus Rusanu                             | 2016-04-15 |             |
| [What to Do When DBCC CHECKDB Reports Corruption]                                                                       | Brent Ozar                               | 2016-05-19 | [COR]       |
| [Troubleshooting SQL Server CPU Performance Issues]                                                                     | Joe Sack                                 | 2013-05-28 | [P]         |
| [Knee-Jerk Performance Tuning : Incorrect Use of Temporary Tables]                                                      | Paul Randal                              | 2016-04-06 | [P]         |
| [High Performance T-SQL using Code Patterns]                                                                            | Dwain Camps                              | 2015-05-27 |             |
| [SQL Server Database Corruption Repair]                                                                                 | Steve Stedman                            | 2015-08-26 | [COR]       |
| [Basic SQL Server Performance Troubleshooting For Developers]                                                           | Tony Davis                               | 2015-08-14 | [P]         |
| [The Curse and Blessings of Dynamic SQL]                                                                                | Erland Sommarskog                        | 2015-04-14 | [DS]        |
| [Dynamic Search Conditions in T-SQL]                                                                                    | Erland Sommarskog                        | 2016-10-29 |             |
| [Slow in the Application, Fast in SSMS]                                                                                 | Erland Sommarskog                        | 2013-12-18 |             |
| [How to share data between stored procedures]                                                                           | Erland Sommarskog                        | 2013-11-02 |             |
| [Arrays and Lists in SQL Server 2008]                                                                                   | Erland Sommarskog                        | 2016-08-21 |             |
| [Giving Permissions through Stored Procedures]                                                                          | Erland Sommarskog                        | 2011-12-31 |             |
| [Error and Transaction Handling in SQL Server]                                                                          | Erland Sommarskog                        | 2015-05-03 |             |
| [Using the Bulk-Load Tools in SQL Server]                                                                               | Erland Sommarskog                        | 2016-12-08 |             |
| [Using Table-Valued Parameters in SQL Server and .NET]                                                                  | Erland Sommarskog                        | 2016-12-08 |             |
| [SQL Server Columnstore Articles]                                                                                       | Niko Neugebauer                          | 2016-05-09 |             |
| [Documentation: It Does not Suck!]                                                                                      | Jes Schultz Borland                      | 2013-01-15 |             |
| [The Data Loading Performance Guide]                                                                                    | Thomas Kejser, Peter Carlin, Stuart Ozer | 2009-01-15 |             |
| [Required Testing for Installing SQL Server Cumulative Updates and Service Packs]                                       | Kendra Little                            | 2016-04-28 |             |
| [Stop Shrinking Your Database Files. Seriously. Now.]                                                                   | Brent Ozar                               | 2009-08-19 |             |
| [How to shrink a database in 4 easy steps]                                                                              | Andy Mallon                              | 2016-04-28 |             |
| [Introduction to the Index Operational Statistics Dynamic Management Function]                                          | Tim Ford                                 | 2016-04-26 |             |
| [Updating Statistics in SQL Server: Maintenance Questions & Answers]                                                    | Kendra Little                            | 2016-04-18 |             |
| [Overcoming Variable Limitations in SQLCmd Mode]                                                                        | Robert L Davis                           | 2015-11-23 |             |
| [Contents of a Run Book]                                                                                                | Microsoft                                | 2002-11-12 |             |
| [Compressed and Encrypted Backups on the Cheap]                                                                         | Randolph West                            | 2015-04-19 | [B]         |
| [Curing Data-Obesity in OLTP Databases]                                                                                 | Feodor Georgiev                          | 2015-02-06 |             |
| [Understanding GRANT, DENY, and REVOKE in SQL Server]                                                                   | K. Brian Kelley                          | 2013-02-27 |             |
| [Monitor SQL Server Transaction Log File Free Space]                                                                    | Mike Eastland                            | 2015-05-12 |             |
| [Dynamically Query a 100 Million Row Table-Efficiently]                                                                 | Gary Strange                             | 2016-05-27 |             |
| [Understanding and Using Parallelism in SQL Server]                                                                     | Paul White                               | 2011-03-03 |             |
| [Diagnosing and Resolving Latch Contention on SQL Server]                                                               | Microsoft                                | 2014-02-28 |             |
| [Parallel Execution Plans – Branches and Threads]                                                                       | Paul White                               | 2013-10-07 |             |
| [Nasty Fast PERCENT_RANK]                                                                                               | Alan Burstein                            | 2016-06-07 |             |
| [Looking at VIEWs, Close Up]                                                                                            | Joe Celko                                | 2016-05-10 |             |
| [SQL Server 2016: It Just Runs Faster]                                                                                  | Thomas LaRock                            | 2016-06-01 |             |
| [TSQL JOIN Types Poster]                                                                                                | Steve Stedman                            | 2015-05-28 |             |
| [It is Hard To Destroy Data]                                                                                            | Michael J Swart                          | 2015-05-20 |             |
| [How to transfer logins and passwords between instances of SQL Server]                                                  | Microsoft                                | 2013-12-07 |             |
| [Finding File Growths with Extended Events]                                                                             | Andy Galbraith                           | 2016-06-13 |             |
| [Questions You Should Ask About the Databases You Manage]                                                               | Brent Ozar                               | 2016-06-16 |             |
| [Clustered Indexes in SQL Server]                                                                                       | Derik Hammer                             | 2016-06-22 |             |
| [Triage Quiz: Is Your SQL Server Safe?]                                                                                 | Angie Rudduck                            | 2016-06-15 |             |
| [Why Not Just Create Statistics?]                                                                                       | Erik Darling                             | 2016-07-14 |             |
| [Understanding the SQL Server NOLOCK hint]                                                                              | Greg Robidoux                            | 2011-08-16 |             |
| [Recover access to a SQL Server instance]                                                                               | Aaron Bertrand                           | 2012-08-30 |             |
| [SQL Server 2016 Upgrade Planning]                                                                                      | Jen Underwood                            | 2016-06-28 |             |
| [Graphs and Graph Algorithms in T-SQL]                                                                                  | Hans Olav Norheim                        | 2010-05-22 |             |
| [Episode 4: SQL Server R Services makes you a smarter T-SQL Developer]                                                  | Sanjay Mishra                            | 2016-07-12 | [DEV],[R]   |
| [How to Set Max Degree of Parallelism in SQL Server]                                                                    | Kendra Little                            | 2016-07-14 |             |
| [Undocumented Query Plans: Equality Comparisons]                                                                        | Paul White                               | 2016-06-22 |             |
| [Simplified Order Of Operations]                                                                                        | Michael J. Swart                         | 2016-07-20 |             |
| [SQL Server Statistics Basics]                                                                                          | Robert Sheldon                           | 2016-07-22 |             |
| [Learn to Use sp_Blitz, sp_BlitzCache, sp_BlitzFirst, and sp_BlitzIndex with These Tutorial Videos]                     | Brent Ozar                               | 2016-09-12 |             |
| [Where is a record really located?]                                                                                     | Tim Chapman                              | 2016-09-15 |             |
| [Instant File Initialization (IFI)]                                                                                     | Steve Stedman                            | 2016-09-19 |             |
| [How to Query the StackExchange Databases]                                                                              | Brent Ozar                               | 2014-01-17 |             |
| [How to Troubleshoot Performance in SQL Server (Dear SQL DBA)]                                                          | Kendra Little                            | 2016-06-02 |             |
| [How to Log Activity Using sp_whoisactive in a Loop]                                                                    | Brent Ozar                               | 2016-07-01 |             |
| [Logging Activity Using sp_WhoIsActive – Take 2]                                                                        | Tara Kizer                               | 2016-07-26 |             |
| [How To Fix Forwarded Records]                                                                                          | Tara Kizer                               | 2016-07-29 |             |
| [Should I Automate my Windows Updates for SQL Server?]                                                                  | Kendra Little                            | 2016-07-28 |             |
| [Finding the Right Path]                                                                                                | Jason Brimhall                           | 2016-08-24 |             |
| [#BackToBasics : An Updated "Kitchen Sink" Example]                                                                     | Aaron Bertrand                           | 2016-06-01 |             |
| [Locking and Blocking in SQL Server]                                                                                    | Brent OZar                               | 2016-01-01 |             |
| [Nested Loops Prefetching]                                                                                              | Paul White                               | 2013-08-31 |             |
| [Performance tuning backup and restore operations]                                                                      | Derik Hammer                             | 2015-12-21 | [B],[P]     |
| [Execution Plan Analysis: The Mystery Work Table]                                                                       | Paul White                               | 2013-03-08 |             |
| [How to move data between File Groups in SQL Server]                                                                    | Klaus Aschenbrenner                      | 2016-09-26 |             |
| [Optimizing Your Query Plans with the SQL Server 2014 Cardinality Estimator]                                            | Joseph Sack                              | 2014-06-24 |             |
| [Parallelism in SQL Server Query Tuning]                                                                                | Itzik Ben-Gan                            | 2011-03-14 |             |
| [What You Need to Know about the Batch Mode Window Aggregate Operator in SQL Server 2016: Part 1]                       | Itzik Ben-Gan                            | 2016-05-31 |             |
| [What To Do If sp_BlitzFirst Warns About High Compilations]                                                             | Erik Darling                             | 2016-09-27 |             |
| [Questions You Should Be Asking About Your Backups]                                                                     | Erik Darling                             | 2016-10-13 | [B]         |
| [Evolutionary Database Design]                                                                                          | Martin Fowler                            | 2016-05-01 |             |
| [Implementing a custom sort]                                                                                            | Rob Farley                               | 2016-10-17 |             |
| [Deletes that Split Pages and Forwarded Ghosts]                                                                         | Paul White                               | 2012-08-31 |             |
| [Query Optimizer Deep Dive - Part 1]                                                                                    | Paul White                               | 2012-04-28 |             |
| [Query Optimizer Deep Dive - Part 2]                                                                                    | Paul White                               | 2012-04-28 |             |
| [Query Optimizer Deep Dive - Part 3]                                                                                    | Paul White                               | 2012-04-29 |             |
| [Query Optimizer Deep Dive - Part 4]                                                                                    | Paul White                               | 2012-05-01 |             |
| [Should You Rebuild or Reorganize Indexes on Large Tables?]                                                             | Kendra Little                            | 2016-10-13 |             |
| [Retrieving SQL Server Query Execution Plans]                                                                           | Robert Sheldon                           | 2016-10-18 |             |
| [Introduction to Latches in SQL Server]                                                                                 | Klaus Aschenbrenner                      | 2014-06-23 |             |
| [Latch Coupling in SQL Server]                                                                                          | Klaus Aschenbrenner                      | 2016-10-24 |             |
| [Partitioned Views? A How-To Guide]                                                                                     | Erik Darling                             | 2016-09-22 |             |
| [How to Choose Between RCSI and Snapshot Isolation Levels]                                                              | Kendra Little                            | 2016-02-18 |             |
| [TroubleShooting SQL Server Memory Consumption]                                                                         | Satnam Singh                             | 2012-09-28 |             |
| [Time Series Algorithms in SQL Server]                                                                                  | Dinesh Asanka                            | 2015-06-01 |             |
| [Heap Tables in SQL Server]                                                                                             | Klaus Aschenbrenner                      | 2015-10-19 |             |
| [Internals of the Seven SQL Server Sorts – Part 1]                                                                      | Paul White                               | 2015-04-29 |             |
| [Internals of the Seven SQL Server Sorts – Part 2]                                                                      | Paul White                               | 2015-05-07 |             |
| [The 9 Letters That Get DBAs Fired]                                                                                     | Brent Ozar                               | 2011-12-22 |             |
| [Restarting SQL Server – always a good idea?]                                                                           | Klaus Aschenbrenner                      | 2016-08-08 |             |
| [Don’t believe everything you read: Reconfigure flushes the plan cache]                                                 | Matt Bowler                              | 2012-06-25 |             |
| [How-to load data fast into SQL Server 2016]                                                                            | Henk                                     | 2016-10-24 |             |
| [Database Design Matters, RTO and Filegroups]                                                                           | Raul Gonzalez                            | 2016-10-28 |             |
| [Automate Alerting for SQL Server Suspect Database Pages]                                                               | Ben Snaidero                             | 2016-01-25 |             |
| [Successful Anti-Patterns, Storage Requirements]                                                                        | Raul Gonzalez                            | 2016-10-19 |             |
| [SQL Server table columns under the hood]                                                                               | Remus Rusanu                             | 2011-10-20 |             |
| [How to analyse SQL Server performance]                                                                                 | Remus Rusanu                             | 2014-02-24 |             |
| [To BLOB or Not To BLOB: Large Object Storage in a Database or a Filesystem?]                                           | Jim Gray                                 | 2006-04-01 |             |
| [Asynchronous procedure execution]                                                                                      | Remus Rusanu                             | 2009-08-05 |             |
| [What is the CXPACKET Wait Type, and How Do You Reduce It?]                                                             | Brent Ozar                               | 2013-08-27 |             |
| [New indexes, hypothetically]                                                                                           | Kenneth Fisher                           | 2016-11-02 |             |
| [Indexing Wide Keys in SQL Server]                                                                                      | Brent Ozar                               | 2013-05-08 |             |
| [The Anatomy and (In)Security of Microsoft SQL Server Transparent Data Encryption (TDE)]                                | Simon McAuliffe                          | 2016-03-31 |             |
| [Correctly adding data files to tempdb]                                                                                 | Paul Randal                              | 2014-10-14 |             |
| [Why You Should Test Your Queries Against Bigger Data]                                                                  | Erik Darling                             | 2016-11-01 |             |
| [Tally OH! An Improved SQL 8K “CSV Splitter” Function]                                                                  | Jeff Moden                               | 2012-12-28 |             |
| [Set Statistics… Profile?]                                                                                              | Erik Darling                             | 2016-10-11 |             |
| [Hierarchies on Steroids #1: Convert an Adjacency List to Nested Sets]                                                  | Jeff Moden                               | 2014-09-19 |             |
| [Optimizing T-SQL queries that change data]                                                                             | Paul White                               | 2013-01-26 |             |
| [Measuring Query Duration: SSMS vs SQL Sentry Plan Explorer]                                                            | Kendra Little                            | 2016-09-27 |             |
| [Inside the Statistics Histogram & Density Vector]                                                                      | Klaus Aschenbrenner                      | 2014-01-28 |             |
| [Misconceptions on parameter sniffing]                                                                                  | Hugo Kornelis                            | 2016-11-03 |             |
| [CAST vs. CONVERT]                                                                                                      | Aaron Bertrand                           | 2016-11-02 |             |
| [What Every Accidental DBA Needs to Know Now: Basics of SQL Security]                                                   | Tim Ford                                 | 2016-10-03 |             |
| [SQL Server Perfmon (Performance Monitor) Best Practices]                                                               | Brent Ozar                               | 2006-12-30 |             |
| [Top 5 Overlooked Index Features]                                                                                       | Erik Darling                             | 2016-11-10 |             |
| [A Sysadmin’s Guide to Microsoft SQL Server Memory]                                                                     | Brent Ozar                               | 2016-09-15 |             |
| [Searching Strings in SQL Server is Expensive]                                                                          | Brent Ozar                               | 2016-10-18 |             |
| [Altering an INT Column to a BIGINT]                                                                                    | Kendra Little                            | 2016-08-04 |             |
| [Query tuning 101: Problems with IN ()]                                                                                 | Daniel Janik                             | 2016-11-10 |             |
| [Admin: Bulkadmin vs ADMINISTER BULK OPERATIONS]                                                                        | Richard A Brown                          | 2012-01-31 |             |
| [Can Indexes My Query Doesn’t Use Help My Query?]                                                                       | Erik Darling                             | 2016-11-09 |             |
| [SQL Server Audit Walkthrough]                                                                                          | Sadequl Hussain                          | 2016-01-01 |             |
| [The SQL Server 2016 Query Store: Overview and Architecture]                                                            | Enrico van de Laar                       | 2015-11-16 |             |
| [Reading, Writing, and Creating SQL Server Extended Properties]                                                         | Phil Factor                              | 2015-10-21 |             |
| [Questions About SQL Server Security and Access Control You Were Too Shy to Ask]                                        | William Brewer                           | 2016-11-04 |             |
| [The Ten Commandments of SQL Server Monitoring]                                                                         | Adam Machanic                            | 2013-04-09 |             |
| [Should I use NOT IN, OUTER APPLY, LEFT OUTER JOIN, EXCEPT, or NOT EXISTS?]                                             | Adam Machanic                            | 2012-12-27 |             |
| [Parameter Sniffing, Embedding, and the RECOMPILE Options]                                                              | Paul White                               | 2013-08-28 |             |
| [Can comments hamper stored procedure performance?]                                                                     | Aaron Bertrand                           | 2016-11-09 |             |
| [SQL Server Temporary Table Caching]                                                                                    | Simon Liew                               | 2016-08-12 |             |
| [Techniques to Monitor SQL Server memory usage]                                                                         | Basit Farooq                             | 2016-08-01 |             |
| [Troubleshooting Query Regressions Caused By The New Cardinality Estimator]                                             | SQL Scotsman                             | 2016-11-28 |             |
| [Migrating Databases to Azure SQL Database]                                                                             | Tim Radney                               | 2016-10-25 | [MG],[AZ]   |
| [Solve Common SQL Server Restore Issues]                                                                                | Sergey Gigoyan                           | 2015-04-12 |             |
| [Spills SQL Server Doesn’t Warn You About]                                                                              | Erik Darling                             | 2016-11-30 |             |
| [How often should I run DBCC CHECKDB?]                                                                                  | Erik Darling                             | 2016-02-25 |             |
| [Why is My Query Faster the Second Time it Runs?]                                                                       | Kendra Little                            | 2016-11-25 |             |
| [Downgrading the SQL Server Edition of a Dev Environment]                                                               | Kendra Little                            | 2016-11-15 |             |
| [Date Math In The WHERE Clause]                                                                                         | Erik Darling                             | 2016-12-01 |             |
| [Why is This Partitioned Query Slower?]                                                                                 | Kendra Little                            | 2015-09-01 |             |
| [A Beginner’s Guide to the True Order of SQL Operations]                                                                | JOOQ                                     | 2016-12-09 |             |
| [Logical Query Processing: What It Is And What It Means to You]                                                         | Itzik Ben-Gan                            | 2016-01-15 |             |
| [Forcing a Parallel Query Execution Plan]                                                                               | Paul White                               | 2011-12-23 |             |
| [Join Containment Assumption and CE Model Variation]                                                                    | Dmitri Pilugin                           | 2014-05-04 |             |
| [Table Variable Tip]                                                                                                    | Itzik Ben-Gan                            | 2015-02-08 |             |
| [Heap tables in SQL Server]                                                                                             | Derik Hammer                             | 2016-04-13 |             |
| [The ‘B’ in B-Tree – Indexing in SQL Server]                                                                            | Derik Hammer                             | 2016-04-04 |             |
| [How to read the SQL Server Database Transaction Log]                                                                   | Manvendra Singh                          | 2013-10-31 |             |
| [Filtered Statistics Follow-up]                                                                                         | Erik Darling                             | 2016-12-22 |             |
| [SQL Server Query Optimization: No Unknown Unknowns]                                                                    | Itzik Ben-Gan                            | 2015-10-13 |             |
| [Sync Vs Async Statistics: The Old Debate]                                                                              | SQL Scotsman                             | 2016-12-10 |             |
| [Recommended updates and configuration options for SQL Server 2012 and SQL Server 2014 with high-performance workloads] | Microsoft                                | 2016-03-08 |             |
| [Troubleshooting SQL Server backup and restore operations]                                                              | Microsoft                                | 2016-07-23 | [B]         |
| [SQL Server 2016: Getting tempdb a little more right]                                                                   | Aaron Bertrand                           | 2015-09-30 |             |
| [Practical uses of binary types]                                                                                        | Daniel Hutmacher                         | 2017-01-09 |             |
| [Backing Up SQL Server Databases is Easier in PowerShell than T-SQL]                                                    | Aaron Nelson                             | 2017-01-12 |             |
| [Creating, detaching, re-attaching, and fixing a SUSPECT database]                                                      | Paul Randal                              | 2008-08-29 |             |
| [Modifying Tables Online – Part 1: Migration Strategy]                                                                  | Michael J Swart                          | 2012-04-16 | [MG]        |
| [Modifying Tables Online – Part 2: Implementation Example]                                                              | Michael J Swart                          | 2012-04-17 | [MG]        |
| [Modifying Tables Online – Part 3: Example With Error Handling]                                                         | Michael J Swart                          | 2012-04-20 | [MG]        |
| [Modifying Tables Online – Part 4: Testing]                                                                             | Michael J Swart                          | 2012-04-26 | [MG]        |
| [Modifying Tables Online – Part 5: Just One More Thing]                                                                 | Michael J Swart                          | 2012-04-27 |             |
| [DATEDIFF vs. DATEADD]                                                                                                  | Guy Glanster                             | 2017-01-25 |             |
| [Disaster recovery 101: hack-attach a damaged database]                                                                 | Paul Randal                              | 2010-06-18 |             |
| [Bones of SQL - The Calendar Table]                                                                                     | Bob Hovious                              | 2016-09-08 |             |
| [SQL Server 2016, Double or Nothing, Always Encrypted with temporal tables]                                             | Raul Gonzalez                            | 2016-07-27 |             |
| [Reclaiming Space After Column Data Type Change]                                                                        | David Fundakowski                        | 2016-08-09 |             |
| [Packing Intervals with Priorities]                                                                                     | Itzik Ben-Gan                            | 2015-11-10 |             |
| [Avoid Unnecessary Lookups when Using ROW_NUMBER for Paging]                                                            | Itzik Ben-Gan                            | 2014-12-11 |             |
| [Migrating a Disk-Based Table to a Memory-Optimized Table in SQL Server]                                                | Alex Grinberg                            | 2017-02-26 | [MG]        |
| [SQL Server Hardware Optimization]                                                                                      | Basit Farooq                             | 2016-06-01 |             |
| [Index Types  Heaps, Primary Keys, Clustered and Nonclustered Indexes]                                                  | Kendra Little                            | 2017-02-02 |             |
| [Identifying Existence of Intersections in Intervals]                                                                   | Itzik Ben-Gan                            | 2017-02-08 |             |
| [Cheat Sheet  How to Configure TempDB for Microsoft SQL Server]                                                         | Brent Ozar                               | 2016-01-14 |             |
| [A Tourist’s Guide to the sp_Blitz Source Code, Part 1: The Big Picture]                                                | Brent Ozar                               | 2017-02-09 |             |
| [SQL Server Default Configurations That You Should Change]                                                              | Pio Balistoy                             | 2017-02-06 |             |
| [Decoding Key and Page WaitResource for Deadlocks and Blocking]                                                         | Kendra Little                            | 2016-10-17 |             |
| [Security in the CLR World Inside SQL Server]                                                                           | Kiely Don                                | 1990-01-01 |             |
| [On the Advantages of DateTime2(n) over DateTime]                                                                       | William Assaf                            | 2012-12-04 |             |
| [Build Your Own Tools]                                                                                                  | Michael J. Swart                         | 2016-09-23 |             |
| [Enhanced T-SQL Error Handling With Extended Events]                                                                    | Dave Mason                               | 2016-09-14 |             |
| [Compression and its Effects on Performance]                                                                            | Erin Stellato                            | 2017-01-20 |             |
| [Does Truncate Table Reset Statistics]                                                                                  | Kendra Little                            | 2016-12-08 |             |
| [SQL Server Database Decommissioning Check List]                                                                        | Svetlana Golovko                         | 2016-06-23 |             |
| [New SQL Server Database Request Questionnaire and Checklist]                                                           | Svetlana Golovko                         | 2015-02-24 |             |
| [Adding Partitions to the Lower End of a Left Based Partition Function]                                                 | Kendra Little                            | 2017-02-21 |             |
| [Don't Panic  Busting a File Space Myth]                                                                                | Tim Ford                                 | 2016-11-14 |             |
| [#BackToBasics : Dating Responsibly]                                                                                    | Aaron Bertrand                           | 2016-04-06 |             |
| [How to Establish Dedicated Admin Connection (DAC) to SQL Server]                                                       | Mika Wendelius                           | 2016-10-05 |             |
| [SQL and SQL only Best Practice]                                                                                        | Nagaraj Venkatesan                       | 2013-05-27 |             |
| [There Is No Difference Between Table Variables, Temporary Tables, and Common Table Expressions]                        | Grant Fritchey                           | 2016-08-04 |             |
| [Availability Group on SQL Server 2016]                                                                                 | Guy Glantser                             | 2017-02-01 |             |
| [Using SQL Server and R Services for analyzing DBA Tasks]                                                               | Tomaž Kaštrun                            | 2017-02-17 |             |
| [SQLskills SQL101: Dealing with SQL Server corruption]                                                                  | Paul Randal                              | 2017-02-28 |             |
| [Advanced Analytics with R & SQL: Part I - R Distributions]                                                             | Frank A. Banin                           | 2016-10-31 | [R]         |
| [T-SQL Tuesday #85  STOP! Restore Time!]                                                                                | Derik Hammer                             | 2016-12-13 |             |
| [Filtered Indexes: Rowstore vs Nonclustered Columnstore]                                                                | Kendra Little                            | 2016-11-10 |             |
| [ALTER SCHEMA TRANSFER for Zero Downtime Database Upgrades]                                                             | Dave Wentzel                             | 2013-05-21 |             |
| [Delayed Durability in SQL Server 2014]                                                                                 | Aaron Bertrand                           | 2014-04-28 |             |
| [Daylight Savings end affects not only you, but your SQL Server too]                                                    | Aaron Bertrand                           | 2014-04-28 |             |
| [Searching Strings in SQL Server is Expensive]                                                                          | Brent Ozar                               | 2016-10-18 |             |
| [Let’s Corrupt a SQL Server Database Together, Part 1: Clustered Indexes]                                               | Brent Ozar                               | 2017-02-22 | [COR]       |
| [Let’s Corrupt a Database Together, Part 2: Nonclustered Indexes]                                                       | Brent Ozar                               | 2017-02-28 | [COR]       |
| [The Guide  SQL Server Installation Checklist (settings that increase SQL Server Performance)]                          | Mark Varnas                              | 2017-03-03 |             |
| [SQL Browser, what is it good for? Absolutely something!]                                                               | Chris Sommer                             | 2017-03-01 |             |
| [PowerShell Getting More From Generic Error Messages]                                                                   | Shane O'Neill                            | 2017-03-02 | [PS]        |
| [#BackToBasics : Common Table Expressions (CTEs)]                                                                       | Aaron Bertrand                           | 2016-01-06 |             |
| [SQL VNext sp_configure on Windows and Linux with dbatools]                                                             | Rob Sewell                               | 2017-03-02 | [PS]        |
| [Adding a T-SQL Job Step to a SQL Agent Job with PowerShell]                                                            | Rob Sewell                               | 2017-02-20 | [PS],[J]    |
| [Setting up Database Mail to use my Gmail account]                                                                      | Mat Hayward                              | 2017-03-01 | [DM]        |
| [Using DBCC CLONEDATABASE and Query Store for Testing]                                                                  | Erin Stellato                            | 2017-02-22 | [DBCC]      |
| [Getting Started with Natural Earth — A SQL Server Shapefile Alternative (Geospatial Resource)]                         | Jeff Pries                               | 2017-02-17 | [V]         |
| [SQL Server Temporal Tables: How-To Recipes]                                                                            | Alex Grinberg                            | 2017-02-10 | [DEV]       |
| [The Migration Checklist]                                                                                               | Steve Jones                              | 2017-03-08 | [MG]        |
| [Upgrading to SQL Server 2014: A Dozen Things to Check]                                                                 | Steve Jones                              | 2014-06-03 | [MG]        |
| [Introducing the Set-based Loop]                                                                                        | Luis Cazares                             | 2015-07-27 | [DEV]       |
| [Representing Hierarchical Data for Mere Mortals]                                                                       | Phil Factor                              | 2016-10-06 | [DEV]       |
| [KPIs For DBAs to Show Their CIOs]                                                                                      | Thomas Larock                            | 2017-03-08 | [DBA]       |
| [How To Forecast Database Disk Capacity If You Don’t Have A Monitoring Tool]                                            | Edwin M Sarmiento                        | 2015-07-31 | [DBA]       |
| [Statistical Sampling for Verifying Database Backups]                                                                   | Thomas Larock                            | 2010-05-13 | [DBA],[B]   |
| [Inside The Storage Engine  GAM, SGAM, PFS and other allocation maps]                                                   | Paul Randal                              | 2008-03-04 | [DBA]       |
| [Using dbatools for automated restore and CHECKDB]                                                                      | Anthony Nocentino                        | 2017-03-04 | [DBA],[PS]  |
| [Bad Habits Revival]                                                                                                    | Aaron Bertrand                           | 2017-01-26 | [DBA]       |
| [Deploying Multiple SSIS Projects via PowerShell]                                                                       | Nat Sundar                               | 2017-02-27 | [SSIS,][PS] |
| [Determining the Cost Threshold for Parallelism]                                                                        | Grant Fritchey                           | 2017-02-28 | [DBA]       |
| [Identifying a row’s physical location]                                                                                 | Wayne Sheffield                          | 2017-03-08 | [DBA]       |
| [Split a file group into multiple data files]                                                                           | Trayce Jordan                            | 2017-03-03 | [DBA]       |
| [Why PFS pages cannot be repaired]                                                                                      | Paul Randal                              | 2017-03-05 | [DBA]       |
| [ERRORLOG records max out at 2049 characters]                                                                           | Cody Konior                              | 2017-03-02 | [DEV]       |
| [How to Build a SQL Server Disaster Recovery Plan with Google Compute Engine]                                           | Tara Kizer                               | 2017-03-10 | [DBA]       |
| [SQL Server Performance Tuning in Google Compute Engine]                                                                | Erik Darling                             | 2017-03-09 | [DBA],[P]   |
| [Configuring R on SQL Server 2016]                                                                                      | Ginger Grant                             | 2016-12-06 | [DBA],[R]   |
| [Knee-Jerk PerfMon Counters: Page Life Expectancy]                                                                      | Paul Randal                              | 2014-10-20 | [DBA],[P]   |
| [Change Management Template for SQL Server DBAs and Developers]                                                         | Kendra Little                            | 2016-04-12 | [DBA]       |

[SQL Server Index Design Guide]:https://technet.microsoft.com/en-us/library/jj835095.aspx
[SQL Server 2012 Security Best Practices - Microsoft]:http://download.microsoft.com/download/8/f/a/8fabacd7-803e-40fc-adf8-355e7d218f4c/sql_server_2012_security_best_practice_whitepaper_apr2012.docx
[Help, my database is corrupt. Now what?]:http://www.sqlservercentral.com/articles/Corruption/65804/
[What to Do When DBCC CHECKDB Reports Corruption]:https://www.brentozar.com/archive/2016/05/dbcc-checkdb-reports-corruption/
[Understanding how SQL Server executes a query]:http://rusanu.com/2013/08/01/understanding-how-sql-server-executes-a-query/
[Troubleshooting SQL Server CPU Performance Issues]:http://sqlperformance.com/2013/05/io-subsystem/cpu-troubleshooting
[Knee-Jerk Performance Tuning : Incorrect Use of Temporary Tables]:http://sqlperformance.com/2016/04/t-sql-queries/knee-jerk-temporary-tables
[High Performance T-SQL using Code Patterns]:https://dwaincsql.com/2015/05/27/high-performance-t-sql-using-code-patterns/
[SQL Server Database Corruption Repair]:http://stevestedman.com/2015/08/sql-server-database-corruption-repair/
[Basic SQL Server Performance Troubleshooting For Developers]:https://www.simple-talk.com/sql/performance/basic-sql-server-performance-troubleshooting-for-developers/
[The Curse and Blessings of Dynamic SQL]:http://sommarskog.se/dyn-search.html
[Dynamic Search Conditions in T-SQL]:http://www.sommarskog.se/dynamic_sql.html
[Slow in the Application, Fast in SSMS]:http://www.sommarskog.se/query-plan-mysteries.html
[How to share data between stored procedures]:http://www.sommarskog.se/share_data.html
[Arrays and Lists in SQL Server 2008]:http://www.sommarskog.se/arrays-in-sql-2008.html
[Giving Permissions through Stored Procedures]:http://www.sommarskog.se/grantperm.html
[Error and Transaction Handling in SQL Server]:http://www.sommarskog.se/error_handling/Part1.html
[Using the Bulk-Load Tools in SQL Server]:http://www.sommarskog.se/bulkload.html
[Using Table-Valued Parameters in SQL Server and .NET]:http://www.sommarskog.se/arrays-in-sql-2008.html
[SQL Server Columnstore Articles]:http://www.nikoport.com/columnstore/
[Documentation: It Does not Suck!]:https://www.brentozar.com/archive/2013/01/documentation-it-doesnt-suck/
[The Data Loading Performance Guide]:https://msdn.microsoft.com/en-us/library/dd425070%28v=sql.100%29.aspx
[Required Testing for Installing SQL Server Cumulative Updates and Service Packs]:http://www.littlekendra.com/2016/04/28/required-testing-for-installing-sql-server-cumulative-updates-and-service-packs/
[Stop Shrinking Your Database Files. Seriously. Now.]:https://www.brentozar.com/archive/2009/08/stop-shrinking-your-database-files-seriously-now/
[How to shrink a database in 4 easy steps]:http://am2.co/2016/04/shrink-database-4-easy-steps/
[Introduction to the Index Operational Statistics Dynamic Management Function]:http://sqlmag.com/database-performance-tuning/introduction-index-operational-statistics-dynamic-management-function
[Updating Statistics in SQL Server: Maintenance Questions & Answers]:http://www.littlekendra.com/2016/04/18/updating-statistics-in-sql-server-maintenance-answers/
[Overcoming Variable Limitations in SQLCmd Mode]:http://www.sqlsoldier.com/wp/sqlserver/tsqltuesday65overcomingvariablelimitationsinsqlcmdmode
[Contents of a Run Book]:https://technet.microsoft.com/en-us/library/cc917702.aspx
[Compressed and Encrypted Backups on the Cheap]:https://bornsql.ca/2016/04/compressed-encrypted-backups-cheap/
[Curing Data-Obesity in OLTP Databases]:https://www.simple-talk.com/sql/database-administration/curing-data-obesity-in-oltp-databases/
[Understanding GRANT, DENY, and REVOKE in SQL Server]:https://www.mssqltips.com/sqlservertip/2894/understanding-grant-deny-and-revoke-in-sql-server/
[Monitor SQL Server Transaction Log File Free Space]:https://www.mssqltips.com/sqlservertip/3617/monitor-sql-server-transaction-log-file-free-space/
[Dynamically Query a 100 Million Row Table-Efficiently]:http://www.sqlservercentral.com/articles/T-SQL/121906/
[Understanding and Using Parallelism in SQL Server]:https://www.simple-talk.com/sql/learn-sql-server/understanding-and-using-parallelism-in-sql-server/
[Diagnosing and Resolving Latch Contention on SQL Server]:https://www.microsoft.com/en-us/download/details.aspx?id=26665
[Parallel Execution Plans – Branches and Threads]:http://sqlperformance.com/2013/10/sql-plan/parallel-plans-branches-threads
[Nasty Fast PERCENT_RANK]:http://www.sqlservercentral.com/articles/PERCENT_RANK/141532/
[Looking at VIEWs, Close Up]:https://www.simple-talk.com/sql/t-sql-programming/looking-at-views,-close-up/
[SQL Server 2016: It Just Runs Faster]:http://thomaslarock.com/2016/06/sql-server-2016-just-runs-faster/
[TSQL JOIN Types Poster]:http://stevestedman.com/2015/05/tsql-join-types-poster-version-4-1/
[It is Hard To Destroy Data]:http://michaeljswart.com/2015/05/its-hard-to-destroy-data/
[How to transfer logins and passwords between instances of SQL Server]:https://support.microsoft.com/en-us/kb/918992
[Finding File Growths with Extended Events]:http://nebraskasql.blogspot.ru/2016/06/finding-file-growths-with-extended.html
[Questions You Should Ask About the Databases You Manage]:https://www.brentozar.com/archive/2016/06/questions-ask-databases-manage/
[Clustered Indexes in SQL Server]:http://www.sqlhammer.com/clustered-indexes-sql-server/
[Triage Quiz: Is Your SQL Server Safe?]:https://www.brentozar.com/archive/2016/06/triage-quiz-sql-server-safe/
[Why Not Just Create Statistics?]:https://www.brentozar.com/archive/2016/07/not-just-create-statistics/
[Understanding the SQL Server NOLOCK hint]:https://www.mssqltips.com/sqlservertip/2470/understanding-the-sql-server-nolock-hint/
[Recover access to a SQL Server instance]:https://www.mssqltips.com/sqlservertip/2682/recover-access-to-a-sql-server-instance/
[SQL Server 2016 Upgrade Planning]:http://sqlmag.com/sql-server/sql-server-2016-upgrade-planning-0
[Graphs and Graph Algorithms in T-SQL]:http://www.hansolav.net/sql/graphs.html
[Episode 4: SQL Server R Services makes you a smarter T-SQL Developer]:https://blogs.msdn.microsoft.com/sqlcat/2016/07/12/sqlsweet16-episode-4-sql-server-r-services-makes-you-a-smarter-t-sql-developer/
[How to Set Max Degree of Parallelism in SQL Server]:http://www.littlekendra.com/2016/07/14/max-degree-of-parallelism-cost-threshold-for-parallelism/
[Undocumented Query Plans: Equality Comparisons]:http://sqlblog.com/blogs/paul_white/archive/2011/06/22/undocumented-query-plans-equality-comparisons.aspx
[Simplified Order Of Operations]:http://michaeljswart.com/2016/07/simplified-order-of-operations/
[SQL Server Statistics Basics]:https://www.simple-talk.com/sql/performance/sql-server-statistics-basics/
[Learn to Use sp_Blitz, sp_BlitzCache, sp_BlitzFirst, and sp_BlitzIndex with These Tutorial Videos]:https://www.brentozar.com/archive/2016/09/learn-use-sp_blitz-sp_blitzcache-sp_blitzfirst-sp_blitzindex-tutorial-videos/
[Where is a record really located?]:https://blogs.msdn.microsoft.com/sql_pfe_blog/2016/09/15/where-is-a-record-really-located/
[Instant File Initialization (IFI)]:http://stevestedman.com/2016/09/instant-file-initialization-ifi/
[How to Query the StackExchange Databases]:https://www.brentozar.com/archive/2014/01/how-to-query-the-stackexchange-databases/
[How to Troubleshoot Performance in SQL Server (Dear SQL DBA)]:http://www.littlekendra.com/2016/06/02/dear-sql-dba-lost-in-performance-troubleshooting/
[How to Log Activity Using sp_whoisactive in a Loop]:https://www.brentozar.com/responder/log-sp_whoisactive-to-a-table/
[Logging Activity Using sp_WhoIsActive – Take 2]:https://www.brentozar.com/archive/2016/07/logging-activity-using-sp_whoisactive-take-2/
[How To Fix Forwarded Records]:https://www.brentozar.com/archive/2016/07/fix-forwarded-records/
[Should I Automate my Windows Updates for SQL Server?]:http://www.littlekendra.com/2016/07/28/should-i-automate-my-windows-updates-for-sql-server-dear-sql-dba-episode-10/
[Finding the Right Path]:http://jasonbrimhall.info/2016/08/24/finding-the-right-path/
[#BackToBasics : An Updated "Kitchen Sink" Example]:https://blogs.sqlsentry.com/aaronbertrand/backtobasics-updated-kitchen-sink-example/
[Locking and Blocking in SQL Server]:https://www.brentozar.com/sql/locking-and-blocking-in-sql-server/
[Nested Loops Prefetching]:http://sqlblog.com/blogs/paul_white/archive/2013/08/31/sql-server-internals-nested-loops-prefetching.aspx
[Performance tuning backup and restore operations]:http://www.sqlhammer.com/performance-tuning-backup-restore-operations/
[Execution Plan Analysis: The Mystery Work Table]:http://sqlblog.com/blogs/paul_white/archive/2013/03/08/execution-plan-analysis-the-mystery-work-table.aspx
[How to move data between File Groups in SQL Server]:http://www.sqlpassion.at/archive/2016/09/26/how-to-move-data-between-file-groups-in-sql-server/
[Optimizing Your Query Plans with the SQL Server 2014 Cardinality Estimator]:https://msdn.microsoft.com/en-us/library/dn673537.aspx
[Parallelism in SQL Server Query Tuning]:http://sqlmag.com/sql-server/parallelism-sql-server-query-tuning
[What You Need to Know about the Batch Mode Window Aggregate Operator in SQL Server 2016: Part 1]:http://sqlmag.com/sql-server/what-you-need-know-about-batch-mode-window-aggregate-operator-sql-server-2016-part-1
[What To Do If sp_BlitzFirst Warns About High Compilations]:https://www.brentozar.com/archive/2016/09/what-to-do-if-sp_blitzfirst-warns-about-high-compilations/
[Questions You Should Be Asking About Your Backups]:https://www.brentozar.com/archive/2016/10/questions-asking-backups/
[Evolutionary Database Design]:http://martinfowler.com/articles/evodb.html
[Implementing a custom sort]:https://sqlperformance.com/2016/10/sql-plan/implementing-custom-sort
[Deletes that Split Pages and Forwarded Ghosts]:http://sqlblog.com/blogs/paul_white/archive/2012/08/31/deletes-that-split-pages-and-forwarded-ghosts.aspx
[Query Optimizer Deep Dive - Part 1]:http://sqlblog.com/blogs/paul_white/archive/2012/04/28/query-optimizer-deep-dive-part-1.aspx
[Query Optimizer Deep Dive - Part 2]:http://sqlblog.com/blogs/paul_white/archive/2012/04/28/query-optimizer-deep-dive-part-2.aspx
[Query Optimizer Deep Dive - Part 3]:http://sqlblog.com/blogs/paul_white/archive/2012/04/29/query-optimizer-deep-dive-part-3.aspx
[Query Optimizer Deep Dive - Part 4]:http://sqlblog.com/blogs/paul_white/archive/2012/05/01/query-optimizer-deep-dive-part-4.aspx
[Should You Rebuild or Reorganize Indexes on Large Tables?]:https://www.littlekendra.com/2016/10/13/should-you-rebuild-or-reorganize-indexes-on-large-tables-dear-sql-dba-episode-19/
[Retrieving SQL Server Query Execution Plans]:https://www.simple-talk.com/sql/database-administration/retrieving-sql-server-query-execution-plans/ 
[Introduction to Latches in SQL Server]:http://www.sqlpassion.at/archive/2014/06/23/introduction-to-latches-in-sql-server/
[Latch Coupling in SQL Server]:https://www.sqlpassion.at/archive/2016/10/24/latch-coupling-in-sql-server/
[Partitioned Views? A How-To Guide]:https://www.brentozar.com/archive/2016/09/partitioned-views-guide/
[How to Choose Between RCSI and Snapshot Isolation Levels]:https://www.littlekendra.com/2016/02/18/how-to-choose-rcsi-snapshot-isolation-levels/
[TroubleShooting SQL Server Memory Consumption]:http://www.sql-server-performance.com/2016/trouble-shooting-sql-server-ra-memory-consumption/
[Time Series Algorithms in SQL Server]:http://www.sql-server-performance.com/2015/time-series-algorithms-sql-server/
[Heap Tables in SQL Server]:http://www.sqlpassion.at/archive/2015/10/19/heap-tables-in-sql-server/
[Internals of the Seven SQL Server Sorts – Part 1]:https://sqlperformance.com/2015/04/sql-plan/internals-of-the-seven-sql-server-sorts-part-1
[Internals of the Seven SQL Server Sorts – Part 2]:https://sqlperformance.com/2015/05/sql-plan/internals-of-the-seven-sql-server-sorts-part-2
[The 9 Letters That Get DBAs Fired]:https://www.brentozar.com/archive/2011/12/letters-that-get-dbas-fired/
[Restarting SQL Server – always a good idea?]:https://www.sqlpassion.at/archive/2016/08/08/restarting-sql-server-always-a-good-idea/
[Don’t believe everything you read: Reconfigure flushes the plan cache]:https://mattsql.wordpress.com/2012/06/25/dont-believe-everything-you-read-reconfigure-flushes-the-plan-cache/
[How-to load data fast into SQL Server 2016]:http://henkvandervalk.com/how-to-load-data-fast-into-sql-server-2016
[Database Design Matters, RTO and Filegroups]:http://www.sqldoubleg.com/2016/10/28/database-design-matters-rto-and-filegroups/
[Automate Alerting for SQL Server Suspect Database Pages]:https://www.mssqltips.com/sqlservertip/4166/automate-alerting-for-sql-server-suspect-database-pages/
[Successful Anti-Patterns, Storage Requirements]:http://www.sqldoubleg.com/2016/10/19/successful-anti-patterns-storage-requirements/
[SQL Server table columns under the hood]:http://rusanu.com/2011/10/20/sql-server-table-columns-under-the-hood/
[How to analyse SQL Server performance]:http://rusanu.com/2014/02/24/how-to-analyse-sql-server-performance/
[To BLOB or Not To BLOB: Large Object Storage in a Database or a Filesystem?]:https://www.microsoft.com/en-us/research/publication/to-blob-or-not-to-blob-large-object-storage-in-a-database-or-a-filesystem/
[Asynchronous procedure execution]:http://rusanu.com/2009/08/05/asynchronous-procedure-execution/
[What is the CXPACKET Wait Type, and How Do You Reduce It?]:https://www.brentozar.com/archive/2013/08/what-is-the-cxpacket-wait-type-and-how-do-you-reduce-it/
[New indexes, hypothetically]:https://sqlstudies.com/2016/11/02/new-indexes-hypothetically/
[Indexing Wide Keys in SQL Server]:https://www.brentozar.com/archive/2013/05/indexing-wide-keys-in-sql-server/
[The Anatomy and (In)Security of Microsoft SQL Server Transparent Data Encryption (TDE)]:http://simonmcauliffe.com/technology/tde/
[Correctly adding data files to tempdb]:http://www.sqlskills.com/blogs/paul/correctly-adding-data-files-tempdb/
[Why You Should Test Your Queries Against Bigger Data]:https://www.brentozar.com/archive/2016/11/why-you-should-test-your-queries-against-bigger-data/
[Tally OH! An Improved SQL 8K “CSV Splitter” Function]:http://www.sqlservercentral.com/articles/Tally+Table/72993/
[Set Statistics… Profile?]:https://www.brentozar.com/archive/2016/10/set-statistics-profile/
[Hierarchies on Steroids #1: Convert an Adjacency List to Nested Sets]:http://www.sqlservercentral.com/articles/Hierarchy/94040/
[Optimizing T-SQL queries that change data]:http://sqlblog.com/blogs/paul_white/archive/2013/01/26/optimizing-t-sql-queries-that-change-data.aspx
[Measuring Query Duration: SSMS vs SQL Sentry Plan Explorer]:https://www.littlekendra.com/2016/09/27/measuring-query-duration-ssms-vs-sql-sentry-plan-explorer/
[Inside the Statistics Histogram & Density Vector]:http://www.sqlpassion.at/archive/2014/01/28/inside-the-statistics-histogram-density-vector/
[Misconceptions on parameter sniffing]:http://sqlblog.com/blogs/hugo_kornelis/archive/2016/11/03/misconceptions-on-parameter-sniffing.aspx
[CAST vs. CONVERT]:https://blogs.sentryone.com/aaronbertrand/backtobasics-cast-vs-convert/
[What Every Accidental DBA Needs to Know Now: Basics of SQL Security]:http://sqlmag.com/database-security/what-every-accidental-dba-needs-know-now-basics-sql-security
[SQL Server Perfmon (Performance Monitor) Best Practices]:https://www.brentozar.com/archive/2006/12/dba-101-using-perfmon-for-sql-performance-tuning/
[Top 5 Overlooked Index Features]:https://www.brentozar.com/archive/2016/11/top-5-overlooked-index-features/
[A Sysadmin’s Guide to Microsoft SQL Server Memory]:https://www.brentozar.com/archive/2011/09/sysadmins-guide-microsoft-sql-server-memory/
[Searching Strings in SQL Server is Expensive]:https://www.brentozar.com/archive/2016/10/searching-strings-sql-server-expensive/
[Altering an INT Column to a BIGINT]:https://www.littlekendra.com/2016/08/04/altering-an-int-column-to-a-bigint-dear-sql-dba-episode-11/
[Query tuning 101: Problems with IN ()]:http://www.sqlservercentral.com/blogs/confessions-of-a-microsoft-addict/2016/11/10/query-tuning-101-problems-with-in-/
[Admin: Bulkadmin vs ADMINISTER BULK OPERATIONS]:http://richbrownesq-sqlserver.blogspot.ru/2012/01/admin-bulkadmin-vs-administer-bulk.html
[Can Indexes My Query Doesn’t Use Help My Query?]:https://www.brentozar.com/archive/2016/11/can-indexes-query-doesnt-use-help-query/
[SQL Server Audit Walkthrough]:http://www.sql-server-performance.com/2016/walkthrough-sql-server-audit/
[The SQL Server 2016 Query Store: Overview and Architecture]:https://www.simple-talk.com/sql/database-administration/the-sql-server-2016-query-store-overview-and-architecture/
[Reading, Writing, and Creating SQL Server Extended Properties]:https://www.simple-talk.com/sql/database-delivery/reading-writing-creating-sql-server-extended-properties/
[Questions About SQL Server Security and Access Control You Were Too Shy to Ask]:https://www.simple-talk.com/sql/database-delivery/questions-sql-server-security-access-control-shy-ask/
[The Ten Commandments of SQL Server Monitoring]:https://www.simple-talk.com/sql/database-administration/the-ten-commandments-of-sql-server-monitoring/
[Should I use NOT IN, OUTER APPLY, LEFT OUTER JOIN, EXCEPT, or NOT EXISTS?]:https://sqlperformance.com/2012/12/t-sql-queries/left-anti-semi-join
[Parameter Sniffing, Embedding, and the RECOMPILE Options]:https://sqlperformance.com/2013/08/t-sql-queries/parameter-sniffing-embedding-and-the-recompile-options
[Can comments hamper stored procedure performance?]:https://sqlperformance.com/2016/11/sql-performance/comments-hamper-performance
[SQL Server Temporary Table Caching]:https://www.mssqltips.com/sqlservertip/4406/sql-server-temporary-table-caching/
[Techniques to Monitor SQL Server memory usage]:http://www.sql-server-performance.com/2016/monitor-sql-server-memory-usage/
[Troubleshooting Query Regressions Caused By The New Cardinality Estimator]:https://sqlserverscotsman.wordpress.com/2016/11/24/troubleshooting-query-regressions-caused-by-the-new-cardinality-estimator/
[Migrating Databases to Azure SQL Database]:https://sqlperformance.com/2016/10/sql-performance/migrating-to-azure-sql-database
[Solve Common SQL Server Restore Issues]:https://www.mssqltips.com/sqlservertip/4110/solve-common-sql-server-restore-issues/
[Spills SQL Server Doesn’t Warn You About]:https://www.brentozar.com/archive/2016/11/spills-sql-server-doesnt-warn/
[How often should I run DBCC CHECKDB?]:https://www.brentozar.com/archive/2016/02/how-often-should-i-run-dbcc-checkdb/
[Why is My Query Faster the Second Time it Runs?]:https://www.littlekendra.com/2016/11/25/why-is-my-query-faster-the-second-time-it-runs-dear-sql-dba-episode-23/
[Downgrading the SQL Server Edition of a Dev Environment]:https://www.littlekendra.com/2016/11/15/downgrading-the-sql-server-edition-of-a-dev-environment/
[Date Math In The WHERE Clause]:https://www.brentozar.com/archive/2016/12/date-math-clause/
[Why is This Partitioned Query Slower?]:https://www.brentozar.com/archive/2015/09/why-is-this-partitioned-query-slower/
[A Beginner’s Guide to the True Order of SQL Operations]:https://blog.jooq.org/2016/12/09/a-beginners-guide-to-the-true-order-of-sql-operations/
[Logical Query Processing: What It Is And What It Means to You]:http://sqlmag.com/sql-server/logical-query-processing-what-it-and-what-it-means-you
[Forcing a Parallel Query Execution Plan]:http://sqlblog.com/blogs/paul_white/archive/2011/12/23/forcing-a-parallel-query-execution-plan.aspx
[Join Containment Assumption and CE Model Variation]:http://www.queryprocessor.com/ce_join_base_containment_assumption/
[Table Variable Tip]:http://sqlmag.com/t-sql/table-variable-tip
[Heap tables in SQL Server]:http://www.sqlhammer.com/heaps-in-microsoft-sql-server/
[The ‘B’ in B-Tree – Indexing in SQL Server]:http://www.sqlhammer.com/the-b-in-b-tree-indexing-sql-server/
[How to read the SQL Server Database Transaction Log]:https://www.mssqltips.com/sqlservertip/3076/how-to-read-the-sql-server-database-transaction-log/
[Filtered Statistics Follow-up]:https://www.brentozar.com/archive/2016/12/filtered-statistics-follow/
[SQL Server Query Optimization: No Unknown Unknowns]:http://sqlmag.com/sql-server/sql-server-query-optimization-no-unknown-unknowns
[Sync Vs Async Statistics: The Old Debate]:https://sqlserverscotsman.wordpress.com/2016/12/10/sync-vs-async-statistics-the-old-debate/
[Recommended updates and configuration options for SQL Server 2012 and SQL Server 2014 with high-performance workloads]:https://support.microsoft.com/en-gb/kb/2964518
[Troubleshooting SQL Server backup and restore operations]:https://support.microsoft.com/en-us/kb/224071
[SQL Server 2016: Getting tempdb a little more right]:https://blogs.sentryone.com/aaronbertrand/sql-server-2016-tempdb-fixes/
[Practical uses of binary types]:https://sqlsunday.com/2017/01/09/binary-types/
[Backing Up SQL Server Databases is Easier in PowerShell than T-SQL]:http://www.sqlservercentral.com/articles/PowerShell/151510/
[Creating, detaching, re-attaching, and fixing a SUSPECT database]:http://www.sqlskills.com/blogs/paul/creating-detaching-re-attaching-and-fixing-a-suspect-database/
[Modifying Tables Online – Part 1: Migration Strategy]:http://michaeljswart.com/2012/04/modifying-tables-online-part-1-migration-strategy/
[Modifying Tables Online – Part 2: Implementation Example]:http://michaeljswart.com/2012/04/modifying-tables-online-part-2-implementation-example/
[Modifying Tables Online – Part 3: Example With Error Handling]:http://michaeljswart.com/2012/04/modifying-tables-online-part-3-example-with-error-handling/
[Modifying Tables Online – Part 4: Testing]:http://michaeljswart.com/2012/04/modifying-tables-online-part-4-testing/
[Modifying Tables Online – Part 5: Just One More Thing]:http://michaeljswart.com/2012/04/modifying-tables-online-part-5-just-one-more-thing/
[DATEDIFF vs. DATEADD]:http://www.madeiradata.com/datediff-vs-dateadd/
[Disaster recovery 101: hack-attach a damaged database]:http://www.sqlskills.com/blogs/paul/disaster-recovery-101-hack-attach-a-damaged-database/
[Bones of SQL - The Calendar Table]:http://www.sqlservercentral.com/articles/calendar/145206/
[SQL Server 2016, Double or Nothing, Always Encrypted with temporal tables]:http://www.sqldoubleg.com/2016/07/27/sql-server-2016-double-or-nothing-always-encrypted-with-temporal-tables/
[Reclaiming Space After Column Data Type Change]:http://www.sqlservercentral.com/articles/data+type/144308/
[Packing Intervals with Priorities]:http://sqlmag.com/sql-server/packing-intervals-priorities
[Avoid Unnecessary Lookups when Using ROW_NUMBER for Paging]:http://sqlmag.com/t-sql/avoid-unnecessary-lookups-when-using-rownumber-paging
[Migrating a Disk-Based Table to a Memory-Optimized Table in SQL Server]:https://www.simple-talk.com/sql/database-administration/migrating-disk-based-table-memory-optimized-table-sql-server/
[SQL Server Hardware Optimization]:http://www.sql-server-performance.com/2016/sql-server-hardware-optimization/
[Index Types  Heaps, Primary Keys, Clustered and Nonclustered Indexes]:https://www.littlekendra.com/2017/02/02/index-types-heaps-primary-keys-clustered-and-nonclustered-indexes-dear-sql-dba-episode-28/
[Identifying Existence of Intersections in Intervals]:http://sqlmag.com/sql-server/identifying-existence-intersections-intervals
[Cheat Sheet  How to Configure TempDB for Microsoft SQL Server]:https://www.brentozar.com/archive/2016/01/cheat-sheet-how-to-configure-tempdb-for-microsoft-sql-server/
[A Tourist’s Guide to the sp_Blitz Source Code, Part 1: The Big Picture]:https://www.brentozar.com/archive/2017/02/tourists-guide-sp_blitz-source-code-part-1-big-picture/
[SQL Server Default Configurations That You Should Change]:https://www.pythian.com/blog/sql-server-default-configurations-change/
[Decoding Key and Page WaitResource for Deadlocks and Blocking]:https://www.littlekendra.com/2016/10/17/decoding-key-and-page-waitresource-for-deadlocks-and-blocking/
[Security in the CLR World Inside SQL Server]:http://www.codemag.com/article/0603031
[On the Advantages of DateTime2(n) over DateTime]:http://www.sqltact.com/2012/12/on-advantages-of-datetime2n-over.html
[Build Your Own Tools]:http://michaeljswart.com/2016/09/build-your-own-tools/
[Enhanced T-SQL Error Handling With Extended Events]:http://itsalljustelectrons.blogspot.ru/2016/09/Enhanced-TSQL-Error-Handling-With-Extended-Events.html
[Compression and its Effects on Performance]:https://sqlperformance.com/2017/01/sql-performance/compression-effect-on-performance
[Does Truncate Table Reset Statistics]:https://www.littlekendra.com/2016/12/08/does-truncate-table-reset-statistics/
[SQL Server Database Decommissioning Check List]:https://www.mssqltips.com/sqlservertip/4333/sql-server-database-decommissioning-check-list/
[New SQL Server Database Request Questionnaire and Checklist]:https://www.mssqltips.com/sqlservertip/3523/new-sql-server-database-request-questionnaire-and-checklist/
[Adding Partitions to the Lower End of a Left Based Partition Function]:https://www.littlekendra.com/2017/02/21/adding-partitions-to-the-lower-end-of-a-left-based-partition-function/
[Don't Panic  Busting a File Space Myth]:http://sqlmag.com/database-administration/dont-panic-busting-file-space-myth
[#BackToBasics : Dating Responsibly]:https://blogs.sentryone.com/aaronbertrand/backtobasics-dating-responsibly/
[#BackToBasics : Common Table Expressions (CTEs)]:https://blogs.sentryone.com/aaronbertrand/backtobasics-ctes/
[How to Establish Dedicated Admin Connection (DAC) to SQL Server]:https://www.codeproject.com/tips/1136361/how-to-establish-dedicated-admin-connection-dac-to
[SQL and SQL only Best Practice]:http://strictlysql.blogspot.ru/search/label/Best%20Practices
[There Is No Difference Between Table Variables, Temporary Tables, and Common Table Expressions]:https://dzone.com/articles/there-is-no-difference-between-table-variables-tem
[Availability Group on SQL Server 2016]:http://www.madeiradata.com/availability-group-sql-server-2016/
[Using SQL Server and R Services for analyzing DBA Tasks]:http://www.sqlservercentral.com/articles/R+Language/151405/
[SQLskills SQL101: Dealing with SQL Server corruption]:https://www.sqlskills.com/blogs/paul/sqlskills-sql101-dealing-with-sql-server-corruption/
[Advanced Analytics with R & SQL: Part I - R Distributions]:http://www.sqlservercentral.com/articles/Data+Science/146555/
[T-SQL Tuesday #85  STOP! Restore Time!]:http://www.sqlhammer.com/t-sql-tuesday-85-stop-restore-time
[Filtered Indexes: Rowstore vs Nonclustered Columnstore]:https://www.littlekendra.com/2016/11/10/filtered-indexes-rowstore-vs-nonclustered-columnstore/
[ALTER SCHEMA TRANSFER for Zero Downtime Database Upgrades]:http://www.davewentzel.com/content/alter-schema-transfer-zero-downtime-database-upgrades
[Delayed Durability in SQL Server 2014]:https://sqlperformance.com/2014/04/io-subsystem/delayed-durability-in-sql-server-2014
[Daylight Savings end affects not only you, but your SQL Server too]:http://www.sqldoubleg.com/2015/10/28/daylight-savings-end-affects-not-only-you-but-your-sql-server-too/
[Searching Strings in SQL Server is Expensive]:https://www.brentozar.com/archive/2016/10/searching-strings-sql-server-expensive/
[Let’s Corrupt a SQL Server Database Together, Part 1: Clustered Indexes]:https://www.brentozar.com/archive/2017/02/lets-corrupt-sql-server-database-together/
[Let’s Corrupt a Database Together, Part 2: Nonclustered Indexes]:https://www.brentozar.com/archive/2017/02/lets-corrupt-database-together-part-2-nonclustered-indexes/
[The Guide  SQL Server Installation Checklist (settings that increase SQL Server Performance)]:https://red9.com/blog/sql-server-installation-checklist/
[SQL Browser, what is it good for? Absolutely something!]:http://www.cjsommer.com/2017-03-01-sql-browser-what-is-it-good-for-absolutely-something/
[PowerShell Getting More From Generic Error Messages]:https://nocolumnname.wordpress.com/2017/03/02/powershell-getting-more-from-generic-error-messages/
[SQL VNext sp_configure on Windows and Linux with dbatools]:https://sqldbawithabeard.com/2017/02/27/sql-vnext-sp_configure-on-windows-and-linux-with-dbatools/
[Adding a T-SQL Job Step to a SQL Agent Job with PowerShell]:https://sqldbawithabeard.com/2017/02/20/adding-a-t-sql-job-step-to-a-sql-agent-job-with-powershell/
[Setting up Database Mail to use my Gmail account]:https://mathaywardhill.com/2017/03/01/setting-up-database-mail-to-use-my-gmail-account/
[Using DBCC CLONEDATABASE and Query Store for Testing]:https://sqlperformance.com/2017/02/sql-performance/clonedatabase-query-store-testing
[Getting Started with Natural Earth — A SQL Server Shapefile Alternative (Geospatial Resource)]:http://blog.jpries.com/2017/02/17/getting-started-with-natural-earth-sql-server/
[SQL Server Temporal Tables: How-To Recipes]:https://www.simple-talk.com/sql/sql-training/sql-server-temporal-tables-recipes/
[The Migration Checklist]:http://www.sqlservercentral.com/articles/Editorial/154033/
[Upgrading to SQL Server 2014: A Dozen Things to Check]:https://thomaslarock.com/2014/06/upgrading-to-sql-server-2014-a-dozen-things-to-check/
[Number of Rows Read / Actual Rows Read warnings in Plan Explorer]:https://sqlperformance.com/2016/06/sql-indexes/actual-rows-read-warnings-plan-explorer
[Introducing the Set-based Loop]:http://www.sqlservercentral.com/articles/set-based+loop/127670/
[Representing Hierarchical Data for Mere Mortals]:https://www.simple-talk.com/sql/database-administration/representing-hierarchical-data-for-mere-mortals/
[KPIs For DBAs to Show Their CIOs]:https://thomaslarock.com/2017/03/kpis-dbas-show-cios/
[How To Forecast Database Disk Capacity If You Don’t Have A Monitoring Tool]:http://www.edwinmsarmiento.com/how-to-forecast-database-disk-capacity-if-you-dont-have-a-monitoring-tool/
[Statistical Sampling for Verifying Database Backups]:https://www.simple-talk.com/sql/database-administration/statistical-sampling-for-verifying-database-backups/
[Inside The Storage Engine  GAM, SGAM, PFS and other allocation maps]:https://www.sqlskills.com/blogs/paul/inside-the-storage-engine-gam-sgam-pfs-and-other-allocation-maps/
[Using dbatools for automated restore and CHECKDB]:http://www.centinosystems.com/blog/sql/using-dbatools-for-automated-restore-and-checkdb/
[Bad Habits Revival]:https://blogs.sentryone.com/aaronbertrand/bad-habits-revival/
[Deploying Multiple SSIS Projects via PowerShell]:https://www.simple-talk.com/sql/ssis/deploying-multiple-ssis-projects-via-powershell/
[Determining the Cost Threshold for Parallelism]:http://www.scarydba.com/2017/02/28/determining-the-cost-threshold-for-parallelism/
[Identifying a row’s physical location]:http://blog.waynesheffield.com/wayne/archive/2017/03/identifying-rows-physical-location/
[Split a file group into multiple data files]:https://blogs.msdn.microsoft.com/sql_pfe_blog/2017/03/03/split-a-file-group-into-multiple-data-files/
[Why PFS pages cannot be repaired]:https://www.sqlskills.com/blogs/paul/why-pfs-pages-cannot-be-repaired/
[ERRORLOG records max out at 2049 characters]:https://www.codykonior.com/2017/03/02/errorlog-records-max-out-at-2047-characters/
[How to Build a SQL Server Disaster Recovery Plan with Google Compute Engine]:https://www.brentozar.com/archive/2017/03/new-white-paper-build-sql-server-disaster-recovery-plan-google-compute-engine/
[SQL Server Performance Tuning in Google Compute Engine]:https://www.brentozar.com/archive/2017/03/new-white-paper-sql-server-performance-tuning-google-compute-engine/
[Configuring R on SQL Server 2016]:http://sqlmag.com/sql-server/configuring-r-sql-server-2016
[Knee-Jerk PerfMon Counters: Page Life Expectancy]:https://sqlperformance.com/2014/10/sql-performance/knee-jerk-page-life-expectancy
[Change Management Template for SQL Server DBAs and Developers]:https://www.littlekendra.com/2016/04/12/change-management-template-for-sql-server-dbas-and-deveopers/
