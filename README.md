# Fitness_Class

This project was done as part of my DataCamp Data Scientist Associate Certification exam.

## Background of the task

GoalZone operates as a prominent fitness club chain within Canada, providing a diverse selection of fitness classes. These classes are available in two distinct capacities: accommodating 25 and 15 participants, respectively.

It has been observed that certain classes consistently reach full booking capacity; however, this occurrence frequently correlates with a lower attendance rate.

To address this challenge, GoalZone is actively seeking to optimize class space allocation. This objective will be achieved by implementing predictive analytics to determine the likelihood of a member attending a particular class. Such predictive insights will empower GoalZone to efficiently allocate spaces. In cases where non-attendance is anticipated, the freed space can then be made available to other interested members.

By employing this predictive approach, GoalZone aims to enhance the overall utilization of class capacities, ensuring a more effective and satisfying fitness experience for its members.

### My Task

I conducted an analysis of the dataset, delving into various variables concerning class attendance. I trained classification models aimed at predicting a member's likelihood of attending a class.

Two distinct models were employed for this purpose: the base model, `LogisticRegression`  and the comparative model `RandomForestClassifier`.

Upon evaluating the models based on the precision performance metric, it was determined that the **Logistic Regression** model exhibited superior performance, outperforming the RandomForestClassifier by approximately 5%.

For a more detailed exploration of the analysis, models, and results, please refer to the [notebook](https://github.com/damiiete/Fitness_Class/blob/main/notebook.ipynb).
