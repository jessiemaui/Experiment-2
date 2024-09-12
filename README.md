# EXPLOLRING NUMERICAL PYTHON: cast a brief look on my second experiment!

## Welcome to the second experiment in my programming journey.

### Let me introduce to you the NUMPY!

  a Numerical Python (NUMPY), a foundational library for a numerical computing in Python, providing support for large, multi-dimensional arrays and matrices, along with a collection of mathematical functions to operate on these 
    arrays.

First, we are going to determine our:
  I. Objectives
    a. To identify the codes and functions incorporated in the Numpy library.
    b. To be able to apply and use the different codes and function in creating a Python program using a Numpy library.

  II. Instruction
    Write a Python script/code in the Jupyter Notebook to do the given problems. You may submit your Jupyter notebook in the dedicated submission bin.

  #### We are diving into two core problems:
    1. Normalization Problem: Understanding the essense of data processing by centering and scaling data in Python using .mean() and .std()
    2. Divisble by 3 Problem: Creating a 10x10 matrix of squares of the first 100 positive integers.

      Problem 1: Normalization: Bringing Data to Center Stage
        In this experiment:
          Center our data by subtracting the mean of the dataset from each data point, and then, scale it by dividing each value by the standard deviation.

          Here's how it went!
          a. FIRST! writing a code for the first problem is just as easy because its already included in the numpy library and it only took me 4 code cells! Well, ofcourse that's only the code proper.
          b. SECOND! this is where my mind fogged so hard. I actually visited chatgpt to check how can I save my work as an .npy file and it kind of doesn't made sense at first but we did it!
          c. FINALLY! as I saved my work as .ipynb, .nyp file will already be available in the folder. 

            That's so cool, a reason why Python is a very strong programming language.

#### Moving on to the next core problem which is

      Problem 2: A Square Matrix of Perfect Squares
        In this experiment:
          Let's move on to something visually satisfying: constructing a 10 x 10 ndarray where each element is the sqaure of the first 100 positive integers.

          Here's how I did it!
          a. FIRST! I imported numpy and set A as the variable, and then, call the arange function to generate the values we need, perfect squares, of our start value which is 1 up to the stop value which is 100.
          b. SECOND! If you try to print it, it looks messy so I needed to call the reshape function to arrange our matrix into a 10x10 array with the needed data: the perfect squares between 1-100.
          c. THIRD! I summoned the modulus operator or the "%" sign you can see on my code to find the remaided when the value of A, which is the perfect squares of 1-100, when divided by 3. 
          d. FOURTH! As we can see, I added "== 0" to check if the remainder of the division of A divided by 3 is equal to 0. This evaluates to true which means that A is evenly divisible by 3 and false otherwise.
          e. LASTLY! The hard part for me, is saving it into .npy file. Just like what I did on the first one, I just replaced the variables from "X_.npy" to "div_by_3.npy".

          HOWEVER! If you can notice, I put another code cell under the fourth step, the reshape by (3,11) because, to be honest, I only want it to be in the same row and column as the first matrix in first and             second step. You know, for more organized coding!


## That concludes my second experiment in Advanced Programming and Algorithms.
### by refining our skills in data manipulation, we're moving closer to mastering the art of data preprocessing!
##### May we all enjoy coding and keep practicing.

Best regards,
Jessie Mae Domingo
2ECE-D
  
  

