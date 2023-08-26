# Predicting Age from Resting-State fMRI - Project Summary

**Overview**

This project explores the use of resting-state functional Magnetic Resonance Imaging (fMRI) data to predict a subject's age and uncover brain connectivity patterns associated with aging. Through a combination of data preprocessing, feature extraction, and machine learning techniques, we aim to build a predictive model for age while gaining insights into the relationship between brain connectivity and age.

**Key Steps in the Project**

1. **Data Acquisition**: We utilized the Nilearn library to acquire resting-state fMRI data. The dataset was fetched and loaded into the project environment.

2. **Data Exploration**: Extensive exploration of the dataset revealed valuable insights. We inspected the dataset's structure, checked for duplicate entries, explored data types, and identified any missing values. The target variable, 'Age,' was examined for its distribution and statistical characteristics.

3. **Feature Extraction**: Brain connectivity features were extracted from the fMRI data using a predefined brain atlas. These features encapsulated the functional relationships between various brain regions, serving as the input for our predictive model.

4. **Data Preprocessing**: To prepare the data for machine learning, we partitioned it into training and testing sets. Stratified splitting ensured that the age distribution remained consistent between the training and testing datasets.

5. **Model Building**: We employed a Support Vector Regressor (SVR) model for age prediction. Through an exhaustive grid search, optimal hyperparameters for the SVR model were identified. Subsequently, the model was trained on the training dataset and evaluated on the testing dataset.

6. **Interpreting Model Results**: The project culminated in the interpretation of the SVR model's outcomes. We delved into feature importance and visually explored the relationships between brain connectivity patterns and age.

**Conclusion**

This project demonstrates the feasibility of predicting a subject's age from resting-state fMRI data and provides valuable insights into the neural underpinnings of aging. Here are some key takeaways:

- **Data Quality**: The dataset used in this project exhibited good quality, with no missing values and a balanced distribution of age groups.

- **Machine Learning Model**: The Support Vector Regressor (SVR) proved to be an effective choice for age prediction, achieving a mean squared error of approximately 20.1 and an R-squared score of about 0.71 on the testing dataset. These metrics indicate that the SVR model provides reasonably accurate predictions of age from fMRI data.

- **Feature Importance**: Feature importance analysis revealed the specific brain connectivity patterns that contribute to age prediction. This information can be valuable for understanding how the brain changes with age.

- **Further Research**: While this project offers promising results, there is room for further research. More advanced machine learning models, additional data sources, and larger datasets could enhance the accuracy of age prediction and provide deeper insights into the aging process.
