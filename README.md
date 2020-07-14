# Using NLP to newsgroup documents classification

We'll compare Naive Bayes and Deep Learning models used for the classification of [newsgroup texts](http://qwone.com/~jason/20Newsgroups/). 

What we'll be doing: 
1. Multinomial Naive Bayes model
2. Deep Learning model
3. Deep Learning model with pre-trained embedded layer

We'll also check the accuracy of the models and some other metrics as well as ploting a confusion matrix.


# Conclusion

The Naive-Bayes model was very easy and quick to create and it performed very well even on our first try.

The Deep Learning model performed well too, nonetheless it wasn't the best performer model.

- The **Naive-Bayes is very quick to implement**. The model itself does not require tunning it's hiperparameters (not in most cases). On the other hand, the **data must be well pre-processed** before being feed to the model.

- The **Deep Learning model requires a lot of hiperparameter tunning** and also testing and finding a **proper model architecture** to perform better (was not the focus on this notebook). A bigger dataset always happen to help deep learning models as well. That would take a lot more of our time.
