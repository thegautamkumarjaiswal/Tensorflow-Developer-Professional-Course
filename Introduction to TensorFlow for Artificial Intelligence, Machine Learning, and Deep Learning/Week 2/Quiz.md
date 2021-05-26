### Question 1: What’s the name of the dataset of Fashion images used in this week’s code?

* Fashion Data
> **Fashion MNIST**
* Fashion MN
* Fashion Tensors

### Question 2: What do the above mentioned Images look like?

* 28x28 Color
* 82x82 Greyscale
* 100x100 Color
> **28x28 Greyscale**

### Question 3: How many images are in the Fashion MNIST dataset?

* 10,000
> **70,000**
* 60,000
* 42

### Question 4: Why are there 10 output neurons?

> **There are 10 different labels**
* Purely arbitrary
* To make it classify 10x faster
* To make it train 10x faster

### Question 5: What does Relu do?

* It returns the negative of x
* It only returns x if x is less than zero
> **For a value x, it returns 1/x**
* It only returns x if x is greater than zero

### Question 6: Why do you split data into training and test sets?

* To make training quicker
* To train a network with previously unseen data
> **To test a network with previously unseen data**
* To make testing quicker

### Question 7: What method gets called when an epoch finishes?

> **on_epoch_end**
* on_end
* on_epoch_finished
* On_training_complete

### Question 8: What parameter to you set in your fit function to tell it to use callbacks?

* callback=
* oncallback=
> **callbacks=** 
* oncallbacks=