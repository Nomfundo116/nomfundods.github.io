
# Software Developer | Aspiring Data Scientist

#### Technical Skills: Python, SQL, AWS, java

## Education
- BTech, Computer Systems Engineering | Tshwane University of Technology (_October 2022_)								       		
- N DIP, Computer Systems Engineering	| Durban University of Technology (_December 2017_)	 			        		

## Certifications
- AWS cloud Practitioner CLF-C02 | AWS (_Current 2024_)
- Artificial Intelligence in the South African context | Nemisa (_February 2023_)
- The Complete Python Bootcamp from Zero to Hero in Python | Udemy (By Jose Portilla) (_Current 2023_)

## Work Experience
**Software developer and QA  @ Ice Tech  (_October 2018 - Present_)**
- Develop SQL queries to retrieve specific data subsets and perform advanced data manipulations.
- Collaborate with cross-functional teams to identify key performance indicators and deliver actionable insights.
- Produce comprehensive reports and visualizations to communicate findings to stakeholders at various levels of the 
  organization.
- Customize and enhance modules within the iDempiere ERP system using Java. Debug and maintain Java code to configure 
  business logic and integrate third-party solutions.
- Automation and Test analysis.

**GIZ AI Pilot Training Program  @ University Of Johannesburg and Nemisa (_July 2022 - 2023 February_ Part-time_)**
- Python Programming: Developed proficiency in Python for data analysis, utilizing libraries such as Pandas, NumPy, 
   and SciPy.
- Data Manipulation: Conducted data manipulation, cleansing, and preprocessing using Pandas DataFrame.
- Data Visualization: Created insightful visualizations with tools like Matplotlib, Seaborn, and Plotly.
- Statistical Analysis and Machine Learning: Gained advanced knowledge of statistical analysis and machine learning 
  techniques for predictive modeling and data interpretation.
- Natural Language Processing (NLP): Studied and implemented NLP techniques for text analysis and sentiment analysis.
- Advanced Machine Learning: Applied machine learning techniques for classification, regression, clustering, and 
  predictive modeling.
  
**Junior Java developer @ nTier Software Services (_January 2017 - August 2018_)**
- Developed scheduler and non-scheduler class processes, workflow documents, and modified callouts using Java for 
  before-save, after-save, before-delete, after-delete, and M-model operations
- Utilized structured query language (SQL) to query and modify databases, create Jasper report graphics, and implement 
  SQL commands on the iDempiere ERP system for client-facing documents.
- Customized the open-source ERP iDempiere by creating tables, interface windows, info windows, menus, workflow 
  processes, and views.
- Conducted QA testing to verify system development and troubleshoot code (debugging).
- Performed operating system analysis and interacted with users to gather further system requirements.

## Projects
### Amazon Sales Data Analytics

This project involves a comprehensive analysis of Amazon sales data to extract meaningful insights and understand various aspects of product pricing, discounting, and customer reviews. The analysis was conducted using Google Colab, leveraging Python for data manipulation, analysis, and visualization.
Project Description: Analysis of Amazon Sales Data

**Introduction**
This project involves a comprehensive analysis of Amazon sales data to extract meaningful insights and understand various aspects of product pricing, discounting, and customer reviews. The analysis was conducted using Google Colab, leveraging Python for data manipulation, analysis, and visualization.

**Data Upload and Exploration**
Uploading the Dataset: The Amazon sales dataset was uploaded onto Google Colab for analysis.
Viewing Column Names: The dataset includes the following columns: product_id, product_name, category, discounted_price, actual_price, discount_percentage, rating, rating_count, about_product, user_id, user_name, review_id, review_title, review_content, img_link, and product_link.
Dataset Shape: The dataset contains 1465 rows and 16 columns.
Data Types: All columns in the dataset are of object datatype.
Null Values: Initial exploration revealed the presence of null values in the dataset, which were addressed in the data cleaning process.

**Data Cleaning**
Descriptive Analysis: Conducted a descriptive analysis to summarize the dataset, identify key characteristics, and inform decision-making.
Handling Missing Values:
Explored multiple imputation methods, such as using the mean based on product_id and category.
Chose to use the median to impute missing values in the rating_count column. This approach was selected because it is a robust measure of central tendency, less sensitive to outliers, and ensures the overall distribution of the data remains unaffected.

**Data Visualization**
Price Distribution Visualization:
Created graphs to depict the distribution of actual_price, discounted_price, and frequency.
Observed that the majority of prices cluster around the lower end of the price spectrum, with counts decreasing sharply as prices increase.
Both actual prices and discounted prices showed similar patterns, indicating consistent discounting across different price ranges.
Due to extreme skewness, detailed differences in higher price ranges were difficult to discern in the initial plots.
Utilized zoomed-in and log-scaled plots to provide a clearer understanding of the price distributions. These plots highlighted the high concentration of lower prices and the rapid decline in frequency as prices increased. The logarithmic scale emphasized the distribution across the entire price range more effectively.


![Amazon](/assets/downloadamazon.jfif)


### MobileNet Neural Network skin disease detector 
[Publication](https://ieeexplore.ieee.org/document/9183888)

**Introduction**
Skin cancer, one of the deadliest skin diseases, accounts for 8.2 million deaths and 14.1 million new diagnoses annually worldwide. Recognizing the critical need for early referral for skin disease patients, I developed an efficient automated approach to classify skin cancer lesions.

**Project Overview**
I constructed a skin disease module capable of classifying seven types of skin lesions, including Benign Keratosis and Melanoma, utilizing machine learning techniques. The classification process employed a MobileNet convolutional neural network (CNN) implemented on a Raspberry Pi, utilizing the Keras architecture for training.

**Implementation**
MobileNet CNN: I used MobileNet CNN, which implements Depthwise Separable Convolution, significantly reducing computing resource consumption by 8-9 times compared to standard convolution.
Data Collection: Users could take pictures or upload images using a gadget camera through a Telegram chat bot interface.
Training and Validation: The model achieved a top-3 validation accuracy of 0.096 and a top-2 accuracy of 0.89.

![EEG Bandskin disease detector](/assets/downloadbtechprojectimg.jfif)
