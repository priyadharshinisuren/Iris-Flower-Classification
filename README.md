Iris Flower Classification in WEKA




Problem Statement
The iris flower, scientifically known as Iris, is a distinctive genus of flowering plants. Within this genus, there are three primary species: Iris setosa, Iris versicolor, and Iris virginica. These species exhibit variations in their physical characteristics, particularly in the measurements of their sepal length, sepal width, petal length, and petal width.

Objective:

The objective of this project is to develop a machine learning model capable of learning from the measurements of iris flowers and accurately classifying them into their respective species. The model's primary goal is to automate the classification process based on the distinct characteristics of each iris species.

Project Details:

Iris Species: The dataset consists of iris flowers, specifically from the species setosa, versicolor, and virginica.
Key Measurements: The essential characteristics used for classification include sepal length, sepal width, petal length, and petal width.
Machine Learning Model: The project involves the creation and training of a machine learning model to accurately classify iris flowers based on their measurements.
This project's significance lies in its potential to streamline and automate the classification of iris species, which can have broader applications in botany, horticulture, and environmental monitoring.

Project Summary
Project Description:

The Iris Flower Classification project focuses on developing a machine learning model to classify iris flowers into their respective species based on specific measurements. Iris flowers are classified into three species: setosa, versicolor, and virginica, each of which exhibits distinct characteristics in terms of measurements.

Objective:

The primary goal of this project is to leverage machine learning techniques to build a classification model that can accurately identify the species of iris flowers based on their measurements. The model aims to automate the classification process, offering a practical solution for identifying iris species.

Key Project Details:

Iris flowers have three species: setosa, versicolor, and virginica.
These species can be distinguished based on measurements such as sepal length, sepal width, petal length, and petal width.
The project involves training a machine learning model on a dataset that contains iris flower measurements associated with their respective species.
The trained model will classify iris flowers into one of the three species based on their measurements.
Results
I have selected Correctly Classified Instances as the primary evaluation metric for the Iris Flower Classification model. And after removing the overfitted models which have rCorrectly Classified Instances for cross validation as 100%, we get the final list:

Sl. No.	Classification Model	Recall Train (%)	Recall Test (%)
1	Adaboost 95%
2	Random Forest	95%
3	Naive Bayes	96%
4	Logistic regresion 96 %
Conclusion
In the Iris flower classification project, the tuned Random Forest model has been selected as the final prediction model. The project aimed to classify Iris flowers into three distinct species: Iris-Setosa, Iris-Versicolor, and Iris-Virginica. After extensive data exploration, preprocessing, and model evaluation, the following conclusions can be drawn:

Data Exploration: Through a thorough examination of the dataset, we gained insights into the characteristics and distributions of features. We found that Iris-Setosa exhibited distinct features compared to the other two species.

Data Preprocessing: Data preprocessing steps, including handling missing values and encoding categorical variables, were performed to prepare the dataset for modeling in weka steps

Model Selection: After experimenting with various machine learning models, tuned Random Forest was chosen as the final model due to its simplicity, interpretability, and good performance in classifying Iris species.

Model Training and Evaluation: The logitic regression model was trained on the training dataset and evaluated using appropriate metrics. The model demonstrated satisfactory accuracy and precision in classifying Iris species.

Challenges and Future Work: The project encountered challenges related to feature engineering and model fine-tuning. Future work may involve exploring more advanced modeling techniques to improve classification accuracy further.

Practical Application: The Iris flower classification model can be applied in real-world scenarios, such as botany and horticulture, to automate the identification of Iris species based on physical characteristics.

In conclusion, the Iris flower classification project successfully employed Random Forest (tuned) as the final prediction model to classify Iris species. The project's outcomes have practical implications in the field of botany and offer valuable insights into feature importance for species differentiation. Further refinements and enhancements may lead to even more accurate and reliable classification models in the future.
details:
<img width="550" height="733" alt="Screenshot 2026-05-05 132252" src="https://github.com/user-attachments/assets/59de61b0-027b-47d5-b8f3-cb75d78c122d" />
<img width="931" height="733" alt="Screenshot 2026-05-05 132307" src="https://github.com/user-attachments/assets/50030273-3624-411a-8f43-240c11418469" />
<img width="314" height="179" alt="Screenshot 2026-05-05 132320" src="https://github.com/user-attachments/assets/c6004390-c8db-469d-a16d-b89902aa983d" />
<img width="965" height="720" alt="Screenshot 2026-05-05 132433" src="https://github.com/user-attachments/assets/7cf9f992-4eb0-40b5-8995-ef56fb3b03e3" />
<img width="891" height="621" alt="Screenshot 2026-05-05 132648" src="https://github.com/user-attachments/assets/ec46f8f9-1b9c-496d-afcb-ca912cd1fbd1" />
<img width="930" height="350" alt="Screenshot 2026-05-05 132656" src="https://github.com/user-attachments/assets/256097ff-da3c-47ac-9126-309589c5cc83" />
<img width="935" height="701" alt="Screenshot 2026-05-05 132721" src="https://github.com/user-attachments/assets/223b16ed-5c4a-400a-b6b9-f0475c19d6bb" />
<img width="933" height="328" alt="Screenshot 2026-05-05 132731" src="https://github.com/user-attachments/assets/3e11aa83-eed0-49b6-9059-4f895c1c5f7c" />





