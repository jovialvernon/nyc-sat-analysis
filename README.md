#  NYC Public Schools – SAT Performance Analysis

>  **Note:** This project is based on a guided DataCamp exercise. All code, analysis, and insights here are my own.

---

##  Project Objective

Analyze SAT performance across New York City public high schools to answer three key questions:

1. Which schools have the best math scores (≥ 80% of max)?
2. Which are the top 10 schools based on total SAT score?
3. Which NYC borough has the highest variation in SAT performance?

---

##  Dataset Information

**File used:** `schools.csv`  
Each row represents a school with the following columns:

- `school_name`
- `borough`
- `average_math`
- `average_reading`
- `average_writing`

Each SAT section is scored out of **800**.

---

## 📊 Key Results

###  Best Math Schools  
Schools with **math scores ≥ 640**, sorted by `average_math`.

| Rank | School Name                                                             | Average Math |
|------|--------------------------------------------------------------------------|--------------|
| 1    | Stuyvesant High School                                                  | 754          |
| 2    | Bronx High School of Science                                            | 714          |
| 3    | Staten Island Technical High School                                     | 711          |
| 4    | Queens High School for the Sciences at York College                     | 701          |
| 5    | High School for Mathematics, Science, and Engineering at City College   | 683          |
| 6    | Brooklyn Technical High School                                          | 682          |
| 7    | Townsend Harris High School                                             | 680          |
| 8    | High School of American Studies at Lehman College                       | 669          |
| 9    | New Explorations into Science, Technology and Math High School          | 657          |
| 10   | Eleanor Roosevelt High School                                           | 641          |

→ Saved as: `best_math_schools`

---

### Top 10 Schools by Total SAT Score

| Rank | School Name                                                             | Total SAT |
|------|--------------------------------------------------------------------------|-----------|
| 1    | Stuyvesant High School                                                  | 2144      |
| 2    | Bronx High School of Science                                            | 2041      |
| 3    | Staten Island Technical High School                                     | 2041      |
| 4    | High School of American Studies at Lehman College                       | 2013      |
| 5    | Townsend Harris High School                                             | 1981      |
| 6    | Queens High School for the Sciences at York College                     | 1947      |
| 7    | Bard High School Early College                                          | 1914      |
| 8    | Brooklyn Technical High School                                          | 1896      |
| 9    | Eleanor Roosevelt High School                                           | 1889      |
| 10   | High School for Mathematics, Science, and Engineering at City College   | 1889      |

→ Saved as: `top_10_schools`

---

### Borough with Highest SAT Variation

| Borough   | Average SAT | Std Dev SAT | Number of Schools |
|-----------|-------------|-------------|-------------------|
| Manhattan | 1340.13     | 230.29      | 89                |

→ Saved as: `largest_std_dev`

---

## Tools Used

- Python
- pandas
- numpy
- Jupyter Notebook

---

## 🚀 How to Run

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/nyc-sat-analysis.git
