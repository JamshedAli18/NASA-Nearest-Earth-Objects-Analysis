# 🚀 Nearest Earth Objects (NEOs) Analysis 🌌

This project focuses on analyzing Near-Earth Objects (NEOs) using machine learning techniques to predict their potential hazard levels. The project involves data exploration, preprocessing, and modeling using a Random Forest classifier.

## 📁 Project Structure

- **data/**: Contains the dataset of Near-Earth Objects.
- **notebooks/**: Jupyter notebooks detailing each step of the analysis.
- **scripts/**: Python scripts used for data preprocessing, modeling, and visualization.
- **results/**: Output results, including model performance metrics and visualizations.
 
## 🔍 Data Exploration

Explored key attributes of NEOs, such as:
- **Absolute Magnitude**
- **Estimated Diameter (Min & Max)**
- **Relative Velocity**
- **Miss Distance**

## 🔧 Data Preprocessing

1. **Imputation**: Missing values in critical columns were handled using `SimpleImputer`.
2. **Scaling**: Features were normalized to enhance model performance and stability.

## 🌳 Modeling

- **Model**: A Random Forest classifier was implemented to predict the potential hazard levels of NEOs.
- **Evaluation**: Model performance was assessed using confusion matrices and visualized using `seaborn`.

## 🛠️ Tools Used

- **Python** 🐍
- **Pandas** 📊
- **Seaborn** 📉
- **Scikit-learn** 🔍

## 📊 Visualizations

- Pair plots for understanding relationships between features.
- Confusion matrix to evaluate the performance of the Random Forest classifier.

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/NEOs-analysis.git
