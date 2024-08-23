Word Embeddings and text Classification

The goal of this assignment is to train a simple feed foreword neural network for text classification
and get a trained word embedding vector from the network. 
Dataset: https://drive.google.com/file/d/1FXy4vDRDYrzphy_ZNVs8xZAduaKySR5h/view?
usp=drive_link (https://drive.google.com/file/d/1FXy4vDRDYrzphy_ZNVs8xZAduaKySR5h/view?
usp=drive_link)
Part 1 : The goal in this part is to prepare the text data.
 Read the text data and lowercasing and EDA
 Tokenization, encoding and Text vectorization
 Extract features and labels 

Part 2
Build a simple feedforward Neural Network with the below architecture 
1 Embedding layer of shape (,15) 
3 Dense layers with 100 neurons and relu activation functions
1 appropriate output dense layer with appropriate activation function 
Compile the model and train for 50 epocs (or accuracy score of atleast 75%)

Part 3:
Extract the embedding vector from the model 
Visualize the word embeddings in a scatter plot (use PCA)

Predict the class for the below given description 
1. “arguing that transformative ideas don’t arise from the day-to-day, gradual process of
experimentation and data accumulation but that the revolutions in science,”

2. “As the aliens traverse the country in huge three-legged machines, incinerating all in their path
with a heat ray and spreading noxious toxic gases”
Calculate Cosine Similarity of the below pair of words from the extracted word embeddings
1. Scared,fear
2. Secret,private
3. Prison,jail
