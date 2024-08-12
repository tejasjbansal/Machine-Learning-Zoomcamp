# Machine Learning Zoomcamp

This repository serves as a companion guide for the [Machine Learning Zoomcamp](https://github.com/DataTalksClub/machine-learning-zoomcamp) offered by DataTalksClub, a free online course delving into the practical applications of Machine Learning. Here, you'll find comprehensive materials and exercises to follow along with the course and gain hands-on experience.

## Prerequisites

- **Prior programming experience** (at least 1+ year)
- **Comfortable with command line**
- **No prior exposure to machine learning is required**

### Nice to have but not mandatory

- **Python** (but you can learn it during the course)
- **Prior exposure to linear algebra** will be helpful (e.g. you studied it in college but forgot)

## Syllabus

1. **[Introduction to Machine Learning](./01-intro)**
   - Introduction to Machine Learning
   - ML vs Rule-Based Systems
   - Supervised Machine Learning
   - CRISP-DM
   - Model Selection Process
   - Setting up the Environment
   - Introduction to NumPy
   - Linear Algebra Refresher
   - Introduction to Pandas
   - Summary
   - Homework

2. **[Machine Learning for Regression](./02-regression)**
   - Car price prediction project
   - Data preparation
   - Exploratory data analysis
   - Setting up the validation framework
   - Linear regression
   - Linear regression: vector form
   - Training linear regression: Normal equation
   - Baseline model for car price prediction project
   - Root mean squared error
   - Using RMSE on validation data
   - Feature engineering
   - Categorical variables
   - Regularization
   - Tuning the model
   - Using the model
   - Car price prediction project summary
   - Explore more
   - Homework

3. **[Machine Learning for Classification](./03-classification)**
   - Churn prediction project
   - Data preparation
   - Setting up the validation framework
   - EDA
   - Feature importance: Churn rate and risk ratio
   - Feature importance: Mutual information
   - Feature importance: Correlation
   - One-hot encoding
   - Logistic regression
   - Training logistic regression with Scikit-Learn
   - Model interpretation
   - Using the model
   - Summary
   - Explore more
   - Homework

4. **[Evaluation Metrics for Classification](./04-evaluation)**
   - Evaluation metrics: session overview
   - Accuracy and dummy model
   - Confusion table
   - Precision and Recall
   - ROC Curves
   - ROC AUC
   - Cross-Validation
   - Summary
   - Explore more
   - Homework

5. **[Deploying Machine Learning Models](./05-deployment)**
   - Intro / Session overview
   - Saving and loading the model
   - Web services: introduction to Flask
   - Serving the churn model with Flask
   - Python virtual environment: Pipenv
   - Environment management: Docker
   - Deployment to the cloud: AWS Elastic Beanstalk (optional)
   - Summary
   - Explore more
   - Homework

6. **[Decision Trees and Ensemble Learning](./06-trees)**
   - Credit risk scoring project
   - Data cleaning and preparation
   - Decision trees
   - Decision tree learning algorithm
   - Decision trees parameter tuning
   - Ensemble learning and random forest
   - Gradient boosting and XGBoost
   - XGBoost parameter tuning
   - Selecting the best model
   - Summary
   - Explore more
   - Homework

7. **[Production-Ready Machine Learning (Bento ML)](./07-bento-production)**
   - Intro/Session Overview
   - Building Your Prediction Service with BentoML
   - Deploying Your Prediction Service
   - Sending, Receiving and Validating Data
   - High-Performance Serving
   - Bento Production Deployment
   - (Optional) Advanced Example: Deploying Stable Diffusion Model
   - Summary
   - Homework

Midterm Project: [Putting everything we've learned so far in practice](./projects)

8. **[Neural Networks and Deep Learning](./08-deep-learning)**
   - Fashion classification
   - Setting up the Environment on Saturn Cloud
   - TensorFlow and Keras
   - Pre-trained convolutional neural networks
   - Convolutional neural networks
   - Transfer learning
   - Adjusting the learning rate
   - Checkpointing
   - Adding more layers
   - Regularization and dropout
   - Data augmentation
   - Training a larger model
   - Using the model
   - Summary
   - Explore more
   - Homework

For the deep learning part, we need to use a GPU. ML Zoomcamp students can use Saturn Cloud and get extra 150 GPU hours there. Message support and say "I'm enrolled in ML Zoomcamp" to get an upgrade.

9. **[Serverless Deep Learning](./09-serverless)**
   - Introduction to Serverless
   - AWS Lambda
   - TensorFlow Lite
   - Preparing the code for Lambda
   - Preparing a Docker image
   - Creating the lambda function
   - API Gateway: exposing the lambda function
   - Summary
   - Explore more
   - Homework

10. **[Kubernetes and TensorFlow Serving](./10-kubernetes)**
    - Overview
    - TensorFlow Serving
    - Creating a pre-processing service
    - Running everything locally with Docker-compose
    - Introduction to Kubernetes
    - Deploying a simple service to Kubernetes
    - Deploying TensorFlow models to Kubernetes
    - Deploying to EKS
    - Summary
    - Explore more
    - Homework

11. **[KServe (optional)](./11-kserve)**
    - Overview
    - Running KServe locally
    - Deploying a Scikit-Learn model with KServe
    - Deploying custom Scikit-Learn images with KServe
    - Serving TensorFlow models with KServe
    - KServe transformers
    - Deploying with KServe and EKS
    - Summary
    - Explore more

12. **[Final Project](./projects)**
    Putting everything we've learned so far in practice one more time!

Feel free to explore each module, follow the instructions, and complete the homeworks to gain hands-on experience with Machine Learning. Happy learning!