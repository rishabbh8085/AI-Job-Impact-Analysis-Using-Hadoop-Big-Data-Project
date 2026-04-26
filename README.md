# AI Job Impact Analysis using Hadoop

## Big Data Fundamentals Project

Implemented using Hadoop Ecosystem (HDFS, MapReduce, Hive)

---

## Project Overview

This project demonstrates a complete Big Data processing pipeline to analyze the impact of Artificial Intelligence on employment across various industries using the Hadoop ecosystem.

With the rapid adoption of AI technologies across industries, understanding how AI affects job roles, salaries, productivity, and employment status has become crucial. Traditional systems struggle to process such data efficiently.

This project solves that problem using distributed computing techniques to extract meaningful insights such as:

- Job status distribution (Replaced, Modified, Unchanged)
- Industry-wise impact of AI adoption
- Salary changes before and after AI implementation
- Productivity changes based on AI adoption levels
- Upskilling requirements across different job roles
- Automation risk analysis by industry

---

## Objectives

- To store large-scale employment datasets using HDFS
- To process data using MapReduce (Python)
- To perform analytical queries using Hive
- To understand distributed data processing
- To generate insights about AI's impact on workforce

---

## Architecture
Raw CSV Dataset (ai_job_impact.csv)
↓
HDFS (Storage Layer)
↓
MapReduce (Processing Layer)
↓
Processed Output (HDFS)
↓
Hive (Analysis Layer)
↓
Insights (AI Impact Analysis)

---

## Technologies & Tools Used

- HDFS (Storage Layer)
- MapReduce (Data Processing)
- Hive (Data Analysis)
- Python
- Linux / Cloudera
- ChatGPT (Generative AI Assistance)

---

## Dataset Information

The dataset `ai_job_impact.csv` contains employee information across multiple industries with their AI adoption experience.

**Dataset Size:** 2,000+ records | **Format:** CSV | **Attributes:** 17 columns

---

## Key Attributes:

| Attribute | Description |
|-----------|-------------|
| Employee_ID | Unique employee identifier |
| Age | Employee age (years) |
| Gender | Male / Female / Other |
| Education_Level | High School / Bachelor / Master / PhD |
| Industry | IT, Finance, Healthcare, Manufacturing, Retail, Marketing, Education |
| Job_Role | Data Analyst, Software Engineer, Nurse, Teacher, etc. |
| Years_Experience | Total work experience |
| AI_Adoption_Level | High / Medium / Low |
| Automation_Risk | High / Medium / Low |
| Upskilling_Required | Yes / No |
| Salary_Before_AI | Annual salary before AI implementation |
| Salary_After_AI | Annual salary after AI implementation |
| Job_Status | Replaced / Modified / Unchanged |
| Work_Hours_Per_Week | Weekly working hours |
| Remote_Work | Yes / No |
| Job_Satisfaction | Rating 1-9 |
| Productivity_Change_% | Percentage change in productivity |

---

## Workflow Explanation

- The dataset is stored in HDFS for distributed storage
- MapReduce processes the data to calculate job status by industry, salary changes, upskilling requirements, automation risk, and productivity metrics
- Processed data is stored back in HDFS
- Hive is used to analyze and query the results
- Final insights such as AI impact by industry and top affected job roles are generated

---

## Output

- Job status distribution by industry
- Average salary before and after AI by industry
- Top job roles requiring upskilling
- Automation risk analysis by sector
- Productivity change by AI adoption level
- Most affected industries by AI
- Age group and education level analysis

---

## Use of Generative AI

Generative AI played an important role in this project:

- **Code Generation** - Mapper & Reducer code, Hive queries, Bash scripts
- **Debugging Support** - Syntax error fixing, Hadoop streaming troubleshooting
- **Query Assistance** - Complex Hive query formulation for multi-dimensional analysis
- **Concept Understanding** - Big Data tools and MapReduce workflow

---

## Validation

All generated code and outputs were:

- Manually tested on Cloudera VM - ✅ Passed
- Verified for correctness of results - ✅ Passed
- Successfully executed in Hadoop environment - ✅ Passed
- Cross-verified with sample data - ✅ Passed
- Hive queries validated against raw data - ✅ Passed

---

## Key Features

- Scalable Big Data processing for large-scale employment datasets
- Efficient handling of large datasets using distributed computing
- Multi-dimensional analysis across industries, job roles, and demographics
- Integration of AI for enhanced productivity in development
- Comprehensive metrics tracking salary changes, productivity shifts, and job status transitions

---

## Conclusion

This project successfully demonstrates how the Hadoop ecosystem can be used to process and analyze large-scale employment datasets efficiently. By combining **HDFS, MapReduce, and Hive**, the system transforms raw employment data into meaningful insights, enabling better decision-making for workforce planning, policy development, and career guidance in an AI-driven economy.

---

## Author

**Ajay Chauhan**
BCA (Data Science & AI)
Babu Banarasi Das University

---

## Final Note

This project reflects a real-world Big Data solution where distributed computing is essential for handling large-scale data efficiently. The insights generated can help organizations understand AI's impact on their workforce and plan appropriate upskilling strategies for their employees.
