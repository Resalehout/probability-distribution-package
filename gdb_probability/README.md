This is a python package for calculating and visualizing Binomial and Gaussian distributions.

The afformentioned classes, inherit from the General distribution class which contains the following attributes:
    - mean (float) representing the mean value of the distribution
    - stdev (float) representing the standard deviation of the distribution
    - data_list (list of floats) a list of floats extracted from the data file
as well as a method to read in a data file.


BINOMIAL DISTRIBUTION

Attributes:
    - mean (float) representing the mean value of the distribution
    - stdev (float) representing the standard deviation of the distribution
    - p (float) representing the probability of an event occurring
                

    
A binomial distribution is defined by two variables: 
    - the probability of getting a positive outcome 
    - the number of trials
    
If you know these two values, you can calculate the mean and the standard deviation

For example, if you flip a fair coin 25 times, p = 0.5 and n = 25,
You can then calculate the mean and standard deviation with the following formula:
    - mean = p * n
    - standard deviation = sqrt(n * p * (1 - p))


GAUSSIAN DISTRIBUTION

Attributes:
    - mean (float) representing the mean value of the distribution
    - stdev (float) representing the standard deviation of the distribution

Both modules include methods to calculate the mean, standard deviation, and probability density function of the distribution as well as plot a histogram to visualize the distribution of data. They also include a method to add two distributions (for clarity, that is either two Gaussian or two Binomial distribution but not a Gaussian and Binomial distribution.)



HOW TO INSTALL
In your command line, type:
"pip install prob-distributions"

To use either object, open your python interpreter in your command line or use whatever IDE is available and input:
"from prob_distribution import Binomial, Gaussian"
    
     