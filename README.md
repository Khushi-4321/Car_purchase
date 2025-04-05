# 🚗 Car Purchase Prediction with Logistic Regression 📊

This project dives into the world of machine learning to predict whether someone's going to drive off into the sunset with a brand new car 🌅. We're using the power of Logistic Regression to make these predictions based on the age and salary of individuals. Let's buckle up! 🚀

## 🛠️ Tech Stack

Here are the cool tools and libraries we're using:

* **NumPy**: For all those number crunching tasks. 🧮
* **Pandas**: Because data needs to be organized! 🐼
* **Matplotlib**: To make sense of data with awesome plots. 📈
* **Scikit-learn**: Our machine learning powerhouse! 
    * `model_selection.train_test_split`: To slice and dice our data. ✂️
    * `preprocessing.StandardScaler`: To bring features to the same scale. 
    * `linear_model.LogisticRegression`: The star of the show! 
    * `metrics.confusion_matrix`: To check how well we did. 
    * `metrics.accuracy_score`: To measure our success. 

## 📂 Data

We're using the `car_purchase_data.csv` dataset. It's packed with info on people's age, salary, and their car-buying decisions.

## ⚙️ How It Works

1.  **Libraries**: We kick things off by importing all the necessary libraries. 📚
2.  **Dataset**: Loading the data from `car_purchase_data.csv` using Pandas. 📂
3.  **Splitting**: Dividing the data into training (80%) and testing (20%) sets. ➗
4.  **Scaling**: Scaling age and salary to a standard range. 📏
5.  **Training**: Fitting the Logistic Regression model with the training data. 
6.  **Prediction**:
    * Predicting car purchases for new folks based on age and salary. 🔮
    * Predicting outcomes for the test set.
7.  **Evaluation**:
    * Using a Confusion Matrix to see where we nailed it and where we missed. 
    * Calculating the Accuracy Score to quantify our model's performance. 
8.  **Visualization**: Plotting the results to get a clear picture. 

## 💻 Code

* `logistic_regression.ipynb`: This Jupyter Notebook has all the code. It’s where the magic happens! ✨

## 📁 Files

* `car_purchase_data.csv`: The data that fuels our model. 
* `README.md`: This file! Your guide to the project. 

## 🚀 Get Started

1.  Make sure you have Python 3.x installed. 
2.  Install the required packages:
    
    ```bash
    pip install numpy pandas matplotlib scikit-learn
    ```
    
3.  Put `car_purchase_data.csv` in the same folder as the notebook. 📂
4.  Run `logistic_regression.ipynb` using Jupyter or Google Colab. 

## 📊 Visuals

The notebook has visualizations that show how our model makes decisions. It's super helpful to see! 👀


## 📄 License

This project is open-source and available under the [MIT License](https://opensource.org/licenses/MIT). Feel free to use and contribute! 💖
