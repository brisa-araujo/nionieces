# Ñoñeces
## String Operations - Bag of Words in Scikit-Learn

We will learn Scikit-Learn in Module 3 which has built in the BoW feature. Try to use Scikit-Learn to generate the BoW for this challenge and check whether the output is the same as yours. You will need to do some googling to find out how to use Scikit-Learn to generate BoW.

Notes:

To install Scikit-Learn, use `pip install sklearn`.

Scikit-Learn removes stop words by default. You don't need to manually remove stop words.

Scikit-Learn's output has slightly different format from the output example demonstrated above. It's ok, you don't need to convert the Scikit-Learn output.

The Scikit-Learn output will look like below:

```
# BoW:
{u'love': 5, u'ironhack': 3, u'student': 6, u'is': 4, u'cool': 2, u'am': 0, u'at': 1}

# term_freq:
[[0 0 1 1 1 0 0]
 [0 0 0 1 0 1 0]
 [1 1 0 1 0 0 1]]
 ```
