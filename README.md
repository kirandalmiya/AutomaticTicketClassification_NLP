<b>Automatic Ticket Classification Using NLP</b>

<b>Overview</b>

This repository contains the code and documentation for the project "Automatic Ticket Classification Using NLP". This project was completed as part of the Executive PG Programme in Machine Learning & AI at IIIT Bangalore. The primary objective is to automate the classification of customer complaints for a financial company using Natural Language Processing (NLP) techniques.

<b>Problem Statement</b>

Customer complaints are critical for financial companies as they highlight areas for improvement in their products and services. Traditionally, evaluating and assigning these complaints to the relevant departments is a manual and time-consuming process. This project aims to automate this process by building a model to classify customer complaints based on the company's products and services.

<b>Business Goal</b>

Develop an NLP model capable of classifying customer complaints into the following categories:
1.	Credit card / Prepaid card
2.	Bank account services
3.	Theft/Dispute reporting
4.	Mortgages/Loans
5.	Others

<b>Dataset</b>

The dataset consists of 78,313 customer complaints in .json format with 22 features. The data has been converted to a dataframe for processing.

<b>Approach</b>

1.	Data Loading & Preprocessing: Conversion of .json data to a dataframe, followed by text cleaning and preprocessing.
2.	Exploratory Data Analysis (EDA): Detailed analysis to understand the data distribution and extract meaningful insights.
3.	Feature Extraction & Topic Modeling: Use of Non-Negative Matrix Factorization (NMF) to identify patterns and categorize complaints.
4.	Model Building: Training multiple supervised learning models including logistic regression, decision tree, random forest, and naive Bayes.
5.	Model Evaluation: Comparison of models based on accuracy and other evaluation metrics to select the best-performing model.

<b>Results</b>

•	Logistic Regression: Achieved the highest accuracy of 93%.

•	Decision Tree: Accuracy of 76%.

•	Random Forest: Accuracy of 71%.

•	Naive Bayes: Accuracy of 37%.


<b>Impact</b>

The automated classification system significantly reduces response times and improves customer satisfaction by ensuring complaints are quickly routed to the appropriate departments. This also provides valuable insights for continuous service improvement.


<b>Future Work</b>

•	Fine-tuning the models for better accuracy.

•	Exploring additional NLP techniques for feature extraction.

•	Expanding the dataset for more comprehensive analysis.



<b>Technology Used</b>

<b>Programming Languages</b>

•	Python: The primary programming language used for data processing, analysis, and model building.

<b>Libraries and Frameworks</b>

•	Pandas: For data manipulation and analysis.

•	NumPy: For numerical computations.

•	Scikit-learn: For machine learning algorithms, including logistic regression, decision tree, random forest, and naive Bayes.

•	NLTK: For natural language processing tasks such as text preprocessing.

•	SpaCy: For advanced NLP tasks and text processing.

•	Matplotlib & Seaborn: For data visualization and exploratory data analysis.

•	Scikit-learn: For feature extraction, model building, and evaluation.

•	Non-Negative Matrix Factorization (NMF): For topic modeling and identifying patterns in text data.

<b>Development Environment</b>

•	Jupyter Notebook: For interactive development and visualization of the analysis and model building process.

•	Google Colab: For leveraging GPU resources to speed up model training and evaluation.

<b>Tools</b>

•	Git: For version control and collaboration.

•	GitHub: For repository hosting and project management.

<b>Data</b>

•	JSON: The dataset provided was in JSON format, which was converted to a Pandas dataframe for easier processing.

<b>Acknowledgments</b>

•	UpGrad and IIIT Bangalore for providing the platform and resources.

•	Mentors and peers for their guidance and support.

<b>Conclusion</b>

This project demonstrates the potential of NLP in automating customer support systems and driving innovation in the financial sector. Contributions and suggestions are welcome!
