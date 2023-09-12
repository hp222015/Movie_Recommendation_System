<h1> Movie Recommendation System </h1>

This is a content-based movie recommendation system implemented in Python using the Jupyter notebook environment. The system suggests movies based on their content, such as genres, keywords, cast, and crew.

<h2> Getting Started </h2>
<h3>Prerequisites</h3>

You'll need the following Python libraries installed:
<ul>
<li>numpy</li>
<li>pandas</li>
<li>nltk</li>
<li>sklearn</li>
</ul>
You can install these using pip:

pip install numpy pandas nltk scikit-learn
<h4> Data </h4>
The system uses two datasets: tmdb_5000_movies.csv and tmdb_5000_credits.csv. These datasets contain information about movies, including details like title, overview, genres, keywords, cast, and crew.

<h3>Implementation</h3>
The recommendation system is divided into several steps:

<ol>
<h4><li>Data Loading and Preprocessing:</li></h4>
<ul>
<li>Loading movie and credits data.</li>
<li>Merging the datasets based on movie title.</li>
<li>Selecting relevant columns.</li>
</ul>
<h4><li>Data Cleaning and Transformation:</li></h4>
<ul>
        <li>Handling missing values and duplicates.</li>
        <li>Extracting useful information from columns like genres, keywords, cast, and crew.</li>
</ul>


<h4> <li>Text Processing:</li></h4>
<ul>
        <li>Converting text data to a format suitable for analysis.</li>
        <li>Stemming words to reduce variation.</li>
</ul>


<h4><li>Feature Extraction:</li></h4>
<ul><li>Using CountVectorizer to convert text data into numerical vectors.</li>
</ul>

<h4><li>Similarity Calculation:</li></h4>
<ul><li>Using cosine similarity to measure similarity between movies.</li></ul>

<h4><li>Recommendation Function:</li></h4>

<ul><li>Providing a function to recommend similar movies based on a given movie title.</li></ul>
<h4><li>Saving Models:</li></h4>
<ul><li>Pickling the necessary data and models for future use.</li></ul>

<h2>Usage</h2>
<ol>
        <li>Make sure you have the required libraries installed.</li>
        <li>Load and preprocess the data.</li>
        <li>Follow the steps in the notebook to build and evaluate the recommendation system.</li>
        <li>Use the **'recommend(movie_title)'** function to get recommendations based on a movie title.</li>
</ol>




<h2>Files</h2>
<ul>
<li>tmdb_5000_movies.csv: Dataset containing information about movies.</li>
<li>tmdb_5000_credits.csv: Dataset containing information about movie credits.</li>
<li>recommendation_system.ipynb: Jupyter notebook containing the code for the recommendation system.</li>
<li>movies.pkl: Pickle file containing processed movie data.</li>
<li>movie_dict.pkl: Pickle file containing movie data in dictionary format.</li><li>similarity.pkl: Pickle file containing similarity matrix.</li>
</ul>

<h2>Acknowledgments</h2>
<ul>
        <li>The dataset used in this project is from TMDb (The Movie Database).</li>
        <li>Credits to the creators and contributors of the libraries used in this project.</li>
</ul>


