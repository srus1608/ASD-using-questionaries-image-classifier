# Autism Spectrum Disorder (ASD) Detection

This project focuses on detecting Autism Spectrum Disorder (ASD) using two primary methods:
1. **ASD Detection using Questionnaires**
2. **Image Classification using Machine Learning**

The project is containerized using Docker to ensure consistent environments.

## Project Components

### 1. ASD Detection using Questionnaires
 **Objective**: Assess ASD likelihood based on responses to standardized questionnaires.
 **Method**: Machine learning models are trained on questionnaire data to classify responses and predict ASD likelihood.
 **Data**: Various datasets are used for training and testing the model. The data is sourced from Kaggle 
  

### 2. Image Classification using Machine Learning
 **Objective**: Classify images related to ASD research.
 **Method**: Machine learning models, including ResNet and other classifiers, are trained to categorize images.
 **Data**: Image datasets used for training and evaluation. The specifics of these datasets are included in the repository.

### Docker Setup
The project uses Docker for environment consistency. 

#### Docker Commands
 **Build the Docker Image**:
 
  docker build -t asd-detection .
### 3. Installation
To set up the project locally:

Clone the Repository:
git clone https://github.com/srus1608/Autism-Spectrum-Disorder-Detection.git

Navigate to the Project Directory:
cd Autism-Spectrum-Disorder-Detection

Install Dependencies:
If not using Docker, install the required Python libraries:
pip install -r requirements.txt

### 4. Usage
Running the Questionnaire-Based Detection
1. Execute the script for ASD detection using questionnaires:
python questionnaire_detection.py

2.Running the Image Classification
Execute the script for image classification:
python image_classification.py

### 5. Project Files and Directories
DataSet/: Contains various datasets used for training and testing.

DataSet/Images/data.csv
DataSet/Screening/Autism Adolescent/Autism-Adolescent-Data.arff
DataSet/Screening/Autism Adolescent/Autism-Screening-Adolescent-Data Description.docx
DataSet/Screening/Autism Adolescent/csv_result-Autism-Adolescent-Data.csv
DataSet/Screening/Autism Adolescent/new_csv_result-Autism-Adolescent-Data.csv
DataSet/Screening/Autism adults/Autism-Adult-Data.arff
DataSet/Screening/Autism adults/Autism-Screening-Adult-Data Description.docx
DataSet/Screening/Autism adults/autism_screening_2.csv
DataSet/Screening/Autism adults/csv_result-Autism-Adult-Data.csv
DataSet/Screening/Autism adults/new_autism_screening_2.csv
DataSet/Screening/Autism adults/new_csv_result-Autism-Adult-Data.csv
DataSet/Screening/Autism child/Autism-Child-Data.arff
DataSet/Screening/Autism child/Autism-Screening-Child-Data Description.docx
DataSet/Screening/Autism child/csv_result-Autism-Child-Data.csv
DataSet/Screening/Autism child/new_csv_result-Autism-Child-Data.csv
DataSet/Screening/Autism toddler/Toddler Autism dataset July 2018.csv
DataSet/Screening/Autism toddler/Toddler data description.docx
DataSet/Screening/Autism toddler/new Toddler Autism dataset July 2018.csv
DataSet/Screening/Screening question/Autism_Data Description.docx
DataSet/Screening/Screening question/Autism_Data.arff
DataSet/Screening/Screening question/new_Autism_Data.csv
DataSet/Screening/data.csv
Dockerfile: Dockerfile for containerizing the project.

Image Classification/: Contains files for image classification models.

ResNet/model.h5
ResNet/resNet.ipynb
TWSVM_Package/package/KernelFunction.py
TWSVM_Package/package/TVSVM.py
TWSVM_Package/package/TwinPlane1.py
TWSVM_Package/package/TwinPlane2.py
TWSVM_Package/package/simple_test.py
TWSVM_Package/package/synt_testing.py
TWSVM_Package/package/twin_svm.ipynb
image_prediction.ipynb
knn.sav
logistic_regression.sav
naive_bayes.sav
svc.sav


Main.py: Main script to run the project.
streamlit run Main.py

Preprocessed Data/: Contains notebooks for data preprocessing.

data_1_merge.ipynb
data_2_merge.ipynb
data_3_merge.ipynb
data_4_merge.ipynb
images.ipynb
merging.ipynb
Screening/: Contains models for screening.

knn_screening.sav
logistic_regression_screening.sav
naive_screening.sav
svc_screening.sav
asd_detection.ipynb: Jupyter notebook for ASD detection.

poetry.lock, poetry.toml, pyproject.toml: Dependency management files.

questions.py: Script for handling questionnaire data.

utils.py: Utility functions for the project.

## Contributing
Contributions are welcome! Please fork the repository and submit a pull request with your changes.




