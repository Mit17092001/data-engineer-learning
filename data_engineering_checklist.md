# Data Engineering Learning Checklist

> **Track your progress** as you work through the Data Engineering learning path. Mark items as complete by changing `[ ]` to `[x]`.

**Start Date:** _____________  
**Target Completion Date:** _____________  
**Study Hours per Week:** _____________

---

## Phase 1: Foundations (1-2 months) ⏱️ 115-170 hours

### Week 1-2: SQL Mastery (40-60 hours)

#### Basic SQL
- [x] Learn SELECT, WHERE, ORDER BY
- [x] Practice filtering with AND, OR, NOT
- [x] Master DISTINCT and LIMIT
- [x] Understand NULL handling (IS NULL, COALESCE)

#### Intermediate SQL
- [x] Master INNER JOIN
- [x] Learn LEFT/RIGHT/FULL OUTER JOIN
- [x] Practice CROSS JOIN
- [x] Understand self-joins
- [x] Learn GROUP BY and HAVING
- [x] Master aggregate functions (COUNT, SUM, AVG, MIN, MAX)

#### Advanced SQL
- [ ] Learn subqueries (scalar, row, table)
- [ ] Master Common Table Expressions (CTEs)
- [ ] Practice window functions (ROW_NUMBER, RANK, DENSE_RANK)
- [ ] Learn LAG, LEAD, FIRST_VALUE, LAST_VALUE
- [ ] Understand PARTITION BY and ORDER BY in window functions
- [ ] Practice running totals and moving averages

#### Query Optimization
- [ ] Learn to read execution plans
- [ ] Understand indexes (B-tree, Hash)
- [ ] Practice query optimization techniques
- [ ] Learn about query hints and optimization

#### Practice
- [ ] Complete 20+ SQL problems on LeetCode
- [ ] Complete Mode Analytics SQL Tutorial
- [ ] Solve 10+ medium difficulty SQL problems
- [ ] Solve 5+ hard difficulty SQL problems

---

### Week 3-4: Python Fundamentals (40-60 hours)

#### Python Basics
- [ ] Learn data types (int, float, string, bool)
- [ ] Master lists, tuples, dictionaries, sets
- [ ] Understand control flow (if/elif/else)
- [ ] Practice loops (for, while)
- [ ] Learn functions and parameters
- [ ] Understand scope and namespaces

#### Intermediate Python
- [ ] Master list comprehensions
- [ ] Learn dictionary comprehensions
- [ ] Understand lambda functions
- [ ] Practice with *args and **kwargs
- [ ] Learn decorators
- [ ] Understand generators and iterators

#### Object-Oriented Programming
- [ ] Learn classes and objects
- [ ] Understand inheritance
- [ ] Practice encapsulation
- [ ] Learn polymorphism
- [ ] Understand magic methods (__init__, __str__, etc.)

#### Data Manipulation with pandas
- [ ] Learn DataFrame and Series basics
- [ ] Master reading/writing files (CSV, JSON, Excel)
- [ ] Practice data selection and filtering
- [ ] Learn groupby operations
- [ ] Master merge, join, concatenate
- [ ] Practice pivot tables and reshaping
- [ ] Learn handling missing data
- [ ] Understand data type conversions

#### NumPy
- [ ] Learn array creation and manipulation
- [ ] Practice array indexing and slicing
- [ ] Understand broadcasting
- [ ] Learn basic mathematical operations
- [ ] Practice array reshaping

#### File I/O and APIs
- [ ] Learn file reading/writing
- [ ] Practice with JSON files
- [ ] Understand CSV processing
- [ ] Learn requests library for APIs
- [ ] Practice web scraping with BeautifulSoup

#### Practice
- [ ] Complete 10+ Python coding problems
- [ ] Build a data cleaning script with pandas
- [ ] Create an API data fetcher
- [ ] Build a CSV to JSON converter

---

### Week 5-6: Linux & Command Line (20-30 hours)

#### Basic Commands
- [ ] Learn navigation (cd, ls, pwd)
- [ ] Master file operations (cp, mv, rm, mkdir, touch)
- [ ] Understand file permissions (chmod, chown)
- [ ] Learn text viewing (cat, less, head, tail)
- [ ] Practice searching (grep, find)
- [ ] Learn text processing (awk, sed, cut, sort, uniq)

