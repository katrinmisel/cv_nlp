# Natural Language Processing and Computer Vision for the Yelp reviews database

This project is a feasibility study of automatically detecting topics of dissatisfaction in Yelp reviews (NLP) and automatically labeling photos uploaded to Yelp (CV).

The dataset used is the Yelp dataset which can be downloaded freely here: https://www.yelp.com/dataset/
The 32k negative reviews filtered from the original reviews can be found in 'bad_reviews.csv'
All necessary librairies are located in 'requirements.txt'

### Natural Language Processing
1. Filtering out negative reviews from a sample (5000 reviews)
2. Preprocessing reviews to a format compatible with the NLP model
3. Extraction of topics from negative reviews using Gensim LDA
4. Results analysis

### Computer Vision
1. Equalizing the histograms for each photo in the sample (100 photos per label, 500 photos total)
2. Testing ORB for feature extraction
3. Dimensionality reduction and KMeans clustering
4. Using transfer learning with VGG16 for feature extraction
5. Dimensionality reduction and KMeans clustering
6. Visualizing and analyzing results
7. Analying some examples of mislabeled photos

A synthesis of the project can be found here: https://katrinmisel.github.io/project_synthesis.html
