# RNNs, LSTMs & GRUs

This task has been based off a coursework I carried out during my MRes. In this notebook, using PyTorch yet without implementing RNN cells directly, I've come up with code implementations for RNNs, LSTMs and GRUs.

## Dataset
I will be using the Google [*Speech Commands*](https://www.tensorflow.org/tutorials/sequences/audio_recognition) v0.02 [1] dataset. In particular, I will be using a subset of the dataset containing only the words "one", "two" and "three". 

[1] Warden, P. (2018). [Speech commands: A dataset for limited-vocabulary speech recognition](https://arxiv.org/abs/1804.03209). *arXiv preprint arXiv:1804.03209.*

## Methods
Once cells and networks were implemented, given the small cardinality of the set of labels, I manually tuned hyperparameters to obtain optimal classification accuracy.


## Conclusion
In this simpler version of the original task, high accuracies are observed in the test set with simple manual tuning of hyperparameters.
