# CS-GO-Round-Win-ML

This project predicts the outcome of rounds in the game Counter-Strike: Global Offensive (CS:GO) using machine learning techniques.

## Features

- Data extraction and preprocessing from a custom dataset.
- Exploratory data analysis and visualization.
- Machine learning model training and evaluation (using scikit-learn and TensorFlow).
- Interactive charts and visualizations (compatible with Google Colab).

## Requirements

- Python 3.x
- pandas
- numpy
- matplotlib
- seaborn
- tensorflow
- scikit-learn
- requests

Link to Access the Code

https://colab.research.google.com/drive/1hsSQyvfLFvYu0a9MfM8Sq7kzm8upF5iz?usp=sharing

Install dependencies with:

```sh
pip install pandas numpy matplotlib seaborn tensorflow requests scikit-learn
```

# Results

1- Supervised machine learning algorithm by using K-Nearest Neighbors (KNN)

Result
### KNN:
![KNN](https://github.com/user-attachments/assets/e3e2bf4b-0cf9-42ab-b89c-7f28389cff21)


2- RandomizedSearch

Result
### Randomized Search:
![Randomized Search](https://github.com/user-attachments/assets/488a34f6-638d-4fcd-a756-5a35c03ea61e)

3- Random Forest

Result
### Random Forest:
![Random Forest](https://github.com/user-attachments/assets/285dde50-989e-4187-b7a5-8ba5788ef7d8)

4- TensorFlow Keras

Result
### TensorFlow Keras:
![TensorFlow Keras](https://github.com/user-attachments/assets/551ab6ac-99be-4841-8c69-ad27c77006bf)

Epoch 17 Achieved best Results

![.](https://github.com/user-attachments/assets/f0f81200-f542-475b-b697-e1bc1a64cdc1)

## Usage

1. Place your dataset file as `dataset.txt` in the project directory.
2. Open and run the Jupyter notebook:  
   `CS_GO_Round_Prediction_Model.ipynb`
3. Follow the notebook cells to:
   - Load and preprocess data
   - Explore and visualize features
   - Train and evaluate machine learning models
   - View interactive charts

## Project Structure

- `CS_GO_Round_Prediction_Model.ipynb` — Main Jupyter notebook containing all code, analysis, and visualizations.
- `README.md` — Project documentation.

## Notes

- The notebook is designed for use in Google Colab but can be run locally if all dependencies are installed.
- Interactive charts use Colab-specific features for code generation.

## License

This project is publicly accessible, but the code is not available for reuse or 
modification.