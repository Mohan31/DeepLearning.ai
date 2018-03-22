**Back

Hyperparameter tuning, Batch Normalization, Programming Frameworks {.attempt-title .display-1-text}
==================================================================

Quiz, 10 questions

9/10 points (90%)

**

**Congratulations! You passed!**

Next Item

loading
  ![](./Coursera%20_%20Online%20Courses%20From%20Top%20Universities.%20Join%20for%20Free%20_%20Coursera_files/loading.gif)

Load Error!

Question 1

*Correct*

1 / 1 points

1. Question 1 {.c-assess-question-number}
-------------

If searching among a large number of hyperparameters, you should try
values in a grid rather than random values, so that you can carry out
the search more systematically and not rely on chance. True or False?

True

False

Correct 

Question 2

*Correct*

1 / 1 points

2. Question 2 {.c-assess-question-number}
-------------

Every hyperparameter, if set poorly, can have a huge negative impact on
training, and so all hyperparameters are about equally important to tune
well. True or False?

True

False

Correct 

Yes. We've seen in lecture that some hyperparameters, such as the
learning rate, are more critical than others.

Question 3

*Correct*

1 / 1 points

3. Question 3 {.c-assess-question-number}
-------------

During hyperparameter search, whether you try to babysit one model
(“Panda” strategy) or train a lot of models in parallel (“Caviar”) is
largely determined by:

Whether you use batch or mini-batch optimization

The presence of local minima (and saddle points) in your neural network

The amount of computational power you can access

Correct 

The number of hyperparameters you have to tune

Question 4

*Incorrect*

0 / 1 points

4. Question 4 {.c-assess-question-number}
-------------

If you think β

(hyperparameter for momentum) is between on 0.9 and 0.99, which of the
following is the recommended way to sample a value for beta?

``` {contenteditable="false" data-language="python" style="opacity: 1;"}
12r = np.random.rand()beta = r*0.09 + 0.9 XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX
```

``` {contenteditable="false" data-language="python" style="opacity: 1;"}
12r = np.random.rand()beta = 1-10**(- r - 1)XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX
```

``` {contenteditable="false" data-language="python" style="opacity: 1;"}
12r = np.random.rand()beta = 1-10**(- r + 1)XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX
```

This should not be selected 

``` {contenteditable="false" data-language="python" style="opacity: 1;"}
12r = np.random.rand()beta = r*0.9 + 0.09 XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX
```

Question 5

*Correct*

1 / 1 points

5. Question 5 {.c-assess-question-number}
-------------

Finding good hyperparameter values is very time-consuming. So typically
you should do it once at the start of the project, and try to find very
good hyperparameters so that you don’t ever have to revisit tuning them
again. True or false?

True

False

Correct 

Question 6

*Correct*

1 / 1 points

6. Question 6 {.c-assess-question-number}
-------------

In batch normalization as presented in the videos, if you apply it on
the l

th layer of your neural network, what are you normalizing?

a[l]

b[l]

W[l]

z[l]

Correct 

Question 7

*Correct*

1 / 1 points

7. Question 7 {.c-assess-question-number}
-------------

In the normalization formula z(i)norm=z(i)−μσ2+ε√

, why do we use epsilon?

To speed up convergence

To have a more accurate normalization

To avoid division by zero

Correct 

In case μ

is too small

Question 8

*Correct*

1 / 1 points

8. Question 8 {.c-assess-question-number}
-------------

Which of the following statements about γ

and β

in Batch Norm are true?

There is one global value of γ∈R

and one global value of β∈R

for each layer, and applies to all the hidden units in that layer.

Un-selected is correct 

The optimal values are γ=σ2+ε−−−−−√

, and β=μ

.

Un-selected is correct 

They can be learned using Adam, Gradient descent with momentum, or
RMSprop, not just with gradient descent.

Correct 

β

and γ

are hyperparameters of the algorithm, which we tune via random sampling.

Un-selected is correct 

They set the mean and variance of the linear variable z[l]

of a given layer.

Correct 

Question 9

*Correct*

1 / 1 points

9. Question 9 {.c-assess-question-number}
-------------

After training a neural network with Batch Norm, at test time, to
evaluate the neural network on a new example you should:

If you implemented Batch Norm on mini-batches of (say) 256 examples,
then to evaluate on one test example, duplicate that example 256 times
so that you’re working with a mini-batch the same size as during
training.

Skip the step where you normalize using μ

and σ2

since a single test example cannot be normalized.

Use the most recent mini-batch’s value of μ

and σ2

to perform the needed normalizations.

Perform the needed normalizations, use μ

and σ2

estimated using an exponentially weighted average across mini-batches
seen during training.

Correct 

Question 10

*Correct*

1 / 1 points

10. Question 10 {.c-assess-question-number}
---------------

Which of these statements about deep learning programming frameworks are
true? (Check all that apply)

Even if a project is currently open source, good governance of the
project helps ensure that the it remains open even in the long term,
rather than become closed or modified to benefit only one company.

Correct 

A programming framework allows you to code up deep learning algorithms
with typically fewer lines of code than a lower-level language such as
Python.

Correct 

Deep learning programming frameworks require cloud-based machines to
run.

Un-selected is correct 

I, **Mohan R Raheja**, understand that submitting work that isn’t my own
may result in permanent failure of this course or deactivation of my
Coursera account. 

Learn more about Coursera’s Honor Code

Submitting...Submit error! Please try again.

Submit Quiz

Submit Quiz

**

**

**

\<img height="1" width="1" style="display:none"
src="https://www.facebook.com/tr?id=946401778754875&amp;ev=PageView&amp;noscript=1"\>

![](./Coursera%20_%20Online%20Courses%20From%20Top%20Universities.%20Join%20for%20Free%20_%20Coursera_files/0)

### Confirm Navigation

Are you sure you want to leave this page?

Stay on this Page

  

Leave this Page

### Confirm Navigation

Are you sure you want to leave this page?

Stay on this Page

  

Leave this Page


