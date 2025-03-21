<h1 align="center">🎬 Movie Genre Classification</h1>

<p align="justify">
The objective of this project is to develop a machine learning model that classifies movies into genres based on their descriptions. The model utilizes Natural Language Processing (NLP) techniques and machine learning algorithms to predict genres associated with a given movie.
</p>

<h2 align="center">🚀 Key Features</h2>
<ul>
    <li><b>Text Preprocessing:</b> The data undergoes preprocessing steps like removing unnecessary values from the dataset for model training.</li>
    <li><b>Model Training:</b> A TF-IDF vectorizer is combined with Logistic Regression to build the classification model.</li>
    <li><b>Evaluation Metrics:</b> Model performance is assessed using accuracy score and a classification report.</li>
    <li><b>Pipeline Saving:</b> The trained model, along with the vectorizer, is saved as a pickle file in the <code>Model_Trained</code> directory.</li>
</ul>

<h2 align="center">🧠 Concepts Used</h2>
<h3 align="center">Natural Language Processing (NLP)</h3>
<ul>
    <li><b>Tokenization:</b> Splitting movie descriptions into words or phrases for processing.</li>
    <li><b>Stop-word Removal:</b> Filtering out common words to focus on meaningful content.</li>
    <li><b>TF-IDF:</b> A numerical statistic to convert textual data into a weighted feature representation.</li>
</ul>

<h3 align="center" >Machine Learning</h3>
<ul>
    <li><b>Logistic Regression:</b> A classification algorithm used to predict the probability of a movie belonging to one or more genres.</li>
    <li><b>Pipeline Management:</b> Encapsulating the NLP and classification workflow for smooth training and prediction processes.</li>
</ul>

<h2 align="center">⚙️ Approach</h2>
<ul>
    <li>Load movie descriptions from a JSON file.</li>
    <li>Preprocess data and apply TF-IDF vectorization.</li>
    <li>Train a Logistic Regression model on the transformed data.</li>
    <li>Evaluate model performance using accuracy score.</li>
    <li>Save the trained pipeline in the <code>Model_Trained</code> directory.</li>
</ul>

<h2 align="center">🎯 Expected Outcomes</h2>
<ul>
    <li>A trained machine learning model capable of predicting movie genres with high accuracy.</li>
    <li>An automated and structured approach to movie genre classification.</li>
    <li>A reusable model pipeline for further improvements and integrations.</li>
</ul>
