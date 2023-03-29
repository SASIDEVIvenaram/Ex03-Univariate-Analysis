# Ex03-Univariate-Analysis
# AIM:
To read the given data and perform the univariate analysis with different types of plots.
# ALGORITHM:
## STEP 1:
Read the given data.
## STEP 2:
Get the informations and type of datas.
## STEP 3:
Count the values using value_counts().
## STEP 4:
Describe the dataframe.
## STEP 5:
Do plots like boxplots,countplot,distribution plot,histogram plot

# PROGRAM:
Developed by: SASIDEVI V,
Reference number:212222230136
## diabetes.csv
```
import pandas as pd
data1=pd.read_csv("/content/diabetes.csv")
df1=pd.DataFrame(data1)
df1.info()
df1.dtypes
df1['DiabetesPedigreeFunction'].value_counts()
df1.describe()
import seaborn as sns
sns.boxplot(x='SkinThickness',data=df1)
sns.countplot(x="SkinThickness",data=df1)
sns.distplot(df1['SkinThickness'])
sns.histplot(x="SkinThickness",data=df1)
df1.skew()

```
## SuperStore.csv
```
import pandas as pd
data2=pd.read_csv("/content/SuperStore (1).csv")
df2=pd.DataFrame(data2)
df2.info()
df2.dtypes
df2["Postal Code"].value_counts()
df2.describe()
import seaborn as sns
sns.boxplot(x='Sales',data=df2)
sns.countplot(x="Sales",data=df2)
sns.distplot(df2['Sales'])
sns.histplot(x="Sales",data=df2)
df2.skew()

```
# OUTPUT:
## diabetes.csv
### Info
![ds31](https://user-images.githubusercontent.com/118707332/228567793-5ff87dd4-a635-455f-be26-9097dc30be87.png)


### Datatypes
![ds32](https://user-images.githubusercontent.com/118707332/228567852-72fbf17f-e098-4137-8cf3-3eec0421177f.png)

### Valuecounts
![ds33](https://user-images.githubusercontent.com/118707332/228567901-68977234-abca-416d-ab6f-2fdbd34db384.png)

### Describe
![ds34](https://user-images.githubusercontent.com/118707332/228567938-7833b0eb-f9c1-4bd0-a6d7-3466f73fa1a7.png)

### Boxplot
![ds35](https://user-images.githubusercontent.com/118707332/228568127-5ae364da-eff0-414f-912e-2f01ee288354.png)


### Countplot
![DS36](https://user-images.githubusercontent.com/118707332/228568173-43454e8e-17d3-4a04-9bb9-8fc7d5bbccd0.png)

### Distribution plot
![ds37](https://user-images.githubusercontent.com/118707332/228568204-6adecd74-1751-43ea-adc3-cfa4250d5d6a.png)

### Histogram plot
![ds38](https://user-images.githubusercontent.com/118707332/228568230-78d350ad-1576-4872-9ab3-2c18ab6fa296.png)

### Skew
![ds39](https://user-images.githubusercontent.com/118707332/228568255-cabf4e6a-44b0-41a9-8c17-dbd2e561b3f1.png)
## SuperStore.csv

### Info

![ds310](https://user-images.githubusercontent.com/118707332/228569743-4ed681ff-3955-4755-8c2c-6e2405166f09.png)


### Datatypes
![ds311](https://user-images.githubusercontent.com/118707332/228569800-70ee836a-bfc4-4518-bcbf-727278c16a2b.png)


### Valuecounts
![ds312](https://user-images.githubusercontent.com/118707332/228569823-12827ca8-d2e3-436c-a219-18e6560757b3.png)

### Describe
![ds313](https://user-images.githubusercontent.com/118707332/228569856-335604ea-3809-47d4-b192-6dbd4815abce.png)

### Boxplot
![ds314](https://user-images.githubusercontent.com/118707332/228569899-f17b5508-0a2c-48e5-8e24-f3948d8c58af.png)



### Countplot
![ds315](https://user-images.githubusercontent.com/118707332/228569936-5d5a3754-bad4-43a3-b021-1ee9747ba7be.png)


### Distribution plot

![ds316](https://user-images.githubusercontent.com/118707332/228569960-597797c2-20d7-445e-ae99-8c8e54587ae2.png)

### Histogram plot
![ds317](https://user-images.githubusercontent.com/118707332/228569978-31bcb43e-cb0d-4f17-b977-7d8bdf0802f6.png)


### Skew

![ds318](https://user-images.githubusercontent.com/118707332/228570011-7f994a66-8932-482c-a7c6-dcc320a55af5.png)
# RESULT:
Thus we have read the given data and performed the univariate analysis with different types of plots.


