# Optimizing school routes with Machine Learning

This is a ML project to optimize the way school routes users are assigned to buses
by implementing the K-means-constrained Cluster Algorithm.

The first part of this project required to work on the database by standardizing the 
address information in order to use the Google API to obtain latitude and longitude 
coordinates of every user. This standardizing is done taking advantage of Natural 
Language Processing tools.

The second step is to define sectors where users are going to be distributed among
the different available vehicles. 

The third step is to run the K-means-constrained algorithm defining the minimun and
maximun number of users per vehicle. As a result, every cluster turns out to be the 
group of users ready to be assigned to a school route.
