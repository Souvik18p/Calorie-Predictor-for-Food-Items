Food Calorie Prediction

This project involves predicting the calorie content of various food items based on their serving size. The model uses a linear regression algorithm to estimate the calories based on weight extracted from the serving size description.

## Table of Contents

- [Project Overview](#project-overview)
- [Installation](#installation)
- [Usage](#usage)
- [Data](#data)
- [Model](#model)


## Project Overview

The goal of this project is to predict the calorie content of food items based on their weight. The dataset includes information on food items, their serving sizes, and calorie content. The model is trained using a linear regression algorithm to predict the calorie content based on the weight of the food item.

## Installation

1. **Clone the repository:**

    ```bash
    git clone https://github.com/Souvik18p/predict-calories-of-a-food-item.git
  
    ```
2. **Install the required packages:**

    You can use `pip` to install the necessary packages. It is recommended to use a virtual environment.

    `
    pip install pandas scikit-learn matplotlib
    ```
    ## Usage

1. **Prepare the Dataset:**

    Ensure you have the dataset `food_calories.csv` in the same directory as the script. The dataset should contain columns for food names, serving sizes, and calorie content.(https://www.kaggle.com/datasets/vaishnavivenkatesan/food-and-their-calories)

2. **Run the Script:**

    Execute the script to start the calorie prediction tool.
   
3. **Interact with the Program:**

    Enter the name of a food item to predict its calorie content. Type `exit` to quit the program.

    ```
    Enter the name of the food item (or type 'exit' to quit): Apple
    Predicted calories for Apple: 264.14 cal
    Enter the name of the food item (or type 'exit' to quit): kiwi
    Predicted calories for kiwi: 264.89 cal
    Enter the name of the food item (or type 'exit' to quit): potato
    Predicted calories for potato: 287.45 cal
   Enter the name of the food item (or type 'exit' to quit): exit
   Exiting the program.
    
    ```
## Data

The dataset `food_calories.csv` should include the following columns:

- `Food`: The name of the food item.
- `Serving`: Description of the serving size.
- `Calories`: Caloric content of the serving.

Ensure the 'Calories' column is in the format of "<number> cal" and 'Serving' contains weight information in grams.

## Model

- **Algorithm:** Linear Regression
- **Performance Metric:** Mean Squared Error (MSE)

The model is trained to predict calories based on the weight of the food item extracted from the serving size description.
![image](https://github.com/user-attachments/assets/0dff113b-c4dd-42f8-a26e-8bbb54c06ba8)



  
