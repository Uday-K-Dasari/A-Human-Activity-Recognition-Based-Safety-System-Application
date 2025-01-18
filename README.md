# A Human Activity Recognition-Based Safety System Application
Project Overview:
This project extends Human Activity Recognition (HAR) to create an intelligent safety system for women. Leveraging the UCI HAR dataset for training, the system utilizes advanced deep learning techniques such as Recurrent Neural Networks (RNNs) and Long Short-Term Memory (LSTM) networks to detect abnormal activities. The primary goal is to monitor regular activities and identify potentially dangerous situations, such as sudden falls, erratic movements, or rapid running, which may indicate distress or danger.

When abnormal activity is detected, the system takes proactive measures to ensure the user’s safety. By integrating with Twilio, the system automatically sends an SOS alert to designated emergency contacts along with the user’s real-time location, enabling prompt assistance in critical situations.

Key Features:
1)Activity Monitoring:
Utilizes LSTM-based deep learning models to monitor and classify human activities accurately. Recognizes standard activities such as walking, sitting, and running, as well as abnormal patterns indicating distress.

2)Abnormal Activity Detection: 
Identifies potentially dangerous activities like sudden falls, erratic movement, or running unexpectedly. These activities are flagged as high-risk scenarios.

3)SOS Alert System:
Automatically triggers an alert to emergency contacts when abnormal activity is detected. Sends a real-time location link via Twilio SMS, enabling swift action.

4)UCI HAR Dataset Utilization:
The UCI HAR dataset serves as the foundation for training and testing the model, providing labeled data for human activities. 

5)Real-Time Response:
Ensures rapid detection and notification, minimizing response time during emergencies.

Technical Details
1)Dataset:
The UCI HAR dataset contains sensor data from accelerometers and gyroscopes placed on subjects, capturing a range of physical activities.

2)Deep Learning Models:
Recurrent Neural Networks (RNNs): Used for processing sequential data to identify activity patterns.

3)Long Short-Term Memory (LSTM) Networks: Enhance the model’s ability to capture temporal dependencies and improve accuracy in recognizing complex activity sequences.

4)Integration with Twilio:
Twilio's API is used to send real-time SMS alerts containing the user’s location to emergency contacts.

5)Location Sharing:
Real-time location data is shared via GPS integration, ensuring emergency contacts can pinpoint the user's position.



Project Objectives:
1)Extend Human Activity Recognition (HAR) to detect dangerous and abnormal activities.
2)Create an intelligent safety system for women, leveraging deep learning for reliable activity classification.
3)Automate emergency response with SOS alerts and real-time location sharing.
4)Demonstrate the effectiveness of LSTM networks for complex activity recognition tasks.


Usage
1)Setup:
Clone the repository and install the necessary dependencies listed in requirements.txt.
Configure the Twilio API with your account credentials.

2)Data Preparation:
Use the preprocessed UCI HAR dataset or follow the steps provided in the data folder for dataset preparation.

3)Training the Model:
Run the training script to train the LSTM-based model on the UCI HAR dataset.

4)Real-Time Monitoring:
Deploy the system on a wearable device or smartphone with sensors to collect real-time data.

5)Triggering SOS Alerts:
On detecting abnormal activities, the system will automatically send alerts to emergency contacts along with the user’s live location.


Conclusion
This project demonstrates how advanced machine learning techniques can be applied to enhance safety systems, particularly for women. By combining Human Activity Recognition with real-time alerts, the system provides a reliable and proactive solution for personal safety in critical situations.
