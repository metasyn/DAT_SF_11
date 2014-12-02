# Machine learning

* a part of CS that studies and devs algorithms that can learn from data
* a set of methods that can automatically detect patterns in data and use
    uncovered patterns to predict future data or perform other kinds of
    decision making
* a field of study that gives computers the ability to learn without being
    explicity programmed

## When do we need it ?

* Some observable patterns exist
* there are no explicitly known equations or dependencies (formulas)
* we have data on it

## Types of Machine Learning

* supervised learning: the goal is to learn mapping from some given inputs x to
    outputs y, given a labeled set of IO pairs (when the training set contains
    explicity examples of what correct output should be for given input)
* unsupervised learning: the coal is to learn interesting patterns and
    structure in data, given only inputs (not output info given)
* reinforcement learning: no explicitly labeled data is given, but 'reward' /
    'punishment' signals are provided 

## What even **is** learning?

* Learning is not about memorizing data and being able to recall it, but its
    generalizing conclusions to previously unseen examples or extracting
    previously unseen patterns
* Memorizing != Learning

### Supervised Learning

* Predictive learning
* if response variable = categorical: *classification*
* if response variable = continuous: *regression* 

### Unsupervised Learning
- Descriptive learning (knowledge discovery)
  * clustering
  * dimensionality reduction
  * lower-dimension embedding
    * non-linear

### Supervised Learning

#### Pipeline

* training: input - (extract) features - algorithm
* predicition: (extract) features - classifier - label

    - Training: model learning
    - Prediction: model application
      * Train set / test set

#### Machine learning & Dogma

* The 'central dogma' of statistics
  * That inference from population sampling is valid
* your inference is as good as your sample

### Polynomial fitting

* Remember not to overfit !
* Small in-sample error, but generalizes well to general error.
* Training error = in-sample error
* Model complexity: if it fits too well... uh oh.
  * Out of sample error is minimal
* You must prevent lickage:
  * You need to make sure that your algorithm NEVER sees the other data

### Classification Problems
- split dataset
  * 85% training, 15% test
- generalization error
- OOS error (out of sync error)

### Validation
* training / test
* training / test / validation
* **beware of overtraining on validation**
* k-fold cross-validation
  * splitting up that data into multiple packets
  * generally 5 or 10 folds (unless you're Fermin Moscoso)
