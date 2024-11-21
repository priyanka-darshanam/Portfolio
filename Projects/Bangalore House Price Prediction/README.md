# Bangalore House Price Prediction Project

This project predicts house prices in Bangalore based on various input parameters like location, area, number of bedrooms, etc. The system includes a trained machine learning model, a Flask-based backend server, and a user-friendly web interface for predictions.

## Technologies Used

- **Python**: Core programming language.
- **Numpy & Pandas**: For data preprocessing and handling.
- **Matplotlib & Seaborn**: For data visualization.
- **Sklearn**: Used for model building and evaluation.
- **Jupyter Notebook, Visual Studio Code**: IDEs used for development.
- **Python Flask**: Backend server for handling HTTP requests and serving predictions.
- **HTML/CSS/JavaScript**: For the user interface and frontend development.

## Project Structure

### Root Directory
- **`.idea/`, `.ipynb_checkpoints/`, `.vs/`**: IDE-specific files and checkpoints.
- **`columns.json`**: Metadata containing feature names for the model.
- **`House_price_prediction.ipynb`**: Jupyter Notebook for model training and evaluation.
- **`House_price_prediction.pickle`**: Serialized trained model file.

---

### `Model/`
1. **Data**:
   - Preprocessed datasets for training the model.
2. **`columns.json`**:
   - Stores feature names used by the model.
3. **`House_price_prediction.pickle`**:
   - Contains the trained machine learning model.

---

### `Server/`
- **`server.py`**: Flask-based backend server to handle requests and predictions.
- **`util.py`**: Utility functions for data preprocessing and model prediction.
- **`artifacts/`**: Stores model and metadata files.

---

### `Client/`
- **`app.html`**: Main HTML file for the web interface.
- **`app.css`**: Stylesheet for the user interface.
- **`app.js`**: JavaScript for handling user interactions and communicating with the server.

---

## About
The **Bangalore House Price Prediction Project** applies machine learning to predict house prices based on user input parameters. It demonstrates a complete pipeline from model development to deployment, offering an intuitive interface for predictions.

---

---

**Author**: Priyanka  

**Contact**: priyankadarshanam2000@gmail.com

