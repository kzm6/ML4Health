This project is about using NLP for finding semantic patterns in mental health conditions.

To run the project - 
Go through FINAL.ipynb - it contains the entire structure of the project. The project has the following checkpoints - initial cleaning, tfidf, NMF, Sentiment, POS Tag, combine into an embedding, run an SVM.
Then, go through bert_create_embeddings - it contains how the MentalBERT model is used to create embeddings. These embeddings are then used to train and run the same SVM as discussed earlier. Output classification tables are provided as csv files, since running the entire script will take roughly 2-3 hours at least, locally. 

Any raw input data cannot be found here in the repo. Only output and checkpoints are present here. 

Due to the large size of the inputs and outputs throughout this project a lot of code is commented out / used to save data locally or to colab. This was done because of colab frequently crashing or disconnects from runtime. Instead of restarting the entire script, parts were saved locally, which acted as checkpoints. Some of these checkpoints can be found here, which could be uploaded. Most files such as the embeddings and the tfidf vector file, even after zipping were too large for github, and will have to be run organically through the code. 

Any such data that need not be generated again, AND COULD FEASIBLY be uploaded to GitHub can be found in the GitHub repo. 

Certain files which were very large and could not be zipped (windows failure) or uploaded to github, will need to be run through the code. 

EDIT - The very large output files (bert embeddings etc) can now be found in the BOX folder shared in the final report.


