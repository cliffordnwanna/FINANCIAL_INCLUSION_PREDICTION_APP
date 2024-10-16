

# **Financial Inclusion Prediction App**

## **Overview**
The **Financial Inclusion Prediction** project aims to predict whether individuals in East Africa are likely to have a bank account based on demographic information and various financial service usage patterns. Utilizing a machine learning model, this application helps identify individuals who may benefit from targeted financial services, contributing to increased financial inclusion across the region.

## **Dataset Description**
The dataset contains demographic information for approximately **33,600 individuals** across East Africa, detailing their access to financial services. It includes variables such as age, gender, education level, and relationship with the head of the household.

**Dataset Link**: [Financial Inclusion Dataset](https://drive.google.com/file/d/1FrFTfUln67599LTm2uMTSqM8DjqpAaKL/view)

### **Variable Definitions**
- **country**: Country of the interviewee.
- **year**: Year the survey was conducted.
- **uniqueid**: Unique identifier for each interviewee.
- **location_type**: Type of location (Rural, Urban).
- **cellphone_access**: If the interviewee has access to a cellphone (Yes, No).
- **household_size**: Number of people living in the household.
- **age_of_respondent**: Age of the interviewee.
- **gender_of_respondent**: Gender of the interviewee (Male, Female).
- **relationship_with_head**: Relationship with the head of the household.
- **marital_status**: Marital status of the interviewee.
- **education_level**: Highest level of education attained.
- **job_type**: Type of job held by the interviewee.
- **bank_account**: Target variable indicating whether the interviewee has a bank account.

## **Project Structure**
```
Financial-Inclusion-Prediction/
│
├── data/                            # Directory for storing datasets
│   └── Financial_inclusion_dataset.csv   # Dataset file (optional: download via script)
│
│
├── models/                          # Directory for trained models
│   └── streamlit_trained_model.sav  # Trained machine learning model file
│
├── app/                             # Streamlit web application
│   └── app.py                       # Streamlit script for the web app
│
├── src/                             # Source files for training and model scripts
│   ├── train_model.py               # Python script for training the model
│
├── requirements.txt                 # File for project dependencies
├── README.md                        # Project overview and documentation
└── .gitignore                       # File to ignore unnecessary files on GitHub
```

## **Features**
- **Data Preprocessing**: Clean the dataset by handling missing values, removing duplicates, and encoding categorical features.
- **Machine Learning**: Train a **Random Forest Classifier** to predict financial inclusion based on input features.
- **Web Application**: A user-friendly interface built with **Streamlit** that allows users to input data and receive predictions.

## **Installation**
To get a copy of the project up and running on your local machine, follow these steps:

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/cliffordnwanna/FINANCIAL_INCLUSION_PREDICTION_APP.git
   cd FINANCIAL_INCLUSION_PREDICTION_APP
   ```

2. **Install Dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Model Training Script:**
   ```bash
   python src/train_model.py
   ```

4. **Run the Streamlit Web Application:**
   ```bash
   streamlit run APP/app.py
   ```

## **Usage**
1. **Data Preprocessing**: The dataset is cleaned by handling missing values, encoding categorical features, and removing duplicates.
2. **Model Training**: The Random Forest model is trained and saved to the `models` directory.
3. **Streamlit Application**: Users can input data through the Streamlit web app and receive predictions on financial inclusion.

## **Deployment**
The app can be deployed on [Streamlit Cloud](https://share.streamlit.io/). Once deployed, users can access the app online, allowing for easy interaction and demonstration of the predictive capabilities.

## **Contributing**
Contributions are welcome! If you have ideas to improve this project, feel free to fork the repository and create a pull request.

## **License**
This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.

## **Contact**
For any inquiries or suggestions, please reach out to:
- **Name:** Chukwuma Clifford
- **Email:** nwannachumaclifford@gmail.com
- **GitHub:** [https://github.com/cliffordnwanna](https://github.com/cliffordnwanna)

