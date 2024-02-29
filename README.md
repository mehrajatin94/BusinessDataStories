Automated Inquiry Categorization for International Student Enquiries
Overview
This project aims to automate the categorization of inquiries raised by international students studying at Humber International Graduate School across different departments. The dataset contains inquiries along with their corresponding categories. The goal is to deploy a Natural Language Processing (NLP) model, specifically a Linear Support Vector Classifier (LinearSVC), that can accurately classify inquiries into their respective categories, thereby reducing manual workload and streamlining the response process.

Dataset Information
The dataset consists of 158 entries and includes the following columns:

ID: Unique identifier for each inquiry.
Inquiry: Textual description of the student's inquiry.
Category: The category to which the inquiry belongs.
Model Deployment
A machine learning model based on Linear Support Vector Classifier (LinearSVC) has been developed and deployed to automatically categorize student inquiries. The model has been trained using the dataset(train - 70%) and evaluated on a test set(30%) to ensure its effectiveness.

Repository Structure
data/: Contains the dataset used for training and testing the model.
notebooks/: Jupyter notebooks used for data exploration, model development, and evaluation.
src/: Source code for the NLP model and any associated scripts.
model/: Saved model files.
README.md: Overview of the project and instructions for usage.
requirements.txt: List of dependencies required to run the project.
