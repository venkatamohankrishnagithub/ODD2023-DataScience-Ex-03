# ODD2023-DataScience-Ex-03


## AIM:
To read the given data and perform the univariate analysis with different types of plots.

## ALGORITHM:
#### STEP 1: 
   Read the given data.
#### STEP 2: 
   Get the informations and type of datas.
#### STEP 3: 
   Count the values using value_counts().
#### STEP 4:
   Describe the dataframe.
#### STEP 5: 
   Do plots like boxplots,countplot,distribution plot,histogram plot.

## PROGRAM:

### Developed by:chadalawada jaswanth
### Reference number:212221040030

### diabetes.csv
```
import pandas as pd
df=pd.read_csv("/content/diabetes.csv")
df
df.info()
df.dtypes
df['DiabetesPedigreeFunction'].value_counts()
df.describe()
import seaborn as sns
sns.boxplot(x='SkinThickness',data=df)
sns.countplot(x="SkinThickness",data=df)
sns.distplot(df['SkinThickness'])
sns.histplot(x="SkinThickness",data=df)
df.skew()
sns.histplot(x='Insulin',data=df)
sns.distplot(df['BloodPressure'])
df.kurtosis()
sns.boxplot(x='Insulin',data=df)
sns.boxplot(x='SkinThickness',data=df)
```
### employeesal.csv
```
import pandas as pd
df=pd.read_csv("/content/employeesal.csv")
df
df.info()
df.dtypes
df['Salary'].value_counts()
df.describe()
import seaborn as sns
sns.boxplot(x='Experience_Years',data=df)
sns.countplot(x="Experience_Years",data=df)
sns.distplot(df['Experience_Years'])
sns.histplot(x="Experience_Years",data=df)
df.skew()
sns.histplot(x='Salary',data=df)
sns.distplot(df['ID'])
df.kurtosis()
sns.boxplot(x='Salary',data=df)
sns.boxplot(x='Experience_Years',data=df)
```
### SuperStore.csv
```
import pandas as pd
df=pd.read_csv("/content/SuperStore.csv")
df
df.info()
df.dtypes
df['Sales'].value_counts()
df.describe()
import seaborn as sns
sns.boxplot(x='Postal Code',data=df)
sns.countplot(x="Postal Code",data=df)
sns.distplot(df['Postal Code'])
sns.histplot(x="Postal Codes",data=df)
df.skew()
sns.histplot(x='Sales',data=df)
sns.distplot(df['Postal Code'])
df.kurtosis()
sns.boxplot(x='Sales',data=df)
sns.boxplot(x='Row ID',data=df)
```

## OUTPUT:

