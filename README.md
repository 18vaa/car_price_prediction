# AutoPricer - ML-powered Car Price Prediction

A machine learning-based web application that predicts the price of a car based on its attributes. The data was scraped from QuikR, cleaned, and used to train a Linear Regression model. The system is deployed locally using Flask.

![Demo](https://github.com/18vaa/car_price_prediction/blob/main/assets/demo.png)

## Features
- **Data Collection**: Scraped car data (name, company, year, kilometers driven, fuel type) from QuikR.
- **Data Cleaning**: Processed raw data to handle missing values, outliers, and inconsistencies.
- **Machine Learning**: Used Linear Regression, optimized over 1000 iterations to find the best R2 score.
- **Web Interface**: Built a user-friendly frontend with HTML/CSS.
- **Local Deployment**: Flask backend for local hosting.

## Technologies Used
- Python
- Flask (Backend)
- HTML/CSS (Frontend)
- Scikit-Learn (Linear Regression)
- Pandas (Data Cleaning)

## How to Run Locally

### Prerequisites
- Python 3.x
- pip (Python package manager)

### Installation Steps
1. **Clone the repository**:
   ```{bash}
   git clone https://github.com/18vaa/car_price_prediction.git
   cd car_price_predictor
   ```

#### Create a virtual environment (optional but recommended):

```bash
python -m venv venv
source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
```

#### Install dependencies:

```bash
pip install -r requirements.txt
Run the Flask application:
```
```bash
python app.py
Open the application:
```
Visit http://127.0.0.1:5000 in your browser (or whatever port you have selected)

### Future Scope
- Improved Data Collection: Expand the dataset by scraping more sources (e.g., CarDekho, OLX) for better accuracy.

- Advanced Models: Experiment with other algorithms like Random Forest, XGBoost, or Neural Networks.

- Feature Engineering: Add more relevant features (e.g., mileage, engine type, transmission).

- Deployment: Host the app on cloud platforms like AWS, Heroku, or Render.

- User Accounts: Allow users to save predictions or compare different cars.

- Visualizations: Add graphs to show price trends based on different factors.

- Mobile App: Develop a cross-platform mobile version using Flutter or React Native.
