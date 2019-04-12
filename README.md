The project is about MNIST handwritten digit classification using Support Vector Machine (SVM). For the purpose of this tutorial, I will use python programming.
The goal is to classify handwritten digits by teaching you how to train SVM classifier on image data. I utilised 20 percent of the training data for building the model. 

Solution:

I followed two approaches for SvM training. First, SvM with RBF kernel and second, SVM with linear kernel. Although both the approaches performed well (achieved 92% and 94% accuracy), The accuracy achieved using a non-linear kernel (~0.94) is mush higher than that of a linear one (~0.92).

The .ipynb file load the data and subsets 20% of the data for training purpose. Features were scaled and performed grid search with cross-validation for finding the best parameters. Grid search was done for params C and gamma.



