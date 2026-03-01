# SQL Server QnA
<br>
A personal, growing collection of Microsoft SQL Server interview questions & answers, administration notes, T-SQL snippets, performance tuning tips, DBA best practices, and study resources.  <br>
Focused on real-world SQL Server (on-premises & Azure SQL) concepts — perfect for interviews, certifications (e.g., Microsoft Certified: Azure Database Administrator Associate, DP-300), and daily DBA/reference work.
<br>
**Repository**: [https://github.com/rishirajcode/SQL-Server-QnA](https://github.com/rishirajcode/SQL-Server-QnA)  <br>
**Main content folder**: [`SQL Server Resources`](./SQL%20Server%20Resources) (or root files if structured differently)<br>

## 🎯 Purpose
This repo is my centralized hub for everything SQL Server-related:
<br>
- Interview preparation (common & advanced Q&A)<br>
- Core DBA topics: installation, configuration, security, backup/recovery, high availability<br>
- Performance tuning: indexes, statistics, query optimization, execution plans<br>
- T-SQL best practices, query patterns, and troubleshooting<br>
- Always On Availability Groups, replication, log shipping, mirroring (legacy)<br>
- Azure SQL Database / Managed Instance differences & admin tasks<br>
- Quick-reference cheatsheets, scripts, and configuration examples<br>

Great for:<br>

- SQL Server / Azure SQL DBA / Database Engineer interviews<br>
- Microsoft certification prep (DP-300, DP-900, etc.)<br>
- On-the-job reference & quick refreshers<br>

## 📁 Repository Structure
SQL-Server-QnA/<br>
├── SQL Server Resources/             ← Core content directory<br>
│   ├── Interview-Questions/          (detailed Q&A sets – basic to advanced)<br>
│   ├── Cheatsheets/                  (T-SQL syntax, DMVs, configuration quick refs)<br>
│   ├── Scripts/                      (maintenance, backup, index rebuild, monitoring)<br>
│   ├── Notes/                        (concept deep-dives, diagrams if added)<br>
│   ├── Performance-Tuning/           (execution plans, wait stats, indexing strategies)<br>
│   ├── Backup-Recovery-HA/           (Always On, backups, point-in-time restore)<br>
│   ├── Security/                     (logins, roles, encryption, auditing)<br>
│   └── Azure-SQL/                    (Azure-specific admin & differences)<br>
└── README.md                         ← You're reading this!<br>



> **Note**: Currently centered around the `SQL Server Resources` folder (or root markdown/text files). More subfolders and files will be added over time.

## 🔥 Key Highlights
<br>
- 100+ interview-style questions with detailed, explained answers<br>
- Real-world DBA scenarios (e.g., deadlock troubleshooting, slow query fixes)<br>
- Comparison tables: SQL Server vs Azure SQL, on-prem vs cloud<br>
- Useful DMV queries (sys.dm_os_wait_stats, sys.dm_exec_query_stats, etc.)<br>
- Configuration best practices (max server memory, cost threshold for parallelism, etc.)<br>

## 🛠️ How to Use This Repository
<br>
1. **Browse directly on GitHub** — Click through folders/files<br>
2. **Clone for offline use & fast search**:
   ```bash
   git clone https://github.com/rishirajcode/SQL-Server-QnA.git
   cd SQL-Server-QnA
   # Open in VS Code / any editor and search keywords like "Always On", "deadlock", "index fragmentation"<br>

   📚 Main Topics Covered
<br>
Editions & Licensing (Express, Standard, Enterprise)<br>
Storage Engine & Architecture (pages, extents, GAM/SGAM/PFS)<br>
Indexing (clustered, non-clustered, covering, filtered, columnstore)<br>
Query Optimizer & Execution Plans (reading plans, key lookups, scans vs seeks)<br>
Statistics, Cardinality Estimation & Plan Caching<br>
Wait Statistics & Performance Troubleshooting<br>
Backup / Restore (full, differential, log, tail-log, PITR)<br>
High Availability & Disaster Recovery (Always On AG, Failover Clustering, Log Shipping)<br>
Security (contained databases, dynamic data masking, row-level security, TDE)<br>
TempDB Optimization & Configuration<br>
Resource Governor, Query Store, Extended Events<br>
Azure SQL Database / Managed Instance admin differences<br>
Common Interview Traps (implicit conversions, parameter sniffing, etc.)<br>

📄 License<br>
Personal / educational use.<br>
No formal license enforced yet — treat content as MIT-style (free to use, fork, learn from — attribution appreciated where possible).<br>
🙏 Acknowledgments<br>

Microsoft Docs & Learn (official SQL Server / Azure SQL documentation)<br>
Brent Ozar, Erik Darling, Paul Randal, Kimberly Tripp (great blogs & free scripts)<br>
Community forums (Stack Overflow, DBA Stack Exchange)<br>
Popular interview question sources & certification study guides<br>

Happy querying!<br>
Keep calm and SELECT wisely. 🚀<br>
Last updated: February 2026 <br>
Maintained by: Rishi <br>
