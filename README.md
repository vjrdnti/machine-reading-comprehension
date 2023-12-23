used bert transfer learning on a prepared file of squad dataset with discourse and question as features and a target column with a set of correct answers for each.
a large passage was divided into overlapping chunks of varying size to preserve context and the question was tested against each of these discourse tokens for contextual similarity and statistical similarity
like ngrams and tfidf, a combined equation of these two with weights of both as adjustable hyperparameters.
then our bert model will predict answer for the question and the context as the most similar chunks.
parameters shoukld be adjusted for better performance on the desired number of best performing answers in a set.
scope:
train the model to adjust parameters based on question type and passage type complete semantic analysis of it, in order to have the best result might as well train a neural network,
to adjust parameters based on question analysis and passage analysis.
