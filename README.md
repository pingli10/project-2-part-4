# Learning what factors lead HeartDisease
author: Nanping LI

# Health Problem:
What factors lead HeartDisease?

# Data
Our target is categorical value to determine whether the patience have heartDisease or not, this is a classification problem.

# Results:

![age (1)](https://user-images.githubusercontent.com/79428800/188195630-e39b7325-012d-4341-b4a0-c2073e638f4e.png)


(Age)1.heart disease risk increases as age increase especially from the age between 55 to 60



![sex](https://user-images.githubusercontent.com/79428800/188196346-71da5ab9-ef9a-420b-88af-6fe4868bd884.png)

![sexpief](https://user-images.githubusercontent.com/79428800/188196357-a597f26f-967d-4a7e-95e7-21ee8a4f6041.png)

![sexpiemale](https://user-images.githubusercontent.com/79428800/188196368-ed905111-378c-4d43-8a33-f204b7736b78.png)

(Sex)2.Male is mainly affected by heart disease;63 percent of heart disease patients are male, and 26 percent of heart disease patients are female.



![chestpaintype](https://user-images.githubusercontent.com/79428800/188196639-4b3bdfa4-1505-4edf-a068-9b55dd15e8e0.png)

![ChestPainType_ASY](https://user-images.githubusercontent.com/79428800/188196684-33be1701-a3e3-44e8-a75e-b11b9ab517b3.png)

(chestpaintype)3. Patients have asy chest pain and most likely have heart disease.
80 percent of ASY chest pain patients have heart disease.



![cholesterol](https://user-images.githubusercontent.com/79428800/188196458-76780bdf-9625-4b3c-821b-07616ac58cfb.png)

(cholesterol)4.Cholesterol having a value near 200 is good for the heart otherwise low and high cholesterol can cause heart disease.



![fastingbs](https://user-images.githubusercontent.com/79428800/188197236-a56397c5-bd52-40a8-aa40-dd979ee09d93.png)

![fastingbs0](https://user-images.githubusercontent.com/79428800/188197273-076e6b75-f94a-4859-a78f-a631c64bfdff.png)

![fastingbs1](https://user-images.githubusercontent.com/79428800/188197298-3dac9d12-a0a9-4a68-baa5-719ada758b31.png)

(fastingbs)5.80 percent of  (1) fastingbs patients have heart disease.



![restingECG](https://user-images.githubusercontent.com/79428800/188200263-b68c3e53-eade-4f06-ae5f-c96836254fdb.png)

![RestingECG_LVH](https://user-images.githubusercontent.com/79428800/188200283-1a45a7fa-cf59-46c4-a41e-f04f9bf721f8.png)

![RestingECG_Normal](https://user-images.githubusercontent.com/79428800/188200294-247dc2c4-1706-49e0-ab24-eda218ce93ee.png)

(restubgECG)6.For RestingECG is ST there's a 66% chance of heart disease.



![maxhr](https://user-images.githubusercontent.com/79428800/188197500-3aa76b48-dfb1-4eb5-9c7d-eb21910c2d4e.png)

(maxhr)7. Higher value of MaxHR shows sign of healthy heart.



![exerciseangina](https://user-images.githubusercontent.com/79428800/188200427-9bae6cd0-a69d-4805-844c-a2feee0cbed0.png)

![ExerciseAngina_N](https://user-images.githubusercontent.com/79428800/188200446-496948f2-868e-43ab-84c5-03576e66a11c.png)

![ExerciseAngina_Y](https://user-images.githubusercontent.com/79428800/188200466-d2d5fff2-d292-4de2-a0dc-8207b34e3d55.png)

(exerciseAngina)8.85 percent of (Y) exerciseangina patients have heart disease



![oldpeak](https://user-images.githubusercontent.com/79428800/188198331-23854b70-8934-4cda-bb59-735b3cece611.png)

(oldpeak)9.Oldpeak and heart disease have a positive relationship; as old peak value increases, and heart disease incidence increases.



![st_slope](https://user-images.githubusercontent.com/79428800/188200585-01a7783c-bcc5-48e0-91a3-ef321d08248d.png)

![ST_Slope_Down](https://user-images.githubusercontent.com/79428800/188200595-2e2cc448-7577-45ea-baab-7587e6906736.png)

![ST_Slope_up](https://user-images.githubusercontent.com/79428800/188200612-3f2408d4-2fb7-4e58-bebd-3f75097f1372.png)

![ST_Slope_Flat](https://user-images.githubusercontent.com/79428800/188200603-bc4b9968-bcb0-4fe1-af7e-0d3cfd46aab3.png)

(st_slope)10.For ST_Slpoe of Flat and Down have high risk (i.e. 83% and 77% respectively) of heart disease whereas for ST_Slope of Up affection risk is low (20%)






# Recomendation:
knn and Random Forest both models give the result with an accuracy of 88 percent, and both models have no big differences. In our data set, negative values are non-heart disease, false negative patients have heart disease but our model considered the false negative labels as non-heart disease patients, so the patients won't get any treatment. To be less harmful, our goal is to reduce false negative values in our ideal model. KNN performed well with the false negative label.