#### Bash Scripting
- [ ] Learn variables and data types
- [ ] Understand control structures (if, for, while)
- [ ] Practice functions in bash
- [ ] Learn command substitution
- [ ] Understand pipes and redirection
- [ ] Practice error handling

#### System Administration
- [ ] Learn process management (ps, top, kill)
- [ ] Understand cron jobs for scheduling
- [ ] Practice SSH and remote connections
- [ ] Learn environment variables
- [ ] Understand PATH and shell configuration

#### Practice
- [ ] Write 5+ bash scripts for automation
- [ ] Set up a cron job
- [ ] Create a log file parser script
- [ ] Build a backup automation script

---

### Week 7-8: Git & Version Control (15-20 hours)

#### Git Basics
- [ ] Learn git init, clone
- [ ] Master git add, commit
- [ ] Understand git status, log
- [ ] Practice git push, pull
- [ ] Learn git remote operations

#### Branching and Merging
- [ ] Learn git branch, checkout
- [ ] Practice creating and switching branches
- [ ] Understand merge strategies
- [ ] Learn to resolve merge conflicts
- [ ] Practice git rebase

#### Collaboration
- [ ] Learn pull requests
- [ ] Understand code review process
- [ ] Practice forking repositories
- [ ] Learn git stash
- [ ] Understand .gitignore

#### Advanced Git
- [ ] Learn git cherry-pick
- [ ] Understand git reset vs revert
- [ ] Practice interactive rebase
- [ ] Learn git tags

#### Practice
- [ ] Create a GitHub account
- [ ] Build a personal project repository
- [ ] Contribute to an open-source project
- [ ] Practice collaborative workflow with branches

---

## Phase 2: Core Data Engineering (2-3 months) ⏱️ 200-260 hours

### Month 1: Databases (60-80 hours)

#### Relational Database Design
- [ ] Learn database normalization (1NF, 2NF, 3NF, BCNF)
- [ ] Understand entity-relationship diagrams
- [ ] Practice primary and foreign keys
- [ ] Learn constraints (UNIQUE, CHECK, NOT NULL)
- [ ] Understand referential integrity

#### PostgreSQL
- [ ] Install and configure PostgreSQL
- [ ] Learn psql command-line interface
- [ ] Practice creating databases and tables
- [ ] Understand data types in PostgreSQL
- [ ] Learn stored procedures and functions
- [ ] Practice triggers
- [ ] Understand views and materialized views
- [ ] Learn transactions and ACID properties

#### Database Performance
- [ ] Learn index types and when to use them
- [ ] Practice query optimization
- [ ] Understand EXPLAIN and ANALYZE
- [ ] Learn about vacuum and analyze
- [ ] Practice partitioning strategies

#### NoSQL Databases
- [ ] Learn MongoDB basics
- [ ] Practice document-based queries
- [ ] Understand Redis data structures
- [ ] Learn key-value operations
- [ ] Practice caching strategies

#### Project
- [ ] Design a normalized database schema for e-commerce
- [ ] Implement the schema in PostgreSQL
- [ ] Create indexes for optimization
- [ ] Write complex queries for analytics
- [ ] Add stored procedures for common operations

---

### Month 2: Big Data Technologies (80-100 hours)

#### Apache Spark Fundamentals
- [ ] Understand Spark architecture (Driver, Executors, Cluster Manager)
- [ ] Learn RDD concepts
- [ ] Understand transformations vs actions
- [ ] Practice lazy evaluation
- [ ] Learn about DAG (Directed Acyclic Graph)

#### PySpark Programming
- [ ] Install and configure PySpark
- [ ] Learn SparkSession and SparkContext
- [ ] Practice creating DataFrames
- [ ] Master DataFrame operations (select, filter, groupBy)
- [ ] Learn joins in Spark
- [ ] Practice aggregations
- [ ] Understand UDFs (User Defined Functions)

#### Spark SQL
- [ ] Learn to query DataFrames with SQL
- [ ] Practice creating temporary views
- [ ] Understand Catalyst optimizer
- [ ] Learn about Tungsten execution engine

