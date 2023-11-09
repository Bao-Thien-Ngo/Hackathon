# Hackathon
## Project Description
The goal of this project was create an real-time anomaly detection in surveillance video application with high accuracy. Some features we are aim to implement were recording of video clips and alert notifications.

## Team Member
- Feng Zheng - fengz4dt@gmail.com
- Bao Ngo - bndbv@umsystem.edu

## Project Overview
[Project Overview](https://youtu.be/NfLOfrISgSA)

## Data Source
For this project, we will utilize the [UCF Crime Dataset](https://www.dropbox.com/sh/75v5ehq4cdg5g5g/AABvnJSwZI7zXb8_myBA0CLHa?dl=0).
The UCF-Crime Dataset contains a collection of surveillance videos capturing anomalous and normal activities. Each video clip is labeled with information about the type of anomalous event or normal, providing a suitable foundation for training and evaluating our real-time anomaly detection system.

<p align="center">
  <img width="600" alt="image" src="https://github.com/Bao-Thien-Ngo/Hackathon/assets/46905932/cff800ea-27ea-4b03-b706-6a63ed974f0c">
</p>

After applying I3D Feature Extraction, we got our new [Dataset](https://mega.nz/folder/Pw1hlAwa#D7dWaoMUqWBp0vtUa9tIGw)

## Visualization
### ROC Curve
Following previous works on anomaly detection, we use the receiver operating characteristic (ROC) curve and the corresponding area under the curve (AUC) to evaluate the performance of our method.  
Our AUC is 76.23 which is higher than the AUC in the paper conducted at UCF (75.41.)
<p align="center">
  <img width="450" height="300" alt="image" src="https://github.com/Bao-Thien-Ngo/Hackathon/assets/46905932/e5ce0f91-fbef-4409-a876-786e75dc99c0">
</p>
