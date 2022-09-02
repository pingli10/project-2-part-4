# Learning what factors lead HeartDisease
author: Nanping LI

# Health Problem:
What factors lead HeartDisease?

# Data
Our target is categorical value to determine whether the patience have heartDisease or not, this is a classification problem.

# Results:

![age (1)](https://user-images.githubusercontent.com/79428800/188195630-e39b7325-012d-4341-b4a0-c2073e638f4e.png)


1.heart disease risk increases as age increase especially from the age between 55 to 60


![sex](https://user-images.githubusercontent.com/79428800/188196346-71da5ab9-ef9a-420b-88af-6fe4868bd884.png)


![sexpief](https://user-images.githubusercontent.com/79428800/188196357-a597f26f-967d-4a7e-95e7-21ee8a4f6041.png)


![sexpiemale](https://user-images.githubusercontent.com/79428800/188196368-ed905111-378c-4d43-8a33-f204b7736b78.png)


2.Male is mainly affected by heart disease.


![chestpaintype](https://user-images.githubusercontent.com/79428800/188196639-4b3bdfa4-1505-4edf-a068-9b55dd15e8e0.png)

![ChestPainType_ASY](https://user-images.githubusercontent.com/79428800/188196684-33be1701-a3e3-44e8-a75e-b11b9ab517b3.png)



3. Patients have asy chest pain and most likely have heart disease.
80% patients with ASY chest pain have heart disease.


![cholesterol](https://user-images.githubusercontent.com/79428800/188196458-76780bdf-9625-4b3c-821b-07616ac58cfb.png)

4.Cholesterol having a value near 200 is good for the heart otherwise low and high cholesterol can cause heart disease.

![fastingbs](https://user-images.githubusercontent.com/79428800/188197236-a56397c5-bd52-40a8-aa40-dd979ee09d93.png)

![fastingbs0](https://user-images.githubusercontent.com/79428800/188197273-076e6b75-f94a-4859-a78f-a631c64bfdff.png)

![fastingbs1](https://user-images.githubusercontent.com/79428800/188197298-3dac9d12-a0a9-4a68-baa5-719ada758b31.png)

5.80 percent patients with value 1 of fastingbs have heart disease.

![maxhr](https://user-images.githubusercontent.com/79428800/188197500-3aa76b48-dfb1-4eb5-9c7d-eb21910c2d4e.png)

6. Higher value of MaxHR shows sign of healthy heart.

![old peak](https://user-images.githubusercontent.com/79428800/186811676-4185497b-5161-4df2-ba07-422e42377d30.png)

Oldpeak and heart disease have a positive relationship, old peak rate increases, and heartDisease rate increases.








# Model:
knn and Random Forest both give the result with acuracy 88 percentage, and both no big differences. However our false Negtive value (true heart disease)is more problemetic;KNN has best performance in this data set because False Negtive is more problematic in the data set, which knn reduces false negtive rate in order to get treatment for real patiences. 

