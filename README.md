# School_District_Analysis
Software: Python 3.7.6

## Challenge Analysis
Q1. How is the district summary affected?
In the updated district summary, Average Math and Reading, % Passing Math, % Passing Reading and % Overall passing each dropped by 1%.

- In the case of Average Math, the average score went from 78.98% to 78.93%
- In the case of Average reading, the average score went from 81.87% to 81.85%
- In the case of % Passing math, the total % went from 74.98% to 73.88%
- In the case of % Passing reading, the total % wentr from 85.81% to 84.65%
- Int he case of % Passing Overall, the total % went from 65.17% to 64.10%


Q2. How is the school summary affected?

The only school affected by the updated math and reading scores is Thomas High School, all other schools testing metrics remain the same. The effects of the nulling of values is much more significant in Thomas High School as the students in the remainder of the schools are not in the population to flatten out the metrics.

- Average Math: 83.418349 to 83.350937				
- Average Reading: 83.848930 to 83.896082
- Passing Math: 93.27217 to 66.911315
- Passing Reading: 97.308869 to 69.663609
- Overall Passing: 90.948012 to 65.076453


Q3. How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance, relative to the other schools?

Based on the Overall Passing Rate, Thomas High School went from being the second highest performing school, to the eigth.


Q4. How does replacing the ninth-grade scores affect the Math and Reading Scores by Grade, Scores by School Spending, Scores by School Size, and Scores by School Type? 

9th grade math, reading and overall meitrcs were negatively affected by the nullifyed values.

Because Thomas High School is a charter school, charter schools' Passing metrics were affected. Speicifically:

  - % Passing Math: 94	to 90		
  - % Passing Reading: 97 to 93
  - % Passing Overall: 90 to 87

Because Thomas High School is in the $630-644 spending bin, the % Passing Math, Reading and Overall are lower than before the values were nulled. Specifically

  - % Passing Math: 73 to	67
  - % Passing Reading: 84 to 77
  - % Passing Overall: 63 to 56
  
  Because Thomas High School is a 'Medium' School, the math, reading and overall metrics for that bin were adversely affected by the nullified values. Specifically:
  
  - % Passing Math: 94 to 88		
  - % Passing Reading: 97 to 91
  - % Passing Overall: 91 to 85
