<h1 align="center">📩🚫Spam Detection</h1>

<p align="justify">
The objective of this project is to develop a machine learning model that detects whether the messeges are spam or not based on their label and messages. The model utilizes machine learning algorithms to predict whether the message are spam of ham.
</p>

<h2 align="center">🚀 Key Features</h2>
<ul>
    <li><b>Data Loading:</b> The training data is loaded from a JSON file and preprocessed for model training.</li>
    <li><b>Text Processing:</b> A TF-IDF vectorizer is used to transform the messages into numerical representations.</li>
    <li><b>Model Training:</b> A Naïve Bayes classifier (MultinomialNB) is trained on the processed text data.</li>
    <li><b>Evaluation Metrics:</b> Model performance is assessed using accuracy score and a classification report.</li>
    <li><b>Pipeline Saving:</b> The trained model, including the vectorizer, is saved as a pickle file in the <code>Model_Trained</code> directory.</li>
</ul>