# Prediction of Traffic Density

**Kodluyoruz - Data Science for Public Good**

In the program carried out in cooperation with The Istanbul Metropolitan Municipality, we developed a model that predicts traffic density, using the **traffic announcements** and **traffic density** data set from The Istanbul Metropolitan Municipality.

![Resim1](https://user-images.githubusercontent.com/17860575/134295688-6a00b374-aa87-4fb7-9dde-bdb1d580609a.png)


Traffic density and traffic announcement data sets  were used for Esenler, Beşiktaş and Kağıthane regions, that contains data from January 2020 to June 2020. In order to determine the target variable; the median of the speed that belongs to traffic announcement rows was taken as the threshold value. Accordingly, if the speed is less than the threshold value, the traffic is classified as heavy, else the traffic is classified as low (there is no traffic density). In the machine learning model created by matching the location and time information in two data sets, the upcoming traffic density information has been tested with Random Forest, XGBoost and Logistic Regression algorithms and the accuracy of the model is estimated 75%.

<img width="943" alt="trafik duyuruları" src="https://user-images.githubusercontent.com/17860575/134297725-0248f825-44d5-4120-8fb5-1362d392da55.png">





# TEAM
- Elif Kurt
- Gizem Göker
- Fazile Akça
- Betül Çelebi
- Berk Sudan
