# Analysis-Clustering-of-a-Household-s-Electrical-Power-Consumption
Analysis &amp; Clustering of a Household's Electrical Power Consumption
# Problem Statement
Analyze the requirement of electric power and group the houses as per their power consumption.
  
# Dataset Information:
The dataset represents the electric power consumption in the house. The data definition is as follows:
 1. Global_active_power: The global minute-averaged active power of the house (in KW)
 2. Global_reactive_power: The global minute-averaged reactive power of the house (in KW)
 3. Voltage: The minute-averaged voltage of the house (in volt)
 4. Global_intensity: The global minute-averaged current intensity of the house (in ampere)
 5. Kitchen_consumption: The power consumption of the appliances in the kitchen (in watt-hour)
 6. Laundry_consumption: The power consumption of the appliances in the laundry room (in watt-hour)
 7. Other_appliances_consumption: The power consumption of the appliances other than in the kitchen and laundry room (in watt-hour)
 
 # Coclusion
K-means, Hierarchical clustering and DBSCAN was used to get the optimal numbers of clusters.
For the Clusters validation, we have used the Elbow method and Silhouette score. Also we have assigned all the houses in different clusters based on the electrical power consumption.
