# ${\color{Red} L1\ Introduction\ to\ ML}$

## $\color{magenta} Course\ Outline$
1. Regression
2. Classification
3. Decision Tree
4. Unsupervised Learning
5. Times Series Forecasting
6. Ensemble Learning
7. Recommender Systems

$\color{magenta} Installing\ Python\ Packages$
1. python.exe -m pip install --upgrade pip
2. pip install -U scikit-learn
3. pip install -U imbalanced-learn
4. pip install category-encoders
5. pip install scikit-surprise

---

## $\color{red}AI\ vs\ ML\ vs\ Data\ Science$

What is AI?

Machines simulate the human intelligence

AI in practice
1. Self driving cars
2. Voice Assistant
3. Ecommerce Recommendation
4. Image recognition
5. Voice recognition
6. Forecasting
7. Fraud detection

$\color{orange} Data\ Science\ - analysis,\ insights,\ predictions,\ mainly\ via\ the\ statistics$

$\color{lime}AI\ -\ Make\ human\ like\ decisions\ from\ data$

$\color{cyan}ML\ -\ Ability\ to\ learn\ without\ being\ explicitly\ programmed\ ->\ Arthur\ Samuel,\ 1959$

---

## $\color{red}Traditional\ vs\ ML\ Approach$
Example of Spam Filter

Traditional approach give the output
ML approach gives you the model.
1. Traditional

	a. “4U”, “credit card”, “free”, and “amazing”

	b. detection algorithm for each of the patterns

	c. test your program

2. ML

    a. automatically learns which words and phrases are good predictors of 
spam by detecting unusually frequent patterns of words.

Issues with traditional approach
- Spammers keep changing the patterns
- ML model can be auto updated via online training and based on user feedback

---

## $\color{red}ML\ Techniques$
1. Classification - assign a label or category to input data.  Eg: Cat and Dog Image, Handwritten digit, Spam.
2. Categorization - grouping entities into predefined classes. Eg: News articles into topics sorting, products sorting.
3. Clustering - grouping similar data points based on their inherent patterns.  Eg: purchase behaviour, songs into genre.
4. Trend Analysis - Time series analysis of data. Eg: Stocks, weather
5. Anomaly detection - unusual data. Eg: Fraud, intrusion

---

## $\color{red}Applications\ of\ ML$
1. Image recognition, OCR, 
2. Robots
3. Data Mining - Association rules
4. Video games - reinforcement learning
5. Text Analysis - sentiment
6. Healthcare - monitoring, drug testing, image analysis

---

## $\color{red}Types\ of\ ML$
1. Supervised Learning

    a. Data + Label
    
    b. classification and regression

2. Un-supervised Learning

	a. Unlabelled data

	b. Clustering, dimensionality reduction and association

3. Reinforcement Learning

    a. Agent + Environment + Actions + Rewards/Punishment

---

## $\color{red}ML\ Pipeline$
```{mermaid}
%%{init: {'theme': 'default'}}%%
flowchart LR
    A[Data Ingest] --> B[Data Pre-processing] --> C[Model Training] --> D[Model Evaluation] --> E[Model Deployment] --> F[Model Monitoring]
```
```{mermaid}
%%{init: {'theme': 'default'}}%%
flowchart LR
    A[Data Pre-processing] --> B[Data Cleaning]
    A[Data Pre-processing] --> C[Data Transformation]
    A[Data Pre-processing] --> D[Data Analysis]
```
---

## $\color{red}EDA$

1.	 Types of Data - Numerical and Categorical
2.	 Continuous and Discrete Numerical Data
3.	 Ordinal and Nominal Categorical Data
4.	 Check for Null Values - Delete rows and columns
5.	 Check for Duplication
6.	 Check for Invalid values
7.	 Impute the missing values
8.	 Check for outliers
9.	 Discard or impute outliers
10.	 Uni, Bi and Multivariate analysis
11.	 Normalize and Standardise
12.	 Convert categorical to numerical
		1. One hot encoding
		2. Label/ordinal encoding
		3. Binary encoding
13.	 Check for data imbalance
14.	 Split the data into training and testing sets.