
# 🌾 Crop Yield Prediction using Machine Learning

This project aims to predict crop yield based on features like crop year, season, crop type, and area using machine learning. The model is built with a Random Forest Regressor and evaluated for accuracy. Additionally, a Gradio-based UI is included to allow users to interact with the model for real-time predictions.

## 🛠️ Tools & Technologies

- **Python** for data processing and model development
- **Pandas** and **NumPy** for data manipulation
- **Scikit-learn** for machine learning
- **Gradio** for building the interactive web interface
- **Pickle** for saving and loading the trained model

## 📊 Dataset
The project uses a crop production dataset (`crop_production.csv`), containing information about:
- **Crop Year**: Year in which the crop was harvested
- **Season**: The season during which the crop was grown (e.g., Kharif, Rabi)
- **Crop**: The type of crop (e.g., Rice, Wheat)
- **Area**: Area in hectares
- **Production**: The yield of the crop (target variable)

## 🚀 How to Run the Project

### 1. Clone the Repository
```bash
git clone https://github.com/Akhilpresdency/crop-yield-prediction.git
cd crop-yield-prediction
```

### 2. Install Dependencies
```bash
pip install -r requirements.txt
```

### 3. Train the Model
Run the following script to train the model and save the trained model and label encoders.
```bash
python model_training.py
```

### 4. Launch the Gradio Interface
```bash
python app_interface.py
```

This will launch a Gradio interface where you can enter crop details and get yield predictions.

### 5. Evaluate the Model
To evaluate the model’s performance using metrics like RMSE, MAE, and R², run:
```bash
python evaluate_model.py
```

## 📈 Model Evaluation Metrics
- **R² Score**: Measures how well the model fits the data
- **RMSE** (Root Mean Squared Error): Measures prediction accuracy
- **MAE** (Mean Absolute Error): Measures average prediction error

## 📁 Files
- **model_training.py**: Script to train the machine learning model
- **app_interface.py**: Script for the Gradio web interface
- **evaluate_model.py**: Script for model evaluation (optional)
- **model.pkl**: Trained model file (saved using Pickle)
- **encoder.pkl**: Label encoder file for encoding categorical features
- **crop_production.csv**: Dataset used for training the model

## Model Download
Download the trained model from [Google Drive](https://drive.google.com/file/d/1130aHuPSI1hyupITzbggfibNQ4uGA6LL/view).


## 🤖 Author
Your Name – [LinkedIn](https://www.linkedin.com/in/akhil-y-b97b55289/)

## License
This project is licensed under the MIT License – see the [LICENSE](LICENSE) file for details.

## 🤝 Contributing
Contributions are welcome! Please feel free to open an issue or submit a pull request. For major changes, please open an issue first to discuss what you would like to change.
