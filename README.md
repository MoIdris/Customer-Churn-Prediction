<a name="readme-top"></a>

<div align="center">
   <h1><b>Customer-Churn-Prediction : A machine learning model to predict customer churn</b></h1>
</div>

Below is a summary of the procedure structure on this project. To view a full project documentation, kindly visit this page (https://medium.com/@idmoh44/machine-learning-model-customer-churn-prediction-17a8ed80d130)

<!-- TABLE OF CONTENTS -->

# 📗 Table of Contents

- [📗 Table of Contents](#-table-of-contents)
- [Introduction ](#introduction-)
  - [🛠 Built With ](#-built-with-)
    - [Tech Stack ](#tech-stack-)
  - [Key Features ](#key-features-)
  - [💻 Getting Started ](#-getting-started-)
    - [Prerequisites](#prerequisites)
    - [Setup](#setup)
    - [Install](#install)
    - [Usage](#usage)
  - [👥 Authors ](#-authors-)
  - [🔭 Future Features ](#-future-features-)
  - [🤝 Contributing ](#-contributing-)
  - [⭐️ Show your support ](#️-show-your-support-)
  - [🙏 Acknowledgments ](#-acknowledgments-)
  - [📝 License ](#-license-)

<!-- PROJECT DESCRIPTION -->

# Introduction <a name="about-project"></a>
The primary objective of Vodafone Corporation is to reduce customer churn, a prevalent issue across many industries, especially in the telecommunications sector. The ultimate goal is to predict the likelihood of a customer discontinuing their service, identify the main factors contributing to customer churn, and develop strategies to retain customers and mitigate this issue.
Key Performance Indicators (KPIs) for this objective could include the churn rate, customer lifetime value, and customer retention rate.

The project plan involves several steps. First, the data will be prepared for analysis, which may include cleaning the data, handling missing values, and encoding categorical variables. Next, appropriate machine learning algorithms will be selected for model construction. The model will then be trained and tested using the prepared data. The model’s performance will be evaluated using suitable metrics, such as accuracy, recall, precision, and F1 score. Finally, the model will be deployed for predicting customer churn. The key indicators identified by the model can then be used to devise effective strategies for customer retention. The impact of these strategies can be measured using KPIs such as the reduction in churn rate and increase in customer retention rate.

By aligning these steps with the overall business strategy, the company can ensure a data-driven approach to tackling customer churn, ultimately leading to improved customer retention and business growth.

### Data for the Project:

The data for this project has been divided into 3. The first 2 data sets are for training and evaluation the machine learning model while the last data set is for testing the model. The first 3000 records of the dataset can be found in a database which will have to be accessed remotely. The second part of the data is hosted on this GitHub Repository in a file called LP2_Telco-churn-second-2000.csv. Whiles the final data set needed for this project can be found in OneDrive.

Target:

- Churn — Whether the customer churned or not (Yes, No)

Numeric Features:

- SeniorCitizen — Whether the customer is a senior citizen or not (1, 0)
- Tenure — Number of months the customer has been with the company
- MonthlyCharges — The monthly amount charged to the customer
- TotalCharges — The total amount charged to the customer

Categorical Features:

- CustomerID
- Gender — M/F
- Partner — Whether customer has a partner or not (Yes, No)
- Dependents — Whether customer has dependents or not (Yes, No)
- PhoneService — Whether the customer has a phone service or not (Yes, No)
- MulitpleLines — Whether the customer has multiple lines or not (Yes, No, No Phone Service)
- InternetService — Customer’s internet service type (DSL, Fiber Optic, None)
- OnlineSecurity — Whether the customer has Online Security add-on (Yes, No, No Internet Service)
- OnlineBackup — Whether the customer has Online Backup add-on (Yes, No, No Internet Service)
- DeviceProtection — Whether the customer has Device Protection add-on (Yes, No, No Internet Service)
- TechSupport — Whether the customer has Tech Support add-on (Yes, No, No Internet Service)
- StreamingTV — Whether the customer has streaming TV or not (Yes, No, No Internet Service)
- StreamingMovies — Whether the customer has streaming movies or not (Yes, No, No Internet Service)
- Contract — Term of the customer’s contract (Monthly, 1-Year, 2-Year)
- PaperlessBilling — Whether the customer has paperless billing or not (Yes, No)
- PaymentMethod — The customer’s payment method (E-Check, Mailed Check, Bank Transfer (Auto), Credit Card (Auto))

## 🛠 Built With <a name="built-with"></a>

### Tech Stack <a name="tech-stack"></a>

<details>
<summary>Database</summary>
  <ul>
    <li><a href="">Microsoft SQL Server</a></li>
  </ul>
</details>

<details>
<summary>Language</summary>
  <ul>
    <li><a href="">Python</a></li>
    <li><a href="">Jupyter Notebook</a></li>
  </ul>
</details>

<details>
<summary>Model</summary>
  <ul>
    <li><a href="">Sklearn</a></li>
  </ul>
</details>


<p align="right">(<a href="#readme-top">back to top</a>)</p>
<!-- Features -->

## Key Features <a name="key-features"></a>

<p align="right">(<a href="#readme-top">back to top</a>)</p>

**1. Business Understanding:**
This is the initial phase where I define the business problem, objectives, and outcomes. I also identified the key stakeholders and understand their expectations.

**2. Data Understanding:**
This phase involves the following steps:

- Importation: Acquiring the necessary data for the project.
- Data Loading: Loading the data into a suitable format for analysis.
- Action Plan: Creating a plan for how to approach the data analysis.
- Hypothesis: Formulating hypotheses that I will test during the analysis.
- Business Questions: Identifying the key questions that the business needs answers to.

**3. Data Preprocessing:**
This phase involves preparing the data for analysis. This could include data cleaning, data transformation, and data integration.

**4. Data Cleaning:**
This phase involves identifying and correcting errors in the data, dealing with missing values, and removing duplicates.

**5. Hypothesis Testing:**
This phase involves testing the hypotheses that were formulated during the data understanding phase. This could involve statistical tests to determine if there is a significant relationship between variables.

**6. Exploratory Data Analysis (EDA):**
This phase involves exploring the data to understand its characteristics and patterns. This could involve visualizing the data, calculating descriptive statistics, and identifying correlations.

**7. Analysis of Business Questions:**
This phase involves using the insights gained from the EDA and hypothesis testing to answer the business questions identified earlier. This could involve building predictive trends, segmenting the data, or conducting further statistical tests.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

![image](https://github.com/MoIdris/Customer-Churn-Predictor/blob/modelBuiling/Dashboard/Screenshot%202024-04-22%20012631.jpg)

![image](https://github.com/MoIdris/Customer-Churn-Predictor/blob/modelBuiling/Dashboard/Screenshot%202024-04-22%20011405.jpg)

![image](https://github.com/MoIdris/Customer-Churn-Predictor/blob/modelBuiling/Dashboard/Screenshot%202024-04-22%20011659.jpg)

![image](https://github.com/MoIdris/Customer-Churn-Predictor/blob/modelBuiling/Dashboard/Screenshot%202024-04-22%20012203.jpg)

![image](https://github.com/MoIdris/Customer-Churn-Predictor/blob/modelBuiling/Dashboard/Screenshot%202024-04-22%20011606.jpg)

<!-- GETTING STARTED -->

## 💻 Getting Started <a name="getting-started"></a>


To get a local copy up and running, follow these steps.

### Prerequisites

In order to run this project you need:

- Python


### Setup

Clone this repository to your desired folder:


```sh
  cd my-folder
  git clone https://github.com/MoIdris/Customer-Churn-Prediction.git
```

Change into the cloned repository

```sh
  cd Customer-Churn-Prediction
  
```

Create a virtual environment

```sh

python -m venv env

```

Activate the virtual environment

```sh
    env/Scripts/activate
```



### Install

Here, you need to recursively install all the necessary packages to be imported in your notebook 

```sh
   pip install python-dotenv
   pip install pyodbc
   pip install numpy
   pip install pandas
   pip install seaborn
   pip install scipy
   pip install jupyterlab
```


### Usage

To view this analysis, visit the page (https://github.com/MoIdris/Customer-Churn-Prediction.git)

To download the notebook, execute the following steps:


- Navigate to the GitHub page (https://github.com/MoIdris/Customer-Churn-Prediction.git).
- Click on the notebook file name to open it.
- Once the file is open, you will see a Raw button on the top right of the file content. Click on this Raw button.
- The notebook content will be displayed in raw JSON format. Right-click anywhere on the page and select Save As or press Ctrl+S to save the file.
- In the Save dialog box, make sure to add the .ipynb extension to the file name if it’s not already there. For example, if the file name is notebook, change it to notebook.ipynb.
- Choose the location where you want to save the file and click Save.
- Now, you can open this .ipynb file using Jupyter Notebook on your local machine.
- **Please note** that the file might be saved as a .txt file by default, so ensure that you change the extension to .ipynb when saving

## Data Cleaning

The data used in this analysis was sourced from three different sources, github, sql server and onedrive, a connection was created with a connection string defined in the '.env' file

1. Data Collection: Gathering raw data from online database.

2. Data Integration: Consolidating data from different sources into a unified dataset.

3. Missing Value Handling: Identifying and dealing with missing values through imputation or removal.

4. Outlier Detection: Detecting and handling outliers that could skew the analysis results.

5. Normalization and Standardization: Ensuring consistency and comparability of data by normalizing or standardizing where necessary.

6. Data Validation: Verifying the integrity of the cleaned dataset to ensure accuracy in subsequent analyses.

## Data Representation

The cleaned data was represented in structured formats suitable for analysis. This included organizing data into tables and saving the unified dataset as a single '.csv' file. Visualization techniques such as charts, graphs, and maps were also employed to present key findings effectively.

## Analysis Methods

Various analytical methods and techniques were utilized to extract insights from the data:

1. Descriptive Statistics: Summarizing key metrics such as mean, median, mode, and standard deviation to describe the central tendency and dispersion of variables.
2. Time-Series Analysis: Examining trends and patterns over time to understand the evolution of the startup ecosystem.
3. Correlation Analysis: Investigating relationships between different variables, such as funding amount and startup success rate.
4. Segmentation Analysis: Grouping startups based on common characteristics (e.g., sector, funding stage) and analyzing each segment separately.
5. Predictive Modeling: Building predictive models to forecast future trends or identify factors influencing startup performance.

## Final Findings

Based on the analysis conducted, several key findings emerged:




<!-- AUTHORS -->

## 👥 Authors <a name="authors"></a>

🕵🏽‍♀️ **Mohammed Idris**

- GitHub: [GitHub Profile](https://github.com/MoIdris)
- Twitter: [Twitter Handle](https://twitter.com/IdrisBaaba)
- LinkedIn: [LinkedIn Profile](www.linkedin.com/in/idris-ibn-mohammed)
- Medium: [Medium Profile](https://medium.com/@idmoh44)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- FUTURE FEATURES -->

## 🔭 Future Features <a name="future-features"></a>


- **Develop a model for this project**
  
  
<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- CONTRIBUTING -->

## 🤝 Contributing <a name="contributing"></a>

Contributions, issues, and feature requests are welcome!

Feel free to check the [issues page](../../issues/).

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- SUPPORT -->

## ⭐️ Show your support <a name="support"></a>

If you like this project kindly show some love, give it a 🌟 **STAR** 🌟

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- ACKNOWLEDGEMENTS -->

## 🙏 Acknowledgments <a name="acknowledgements"></a>

I would like to thank all my team member for their coorperation, commitment and support. My greatest appreciation goes to Rahael for their immense guidance and support.Thanks to all online contributors for the available resources.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- LICENSE -->

## 📝 License <a name="license"></a>

This project is [MIT](./LICENSE) licensed.

<p align="right">(<a href="#readme-top">back to top</a>)</p>



