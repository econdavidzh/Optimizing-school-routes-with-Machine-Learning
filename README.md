# Optimizing school routes with Machine Learning


This is a ML project to optimize the way school routes users are assigned to buses
by implementing the K-means-constrained Cluster Algorithm.

The first part of this project required to work on the database by standardizing the 
address information in order to use the Google API to obtain latitude and longitude 
coordinates of every user. This standardizing is done taking advantage of Natural 
Language Processing tools.

![Captura de pantalla 2021-08-26 a la(s) 4 36 17 p  m](https://user-images.githubusercontent.com/82787004/133240388-e3462a19-9c2d-495b-9f0e-002d294fed23.png)

The second step is to define sectors where users are going to be distributed among
the different available vehicles. 

![Captura de pantalla 2021-08-26 a la(s) 4 42 24 p  m](https://user-images.githubusercontent.com/82787004/133240474-2b05a3b5-99eb-419f-8d2a-2571e78c0f79.png)

The third step is to run the K-means-constrained algorithm defining the minimun and
maximun number of users per vehicle. As a result, every cluster turns out to be the 
group of users ready to be assigned to a school route.

Before (colors represent vehicles):

![Captura de pantalla 2021-08-26 a la(s) 4 15 09 p  m](https://user-images.githubusercontent.com/82787004/133240796-46b85792-98d9-4cb9-9638-a504a6abc5b5.png)

After (colors represent vehicles):

![Captura de pantalla 2021-08-26 a la(s) 4 15 17 p  m](https://user-images.githubusercontent.com/82787004/133240834-ba74dc6a-5e2a-4727-96f8-46cc4b7d5972.png)
