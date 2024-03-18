# Customer Segmentation with PyCaret and Streamlit

## Overview
This project focuses on the pivotal role of customer analytics in marketing, utilizing predictive modeling, data visualization, information management, and segmentation. We have implemented a customer segmentation model and a product recommendation engine to boost sales and conversions. Segmentation allows marketers to target potential buyers more effectively.

## Business Importance
Customer analytics is essential for designing effective marketing strategies. It involves techniques like predictive modeling, data visualization, information management, and segmentation. In this project, we use customer segmentation and product recommendations to maximize sales and conversions, enabling marketers to identify and target potential buyers more accurately.

## PyCaret Integration
PyCaret, a low-code machine learning library in Python, streamlines the process from data preparation to model deployment. We used K-means clustering for data segmentation in this project. The project's workflow was modularized, followed by the development of a Streamlit-based UI for interaction, which was then deployed on AWS ECS.

## Data Description
The project uses the ‘jewellery’ dataset from PyCaret’s collection, which includes customer profiles with attributes like age, income, spending score, and savings. Our goal is to segment these customers effectively to help the marketing team target potential buyers.

## Tech Stack
- **Language:** Python
- **Containers:** Docker
- **Libraries:** PyCaret, pandas, Streamlit
- **Cloud Services:** AWS ECS and ECR

## Getting Started
To run this project locally, follow these steps:

1. Clone the repository to your local machine.
2. Ensure Docker is installed and running.
3. Build the Docker container using the provided Dockerfile.
4. Run the container, and access the Streamlit application on your local server.

## Deployment on AWS ECS
The application is containerized using Docker and deployed on AWS ECS for scalable and efficient access. AWS ECR is used for container image storage and management. Detailed steps for deployment include container image creation, uploading to ECR, and setting up ECS services and tasks to run the application.

## License
This project is licensed under the Creative Commons Attribution-NonCommercial (CC BY-NC) License. This allows others to remix, tweak, and build upon the work non-commercially, as long as they credit the creator and license their new creations under the identical terms.

For more details, see [Creative Commons Attribution-NonCommercial (CC BY-NC) License](https://creativecommons.org/licenses/by-nc/4.0/).