#### Data Processing
- [ ] Learn reading/writing various formats (CSV, JSON, Parquet)
- [ ] Practice partitioning data
- [ ] Understand bucketing
- [ ] Learn data caching and persistence
- [ ] Practice broadcast variables
- [ ] Understand accumulators

#### Spark Optimization
- [ ] Learn about shuffle operations
- [ ] Practice minimizing shuffles
- [ ] Understand partition sizing
- [ ] Learn broadcast joins
- [ ] Practice repartition vs coalesce
- [ ] Understand Spark UI for debugging

#### Practice
- [ ] Process a large CSV file (1GB+) with PySpark
- [ ] Build a data aggregation pipeline
- [ ] Implement a join operation on large datasets
- [ ] Optimize a slow Spark job
- [ ] Create a data quality check script

---

### Month 3: Data Warehousing (60-80 hours)

#### Data Warehouse Concepts
- [ ] Understand OLTP vs OLAP
- [ ] Learn data warehouse architecture
- [ ] Understand ETL vs ELT
- [ ] Learn about data marts
- [ ] Understand slowly changing dimensions (SCD)

#### Dimensional Modeling
- [ ] Learn fact tables
- [ ] Understand dimension tables
- [ ] Practice star schema design
- [ ] Learn snowflake schema
- [ ] Understand galaxy schema
- [ ] Practice designing fact and dimension tables

#### Cloud Data Warehouses
- [ ] Choose a platform (Snowflake, BigQuery, or Redshift)
- [ ] Set up an account and configure
- [ ] Learn data loading techniques
- [ ] Practice creating tables and schemas
- [ ] Understand clustering and partitioning
- [ ] Learn about materialized views
- [ ] Practice query optimization

#### Data Modeling Techniques
- [ ] Learn Data Vault modeling
- [ ] Understand Anchor modeling
- [ ] Practice denormalization strategies
- [ ] Learn about bridge tables
- [ ] Understand junk dimensions

#### Project
- [ ] Design a star schema for a business domain
- [ ] Implement the schema in a cloud data warehouse
- [ ] Load sample data
- [ ] Create aggregation tables
- [ ] Build analytical queries
- [ ] Optimize query performance

---

## Phase 3: Advanced Topics (2-3 months) ⏱️ 200-260 hours

### Month 1: Workflow Orchestration (60-80 hours)

#### Apache Airflow Fundamentals
- [ ] Understand Airflow architecture
- [ ] Learn about DAGs (Directed Acyclic Graphs)
- [ ] Install and configure Airflow
- [ ] Understand scheduler, executor, and webserver
- [ ] Learn about metadata database

#### Writing DAGs
- [ ] Create your first DAG
- [ ] Learn about operators (PythonOperator, BashOperator)
- [ ] Practice task dependencies
- [ ] Understand sensors
- [ ] Learn about hooks
- [ ] Practice XCom for task communication
- [ ] Understand task groups

#### Advanced Airflow
- [ ] Learn about custom operators
- [ ] Practice dynamic DAG generation
- [ ] Understand branching and conditional logic
- [ ] Learn about SubDAGs
- [ ] Practice error handling and retries
- [ ] Understand SLAs and alerts

#### Monitoring and Debugging
- [ ] Learn to use Airflow UI
- [ ] Practice debugging failed tasks
- [ ] Understand logs and logging
- [ ] Learn about task instance states
- [ ] Practice backfilling

#### Project
- [ ] Build an ETL pipeline with Airflow
- [ ] Create a DAG with multiple dependencies
- [ ] Implement error handling and notifications
- [ ] Schedule daily data processing
- [ ] Add data quality checks

---

### Month 2: Streaming Data (80-100 hours)

#### Apache Kafka Fundamentals
- [ ] Understand Kafka architecture
- [ ] Learn about topics, partitions, and offsets
- [ ] Install and configure Kafka
- [ ] Understand brokers and clusters
- [ ] Learn about ZooKeeper (or KRaft)

#### Producers and Consumers
- [ ] Create a Kafka producer in Python
- [ ] Learn about message serialization
- [ ] Practice consumer groups
- [ ] Understand offset management
- [ ] Learn about consumer rebalancing
- [ ] Practice error handling

