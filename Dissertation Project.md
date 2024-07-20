## Analysis Of Higher Education Students’ Performance Using Machine Learning Techniques

With the tremendous changes occurring world wide, the importance of education is witnessed and has been growing day by day.
Analyzing the performance of students in higher education is a crucial aspect and one of the important areas of research, with manifold implications for educational institutions like schools, colleges, universities, public and private institutions, tuition centres and so on. In real-time, this research will have a significant impact on a number of aspects of the education system.

The dataset offers a comprehensive glimpse into the intricate web of factors influencing students’ academic journeys. From personal demographics such as age,
gender, and family background to lifestyle choices like extracurricular activities and work commitments, the dataset delves into the multifaceted dimensions of student life. Academic preparation, attendance, and engagement in various aspects of university life are meticulously documented, providing a rich tapestry of information. Furthermore, it encapsulates familial nuances such as parental education, occupation, and family structure. With detailed insights into the students’ perspectives on the impact of their activities on academic success, the dataset not only paints a vivid picture of the individual but also serves as a valuable resource for understanding the dynamics between personal attributes and academic performance.

The data was collected from the Faculty of Engineering and Faculty of Educational Sciences students in 2019. The purpose is to predict students’ end-of-term performances. The dataset contains 33 attributes of 145 students to analyze their performance.


*Methodologies*
Data Investigation/Inspection
Exploratory Data Analysis(EDA)
Feature Scaling
Selection of Models
 --> Random Forest
 --> Logistic Regression
 --> Support Vector Machine

 *Conclusion*

|Model|Accuracy|
|-----|--------|
| Random Forest | 0.62 |
| Logistic Regression | 0.21 |
| Support vector Machine | 0.17 |

To summarize/conclude, the analysis of the three different algorithms that are used on the dataset reveals varying degrees of success in identifying or analyzing the output grades of students. The Random forest model stands out as the most accurate for the dataset considered resulting in 62% accuracy. Nevertheless, a deep investigation of other metrics such as precision, recall, and F1-score of different classes indicates disparities or variations. This points out an in-depth analysis of class imbalances. The Logistic regression, with an accuracy of 21%, reflects limitations in predicting characteristics, especially in a few classes. In this regard, further analysis involving regularization techniques and feature engineering is recommended. The Support vector machine model which resulted in the lowest accuracy at 17%, underscores the challenges summoned by imbalanced datasets. highlighting the need for hyper parameter tuning and feature engineering. Although accuracy is a remarkable factor, the variations produced by precision, recall, and F1-score factors emphasize the value or the importance of addressing class imbalances for strong and accurate model development. Finally, the Random forest model exhibits the highest overall accuracy, but all models call attention to further investigations to enhance their predictive capabilities, especially when dealing with diversified and imbalanced data sets.
