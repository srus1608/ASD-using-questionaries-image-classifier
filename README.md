# Autism Spectrum Disorder (ASD) Detection

This project focuses on detecting Autism Spectrum Disorder (ASD) using two primary methods:

1. **ASD Detection using Questionnaires**
2. **Image Classification using Machine Learning**

The project is containerized using Docker to ensure consistent environments.

## Project Components

### 1. ASD Detection using Questionnaires
 1.**Objective**: Assess ASD likelihood based on responses to standardized questionnaires.
 2.**Method**: Machine learning models are trained on questionnaire data to classify responses and predict ASD likelihood.
 3.**Data**: Various datasets are used for training and testing the model. The data is sourced from Kaggle 
  

### 2. Image Classification using Machine Learning
 1.**Objective**: Classify images related to ASD research.
 2.**Method**: Machine learning models, including ResNet and other classifiers, are trained to categorize images.
 3.**Data**: Image datasets used for training and evaluation. The specifics of these datasets are included in the repository.

### Docker Setup
The project uses Docker for environment consistency. 

#### Docker Commands
 **Build the Docker Image**:
 docker build -t asd-detection .
 
### 3. Installation
To set up the project locally:

## Clone the Repository:
git clone https://github.com/srus1608/Autism-Spectrum-Disorder-Detection.git

1.Navigate to the Project Directory:

cd Autism-Spectrum-Disorder-Detection

2.Install Dependencies:
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

1.DataSet/Images/data.csv
2.DataSet/Screening/Autism Adolescent/Autism-Adolescent-Data.arff
3.DataSet/Screening/Autism Adolescent/Autism-Screening-Adolescent-Data Description.docx
4.DataSet/Screening/Autism Adolescent/csv_result-Autism-Adolescent-Data.csv
5.DataSet/Screening/Autism Adolescent/new_csv_result-Autism-Adolescent-Data.csv
6.DataSet/Screening/Autism adults/Autism-Adult-Data.arff
7.DataSet/Screening/Autism adults/Autism-Screening-Adult-Data Description.docx
8.DataSet/Screening/Autism adults/autism_screening_2.csv
9.DataSet/Screening/Autism adults/csv_result-Autism-Adult-Data.csv
10.DataSet/Screening/Autism adults/new_autism_screening_2.csv
11.DataSet/Screening/Autism adults/new_csv_result-Autism-Adult-Data.csv
12.DataSet/Screening/Autism child/Autism-Child-Data.arff
13.DataSet/Screening/Autism child/Autism-Screening-Child-Data Description.docx
14.DataSet/Screening/Autism child/csv_result-Autism-Child-Data.csv
15.DataSet/Screening/Autism child/new_csv_result-Autism-Child-Data.csv
16.DataSet/Screening/Autism toddler/Toddler Autism dataset July 2018.csv
17.DataSet/Screening/Autism toddler/Toddler data description.docx
18.DataSet/Screening/Autism toddler/new Toddler Autism dataset July 2018.csv
19.DataSet/Screening/Screening question/Autism_Data Description.docx
20.DataSet/Screening/Screening question/Autism_Data.arff
21.DataSet/Screening/Screening question/new_Autism_Data.csv
22.DataSet/Screening/data.csv
23.Dockerfile: Dockerfile for containerizing the project.

Image Classification/: Contains files for image classification models.

1.ResNet/model.h5
2.ResNet/resNet.ipynb
3.TWSVM_Package/package/KernelFunction.py
4.TWSVM_Package/package/TVSVM.py
5.TWSVM_Package/package/TwinPlane1.py
6.TWSVM_Package/package/TwinPlane2.py
7.TWSVM_Package/package/simple_test.py
8.TWSVM_Package/package/synt_testing.py
9.TWSVM_Package/package/twin_svm.ipynb
10.image_prediction.ipynb
11.knn.sav
12.logistic_regression.sav
13.naive_bayes.sav
14.svc.sav


## Main.py: Main script to run the project.
streamlit run Main.py

## Preprocessed Data/: Contains notebooks for data preprocessing.

1. data_1_merge.ipynb
2. data_2_merge.ipynb
3. data_3_merge.ipynb
4. data_4_merge.ipynb
5. images.ipynb
6. merging.ipynb

  ### Screening/: Contains models for screening.

1. knn_screening.sav
2. logistic_regression_screening.sav
3. naive_screening.sav
4. svc_screening.sav

## asd_detection.ipynb: Jupyter notebook for ASD detection.

poetry.lock, poetry.toml, pyproject.toml: Dependency management files.

questions.py: Script for handling questionnaire data.

utils.py: Utility functions for the project.

## Contributing
Contributions are welcome! Please fork the repository and submit a pull request with your changes.




