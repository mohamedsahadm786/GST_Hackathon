# GST_Hackathon
GST HACKATHON PREDICTIVE MODEL 
The goal of this project is to build a machine learning model that can predict binary outcomes for a highly imbalanced target variable. Specifically, the challenge involves using historical data to train a model that can predict whether the target value for new data points will be "0" or "1". The dataset provided consists of both categorical and continuous variables, with many missing values that need to be carefully handled to ensure robust predictions.

Given that the target class is imbalanced, with 90.5% of the instances in the majority class ("0") and only 9.5% in the minority class ("1"), a key focus of the model development process is addressing this imbalance. This is done by utilizing specific machine learning techniques and parameter tuning (like adjusting the scale_pos_weight in XGBoost) to avoid model bias towards the majority class. Moreover, the large size of the dataset (785,133 rows in the training set) presents an opportunity for the model to learn rich patterns but also poses computational challenges that need to be managed efficiently.

The pipeline designed for this project not only cleans and preprocesses the data by imputing missing values, scaling continuous features, and encoding categorical variables, but also uses an ensemble learning approach (XGBoost classifier). XGBoost is well-suited for tabular data with complex interactions, and its built-in support for handling class imbalance makes it an ideal choice for this problem.

In summary, the primary concept is to build a model that can accurately predict binary outcomes for a highly imbalanced dataset using advanced machine learning techniques and careful preprocessing of both categorical and continuous features.
