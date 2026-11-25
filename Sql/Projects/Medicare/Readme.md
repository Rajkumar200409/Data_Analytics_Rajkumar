MediCare Healthcare Database Analysis
```{=html}
<p align="center">
```
`<img src="healthplus_care_Schema_Img.png" alt="MediCare Healthcare Database Entity Relationship Diagram" width="100%">`{=html}
```{=html}
</p>
```
```{=html}
<p align="center">
```
`<strong>`{=html}Healthcare Analytics | MySQL | SQL | Relational
Database Analysis`</strong>`{=html}
```{=html}
</p>
```
```{=html}
<p align="center">
```
A SQL-based analysis of healthcare resources, doctor availability,
medical specializations, appointment activity, and consultation-fee
patterns.
```{=html}
</p>
```
---
1. Project Overview
The MediCare Healthcare Database Analysis project uses SQL to
explore healthcare operations and support data-driven resource planning.
The analysis examines how doctors, hospitals, departments, patients,
appointments, and healthcare infrastructure are represented in the
database. SQL queries are used to summarize resource distribution,
compare operational activity, and identify areas that may require closer
attention.
Business Problem
How can MediCare optimize doctor and hospital capacity while improving
access to the most in-demand medical specializations?
MediCare needs to understand how healthcare resources are distributed
across hospitals and specializations, identify areas with higher demand,
and evaluate whether staffing and infrastructure can support healthcare
service requirements.
Business Objectives
Identify medical specializations with higher doctor availability and
demand.
Evaluate doctor distribution and staffing levels across hospitals.
Analyze hospital infrastructure and bed capacity.
Understand appointment volumes and doctor workload patterns.
Compare consultation fees across doctors and specializations.
Identify experienced doctors to support workforce planning.
Generate insights that can inform healthcare resource allocation.
---
2. Database Structure
The project uses a relational healthcare database. The supplied ER
diagram illustrates the broader schema and its relationships.
Entity Relationship Diagram
![MediCare Healthcare Database ER](healthplus_care_Schema_Img.png)
The diagram shows healthcare entities and relationships, including
clinics, members, staff, consultations, prescriptions, billing, and
other healthcare-related tables.
Core Business Entities in the Analysis
---
Entity                              Purpose
---
Hospitals                           Stores hospital information and
hospital-level details.
Doctors                             Contains doctor details,
specializations, experience, and
consultation fees.
Departments                         Stores department information
associated with hospitals.
Patients                            Maintains patient information used
in healthcare operations.
Appointments                        Records appointment activity for
utilization analysis.
> The ER diagram represents the broader database structure. The entities
> listed above describe the core business areas stated in the project
> analysis.
---
3. Tools & Technologies
---
Technology                          Purpose
---
MySQL                               Relational database management and
SQL execution
SQL                                 Data retrieval, transformation,
aggregation, and analysis
MySQL Workbench                     Database schema exploration and SQL
query development
SQL Concepts Applied
Data retrieval with `SELECT` and `DISTINCT`
Filtering with `WHERE`
Grouping and aggregate filtering with `GROUP BY` and `HAVING`
Sorting with `ORDER BY`
Aggregate functions: `COUNT()`, `SUM()`, `AVG()`, `MIN()`, and
`MAX()`
Joins: `INNER JOIN` and `LEFT JOIN`
Subqueries
Window functions: `ROW_NUMBER()`, `RANK()`, `LAG()`, and `LEAD()`
---
4. SQL Analysis
Hospital Analysis
Count the hospitals in the database.
Identify unique hospital names.
Review hospital-level information.
Compare doctor availability across hospitals.
Examine hospital capacity and available resources.
Doctor Analysis
Count doctors and analyze their distribution by specialization.
Identify doctors with more than 10 years of experience.
Identify specializations with more than 20 doctors.
Rank specializations by doctor count.
Compare doctor availability across hospitals.
Department Analysis
Count and analyze departments.
Examine department distribution across hospitals.
Compare hospitals based on department availability.
Appointment Analysis
Analyze appointment records and appointment volumes.
Compare appointment activity across doctors.
Identify doctors and hospitals with higher appointment activity.
Use appointment volume as an indicator of service utilization.
Consultation-Fee Analysis
Calculate average consultation fees by specialization.
Rank doctors based on consultation fees.
Compare fee patterns across doctors and specializations.
Apply window functions for ranking and comparisons.
Healthcare Capacity Analysis
Analyze hospital bed capacity.
Compare infrastructure availability across hospitals.
Consider bed capacity alongside doctor availability to support
resource planning.
---
5. Key Metrics
---
Metric                              Business Purpose
---
Hospital Count                      Measures the number of hospitals
represented in the database.
Doctor Count                        Evaluates the available healthcare
workforce.
Department Availability             Shows how departments are
distributed across hospitals.
Bed Capacity                        Indicates the scale of hospital
infrastructure.
Doctor Experience                   Identifies experienced doctors,
including those with more than 10
years of experience.
Specialization Distribution         Shows how doctors are distributed
across medical specializations.
Appointment Volume                  Helps compare service utilization
across doctors and hospitals.
Average Consultation Fee            Supports fee comparisons across
specializations.
Doctor Fee Ranking                  Compares consultation fees at the
doctor level.
---
6. Key Insights
The analysis is designed to provide evidence for the following
operational questions:
Doctor availability across specializations: Identify
specializations with higher doctor counts and areas that may require
further workforce review.
Specialization representation: Find specializations with more
than 20 doctors and rank specializations by doctor count.
Hospital staffing differences: Compare doctor availability
across hospitals to identify potential resource imbalances.
Experienced workforce: Identify doctors with more than 10 years
of experience to support workforce planning.
Consultation-fee variation: Compare average fees by
specialization and rank doctors by consultation fee.
Appointment activity: Compare appointment volumes to understand
differences in service utilization and workload.
The project description does not provide the underlying query outputs
or numerical findings. Add validated result values here when available;
do not interpret the analysis questions as confirmed findings.
---
7. Recommendations
Based on the analysis areas, MediCare can:
Monitor specializations with higher doctor and appointment demand.
Review staffing levels across hospitals to investigate possible
resource imbalances.
Use bed capacity and doctor availability together when planning
hospital resources.
Monitor appointment volumes as one input to workload and staffing
decisions.
Compare consultation fees across specializations when reviewing
pricing patterns.
Use experience-based analysis to inform mentoring, specialized care,
and workforce planning.
Continue monitoring doctor, appointment, and capacity metrics to
support data-informed decisions.
These recommendations should be assessed alongside operational context
and validated query results before being used for decisions.
---
8. Data Profiling & Preparation
Before analysis, the healthcare tables were reviewed to understand their
structure, fields, and relationships.
The preparation activities included:
Reviewing table structures and available columns.
Identifying business attributes relevant to healthcare operations.
Examining hospital, doctor, department, and appointment records.
Using distinct-value analysis for categorical fields.
Reviewing relationships between related tables.
Applying filters and aggregations to create business summaries.
The SQL queries then transform the relational records into
analysis-ready results.
---
9. Conclusion
The MediCare Healthcare Database Analysis demonstrates how SQL can be
used to examine healthcare resources, doctor availability,
specialization distribution, appointment activity, and consultation-fee
patterns.
The project provides a structured analytical approach to healthcare
workforce and capacity planning. Its outputs can help identify areas for
further review, support resource allocation discussions, and encourage
data-informed operational decisions.
---
10. Skills Demonstrated
SQL database analysis
Relational database concepts
Healthcare data analysis
Data profiling and preparation
Data aggregation and filtering
Multi-table joins
Subqueries
Window functions and ranking analysis
Business problem-solving
Data-driven recommendations
---
Author
Rajkumar  
Aspiring Data Analyst | SQL | MySQL | Data Analytics
GitHub Profile
---
```{=html}
<p align="center">
```
`<em>`{=html}Turning healthcare data into meaningful insights for
resource planning and operational decision-making.`</em>`{=html}
```{=html}
</p>
```
