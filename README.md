# donorchoose-projects-screening

The goal of this project is to develop a predictive model that can determine the likelihood of approval for project proposals submitted by teachers on DonorsChoose.org. To achieve this, the project involved several key steps.

1. **Data Preprocessing:** The project began with the collection of project descriptions, teacher information, and school metadata from DonorsChoose.org. This raw data was then preprocessed to clean and organize it for analysis.

2. **Text Vectorization:** The text content of project descriptions was transformed into numerical vectors using techniques such as TF-IDF (Term Frequency-Inverse Document Frequency) or word embeddings like Word2Vec or GloVe. This allowed the model to work with the textual information effectively.

3. **Handling Categorical Values:** The categorical variables, such as teacher and school information, were encoded into numerical values using techniques like one-hot encoding or label encoding. This enabled the inclusion of these important features in the machine learning model.

4. **Feature Engineering:** Additional features were derived from the available metadata, such as teacher experience, school location, and project category. These features provided more context and information for the model to make predictions.

5. **Model Selection:** Different machine learning algorithms were explored, including decision trees, random forests, support vector machines, and neural networks. Each algorithm's strengths and weaknesses were considered, and the best-suited models were chosen for experimentation.

6. **Model Training and Evaluation:** The dataset was divided into training and testing sets to train the chosen models. Evaluation metrics like accuracy, precision, recall, and F1-score were used to assess the model's performance on the test set.

7. **Hyperparameter Tuning:** Hyperparameters of the selected models were fine-tuned using techniques like grid search or random search to optimize their performance.

8. **Ensemble Methods:** To further improve predictive accuracy, ensemble methods like stacking or boosting were explored. These techniques combine the predictions of multiple models to create a more robust final prediction.

9. **Cross-Validation:** To validate the models more rigorously, k-fold cross-validation was applied, ensuring that the models' performance wasn't influenced by a specific train-test split.



In summary, this project aimed to predict the approval or rejection of DonorsChoose.org project proposals using a combination of natural language processing techniques, feature engineering, and various machine learning algorithms. By utilizing project descriptions, teacher information, and school metadata, the model provided valuable insights to both teachers and the platform, ultimately enhancing the success rate of impactful educational projects.
