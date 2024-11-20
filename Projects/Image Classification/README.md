# Image Classification Project

This project demonstrates an end-to-end image classification pipeline using OpenCV, pre-trained models, and a custom UI. It classifies images of cricketers into five categories: Jasprit Bumrah, KL Rahul, Rohit Sharma, Sachin Tendulkar, and Virat Kohli.

## Technologies Used

- **Python**: Primary language for development.
- **Numpy & OpenCV**: Used for data cleaning and image processing.
- **Matplotlib & Seaborn**: For data visualization.
- **Sklearn**: Used for model building and evaluation.
- **Jupyter Notebook, Visual Studio Code, PyCharm**: Integrated Development Environments (IDEs) used for development.
- **Python Flask**: Backend server for handling HTTP requests and serving predictions.
- **HTML/CSS/JavaScript**: For the user interface and frontend development.

## Project Structure

### Root Directory
- **`class_dictionary`**: Stores the mapping of classes to their respective labels.
- **`saved_model.pkl`**: Serialized model file for predictions.
- **`sportify.ipynb`**: Jupyter Notebook for exploratory data analysis and training.

---

### `model/`
1. **Dataset**:
    - Contains subfolders for each cricketer's images: `bumrah`, `rahul`, `rohit_sharma`, `sachin_tendulkar`, `virat_kohli`.
    - **`cropped/`**: Pre-processed and cropped versions of the images.
2. **`opencv/`**: Scripts for using OpenCV in image processing.
3. **`test_images/`**: Test images for validating the model.
4. **`requirements.txt`**: Lists dependencies required for the project.

---

### `server/`
- **`artifacts/`**: Stores intermediate outputs and final model artifacts.
- **`test_images/`**: Test images used for server validation.
- **`server.py`**: Backend server to handle classification requests.
- **`util.py`**: Utility functions for image processing and prediction.
- **`wavelet.py`**: Wavelet transformation script for image enhancement.

---

### `UI/`
- **`images/`**: Static images used in the web application.
- **`test_images/`**: Test images displayed on the UI.
- **`app.html`**: Main HTML file for the user interface.
- **`app.css`**: Stylesheet for the UI.
- **`app.js`**: JavaScript logic for interacting with the backend.
- **`dropzone.min.css`**: Styling for file upload drag-and-drop functionality.
- **`dropzone.min.js`**: Library for drag-and-drop file uploads.

---

## About
This project integrates machine learning, image processing, and web development to classify cricket players based on their photos. It includes a trained classification model, a backend server for predictions, and a web-based user interface for interaction.

---

**Author**: Priyanka 
**Contact**: priyankadarshanam2000@gmail.com
