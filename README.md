# Objective
Built video recommendation system based on content based filtering and KNN algorithm.

# Data
Scrapped the data from Youtube using google client api.
Extracted data of five category like food, travel,arts and science.
data consist video id,title and description of the video.

# Data Preprocessing
Preprocessed the data using NLP library.
Preprocessing of data include remove the emojies,duplicate records if present and numerical value.
extracted only english language data from scrapped data.

# Model Building
for model building phase, builded model using TF-IDF and K-Nearest Neighbour method that recommend top five similar videos to user.

# Deployment
deployed the model using Flask.
