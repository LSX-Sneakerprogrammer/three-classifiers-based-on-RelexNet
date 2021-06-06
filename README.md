# three-classifiers-based-on-RelexNet
This is my own approach for ANU honours project
## Files
There are 6 files in the repository. 

The relexnet (without modifier).ipynb, relexnet with modifier.ipynb and relexnet negative exper.ipynb means the experiment for classifier without modifiers, classifier with modifiers and classifier with modifiers and negative words separately, by using 10-fold cross validation. 

The relexnet without modifier final model.ipynb, relexnet with modifier final model.ipynb and relexnet negative final model.ipynb means the experiment for classifier without modifiers, classifier with modifiers and classifier with modifiers and negative words separately, using the whole training dataset.

## Structure
There are 4 classes, Modifiers, Preprocessor, DataLoader, Relexnet, and train_model function. 

Modifiers class stores the modifiers and negative words from Vader sentiment. 

Preprocessor class stores the text cleaning and tokenizing parts. 

DataLoader class transforms the text into input vector. 

Relexnet is the structure of different classifier based on Relexnet.

train_model function is used to train the model.

I add the comments mainly in relexnet with modifier.ipynb, for relexnet negative exper.ipynb, I mainly add the comments on how to handle negative words and N layer.
