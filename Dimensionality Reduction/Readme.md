# Dimensionality Reduction

![](dr.png)


The number of input variables or features for a dataset is referred to as its dimensionality.

Dimensionality reduction refers to techniques that reduce the number of input variables in a dataset.

More input features often make a predictive modeling task more challenging to model, more generally referred to as the curse of dimensionality.

High-dimensionality statistics and dimensionality reduction techniques are often used for data visualization. Nevertheless these techniques can be used in applied machine learning to simplify a classification or regression dataset in order to better fit a predictive model

I will discover a gentle introduction to dimensionality reduction for machine learning

### After reading this, you will know:

<li>Large numbers of input features can cause poor performance for machine learning algorithms.</li>
<li>Dimensionality reduction is a general field of study concerned with reducing the number of input features.</li>
<li>Dimensionality reduction methods include feature selection, linear algebra methods, projection methods, and autoencoders.</li>

## Problem With Many Input Variables

The performance of machine learning algorithms can degrade with too many input variables.

If your data is represented using rows and columns, such as in a spreadsheet, then the input variables are the columns that are fed as input to a model to predict the target variable. Input variables are also called features.

We can consider the columns of data representing dimensions on an n-dimensional feature space and the rows of data as points in that space. This is a useful geometric interpretation of a dataset.

Having a large number of dimensions in the feature space can mean that the volume of that space is very large, and in turn, the points that we have in that space (rows of data) often represent a small and non-representative sample.

This can dramatically impact the performance of machine learning algorithms fit on data with many input features, generally referred to as the “curse of dimensionality.”

Therefore, it is often desirable to reduce the number of input features.

This reduces the number of dimensions of the feature space, hence the name “dimensionality reduction.”

## Dimensionality Reduction

Dimensionality reduction refers to techniques for reducing the number of input variables in training data.

     When dealing with high dimensional data, it is often useful to reduce the dimensionality by projecting the data to a lower dimensional subspace
                      which captures the   “essence” of the data. This is called dimensionality reduction.


High-dimensionality might mean hundreds, thousands, or even millions of input variables.

Fewer input dimensions often mean correspondingly fewer parameters or a simpler structure in the machine learning model, referred to as degrees of freedom. A model with too many degrees of freedom is likely to overfit the training dataset and therefore may not perform well on new data.

It is desirable to have simple models that generalize well, and in turn, input data with few input variables. This is particularly true for linear models where the number of inputs and the degrees of freedom of the model are often closely related.

         The fundamental reason for the curse of dimensionality is that high-dimensional functions have the potential to be much more complicated than low-dimensional ones, 
                and that those complications are harder to discern. The only way to beat the curse is to incorporate knowledge about the data that is correct.

Dimensionality reduction is a data preparation technique performed on data prior to modeling. It might be performed after data cleaning and data scaling and before training a predictive model.

     dimensionality reduction yields a more compact, more easily interpretable representation of the target concept, focusing the user’s 
                attention on the most relevant variables.


As such, any dimensionality reduction performed on training data must also be performed on new data, such as a test dataset, validation dataset, and data when making a prediction with the final model.