#### Kafka Advanced Concepts
- [ ] Learn about replication and fault tolerance
- [ ] Understand partitioning strategies
- [ ] Practice configuring retention policies
- [ ] Learn about compaction
- [ ] Understand exactly-once semantics

#### Stream Processing
- [ ] Learn Spark Streaming basics
- [ ] Practice DStream operations
- [ ] Understand Structured Streaming
- [ ] Learn about windowing operations
- [ ] Practice stateful transformations
- [ ] Understand watermarking

#### Real-time Analytics
- [ ] Learn about stream-table joins
- [ ] Practice aggregations on streams
- [ ] Understand late data handling
- [ ] Learn about checkpointing

#### Project
- [ ] Build a real-time data pipeline with Kafka
- [ ] Create producers for event data
- [ ] Implement consumers for processing
- [ ] Build a streaming aggregation with Spark
- [ ] Create a real-time dashboard

---

### Month 3: Cloud Platforms (60-80 hours)

#### Cloud Fundamentals (Choose AWS, GCP, or Azure)
- [ ] Create a cloud account
- [ ] Learn about IAM and permissions
- [ ] Understand regions and availability zones
- [ ] Practice cost management
- [ ] Learn about billing and budgets

#### Cloud Storage
- [ ] Learn object storage (S3/GCS/Blob Storage)
- [ ] Practice uploading and downloading files
- [ ] Understand storage classes
- [ ] Learn about lifecycle policies
- [ ] Practice access control

#### Cloud Data Services
- [ ] Learn about cloud data warehouses
- [ ] Practice managed databases
- [ ] Understand serverless computing
- [ ] Learn about data lakes
- [ ] Practice ETL services (Glue/Dataflow/Data Factory)

#### Infrastructure as Code
- [ ] Learn Terraform basics
- [ ] Practice creating resources with IaC
- [ ] Understand state management
- [ ] Learn about modules
- [ ] Practice version control for infrastructure

#### Networking and Security
- [ ] Learn about VPCs and subnets
- [ ] Understand security groups
- [ ] Practice encryption at rest and in transit
- [ ] Learn about secrets management
- [ ] Understand compliance and governance

#### Project
- [ ] Deploy a data pipeline on cloud
- [ ] Set up cloud storage and databases
- [ ] Implement IAM policies
- [ ] Create infrastructure with Terraform
- [ ] Set up monitoring and alerts

---

## Phase 4: Specialization & Production (3-6 months) ⏱️ 200-300 hours

### Advanced Topics (100-150 hours)

#### Data Quality Frameworks
- [ ] Learn Great Expectations
- [ ] Practice creating expectations
- [ ] Understand data validation
- [ ] Learn about data profiling
- [ ] Practice data quality monitoring

#### dbt (data build tool)
- [ ] Install and configure dbt
- [ ] Learn about models and transformations
- [ ] Practice writing SQL transformations
- [ ] Understand testing in dbt
- [ ] Learn about documentation
- [ ] Practice incremental models
- [ ] Understand macros and packages

#### Docker
- [ ] Learn Docker basics
- [ ] Practice creating Dockerfiles
- [ ] Understand images and containers
- [ ] Learn about Docker Compose
- [ ] Practice multi-container applications
- [ ] Understand volumes and networking

#### Kubernetes
- [ ] Learn Kubernetes architecture
- [ ] Understand pods, deployments, services
- [ ] Practice creating manifests
- [ ] Learn about ConfigMaps and Secrets
- [ ] Understand scaling and load balancing

#### CI/CD for Data Pipelines
- [ ] Learn about CI/CD concepts
- [ ] Practice with GitHub Actions or GitLab CI
- [ ] Understand automated testing
- [ ] Learn about deployment strategies
- [ ] Practice blue-green deployments

#### Data Governance and Security
- [ ] Learn about data lineage
- [ ] Understand data cataloging
- [ ] Practice access control
- [ ] Learn about data masking
- [ ] Understand GDPR and compliance

---

### Real-World Projects (100-150 hours)

#### Project 1: E-commerce Analytics Pipeline
- [ ] Design the architecture
- [ ] Set up data sources (mock or real)
- [ ] Build ingestion layer
- [ ] Create transformation logic
- [ ] Implement data warehouse
- [ ] Build analytics dashboards
- [ ] Add data quality checks
- [ ] Document the pipeline

