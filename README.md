# Click Fraud Prediction - DIC Project

This repository contains the code for a Click Fraud Prediction project, including data preprocessing, exploratory data analysis (EDA), model building, and a Streamlit web application.

## Project Structure

- dicproject.ipynb: Jupyter Notebook containing the code for data preprocessing, EDA, and model building.
- DICwebsite1.py: Streamlit code for the web application.
- final_random_forest_model.pkl : Pickle file of our best model which is random forest, this file has been used to build Streamlit web application.
- cleaned_data.pkl : During preprocessing, the 'click_time' column is transformed into datetime format, and the 'hour' is extracted, so the file contains cleaned_data which is used in building web application.
- Pipfile : It is used to install thw Streamlit.
- randomsample.csv : It is a sample data which is subset of train.csv, which can be used as a user input in visualization tab, such that we can see tailored visuals according to this random_sample data

## Running the Streamlit Web App

To launch the Streamlit web app for click fraud prediction, follow these detailed steps:
 1. Install Dependencies:
⁃ Before running the application, make sure you have the required dependencies installed.
⁃ Streamlit
 		
 2. Open a Terminal or Command Prompt:
⁃ Open a terminal or command prompt on your machine.
 		
 3.  Navigate to the Working Directory:
⁃ Navigate to the directory where the Streamlit app files are located. Use the cd command:
⁃ cd path/to/project
 		
 4. Execute the Streamlit Command:
⁃ Execute the following command to run the Streamlit app:
⁃ streamlit run DICwebsite1.py
 		
 5. Access the Web App:
⁃ After running the command, Streamlit will initiate the app, and a local development server will start. Look for the output in the terminal, which will include a local URL (usually starting with http://localhost).
 		
 6. Open a Web Browser:
⁃ Open a web browser and enter the provided URL to access the Streamlit web app.
 		
 7. Explore the App:
⁃ Explore the different sections through the user-friendly interface, including:
⁃ Home: This screen contains an introduction and overview of the project with a logo and other elements.
⁃ Predictions: Input data in this section to see real-time predictions based on the pre-trained Random Forest model. Users can input data here and click on the validate button to see the prediction.
⁃ Visualizations: Navigate through various visualizations in this section to gain insights into different aspects of the click fraud dataset. Users can also input their dataset, and after uploading the dataset, the user will get tailored visuals according to the given input dataset.
⁃ Interactive Usage:
⁃ In the 'Predictions' section, input data following the provided guidelines to receive real-time predictions. Use the sliders, input fields, or other interactive elements in the 'Visualizations' section to customize your exploration.
 8. Stop the Streamlit App:
⁃ To stop the Streamlit app, return to the terminal and press Ctrl + C.
