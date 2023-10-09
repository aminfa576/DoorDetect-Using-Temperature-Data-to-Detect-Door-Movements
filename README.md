# DoorDetect: Using Temperature Data to Detect Door Movements

## Overview
DoorDetect is a project developed as part of the Statistical Machine Learning module in the MSc Data Analytics course at Aston University. It utilizes temperature readings from four sensors placed in a room to infer door movements. The project applies Principal Component Analysis (PCA) and K-Means clustering to highlight temperature variations indicative of door activity, providing a unique approach to environmental monitoring in enclosed spaces.
 
## Tasks
The project was structured around the following key tasks:
1. **Data Visualization**: Temperature readings plotted against time for preliminary analysis.
2. **PCA Analysis**: PCA applied to retain components accounting for 93% of data variance, with principal components plotted against time.
3. **Sensor Comparison**: Comparison of readings between sensors on the same side of the room.
4. **K-Means Clustering**: Execution of K-Means clustering for k values of 2 to 5, with silhouette score as the selection criterion for optimal k.
5. **Final Analysis**: Clustering results analyzed to deduce if a door was opened during measurement.

## Dataset
The dataset, `room-temperature.csv`, contains timestamped temperature readings from four sensors: Front Left, Front Right, Back Left, and Back Right.

## Technologies and Libraries
- Python
- Pandas
- Matplotlib
- scikit-learn


## Conclusion
DoorDetect successfully identified potential door movements by analyzing temperature readings and clustering data points into distinct groups. The project demonstrated the effective application of PCA and K-Means clustering techniques to discern patterns within the temperature data, providing valuable insights into environmental changes within the monitored room. The findings from this project suggest potential applications in security, energy management, and smart building solutions, showcasing the practical implications of data-driven decision-making processes in various domains.

