# recursive-sql-courier
Recursive SQL queries for PostgreSQL & Oracle
- This repository contains a collection of recursive SQL queries developed for a fictitious courier company. 
- The purpose of these queries is to analyze execution performance under large‑scale data conditions in both PostgreSQL and Oracle.
- These recursive queries are designed to simulate real‑world logistics scenarios such as route traversal, package movement, and hierarchical relationships between operational nodes.
- The structure of the database used for these tests can be viewed in the following image.
<br></br>
<img
  src="https://github.com/Daniel-Cristian/recursive-sql/assets/90038552/f707e3a4-7110-4738-acbe-c1644c398efe"
  alt="E-R Diagram of Database"
  title="E-R Diagram of Database"
  width="600" height="600">
  <br></br>
- To support performance benchmarking, two separate databases were created:
a small‑scale database, used to validate query logic and correctness
a large‑scale database, designed to stress‑test performance and simulate production‑level workloads
  <br></br>
  <img
  src="https://github.com/Daniel-Cristian/recursive-sql-courier/blob/4d8db6ebdb756597e4366c52a2b6a2b12eb1f4d7/nofrecords.png"
  alt="Number of database records"
  title="Number of database records"
  width="600" height="600">
  
