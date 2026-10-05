# AWS RDS Relational Database Lab

A cloud infrastructure and database deployment demonstration featuring an **Amazon RDS PostgreSQL** database provisioned within a private AWS VPC environment.

## Architecture & Security
1. **Isolated Infrastructure**: Deployed in a dedicated private DB Subnet Group across multiple Availability Zones.
2. **Network Isolation**: Public accessibility disabled (`--no-publicly-accessible`).
3. **Least Privilege Ingress**: Inbound access restricted strictly to port 5432 from internal VPC CIDR blocks via AWS Security Groups.

---

## Live Database Verification
```text
Successfully connected to AWS RDS PostgreSQL!
Database Version: PostgreSQL 16.1 on x86_64-pc-linux-gnu
```

---

## Tech Stack
* **Cloud Provider**: AWS (RDS PostgreSQL, VPC, Security Groups, Subnet Groups)
* **Language/SDK**: Python 3.12, psycopg2, boto3
* **Infrastructure Management**: AWS CLI & Git / GitHub
