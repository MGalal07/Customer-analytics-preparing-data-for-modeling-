# Data Science Student Job Prediction

## Project Overview

This project is focused on cleaning and optimizing a large dataset provided by **Training Data Ltd.** The goal is to prepare the data for further analysis and modeling, which will help predict whether students are looking for a new job. The cleaned data will ultimately be used by recruiters to target job-seeking students.

## Dataset

The dataset used for this project contains anonymized information about students, including their demographic details, work experience, education background, and current job status. 

### Key Columns:
- **student_id**: A unique ID for each student.
- **city**: A code representing the city where the student resides.
- **city_development_index**: A numerical index reflecting the development of the city.
- **gender**: The student's gender.
- **relevant_experience**: Indicates whether the student has relevant work experience.
- **enrolled_university**: The type of university course the student is enrolled in.
- **education_level**: The student's education level.
- **major_discipline**: The student's area of study.
- **experience**: Total years of work experience.
- **company_size**: The size of the company where the student is currently employed.
- **company_type**: The type of company employing the student.
- **last_new_job**: The number of years since the student's last job change.
- **training_hours**: Total hours of training completed.
- **job_change**: Whether the student is looking for a new job (1 for Yes, 0 for No).

## Objectives

- **Data Cleaning**: Initial cleaning of the dataset to handle missing values, inconsistent data types, and other data quality issues.
- **Efficient Storage**: Optimize the data types to ensure the dataset is stored efficiently without affecting its integrity.
- **Exploratory Data Analysis (EDA)**: Basic exploration of the dataset to understand key patterns, distributions, and relationships between features.

## Getting Started

1. Clone the repository:
    ```bash
    git clone https://github.com/MGalal07/data-science-student-job-prediction.git
    ```
2. Install the required libraries:
    ```bash
    pip install -r requirements.txt
    ```
3. Run the notebook:
    Open the `notebook.ipynb` file to view the data cleaning and exploration process.

## Next Steps

- Improve data type handling (especially converting categorical features).
- Perform further analysis, including feature engineering and predictive modeling.
- Explore visualization techniques to better understand the distribution of the data.

## License

This project is licensed under the MIT License.

## Acknowledgments

- **Training Data Ltd.** for providing the dataset.
- Open-source libraries: `pandas`, `numpy`, and `matplotlib`.
