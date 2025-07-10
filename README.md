## SKILL EXTRACTION FROM RESUME USING CUSTOM ENTITY RECOGNITION
A cloud-based NLP project that automates the extraction of skills from resumes using a custom Named Entity Recognition (NER) model trained with Amazon Comprehend. This project simplifies resume parsing and speeds up talent screening by identifying key skills like programming languages, tools, and soft skills from unstructured text.


#### Key Features
- Trained a custom NER model to identify entities such as programming languages, tools, certifications, and soft skills
- Utilized Amazon Comprehend and Amazon S3 for scalable and secure model training and data handling
- Implemented IAM roles to manage access to S3 buckets and Comprehend services
- Validated the model using test documents, with results stored and visualized from JSON outputs
- Tools and Technologies
- Amazon Comprehend
- Amazon S3
- IAM (Identity and Access Management)
- Python (for data preprocessing and file conversion)
- Converted resume content into plain text files
- Created an entity list CSV for model training
- Uploaded all training and testing data to an Amazon S3 bucket

#### DATASET USED
- Dataset - Resume Entities for NER (Kaggle)
- Dataset Preparation - Downloaded the JSON dataset from Kaggle
