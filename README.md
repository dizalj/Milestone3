# Milestone 3: Data Acquisition and Preparation

## Overview
This milestone focuses on the development of a Machine Learning (ML) pipeline for data acquisition, preprocessing, validation, feature engineering, and versioning. The pipeline was built using ZenML, DVC/Git LFS, Feast, and MongoDB, and was executed in Google Colab. The goal was to create a modular and reproducible pipeline that ensures data quality, versioning, and scalability for future iterations.

## Achievements
- Developed a modular ML pipeline, ensuring that each component (data ingestion, preprocessing, validation, feature engineering, and versioning) could be developed, tested, and maintained independently.
- Implemented data versioning with DVC/Git LFS to track processed datasets, although challenges with cloud storage integration were encountered :(.
- Integrated MongoDB for centralized data storage and Feast for feature store integration, ensuring data scalability.
- Addressed tool compatibility issues and runtime constraints, particularly when using ZenML in Google Colab.

For more detailed information on the project, please refer to my [report](./Milestone3.pdf).

## Repository Structure
- **Milestone3.ipynb:** Notebook demonstrating the pipeline’s steps, including data ingestion, preprocessing, validation, feature engineering, and data versioning using DVC.
- **M3.ipynb:** Another notebook but data versioning using Git LFS.
- **data.csv:** The dataset used in the pipeline for ingestion and processing.
- **feature_store.yaml:** Configuration file for integrating the feature store (Feast) in the pipeline.

## Future Work
There is potential for further optimization in the pipeline's performance, especially with DVC integration, as well as additional exploration into more advanced data validation techniques.
