# DLND your first network

First udacity project, implementing a neural net in numpy.
Predicting ride sharing usage,
based on actual data.

## My Notebook

This builds on the homework lessons, where solutions were provided.
Combining all of them together.
This was fiddly.

Once the neural net is coded, the main bit of work is picking the hyperparameters.
A few observations there.
You can graphically see when the training rate is too high or too low by looking at the loss functions over epochs.
If it slopes down too slowly, increase the training rate.
If it jumps about too much, then the training rate is too high.

I don't have an intuition for the number of nodes in the hidden layer yet, 
this is something that I'll have to do more reading on.
It isn't just a case that putting more hidden nodes in is always a good thing.
