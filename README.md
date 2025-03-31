

# Disease Predictor

Disease Predictor is a Flask-based web application that uses machine learning algorithms to predict various diseases. Currently, the application can predict the following:
- Diabetes
- Heart Disease
- Parkinson's Disease

This project aims to provide users with an easy-to-use interface for entering medical data and receiving predictions quickly and accurately.

## Features
- User-friendly web interface.
- Integrated machine learning models for accurate disease predictions.
- Supports predictions for multiple diseases.

---

## Getting Started

### Prerequisites
Ensure you have Python installed on your computer. You can download it from [Python's official website](https://www.python.org/).

### Clone the Repository
```bash
git clone https://github.com/yourusername/disease-predictor.git
cd disease-predictor
```

### Create a Virtual Environment
To ensure that the application runs seamlessly, it is recommended to set up a virtual environment:
```bash
python -m venv venv
```
Activate the virtual environment:
- On Windows:
  ```bash
  venv\Scripts\activate
  ```
- On macOS/Linux:
  ```bash
  source venv/bin/activate
  ```

### Install Dependencies
Install the required dependencies using `pip`:
```bash
pip install -r requirements.txt
```

---

## Running the Application
Start the Flask server by running:
```bash
python app.py
```
The application will be available at `http://127.0.0.1:5000` in your browser.

---

## Deployment
To use this application on another computer, follow these steps:
1. Clone the repository on the target machine.
2. Set up the virtual environment as described above.
3. Install the required dependencies using `requirements.txt`.
4. Run the application using `python app.py`.

---

## Output Images
Below are example screenshots of the application in action:

1. **Home Page**  
  ![HomePage](https://github.com/PukhrajDewangan22/disease_predictor/blob/main/home.jpg)


2.  **Dibaties Page**  
  ![Dibaties Page](https://github.com/PukhrajDewangan22/disease_predictor/blob/main/dibaties.jpg)  
  
3.  **Dibaties Prediction**  
  ![Dibaties Prediction](https://github.com/PukhrajDewangan22/disease_predictor/blob/main/dibatiesfill.jpg)  
  
4. **Parkinson Prediction**  
  ![Parkinson Prediction](https://github.com/PukhrajDewangan22/disease_predictor/blob/main/parkinson.jpg)  
5.   **Heart Prediction**  
  ![Heart Prediction](https://github.com/PukhrajDewangan22/disease_predictor/blob/main/heart.jpg)  



## Technologies Used
- Python
- Flask
- Machine Learning (e.g., Scikit-learn, TensorFlow, or Pillow)
- HTML/CSS for front-end design

---
## Contributing
Contributions are welcome! Please follow these steps:
1. Fork the repository.
2. Create a new branch for your feature.
3. Commit your changes.
4. Submit a pull request.
