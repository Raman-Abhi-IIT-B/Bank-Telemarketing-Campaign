# Bank-Telemarketing-Campaign
This code contains all the code as a part of Winter in Data Science. The data has been obtained from https://www.kaggle.com/yufengsui/portuguese-bank-marketing-data-set.<br>


The details of the input variables are as follows:<br>

**age** (Age): Indicates th age of the person<br>
**job** (Job): Indicates the profession of the person<br>
**marital** (Marital Status): Indicates if the person is married.<br>
**education** (Educational Level): Indicates the educational qualification of the person<br>
**default** (Default status): Indicates if the person has credit in default.<br>
**balance** (Balance): Indicates the bank balance<br>
**housing** (Housing Loan Status): Indicates if the person has a housing loan<br>
**loan** (Personal Loan Status): Indicates if the person has a personal loan<br>
**contact** (Mode of contact): Indicates the mode of contact<br>
**day** (Last contact day): Indicates the last contact day of the week<br>
**month** (Last contact month): Indicates the last contact month of the year<br>
**duration** (Last contact duration): Indicates the duration of the last contact in seconds<br>
**campaign** (Number of contacts): Indicates the number of contacts performed during this campaign and for this client<br>
**pdays** (Number of days that passed by after the client was last contacted from a previous campaign)<br>
**previous** (Number of contacts performed before this campaign and for this client)<br>
**poutcome** (Outcome of the previous marketing campaign)<br>
The target variable is y.<br>

The project has been divided into the following sections: 1. Preprocessing the data 2. Exploratory Data Analysis 3. Data Visualization 4. Machine Learning 5. Boosting Models 6. Conclusion and Recommendations<br>


Accuarcy obtained from using different machine learning models include:<br>

**Logistic Regression: 88.7%**<br>
**KNN : 87.63%**<br>
**Decision Tree : 83.34%**<br>

Following this, **XGBoost** was used to boost the model performance. Final **F1 score** obtained from XGBoost was **0.94**.