#### Project 2: Real-time Dashboard
- [ ] Design streaming architecture
- [ ] Set up Kafka for event streaming
- [ ] Build stream processing with Spark
- [ ] Create real-time aggregations
- [ ] Store results in database
- [ ] Build visualization layer
- [ ] Implement monitoring

#### Project 3: Data Lake Implementation
- [ ] Design data lake architecture
- [ ] Set up cloud storage
- [ ] Implement data ingestion
- [ ] Create data catalog
- [ ] Build data processing layers (bronze/silver/gold)
- [ ] Implement access control
- [ ] Add data governance

#### Project 4: ML Feature Store
- [ ] Design feature store architecture
- [ ] Build feature engineering pipelines
- [ ] Implement feature storage
- [ ] Create feature serving layer
- [ ] Add versioning and lineage
- [ ] Build feature monitoring
- [ ] Document features

---

## Additional Skills & Certifications

### Certifications (Optional)
- [ ] AWS Certified Data Analytics - Specialty
- [ ] Google Professional Data Engineer
- [ ] Azure Data Engineer Associate
- [ ] Databricks Certified Data Engineer
- [ ] Snowflake SnowPro Core Certification

### Soft Skills
- [ ] Practice technical communication
- [ ] Learn to write technical documentation
- [ ] Practice presenting technical concepts
- [ ] Develop problem-solving skills
- [ ] Learn project management basics
- [ ] Practice collaboration and teamwork

### Portfolio Development
- [ ] Create a GitHub portfolio
- [ ] Document all projects with README files
- [ ] Add architecture diagrams
- [ ] Write blog posts about learnings
- [ ] Create a personal website/portfolio
- [ ] Share projects on LinkedIn

---

## Job Preparation

### Resume & Portfolio
- [ ] Update resume with projects
- [ ] Create a LinkedIn profile
- [ ] Build a portfolio website
- [ ] Add GitHub projects
- [ ] Write technical blog posts

### Interview Preparation
- [ ] Practice SQL interview questions (50+)
- [ ] Solve Python coding problems (50+)
- [ ] Study system design patterns
- [ ] Practice behavioral questions
- [ ] Mock interviews with peers
- [ ] Review data engineering concepts

### Networking
- [ ] Join data engineering communities
- [ ] Attend meetups and conferences
- [ ] Connect with professionals on LinkedIn
- [ ] Participate in online forums
- [ ] Contribute to open-source projects

### Job Search
- [ ] Identify target companies
- [ ] Apply to entry-level positions
- [ ] Prepare for technical interviews
- [ ] Practice take-home assignments
- [ ] Follow up on applications

---

## Progress Tracking

### Monthly Review
- [ ] Month 1 completed
- [ ] Month 2 completed
- [ ] Month 3 completed
- [ ] Month 4 completed
- [ ] Month 5 completed
- [ ] Month 6 completed
- [ ] Month 7 completed
- [ ] Month 8 completed
- [ ] Month 9 completed
- [ ] Month 10 completed
- [ ] Month 11 completed
- [ ] Month 12 completed

### Milestones
- [ ] Completed Phase 1: Foundations
- [ ] Completed Phase 2: Core Data Engineering
- [ ] Completed Phase 3: Advanced Topics
- [ ] Completed Phase 4: Specialization
- [ ] Built 4+ portfolio projects
- [ ] Obtained 1+ certification (optional)
- [ ] Applied to 20+ jobs
- [ ] Received first interview
- [ ] Received job offer
- [ ] Started first Data Engineering role! 🎉

---

## Notes & Reflections

### What I learned this week:
_Use this space to reflect on your weekly learnings_

---

### Challenges faced:
_Document any difficulties and how you overcame them_

---

### Resources that helped:
_Keep track of useful courses, articles, and tutorials_

---

### Next week's goals:
_Plan ahead for the upcoming week_

---

**Remember:** 
- ✅ Consistency is more important than speed
- ✅ Build projects to apply what you learn
- ✅ Don't just watch tutorials - code along!
- ✅ Join communities and ask questions
- ✅ Review and revise regularly
- ✅ Celebrate small wins along the way! 🎉

**Good luck on your Data Engineering journey! 🚀**
