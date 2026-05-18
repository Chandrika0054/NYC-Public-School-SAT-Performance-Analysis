# NYC-Public-School-SAT-Performance-Analysis

Exploratory data analysis of SAT scores across 375+ New York City public  schools, identifying top performers and borough-level disparities.

## Objectives
- Identify schools with the strongest math performance (score ≥ 640)
- Rank the top 10 schools by combined SAT score across all three sections
- Determine which NYC borough has the highest variation in SAT performance

## Dataset
`NYC_schools.csv` — contains school-level SAT scores (math, reading, writing) 
and borough metadata for NYC public schools.

## Key Findings
- Stuyvesant High School ranked #1 with a total SAT score of 2144
- Manhattan showed the highest standard deviation in SAT scores, 
  indicating the widest performance gap between schools within a borough
- Top-performing schools are concentrated in specialised science 
  and humanities programmes

## Tools & Techniques
- Python, Pandas
- Boolean indexing and multi-column sorting
- GroupBy aggregation with count, mean, and standard deviation
- Composite metric engineering

## Structure
- NYC_SAT_notebook.ipynb -> Main analysis notebook
- NYC_schools.csv -> Dataset
- README.md
