# Learning what factors lead HeartDisease
author: Nanping LI

# Health Problem:
What factors lead HeartDisease?

# Data
Our target is categorical value to determine whether the patience have heartDisease or not, this is a classification problem.

# Results:

![age](https://user-images.githubusercontent.com/79428800/186811573-8c95a056-2b87-4912-bcfb-d07f6bf2e371.png)
HeartDisease risk increases as age increases from 50 to 60.

![RestingBP](https://user-images.githubusercontent.com/79428800/186811687-bfbc7c1d-781e-439b-9e1e-f761f14b82be.png)
the value of 200 and 0 is good for non-heartDisease but others.

![Cholesterol](https://user-images.githubusercontent.com/79428800/186811637-b33a5e50-cb3a-43a7-ab13-935751a5eb5f.png)

![MaxHR](https://user-images.githubusercontent.com/79428800/186811664-19c42755-6fc6-48f9-8c91-87dec7f269ce.png)
The value of 120 of MaxHR has great distribution for heartDisease whereas maxhr increases heartDisease rate decreases.

![old peak](https://user-images.githubusercontent.com/79428800/186811676-4185497b-5161-4df2-ba07-422e42377d30.png)
Oldpeak and heartdisease have postive relationship, old peak rate increases and heartDisease rate increases.








# Model:
KNN has best performance in this data set because False Negtive is more problematic in the data set, which knn reduces false negtive rate in order to get treatment for real patiences. 
