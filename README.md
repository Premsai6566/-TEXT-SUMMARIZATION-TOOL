# -TEXT-SUMMARIZATION-TOOL
COMPANY: CODTECH IT SOLUTIONS

NAME: SITHARAM PREM SAI

INTERN ID: CODHC71

DURATION: 8 WEEKS

MENTOR: NEELA SANTHU

##Description:
ETL Pipeline for Data Preprocessing
This repository contains an end-to-end ETL (Extract, Transform, Load) pipeline for structured data preprocessing using pandas and scikit-learn. The script reads raw data, applies transformations (handling missing values, scaling, and encoding categorical variables), and saves the processed dataset for further analysis or machine learning tasks.
Features
 Reads raw data from a CSV file
 Handles missing values using mean imputation (numerical) and most frequent imputation (categorical)
 Scales numerical features using StandardScaler
 Encodes categorical features using OneHotEncoder
 Saves the transformed dataset as a CSV file
Technologies Used
Python 
Pandas
NumPy
Scikit-learn
Installation & Usage
 Clone this repository:
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
Install required dependencies:
pip install -r requirements.txt
 Run the ETL pipeline:
python etl_pipeline.py
Project Structure
 your-repo-name
│── data/
│   ├── raw_data.csv        # Raw dataset (input)
│   ├── processed_data.csv  # Processed dataset (output)
│── etl_pipeline.py         # Main ETL script
│── requirements.txt        # Dependencies
│── README.md               # Project documentation
