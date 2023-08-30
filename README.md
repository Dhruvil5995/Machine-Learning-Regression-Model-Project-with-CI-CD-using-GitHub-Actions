# Machine-Learning-Regression-Model-Project-with-CI-CD-using-GitHub-Actions
# Real Estate Price Prediction with TensorFlow Regression

Welcome to my Real Estate Price Prediction project! In this project, I'll guide you through building a machine learning model that predicts real estate property prices using TensorFlow. I've also set up Continuous Integration and Continuous Deployment (CI/CD) using GitHub Actions, making the development and deployment process smoother than ever.

## Table of Contents

- [Overview](#overview)
- [Project Structure](#project-structure)
- [Getting Started](#getting-started)
- [Continuous Integration and Deployment](#continuous-integration-and-deployment)
- [Results and Reports](#results-and-reports)
- [Contributing](#contributing)
- [License](#license)

## Overview

Imagine being able to predict real estate prices based on various factors like location, square footage, and the number of bedrooms. This project brings that idea to life using machine learning. I've developed a TensorFlow regression model that learns from historical data to make accurate predictions.

## Project Structure

- `model.py`: I define, compile, and train my TensorFlow regression model here.

- `requirements.txt`: All the necessary dependencies to run my project are listed here.

- `.github/workflows/mlops-example-tensorflow-regression.yml`: This GitHub Actions workflow automates testing, training, and reporting whenever code is pushed.

## Getting Started

1. **Clone the Repository**: Start by cloning this repository to your local machine.

2. **Setup Virtual Environment**: It's recommended to create a virtual environment for this project:
  
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate

3. **Install Dependencies**: Install the required packages using the provided requirements.txt file:

   pip install -r requirements.txt

4. **Explore the Model** : Open model.py to see how the TensorFlow regression model is defined, compiled, and trained.

## Continuous Integration and Deployment (CI/CD)

**I've set up CI/CD using GitHub Actions. Whenever you push code changes, GitHub Actions will:**

Check out the latest code.
Use a Docker container with necessary tools for ML workflows.
Install dependencies and execute the model training script.
Generate a report with model metrics and performance plot.
Comment the report on the pull request for easy tracking.

### Results and Reports
After running the model, you'll see updates and results in various formats:
 **Pull Request Comments**: The model performance metrics and plots will be automatically added as comments to the corresponding pull request.

 ![2023-08-30 (2)](https://github.com/Dhruvil5995/Machine-Learning-Regression-Model-Project-with-CI-CD-using-GitHub-Actions/assets/64741151/e08f06df-df8a-4f6d-959b-74b86e905e90)
 ![2023-08-30 (3)](https://github.com/Dhruvil5995/Machine-Learning-Regression-Model-Project-with-CI-CD-using-GitHub-Actions/assets/64741151/99ea843e-1b48-44cd-9c84-395a3f1a553b)

**Email Notifications**: You'll receive notifications with updates about the model performance via email.

![2023-08-30 (4)](https://github.com/Dhruvil5995/Machine-Learning-Regression-Model-Project-with-CI-CD-using-GitHub-Actions/assets/64741151/f599fe74-51a1-4b55-b4d3-f622616c3a94)


### Contributing
I welcome contributions! Whether it's fixing a bug, improving the model, or enhancing the documentation, your help is appreciated. Please fork this repository, make your changes, and submit a pull request.

### License
This project is licensed under the MIT License. See the LICENSE file for details.













   
