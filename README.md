# Wine-Quality-Prediction
 
**Project Overview**  
This project predicts the quality of red wine using machine learning techniques. The dataset, `winequality-red.csv`, contains various chemical properties of red wine, including acidity, alcohol content, and other features that influence its quality. The task is to classify the wine quality as either "good" (quality >= 7) or "bad" (quality < 7), using the Random Forest Classifier model. The project involves data preparation, exploratory data analysis (EDA), model training, and evaluation.

**Technical Highlights**  
- **Data Preprocessing**: The dataset is cleaned by handling missing values (none in this case), and the target variable is binarized (good or bad quality wine).
- **Libraries Used**: 
  - `pandas` for data manipulation.
  - `numpy` for numerical operations.
  - `matplotlib` and `seaborn` for visualization.
  - `scikit-learn` for model training and evaluation.
- **Model**: Random Forest Classifier.
- **Performance**: The model achieves an accuracy of approximately 89.79% on the test set, with good precision and recall scores.

**Purpose and Applications**  
The purpose of this project is to classify red wine into two categories based on its quality. It can be useful in the wine industry for quality control and grading purposes. Potential applications include:
- **Wine Quality Assessment**: Automatically categorizing wine based on chemical properties.
- **Wine Industry Automation**: Assisting producers in ensuring consistent quality in their products.
- **Consumer Recommendations**: Helping consumers select wines with a desired quality based on chemical composition.

**Installation**  
To set up and run the project, follow these steps:
1. **Clone the repository**:
   ```bash
   git clone https://github.com/BhaveshBhakta/Wine-Quality-Prediction-Using-ML.git
   ```
2. **Navigate to the project directory**:
   ```bash
   cd Wine-Quality-Prediction-Using-ML
   ```
3. **Run the jupyter notebook**:

**Collaboration**  
Contributions are welcome! Feel free to fork the repository, make improvements, and submit a pull request.
