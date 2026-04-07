**COVID-19 Data Analysis & Dashboard (Using Synthetic Data)**


 **Introduction**


The outbreak of COVID-19 led to the generation of vast amounts of data worldwide, including information on confirmed cases, deaths, recoveries, and active cases.
Analyzing this data is important to understand how the virus spreads and to identify patterns across different regions.In some cases, real-world datasets may not
be easily accessible or convenient to use. 
To overcome this limitation, this project uses synthetically generated data created with the Faker library.The generated dataset mimics real COVID-19 
statistics and is used to perform data analysis and visualization, helping to understand trends and relationships effectively.

 **Aim of the Project**



This project aims to simulate and analyze COVID-19 data using artificial data.

**The main objectives are:**

• Create a realistic dataset using Faker.

• Represent COVID-19 trends across multiple countries

• Clean and prepare the data for analysis

• Study patterns over time

• Perform comparisons between countries

• Identify relationships between key variables

• Visualize the results using different charts

• Draw meaningful conclusions from the data

 **Dataset Details**


The dataset is artificially generated and includes records for different countries over various dates.


**Attributes included:**

• Date – The recorded date of observation

• Country – Name of the country

• Confirmed – Number of confirmed cases

• Deaths – Number of deaths

• Recovered – Number of recovered cases

• Active – Currently active cases


 **Active cases are calculated as:**

 
Active = Confirmed − Deaths − Recovered

•  Tools and Libraries Used

**The project is implemented using the following technologies:**

Python


• Pandas (data manipulation)

• NumPy (numerical operations)

• Matplotlib (basic visualization)

• Seaborn (advanced visualization)

• Plotly (interactive charts)

• Faker (synthetic data generation)

 **Methodology**
 
**1. Data Creation**
Synthetic dataset is generated using Faker
Random values are used to simulate realistic case numbers
Data includes multiple countries and time periods


**2. Data Preparation**
Converted date column into datetime format
Removed duplicate entries
Handled missing values
Ensured correct data types



**3. Data Exploration**
Calculated total cases, deaths, and recoveries
Examined overall data distribution
Summarized key statistics


**4. Trend Analysis**
Studied how cases change over time
Identified rises and declines (waves)
Observed patterns in daily data


**5. Country Comparison**
Determined highly affected countries
Compared confirmed, death, and recovery counts
Analyzed differences between countries


**6. Relationship Study**
Compared:
Confirmed vs Deaths
Confirmed vs Recovered
Active vs Confirmed
Evaluated correlations between variables


**7. Visualization**

Different charts were used to represent the data:

• Line chart → Time-based trends
• Bar chart → Country comparisons
• Pie chart → Distribution of cases
• Scatter plot → Variable relationships
• Heatmap → Correlation analysis
• Interactive charts using Plotly

 **Observations**

 
• Case numbers vary significantly over time

• Certain countries show consistently higher values

• There is a strong link between confirmed cases and deaths

• Recovery rates differ across regions

•Active cases are influenced by recovery and death rates

 **Execution Steps**

 
Step 1: Install Required Packages
pip install pandas numpy matplotlib seaborn faker plotly


Step 2: Run the Code
Use Google Colab / Jupyter Notebook / VS Code


Step 3: Output Generated
Synthetic dataset file (covid_fake_dataset.csv)
Visual charts and analysis results


 **Folder Structure**

 
COVID-Analysis/
│
├── main.py
├── dataset.csv
├── README.md
└── charts/
🔮 Enhancements



**Future improvements can include:**

Developing a full interactive dashboard using Plotly Dash

•Using real-time COVID datasets

•Applying machine learning for predictions

•Deploying the project as a web application

**output screenshots**

<img width="735" height="385" alt="image" src="https://github.com/user-attachments/assets/8d8ea532-d48f-4152-82fa-d0e807d548fb" />
<img width="750" height="450" alt="image" src="https://github.com/user-attachments/assets/d8216d79-b58d-4029-b1c5-4c7ede45702b" />
<img width="726" height="466" alt="image" src="https://github.com/user-attachments/assets/7d865706-88ec-4055-b98d-8e8e8fec26b8" />
<img width="727" height="477" alt="image" src="https://github.com/user-attachments/assets/e2a76492-7362-42d3-b832-c76a82d41764" />
<img width="602" height="382" alt="image" src="https://github.com/user-attachments/assets/ce21136d-1d6e-4dd6-ab0e-aede83be5634" />



 **Summary**

This project highlights how synthetic data can be used effectively for data analysis and visualization.It demonstrates key concepts such as data preprocessing, trend analysis, and graphical representation in a simple and practical way.
