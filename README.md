# Ex03-Univariate-Analysis
# PROGRAM:
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
sns.histplot(x="Glucose",data=df1)
sns.distplot(df1['BloodPressure'])
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
sns.histplot(x="Postal Code",data=df2)
sns.distplot(df2['Row ID'])
```
