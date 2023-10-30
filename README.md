# Summer_analytics_final_hackathon
Built a machine learning model to predict whether a person is living a healthy lifestyle using various lifestyle factors. The model was trained on the data of 25,920 people.
### Visualising the data

![image](https://github.com/Parth-Agarwal216/Summer_analytics_final_hackathon/assets/118837763/6a2ffb5c-7112-4dc0-8b16-75a360330b0d)

![image](https://github.com/Parth-Agarwal216/Summer_analytics_final_hackathon/assets/118837763/0efd0899-3df1-494a-9a26-5fbdeaeb00f2)

![image](https://github.com/Parth-Agarwal216/Summer_analytics_final_hackathon/assets/118837763/0cd51e33-5a6f-4796-9d10-cf4a4b61e75e)

## Feature Selection:

- ID1, ID2 are dropped as they are irrelevant.
- 'Any hereditary condition' and 'mental health managment' is dropped as for the given data, all people have same data for this column.
- Other features show close relation with health of a person.


## Model used for final prediction:
- Catboost Classifier with hyperparameters fine-tuned through GridSearchCV were used
- Regularization parameters were added to avoid over fittiing
