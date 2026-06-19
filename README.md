# Student Performance Data Analysis

## Project Overview
This project analyzes student performance data to identify factors affecting academic success. The dataset contains student scores in math, reading, and writing, along with demographic information.

## Project Structure

| File/Folder | Description |
|---|---|
| 📄 **Documentation** | |
| `README.md` | Project overview and documentation |
| `LICENSE` | MIT License |
| | |
| 📓 **Notebook** | |
| `student_performance_analysis.ipynb` | Main analysis notebook |
| | |
| 📊 **Data** | |
| `StudentsPerformance.csv` | Cleaned dataset |
| | |
| 📈 **Visualizations** | |
| `lunch_effect.png` | Impact of lunch type on performance |
| `math_distribution.png` | Distribution of math scores |
| `math_score_gender.png` | Average math score by gender |
| `parent_education.png` | Impact of parental education on scores |
| `test_prep.png` | Effect of test preparation on scores |

## Dataset

**Source: Kaggle — Students Performance in Exams**  
[https://www.kaggle.com/datasets/spscientist/students-performance-in-exams](https://www.kaggle.com/datasets/spscientist/students-performance-in-exams)

| Variable | Type | Description |
|---|---|---|
| `gender` | Categorical | Student's gender |
| `race/ethnicity` | Categorical | Ethnic group (A–E) |
| `parental level of education` | Ordinal | Parent's highest education level |
| `lunch` | Categorical | Lunch type (standard / free/reduced) |
| `test preparation course` | Categorical | Completed test prep course (yes / no) |
| `math score` | Numerical | Math score (0–100) |
| `reading score` | Numerical | Reading score (0–100) |
| `writing score` | Numerical | Writing score (0–100) |

The dataset contains **1,000 student records** with demographic information and test scores.

##  Key Analyses Performed
1. **Score Statistics**: Calculated average, max, and min scores for each subject
2. **Gender Analysis**: Compared math performance between male and female students
3. **Parental Education**: Examined the impact of parental education on math scores
4. **Test Preparation**: Analyzed effectiveness of test preparation courses
5. **Lunch Program**: Investigated how lunch type affects student performance
6. **Top Performers**: Identified the 10 highest-performing students

## Visualizations
The project includes several visualizations:
- Average math score by gender
- Math score distribution
- Impact of parental education on scores
- Effect of test preparation
- Lunch type impact on performance

## Technologies Used
- Python 3
- Pandas (Data manipulation)
- Matplotlib (Data visualization)
- Jupyter Lab (Development environment)
