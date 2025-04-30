# Car Price Prediction Web Application Using Linear Regression

This project is a web application that predicts car prices using a pre-trained Linear Regression model. The model is trained on a dataset of car features (e.g., mileage, year, company) sourced from Quikr, a marketplace. The application is built with Flask, allowing users to input car details and receive price predictions. It includes data analysis, model training, and deployment on Vercel.

## Overview
The project consists of the following components:
1. **Data Collection**: Two datasets (`quikr_car.csv` and `Cleaned_Car_data.csv`) containing car attributes and prices.
2. **Data Analysis**: Jupyter Notebook (`QuikrAnalysis.ipynb`) and Python script (`QuikrAnalysis.py`) for data exploration and preprocessing.
3. **Model Training**: A Linear Regression model (`LinearRegressionModel.pkl`) trained on the cleaned dataset.
4. **Web Application**: A Flask app (`application.py`) with HTML/CSS templates for user input and price prediction.
5. **Deployment**: Configured for deployment on Vercel (`vercel.json`).

## Contents
- `static/css`: CSS files for styling the web application.
- `templates`: HTML templates for the Flask app.
- `Cleaned_Car_data.csv`: Preprocessed dataset used for training the model.
- `LinearRegressionModel.pkl`: Pre-trained Linear Regression model for price prediction.
- `QuikrAnalysis.ipynb`: Jupyter Notebook for data analysis and model training.
- `QuikrAnalysis.py`: Python script version of the data analysis.
- `README.md`: This documentation file.
- `application.py`: Flask application for the web interface.
- `quikr_car.csv`: Original dataset sourced from Quikr.
- `requirements.txt`: List of Python dependencies.
- `vercel.json`: Configuration for Vercel deployment.

## Setup Instructions
1. **Clone the Repository**:
   - Run `git clone https://github.com/yourusername/car-price-prediction.git` in your terminal.
2. **Install Dependencies**:
   - Ensure Python 3.x is installed.
   - Install dependencies from `requirements.txt`:                                                                                            - Common dependencies include `flask`, `scikit-learn`, `pandas`, `numpy`, `jupyter` (for the notebook).
3. **Run the Flask Application Locally**:
- Navigate to the project directory.
- Run the Flask app:
- - Open your browser and go to `http://localhost:5000` (or the port specified in the console).
4. **Use the Web Interface**:
- Enter car details (e.g., company, year, mileage) in the form.
- Submit to get the predicted price.
5. **Explore the Analysis**:
- Open `QuikrAnalysis.ipynb` in Jupyter Notebook to view the data analysis and model training steps:
  
## Deployment on Vercel
1. **Install Vercel CLI**:
- Run `npm install -g vercel` to install the Vercel CLI.
2. **Deploy the App**:
- In the project directory, run:
- - Follow the prompts to deploy the app.
- The `vercel.json` file configures the deployment settings (e.g., Flask routing).
3. **Access the App**:
- Vercel will provide a live URL (e.g., `https://your-app-name.vercel.app`).

## Usage
- Use the web interface to predict car prices by entering details like company, year, and mileage.
- Modify `application.py` to add new features or adjust the prediction logic.
- Retrain the model by updating `QuikrAnalysis.ipynb` or `QuikrAnalysis.py` with new data.

## Troubleshooting
- **Flask Errors**: Ensure all dependencies are installed (`pip install -r requirements.txt`) and the port (e.g., 5000) is free.
- **Model Issues**: If predictions are inaccurate, check `LinearRegressionModel.pkl`. Retrain using `QuikrAnalysis.ipynb` with updated data.
- **Vercel Deployment**: Verify `vercel.json` settings and ensure Flask is compatible with Vercel’s serverless environment.

## Contact
Have questions or suggestions? Reach out to  email me at educationarhum@gmail.com.
LinkedIn: https://www.linkedin.com/in/arhumkhan049/

## License
This project is licensed under the MIT License - see the [LICENSE](./LICENSE) file for details.
   
