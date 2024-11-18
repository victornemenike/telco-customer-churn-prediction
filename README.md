# Telco Customer Churn Prediction


## Project Description
This is the implementation of my project for the course machine-learning-zoomcamp from [DataTalksClub](https://github.com/DataTalksClub/machine-learning-zoomcamp).
The goal of this project is to deploy a web service for a machine learning model for customer churn in a Telco company.

## Problem Statement
Customer churn is a important topic for the bottom line of most companies providing Business-to-Customer (B2C) services.

## Dataset
The dataset used for this project has been sourced from Kaggle (see [link](https://www.kaggle.com/datasets/alfathterry/telco-customer-churn-11-1-3/data)).


## Project Details
This repository has the following files:
- The `data` folder contains the dataset used in this project. 
- The `src` folder contains the source code for the project.
- The `web-service` folder contains the code for deploying the trained model as a web service with `Docker` and `Flask`.
- The `images` folder contains screenshots and other images used in this `README.md` file.
- The `Dockerfile` defines the Docker image for the project, specifying the environment and dependencies required to run the code.
- The `requirements.txt` lists all the Python dependencies required for the project.



## **Quick Start**
To get started with this project, do the following in the terminal:

1. **Clone the repository:**
```bash
git clone https://github.com/victornemenike/telco-customer-churn-prediction.git
```

2. **Navigate to the project directory:**
```bash
cd telco-customer-churn-prediction/
```

To prepare the project and install all dependencies, run the following:

3. **Set up the environment:**

Ensure you have a Python environment set up. You can create a virtual environment using:

```bash
python3.11 -m venv venv
```

```bash
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
```


For more details on how the project was implemented, please see the [Implementation Details](#implementation-details) section below.

## Cloud

Amazon Web Services was used as the cloud provider for the model deployment.

## Implementation Details

### **1. Exploratory Data Analysis



---
