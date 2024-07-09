# Coding_Projects
This repository contains 3 coding projects we did: Blackjack, Data Transformation and Model Visualization in R, and Airline Rating Prediction.

## Blackjack
In this project, we developed a fully functional Blackjack game using Python and Object-Oriented Programming (OOP) principles. The game was designed with modularity in mind, breaking down the functionality into separate Python files for better organization and maintainability. The components of the game include:

- **Card:** Represents a single playing card.
- **Deck:** Manages a collection of cards, including operations like shuffling.
- **Hand:** Represents a player's hand of cards, allowing for operations such as adding a card and calculating the hand's value.
- **Shuffle:** Handles the shuffling logic for the deck.

These components were then integrated into the main game logic within `blackjack.py`, ensuring clear separation of concerns and easy readability. The use of OOP allowed us to create a clean and efficient codebase, making the game extensible and easy to understand.

## Data Transformation and Model Visualization in R
In this project, we utilized R to perform data transformation and model visualization on a dataset. The steps included:

1. **Data Transformation:** 
   - **Standardization:** Adjusted the data to have a mean of zero and a standard deviation of one.
   - **Log Transformation:** Applied log transformation to stabilize the variance and make the data more normally distributed.
   - **Discretization:** Converted continuous data into discrete bins for certain analyses.

2. **Model Training:**
   - Trained Logistic Regression models using standardized, log-transformed, and discretized data.
   - Computed and compared error rates for each model.
   - Trained additional models including Linear Discriminant Analysis (LDA), Quadratic Discriminant Analysis (QDA), Linear Support Vector Machine (SVM), and Non-linear SVM.

3. **Model Visualization:**
   - Applied appropriate visualization methods to each transformed dataset to better understand the data distribution and model performance.
   - Analyzed the significance of features based on the trained models.

By leveraging R for these tasks, we ensured a robust analysis pipeline, combining statistical rigor with insightful visualizations.

## Airline Rating Prediction
This project aimed to predict overall ratings from a Kaggle dataset containing various airline reviews. We utilized an ensemble model combining TF-IDF and a Random Forest Regressor, which outperformed other models. The success of this model was driven by effective feature representation and optimization techniques.

Key steps and findings:

1. **Data Analysis:**
   - The dataset indicated a high prevalence of negative reviews, highlighting areas for airline improvement.
   - Features such as 'Seat Comfort,' 'Cabin Staff Service,' and 'Value for Money' were crucial in predicting overall ratings.

2. **Data Preprocessing:**
   - Applied TF-IDF transformation to textual reviews.
   - Employed one-hot encoding for categorical features.
   - Addressed missing values using imputation methods.

3. **Model Training and Evaluation:**
   - Compared Linear Regression, Random Forest, and XGBoost models.
   - The ensemble model (TF-IDF + Random Forest) achieved the lowest Mean Squared Error (MSE) and superior predictive performance.
   - Hyperparameter tuning, especially optimizing "n_estimators," further improved model performance.

4. **Insights and Literature Review:**
   - Confirmed the significance of service-related features in predicting ratings.
   - Explored existing studies and aligned our findings with industry insights.

In conclusion, our ensemble model provided valuable insights into the airline industry, emphasizing the importance of specific service features in predicting overall ratings.