### For diabetes.csv file
#### Data frame
![Screenshot 2023-09-22 183010](https://github.com/Yuvaranithulasingam/ODD2023-DataScience-Ex-03/assets/121418522/6af78936-64b1-4fc0-bf73-4059c3eface9)

#### Data information
![Screenshot 2023-09-22 183050](https://github.com/Yuvaranithulasingam/ODD2023-DataScience-Ex-03/assets/121418522/9814aa52-1d96-4596-9931-8beb8034f3b5)

#### Data type and value_count
![image](https://github.com/Yuvaranithulasingam/ODD2023-DataScience-Ex-03/assets/121418522/b5996596-252c-408b-a841-d3c874211a06)

#### Describing a data
![Screenshot 2023-09-22 183505](https://github.com/Yuvaranithulasingam/ODD2023-DataScience-Ex-03/assets/121418522/751fbe9e-7ac8-44f9-9057-9c92701b3e82)

#### Boxplot
![image](https://github.com/Yuvaranithulasingam/ODD2023-DataScience-Ex-03/assets/121418522/8b547231-a9e2-4164-82c4-9c3e5334412a)

#### Countplot
![image](https://github.com/Yuvaranithulasingam/ODD2023-DataScience-Ex-03/assets/121418522/5214963a-77f0-433b-8d1f-8415ee25f248)

#### Distribution plot
![image](https://github.com/Yuvaranithulasingam/ODD2023-DataScience-Ex-03/assets/121418522/d288ffb7-ece3-4fe2-b74b-32c092ffb7d3)

#### Histogram plot
![image](https://github.com/Yuvaranithulasingam/ODD2023-DataScience-Ex-03/assets/121418522/cd3a24a5-9d8a-4101-ac6f-a00cc083e272)

#### Skewness
![image](https://github.com/Yuvaranithulasingam/ODD2023-DataScience-Ex-03/assets/121418522/10c69a52-ff83-4a82-87b2-2e375f40f86d)

![image](https://github.com/Yuvaranithulasingam/ODD2023-DataScience-Ex-03/assets/121418522/736c7d87-53e8-45c7-b353-2a9b10382f3e)

![image](https://github.com/Yuvaranithulasingam/ODD2023-DataScience-Ex-03/assets/121418522/6c90cf85-3320-41e4-b7b8-7c1dd5efb455)

#### Kurtosis
![image](https://github.com/Yuvaranithulasingam/ODD2023-DataScience-Ex-03/assets/121418522/95f82700-23a1-44be-adaa-74eab7e6a1ec)

![image](https://github.com/Yuvaranithulasingam/ODD2023-DataScience-Ex-03/assets/121418522/66aec4c6-bdf7-4a53-914e-d5da52d13648)

### For employeesal.csv file
#### Data frame
![image](https://github.com/Yuvaranithulasingam/ODD2023-DataScience-Ex-03/assets/121418522/a374d247-7afa-4563-9577-2c383a4aaddc)

#### Data information
![image](https://github.com/Yuvaranithulasingam/ODD2023-DataScience-Ex-03/assets/121418522/c53089ef-6ca7-4230-a0d7-82b8b4410180)

#### Data type and value count
![image](https://github.com/Yuvaranithulasingam/ODD2023-DataScience-Ex-03/assets/121418522/bd2de3dc-0b49-4704-9b9d-643caedb0365)

#### Describing a data
![image](https://github.com/Yuvaranithulasingam/ODD2023-DataScience-Ex-03/assets/121418522/b522ee5f-8ef1-4662-9b0f-8ea09ce824d0)

#### Boxplot
![image](https://github.com/Yuvaranithulasingam/ODD2023-DataScience-Ex-03/assets/121418522/6bf734f5-20b0-47c1-b5cb-48b76f23cf14)

#### Countplot
![image](https://github.com/Yuvaranithulasingam/ODD2023-DataScience-Ex-03/assets/121418522/0824f84a-49a7-4fb1-bce4-212b57e9de37)

#### Distributionplot
![image](https://github.com/Yuvaranithulasingam/ODD2023-DataScience-Ex-03/assets/121418522/f75444cc-4bd4-43c4-a842-d82fc1ef4616)

#### Histogramplot
![image](https://github.com/Yuvaranithulasingam/ODD2023-DataScience-Ex-03/assets/121418522/40c3df27-bfd8-47da-9a2a-09c9728e9903)

#### Skewness
![image](https://github.com/Yuvaranithulasingam/ODD2023-DataScience-Ex-03/assets/121418522/d6eeef00-4b63-420e-8c24-b8f594420a9d)

![image](https://github.com/Yuvaranithulasingam/ODD2023-DataScience-Ex-03/assets/121418522/030402f7-ac4c-4032-9633-2409724a15d0)

![image](https://github.com/Yuvaranithulasingam/ODD2023-DataScience-Ex-03/assets/121418522/851fb807-09f7-49be-b059-39f3d883bcc0)

#### Kurtosis
![image](https://github.com/Yuvaranithulasingam/ODD2023-DataScience-Ex-03/assets/121418522/b173998b-280e-48cc-bc59-9c3e7acf648e)

![image](https://github.com/Yuvaranithulasingam/ODD2023-DataScience-Ex-03/assets/121418522/fdb18ca7-7e90-4cca-904e-2a28119607b0)

![image](https://github.com/Yuvaranithulasingam/ODD2023-DataScience-Ex-03/assets/121418522/b5291f36-2421-4087-90b7-81f97532074b)

### For SuperStore.csv file
#### Data frame
![image](https://github.com/Yuvaranithulasingam/ODD2023-DataScience-Ex-03/assets/121418522/294fbf92-583b-467f-981c-f1d3ccd07c8b)

#### Data information
![image](https://github.com/Yuvaranithulasingam/ODD2023-DataScience-Ex-03/assets/121418522/b194209e-4b10-477a-bf1f-2cffd39e16c6)

#### Data type and value count
![image](https://github.com/Yuvaranithulasingam/ODD2023-DataScience-Ex-03/assets/121418522/5e521c68-aeb1-4e30-9fae-bb8cb7e9a547)

#### Describing a data
![image](https://github.com/Yuvaranithulasingam/ODD2023-DataScience-Ex-03/assets/121418522/87041268-79bf-4d04-935c-2dd605182c81)

#### Boxplot
![image](https://github.com/Yuvaranithulasingam/ODD2023-DataScience-Ex-03/assets/121418522/77feacfc-b7ec-49d8-b727-6d7f51bb3221)

#### Countplot
![image](https://github.com/Yuvaranithulasingam/ODD2023-DataScience-Ex-03/assets/121418522/e1d641f6-026e-49bc-a8b7-8153b830df40)

#### Distributionplot
![image](https://github.com/Yuvaranithulasingam/ODD2023-DataScience-Ex-03/assets/121418522/5e41742f-3627-4c18-9af2-eb169c815e7e)

#### Histogramplot
![image](https://github.com/Yuvaranithulasingam/ODD2023-DataScience-Ex-03/assets/121418522/d6895423-a48e-482e-af6a-8344c60244dc)

#### Skewness
![image](https://github.com/Yuvaranithulasingam/ODD2023-DataScience-Ex-03/assets/121418522/bdd08263-c1a4-4dfb-957a-478b3589c0a8)

![image](https://github.com/Yuvaranithulasingam/ODD2023-DataScience-Ex-03/assets/121418522/9708c614-447b-4eb3-87bc-be1668322ea4)

![image](https://github.com/Yuvaranithulasingam/ODD2023-DataScience-Ex-03/assets/121418522/0d7dd25f-830a-418b-9247-58fd12fe3e5f)

#### Kurtosis
![image](https://github.com/Yuvaranithulasingam/ODD2023-DataScience-Ex-03/assets/121418522/01800ada-438b-4a3c-9a80-53c38a0482db)

![image](https://github.com/Yuvaranithulasingam/ODD2023-DataScience-Ex-03/assets/121418522/1b68b4a7-4743-4020-9a4f-c594b07b7c40)

![image](https://github.com/Yuvaranithulasingam/ODD2023-DataScience-Ex-03/assets/121418522/0f5816cb-0560-483e-994b-401fe7d4ce5b)

## RESULT:
Thus we have read the given data and performed the univariate analysis with different types of plots.
