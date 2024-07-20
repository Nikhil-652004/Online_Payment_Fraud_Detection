# Online_Payment_Fraud_detection
 This project focuses on developing a machine learning-based system to detect fraudulent online payment transactions. Utilizing a logistic regression algorithm, the model analyzes various transaction features such as transaction type, amount, and account balances before and after transactions. The goal is to accurately classify transactions as fraudulent or non-fraudulent, thereby helping financial institutions and e-commerce platforms mitigate financial losses and enhance security. The project employs data preprocessing and feature engineering techniques to improve model accuracy, and it is deployed using Streamlit to provide an interactive and user friendly interface for real-time fraud detection. Through this project, we aim to contribute to a safer online transaction environment by leveraging data-driven approaches to identify and prevent fraudulent activities. 

# How to run the project
1. Clone the repo into a folder(recommended).
2. Check the "fraud.py" file that 
   i. model which is stored in "detector.pkl" was correctly pathed.
   ii. Make sure to install pickle and streamlit library beforehand deployment.
3. Open the command prompt in the cloned folder and type "streamlit run fraud.py". Your entire command prompt should look like "path_to_your_folder>streamlit run fraud.py".
4. Now streamlit automatically opens the localhost website on your default browser. You can view in any another browser by copy pasting the localhost url.
5. Now enter the inputs in the deployment page and Hit "Predict" Button
6. "Voila!!". You are able to deploy the model and use it user-friendly via a browser.



