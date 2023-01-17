1. What types of ML do we cover in IAML? <br>
Answers:
- [x] regression
- [ ] analysis
- [x] classification
- [ ] reasoning
- [ ] interpretation
- [x] clustering

2. Which of the following types of problems are machine learning problems?
- [x] Given a large database of previous opinion polls and election results, learn a function that can predict a forthcoming election result given current opinion polls
- [x] Given an email, predict whether it is spam or not
- [x] Given an image, predict whether it contains a face or not
- [ ] Given a cookbook full of haggis recipes, and a set of ingredients in my kitchen, learn a model to predict whether I can make a haggis

3. Match up the attribute type on the left with the examples of values on the right

A. Animal, Vegetable, Fish (Categorical) <br>
B. 10.1, 15.6, 1.3 (Numerical) <br>
C. Low, Medium, High (ordinal) <br>

	
4. Normally categorical attributes are represented by numbers so that we can compute with them more efficiently.  Given that kind of representation, the following operations on two attribute values (a and b) are meaningful:

- [X] A. a = b <br>
- [ ] B. a2 <br>
- [ ] C. a < b 

5.  Normally ordinal attributes are represented by numbers so that we can compute with them more efficiently.  Given that representation, the following operations on two attribute values (a and b) are meaningful:

- [X] A. a < b <br>
- [ ] B. a + b <br>
- [X] C. a = b

6. Which of the following operations are meaningful for two numerical attribute values a and b?

- [X] A. a = b
- [X] B. a < b
- [X] C. a + b

7. Normalisation of attribute values applies to the following types of attributes:

- [ ] Ordinal
- [ ] Categorical
- [X] Numeric

7. Normalisation of attribute values applies to the following types of attributes:

- [ ] Ordinal
- [ ] Categorical
- [X] Numeric

8. The purpose of normalisation is to:
- [ ] remove outliers from the training data
- [ ] quantize values into discrete non-overlapping ranges
- [ ] make all values of attributes be non-negative
- [X] make values of different attributes be roughly comparable

9. Normalisation can be achieved by all of the following methods:

- [X] converting the data to overlapping numerical ranges
- [X] removing outliers
- [X] taking the logarithm of the values
- [X] converting to zero mean and unit variance
- [X] converting to the range [0,1]
- [ ] binarizing by converting all values to {0,1}
- [ ] visualising  so as to be able to find and remove data points with unusually large or small values

10. Match up the following numerical attribute issues with a way of dealing with it

- Outliers can be found by -> E. visualising and observing datapoints with unusual values.
- Skewed distributions can be dealt with by -> C. taking the logarithm of the values.
- A non-monotonic relationship between numerical or ordinal values and the class can be dealt with by -> D. converting the values to a variety of overlapping numerical ranges.

11. Normalising (e.g., if we scale, centre and deslant the image) allows us to use post-normalisation pixel values as features for classification
- [ ] It depends on the types of images and the classi�cation task
- [ ] Never
- [ ] Always
- [X] It depends on the pixel values in the images

12. For object recognition in images, we want attributes that are
- [X]invariant to irrelevant differences in the training images such as scale, rotation, lighting
- [ ] normalised across the training images
- [ ] the result of taking the Fourier transform of the images
- [X] have similar values for images in the same class and different values for images in different classes

13. For representing text, which would be the better choice?
- [X] use the possible words (the vocabulary) as the attribues and the existince of that word in the document as the value.
- [ ] use the position of the word as the attribute (e.g., first, second, third, ...) and the word at that position as the value

14. For representing sound signals such as speech or music, a good representation could be based on
- [ ] the duration of the signal
- [ ] a histogram of the amplitudes of the signal
- [ ] the amplitude of the signal at each time point
- [X] the frequencies present in the signal

15. Accuracy is a good success metric for comparing classifiers if
- [X] the classes are balanced
- [ ] it is an image recognition problem
- [ ] there are only two classes
- [ ] the attributes are numeric

16. Differences between Generative and Discriminative classifiers include
- [X] Generative models the classes, discriminative models the decision boundary
- [ ] Generative models the decision boundary, discriminative models the classes
- [ ] Generative may or may not be probabilistic, discriminative is almost always probabilistic
- [X] Generative is almost always probabilistic, discriminative may or may not be probabilistic
- [ ] Generative can't use unlabelled data, discriminative can
- [X] Discriminative can't use unlabelled data, generative can