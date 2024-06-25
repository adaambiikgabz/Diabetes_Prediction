# Diabetes Prediction

This project focuses on predicting diabetes using various machine learning algorithms. The dataset contains features such as age, gender, BMI, cholesterol levels, triglycerides, HDL, LDL, creatinine, and BUN.

## Project Structure
- `data/`: Contains the dataset files.
- `notebooks/`: Jupyter notebooks for data exploration and model training.
- `src/`: Source code for data processing and model building.
- `models/`: Saved machine learning models.
- `README.md`: Project overview and instructions.

## Setup and Installation
1. Clone the repository:
    ```bash
    git clone https://github.com/adaambiikgabz/Diabetes_Prediction.git
    cd Diabetes_Prediction
    ```
2. Create a virtual environment and activate it:
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```
3. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

## Usage
1. Preprocess the data:
    ```bash
    python src/preprocess.py
    ```
2. Train the model:
    ```bash
    python src/train.py
    ```
3. Evaluate the model:
    ```bash
    python src/evaluate.py
    ```

## Results
- Accuracy: 0.798
- Confusion Matrix: 
- Classification Report:

          precision    recall  f1-score   support

       0       0.80      0.87      0.84       604
       1       0.79      0.70      0.74       423

accuracy                           0.80      1027


- Cross-Validation Accuracy Scores: [0.870, 0.848, 0.797, 0.776, 0.786]
- Average Cross-Validation Accuracy: 0.815

## Contributing
Feel free to submit issues and pull requests.

## License
This project is licensed under the MIT License.
