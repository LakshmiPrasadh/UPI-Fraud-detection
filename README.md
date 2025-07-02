# UPI-Fraud-detectionimport pickle

# File path for saving the pickle file
pickle_file_path = "UPI Fraud Detection updated.pkl"

# Save the trained XGBoost model to a pickle file
with open(pickle_file_path, 'wb') as file:
    pickle.dump(XGBoost_model, file)

http://localhost:8888/notebooks/Untitled3-Copy1.ipynb#
