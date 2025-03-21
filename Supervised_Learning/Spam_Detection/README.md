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

<h2 align="center">🧠 Concepts Used</h2>

<h3 align="center">Natural Language Processing (NLP)</h3>
<ul>
    <li><b>TF-IDF:</b> A numerical statistic used to convert text messages into a weighted feature representation.</li>
</ul>

<h3 align="center">Machine Learning</h3>
<ul>
    <li><b>Naïve Bayes (MultinomialNB):</b> A probabilistic classification algorithm used for text-based spam detection.</li>
    <li><b>Pipeline Management:</b> Combining text processing and classification steps into a single workflow for efficient training and prediction.</li>
</ul>

<h2 align="center">⚙️ Approach</h2>
<ul>
    <li>Load text message data from a JSON file.</li>
    <li>Preprocess data and apply TF-IDF vectorization.</li>
    <li>Train a Naïve Bayes (MultinomialNB) model on the transformed data.</li>
    <li>Evaluate model performance using accuracy score and classification report.</li>
    <li>Save the trained pipeline in the <code>Model_Trained</code> directory.</li>
</ul>

<h2 align="center">🎯 Expected Outcomes</h2>
<ul>
    <li>A trained machine learning model capable of classifying spam and non-spam messages with high accuracy.</li>
    <li>An automated and structured approach to spam detection.</li>
    <li>A reusable model pipeline for further improvements and integrations.</li>
</ul>
