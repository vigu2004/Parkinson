Parkinson’s Freezing of Gait Prediction
This project aims to predict Freezing of Gait (FoG) episodes in Parkinson’s disease patients using deep learning on time-series sensor data. The model is based on a hybrid CNN-LSTM architecture that extracts spatial features from accelerometer signals and learns sequential patterns associated with movement disorders.

Approach
The model predicts three key movement states:

Start Hesitation – Detects hesitation before freezing.

Turning – Identifies turning movements, a common trigger for freezing.

Walking – Classifies normal walking behavior.

By analyzing these outputs, a decision rule or a meta-learning model is applied to predict FoG episodes, enabling early intervention and caregiver alerts.

Applications
This system can assist in real-time monitoring of Parkinson’s patients, help neurologists analyze movement patterns, and contribute to wearable device integrations for proactive assistance.