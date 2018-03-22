**Back

Practical aspects of deep learning {.attempt-title .display-1-text}
==================================

Quiz, 10 questions

8/10 points (80%)

**

**Congratulations! You passed!**

Next Item

loading   ![](./c2w1q1_dl_files/loading.gif)

Load Error!

Question 1

*Correct*

1 / 1 points

1. Question 1 {.c-assess-question-number}
-------------

If you have 10,000,000 examples, how would you split the train/dev/test
set?

60% train . 20% dev . 20% test

33% train . 33% dev . 33% test

98% train . 1% dev . 1% test

Correct 

Question 2

*Correct*

1 / 1 points

2. Question 2 {.c-assess-question-number}
-------------

The dev and test set should:

Come from the same distribution

Correct 

Come from different distributions

Be identical to each other (same (x,y) pairs)

**Have the same number of examples**

Question 3

*Correct*

1 / 1 points

3. Question 3 {.c-assess-question-number}
-------------

If your Neural Network model seems to have high bias, what of the
following would be promising things to try? (Check all that apply.)

Get more training data

Un-selected is correct 

Increase the number of units in each hidden layer

Correct 

Get more test data

Un-selected is correct 

Add regularization

Un-selected is correct 

Make the Neural Network deeper

Correct 

Question 4

*Correct*

1 / 1 points

4. Question 4 {.c-assess-question-number}
-------------

You are working on an automated check-out kiosk for a supermarket, and
are building a classifier for apples, bananas and oranges. Suppose your
classifier obtains a training set error of 0.5%, and a dev set error of
7%. Which of the following are promising things to try to improve your
classifier? (Check all that apply.)

Increase the regularization parameter lambda

Correct 

Decrease the regularization parameter lambda

Un-selected is correct 

Get more training data

Correct 

Use a bigger neural network

Un-selected is correct 

Question 5

*Correct*

1 / 1 points

5. Question 5 {.c-assess-question-number}
-------------

What is weight decay?

The process of gradually decreasing the learning rate during training.

Gradual corruption of the weights in the neural network if it is trained
on noisy data.

A technique to avoid vanishing gradient by imposing a ceiling on the
values of the weights.

A regularization technique (such as L2 regularization) that results in
gradient descent shrinking the weights on every iteration.

Correct 

Question 6

*Correct*

1 / 1 points

6. Question 6 {.c-assess-question-number}
-------------

What happens when you increase the regularization hyperparameter lambda?

Weights are pushed toward becoming smaller (closer to 0)

Correct 

Weights are pushed toward becoming bigger (further from 0)

Doubling lambda should roughly result in doubling the weights

Gradient descent taking bigger steps with each iteration (proportional
to lambda)

Question 7

*Incorrect*

0 / 1 points

7. Question 7 {.c-assess-question-number}
-------------

With the inverted dropout technique, at test time:

You apply dropout (randomly eliminating units) and do not keep the
1/keep\_prob factor in the calculations used in training

You apply dropout (randomly eliminating units) but keep the 1/keep\_prob
factor in the calculations used in training.

You do not apply dropout (do not randomly eliminate units) and do not
keep the 1/keep\_prob factor in the calculations used in training

You do not apply dropout (do not randomly eliminate units), but keep the
1/keep\_prob factor in the calculations used in training.

This should not be selected 

Question 8

*Correct*

1 / 1 points

8. Question 8 {.c-assess-question-number}
-------------

Increasing the parameter keep\_prob from (say) 0.5 to 0.6 will likely
cause the following: (Check the two that apply)

Increasing the regularization effect

Un-selected is correct 

Reducing the regularization effect

Correct 

Causing the neural network to end up with a higher training set error

Un-selected is correct 

Causing the neural network to end up with a lower training set error

Correct 

Question 9

*Incorrect*

0 / 1 points

9. Question 9 {.c-assess-question-number}
-------------

Which of these techniques are useful for reducing variance (reducing
overfitting)? (Check all that apply.)

Gradient Checking

Un-selected is correct 

Vanishing gradient

Un-selected is correct 

Xavier initialization

Un-selected is correct 

Data augmentation

This should be selected 

Dropout

Correct 

L2 regularization

Correct 

Exploding gradient

Un-selected is correct 

Question 10

*Correct*

1 / 1 points

10. Question 10 {.c-assess-question-number}
---------------

Why do we normalize the inputs x

?

It makes the cost function faster to optimize

Correct 

Normalization is another word for regularization--It helps to reduce
variance

It makes it easier to visualize the data

It makes the parameter initialization faster

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

![](./c2w1q1_dl_files/0)

### Confirm Navigation

Are you sure you want to leave this page?

Stay on this Page

  

Leave this Page

### Confirm Navigation

Are you sure you want to leave this page?

Stay on this Page

  

Leave this Page


