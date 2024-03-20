# Survey Tool for Data Collection and Analysis

This repository contains code for a survey tool developed with Flask, MongoDB, and Python for data analysis.

## Getting Started

### Prerequisites

- Python 3.x
- Flask
- MongoDB
- pymongo

### Installing Dependencies

`Install Flask using pip:`

`Install pymongo for MongoDB integration:`


### Running the Flask Application

1. Ensure MongoDB is running locally.
2. Run the Flask application by executing the following command:


3. Access the application in your web browser 

## Data Processing

The `user.py` file contains a Python class for representing user data. It also includes functions for storing user data in CSV format.

## MongoDB Configuration

Make sure MongoDB is installed and running locally. Create a database named `survey_database` and a collection named `user_data` to store user information.

## Data Visualization

For data analysis and visualization, load the CSV file generated by the Flask application into a Jupyter notebook. Use libraries like Pandas, Matplotlib, and Seaborn for analysis and visualization.

## Deployment on AWS

To deploy the Flask application on AWS, follow these steps:

1. Set up an AWS account if you haven't already.
2. Launch an EC2 instance or deploy the application using Elastic Beanstalk.
3. Configure security groups and network settings to allow traffic to the application.

