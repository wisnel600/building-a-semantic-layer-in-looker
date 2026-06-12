# building-a-semantic-layer-in-looker
Analytics engineering project built with Google Cloud Looker and LookML. Includes data modeling, business KPIs, derived tables, Explore governance, query optimization, and caching strategies on BigQuery.

# Building a Semantic Layer in Looker with LookML
## Overview
This project demonstrates the development of a semantic layer in Google Cloud Looker using LookML. The work was completed through a series of hands-on labs focused on data modeling, business metric development, derived tables, Explore governance, and query performance optimization.

The project is built on an e-commerce dataset hosted in BigQuery and showcases how LookML can be used to create a governed and reusable analytics layer for business users.

---

## Business Scenario
Business users often need access to reliable metrics and data without writing SQL queries.
To support self-service analytics, a semantic layer was developed in Looker using LookML. This layer provides consistent definitions for dimensions, measures, joins, derived tables, and filtering logic while improving query performance through caching mechanisms.

---
## Project Objectives
* Develop LookML views and explores
* Create reusable dimensions and measures
* Build business KPIs
* Create SQL and Native Derived Tables
* Implement Explore-level governance
* Configure caching policies using datagroups
* Improve query performance and scalability

---

## Project Structure

```text
building-a-semantic-layer-in-looker/
│
├── 01-data-modeling/
├── 02-kpis-and-business-metrics/
├── 03-derived-tables/
├── 04-data-governance/
├── 05-performance-optimization/
```

---

## Project Components

### 1. Data Modeling
Developed foundational LookML objects including:

* Views
* Explores
* Dimensions
* Measures
* Joins

A custom view (`users_limited`) was created and joined to an existing Explore to extend the semantic model.

**Key Skills**

* LookML Development
* Data Modeling
* Explore Design

---

### 2. KPI and Business Metrics Development

Created analytical fields and business metrics including:

* Shipping Days
* Total Revenue
* Revenue from Completed Orders
* Distinct Order Count
* Customer Age Tiers
* Email Source Identification

**Key Skills**

* KPI Development
* Business Logic Implementation
* Metric Design

---

### 3. Derived Tables

Implemented multiple types of derived tables:

* SQL Derived Tables
* Native Derived Tables (NDTs)
* Persistent Derived Tables (PDTs)

Derived tables were used to summarize order-level information and improve analytical flexibility.

**Key Skills**

* Data Aggregation
* Query Optimization
* Analytics Engineering

---

### 4. Data Governance

Implemented Explore-level controls using:

* always_filter
* sql_always_where
* sql_always_having
* conditionally_filter

These configurations help enforce business rules while maintaining flexibility for end users.

**Key Skills**

* Data Governance
* Access Control
* Explore Optimization

---

### 5. Performance Optimization

Configured datagroups and caching policies to improve performance and reduce unnecessary database queries.

Implemented:

* Datagroups
* SQL Triggers
* Cache Refresh Policies
* Explore Persistence

**Key Skills**

* Query Optimization
* Performance Engineering
* Caching Strategies

---

## Technologies Used

* Google Cloud Platform (GCP)
* Looker
* LookML
* BigQuery
* SQL
* GitHub

---

## Skills Demonstrated

### Analytics Engineering

* Semantic Layer Development
* Data Modeling
* Derived Table Design
* KPI Development

### Business Intelligence

* Explore Design
* Self-Service Analytics
* Metric Governance
* Dashboard Optimization

### Data Engineering Concepts

* SQL Development
* Data Aggregation
* Query Performance Optimization
* Cache Management

---

## Key Learning Outcomes

Through this project, I gained practical experience in:

* Building semantic data models with LookML
* Designing reusable business metrics
* Creating and managing derived tables
* Applying governance rules to analytical environments
* Optimizing analytical workloads through caching and persistence

---

## Author

Wisnel François

Skills: SQL • Python • BigQuery • Looker • Data Visualization • Statistical Analysis
