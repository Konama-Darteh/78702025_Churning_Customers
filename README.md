# Konama_Churning_Customers
#The below link leads to the recorded video

https://youtu.be/S_j19lByWj4

# The fuctionalities of the Code
The app starts with a user-friendly title, "Churn Prediction App."
Users can interact with intuitive sliders and selection boxes to input information such as tenure, monthly charges, total charges, contract type, online security, payment method, tech support, internet service, online backup, and gender.

# Prediction Button:
A button labeled "Predict Churn" allows users to trigger the prediction process.
Prediction Display:

After clicking the "Predict Churn" button, the app transforms the user's input, encodes categorical variables, scales the input, and feeds it into a pre-trained neural network model.
The app then displays the churn probability and a user-friendly prediction message. If the churn probability is equal to or greater than 0.5, it predicts "Yes, Customer will Churn"; otherwise, it predicts "Customer will not Churn."
Categorical variables like contract type, online security, payment method, etc., are encoded to numerical values for model input. This is done using a LabelEncoder to ensure the model can process the data correctly.

# Scalability:
The app is designed to handle categorical variables gracefully by using a LabelEncoder. This ensures the model receives appropriately preprocessed input.
User-Friendly Display:
The app utilizes the Streamlit framework to create a user-friendly interface with sliders, selection boxes, and clear result displays.

# Main Function Execution:
The main functionality is encapsulated in the main() function, which is executed when the script is run.

# Compatibility Check:
The app checks whether it is the main script being executed to avoid unintended execution when imported as a module.
The results are not only presented as a probability but also interpreted into a plain-language prediction, making it more understandable for users.
