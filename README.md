# Titanic_Classification
This project aims to explore the factors that influenced survival rates among passengers aboard the Titanic. By analyzing passenger data, including socio-economic status, age, and gender, the system seeks to understand the dynamics of survival during the disaster. For instance, historical data suggests that women and children were more likely to survive, indicating the importance of the "Sex" and "Age" features in predicting survival outcomes. Additionally, the "Pclass" feature, representing passenger class, may provide insights into how access to resources affected survival chances. Through machine learning techniques, this project aims to shed light on the key factors that contributed to survival during one of the most tragic maritime incidents in history.

## Dataset
The dataset used in this project provides valuable insights into the passengers aboard the RMS Titanic during its ill-fated maiden voyage in 1912. It includes information about passengers' demographics, family relationships, ticket details, and survival outcomes. Here is a brief overview of the key attributes included in the dataset:

- **PassengerId:** A unique identifier assigned to each passenger.
- **Survived:** Indicates whether a passenger survived (1) or died (0) in the disaster.
- **Pclass:** Represents the passenger class, indicating the socio-economic status of passengers.
- **Name:** The name of the passenger.
- **Sex:** Represents the gender of the passenger.
- **Age:** The age of the passenger at the time of boarding.
- **SibSp:** Indicates the number of siblings or spouses traveling with the passenger.
- **Parch:** Represents the number of parents or children traveling with the passenger.
- **Ticket:** The ticket number associated with the passenger's ticket.
- **Fare:** The fare paid by the passenger for the ticket.
- **Cabin:** Represents the cabin category or number assigned to the passenger, if available.
- **Embarked:** Indicates the port where the passenger embarked from.

This dataset serves as a valuable resource for understanding the demographics and circumstances of the passengers aboard the Titanic, and it provides the foundation for analyzing factors that influenced survival rates during this historic maritime disaster. Through data analysis and machine learning techniques, we aim to gain insights into the factors that contributed to survival and further our understanding of this tragic event.

## Requirements
1. **Python:** 
2. **Libraries:** The following Python libraries are used in this project:
   - pandas (version >= 1.2.0): A powerful data manipulation and analysis library.
   - numpy (version >= 1.20.0): A fundamental package for scientific computing with Python.
   - matplotlib (version >= 3.3.0): A plotting library for creating static, animated, and interactive visualizations.
   - seaborn (version >= 0.11.0): A data visualization library based on matplotlib, providing a high-level interface for drawing attractive and informative statistical graphics.
   - scikit-learn (version >= 0.24.0): A machine learning library containing various classification, regression, and clustering algorithms.
   - imbalanced-learn (version >= 0.8.0): A library for dealing with imbalanced datasets in machine learning.
   - xgboost (version >= 1.3.0): A scalable and accurate implementation of gradient boosting machines.
3. **Jupyter Notebook or Google Colab:** The project files are typically written in Jupyter Notebook format (.ipynb) or Google Colab environment.

### Installation

1. To install the required Python libraries, run the following command:
   ```
   pip install pandas numpy matplotlib seaborn scikit-learn imbalanced-learn xgboost
   ```

2. If using Jupyter Notebook or Google Colab, no additional installation is required.

## Usage

1. Clone the repository or download the project files from GitHub.
2. Open the Jupyter Notebook (.ipynb) files in Jupyter Notebook or Google Colab.
