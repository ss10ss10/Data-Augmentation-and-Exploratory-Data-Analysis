# Data Augmentation and Exploratory Data Analysis
### This study aims to find whether the effects of simple aritmetic operations on numerical data fields keep the trends in the original data or not and whether these arithmetic operations are a good way to augment data.
##### The dataset used is the ```Student Study Hours``` dataset from Kaggle: https://www.kaggle.com/datasets/himanshunakrani/student-study-hours?resource=download
- Column1: Number of hours studied
- Column2: Marks received

```Data```

![image](https://user-images.githubusercontent.com/64100540/188333065-75720a63-e245-48b2-8bc2-521c3abf6472.png)


## Data Augmentation
### A total of 5 arithmetic operations have been carried out on the data
- Multiplying by 10: ```Data1```
  - ![image](https://user-images.githubusercontent.com/64100540/188333108-15aaac84-cab8-4678-a0ab-57b0741d677d.png)
- Dividing by 10: ```Data2```
  - ![image](https://user-images.githubusercontent.com/64100540/188333143-ce7dde30-00d1-4bdb-a694-bad6821c8060.png)
- Taking the square of the data: ```Data3```
  - ![image](https://user-images.githubusercontent.com/64100540/188333174-63f79134-551f-4447-adb5-4d6209022e44.png)
- Taking the square root of the data: ```Data4```
  - ![image](https://user-images.githubusercontent.com/64100540/188333217-bf9795b2-995e-4c8c-84f6-273bd877f723.png)
- Taking the common logarithm of the data: ```Data5```
  - ![image](https://user-images.githubusercontent.com/64100540/188333224-4a530ffd-8dea-4c15-be32-d740fea90eef.png)<br >

```Note:``` after these operations were carried out, the arrays were concatenated together and then randomly shuffled before being turned into a Data Frame<br >

### Final Data (34 out of 174 rows shown)
![image](https://user-images.githubusercontent.com/64100540/188335118-31820921-c40a-4c0f-865d-388828abe9b8.png)


## Exploratory Data Analysis
### The ```ProfileReport``` functionality in the ```pandas_profiling``` module was used to generate the reports on the new data
You can find the generated reports and the code base in the repository.
