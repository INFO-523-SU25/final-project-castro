# Data
-   **[Dataset]**: Description of the dataset 

# Codebook for [chosen] Dataset

## Variable Names and Descriptions:

### Dataset 1. Source: Kaggle - https://www.kaggle.com/datasets/shivamb/machine-predictive-maintenance-classification

The dataset consists of 10 000 data points stored as rows with 14 features in columns

UID: unique identifier ranging from 1 to 10000
productID: consisting of a letter L, M, or H for low (50% of all products), medium (30%), and high (20%) as product quality variants and a variant-specific serial number
air temperature [K]: generated using a random walk process later normalized to a standard deviation of 2 K around 300 K
process temperature [K]: generated using a random walk process normalized to a standard deviation of 1 K, added to the air temperature plus 10 K.
rotational speed [rpm]: calculated from powepower of 2860 W, overlaid with a normally distributed noise
torque [Nm]: torque values are normally distributed around 40 Nm with an Ïƒ = 10 Nm and no negative values.
tool wear [min]: The quality variants H/M/L add 5/3/2 minutes of tool wear to the used tool in the process. and a
'machine failure' label that indicates, whether the machine has failed in this particular data point for any of the following failure modes are true.

### Dataset 2. Source: Kaggle - https://www.kaggle.com/datasets/ziya07/intelligent-manufacturing-dataset/data

The Intelligent Manufacturing Dataset for Predictive Optimization is a dataset designed for research in smart manufacturing, AI-driven process optimization, and predictive maintenance. It simulates real-time sensor data from industrial machines, incorporating 6G network slicing for enhanced communication and resource allocation.

Key Features:
✔ Industrial IoT Sensor Data – Temperature, vibration, power consumption, etc.
✔ 6G Network Performance Metrics – Latency, packet loss, and communication efficiency.
✔ Production Efficiency Indicators – Defect rate, predictive maintenance score, error rate.
✔ Target Column (Efficiency_Status) – Classifies manufacturing efficiency as High, Medium, or Low based on performance metrics.





