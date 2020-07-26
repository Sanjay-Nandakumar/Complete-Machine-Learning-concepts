# Hyperparameter optimization

![alt text](https://images.unsplash.com/photo-1545153556-bb9eb1bd6031?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=750&q=80)

In machine learning, hyperparameter optimization or tuning is the problem of choosing a set of optimal hyperparameters for a learning algorithm. A hyperparameter is a parameter whose value is used to control the learning process. By contrast, the values of other parameters (typically node weights) are learned.

The same kind of machine learning model can require different constraints, weights or learning rates to generalize different data patterns. These measures are called hyperparameters, and have to be tuned so that the model can optimally solve the machine learning problem. Hyperparameter optimization finds a tuple of hyperparameters that yields an optimal model which minimizes a predefined loss function on given independent data. The objective function takes a tuple of hyperparameters and returns the associated loss. Cross-validation is often used to estimate this generalization performance.

# Grid search

![alt text](https://images.unsplash.com/photo-1531062916849-ac6624741870?ixlib=rb-1.2.1&auto=format&fit=crop&w=750&q=80)

The traditional way of performing hyperparameter optimization has been grid search, or a parameter sweep, which is simply an exhaustive searching through a manually specified subset of the hyperparameter space of a learning algorithm. A grid search algorithm must be guided by some performance metric, typically measured by cross-validation on the training set or evaluation on a held-out validation set.

Since the parameter space of a machine learner may include real-valued or unbounded value spaces for certain parameters, manually set bounds and discretization may be necessary before applying grid search.

# Boosting

![alt text](https://images.unsplash.com/photo-1524178232363-1fb2b075b655?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1050&q=80)

In machine learning, boosting is an ensemble meta-algorithm for primarily reducing bias, and also variance[1] in supervised learning, and a family of machine learning algorithms that convert weak learners to strong ones. Boosting is based on the question posed by Kearns and Valiant (1988, 1989)."Can a set of weak learners create a single strong learner?" A weak learner is defined to be a classifier that is only slightly correlated with the true classification (it can label examples better than random guessing). In contrast, a strong learner is a classifier that is arbitrarily well-correlated with the true classification.

Robert Schapire's affirmative answer in a 1990 paper to the question of Kearns and Valiant has had significant ramifications in machine learning and statistics, most notably leading to the development of boosting.

When first introduced, the hypothesis boosting problem simply referred to the process of turning a weak learner into a strong learner. "Informally, (the hypothesis boosting) problem asks whether an efficient learning algorithm that outputs a hypothesis whose performance is only slightly better than random guessing (i.e. a weak learner) implies the existence of an efficient algorithm that outputs a hypothesis of arbitrary accuracy (i.e. a strong learner). Algorithms that achieve hypothesis boosting quickly became simply known as "boosting". Freund and Schapire's arcing (Adaptive Resampling and Combining), as a general technique, is more or less synonymous with boosting.
