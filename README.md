# ml-recommender

This project contains two scripts. The first is an Anomaly detection algorithm to detect anomolous behavior in server computers based on the features throughput adn latency. The second is a recommender algorithm that implements a collaborative filtering learning algorithm to recommend movies to users based on how they have rated movies in the past.

Files included in this exercise

ex8.m - Octave/MATLAB script for first part of exercise

ex8 cofi.m - Octave/MATLAB script for second part of exercise

ex8data1.mat - First example Dataset for anomaly detection

ex8data2.mat - Second example Dataset for anomaly detection

ex8 movies.mat - Movie Review Dataset

ex8 movieParams.mat - Parameters provided for debugging 

multivariateGaussian.m - Computes the probability density function for a Gaussian distribution

visualizeFit.m - 2D plot of a Gaussian distribution and a dataset 

checkCostFunction.m - Gradient checking for collaborative filtering 

computeNumericalGradient.m - Numerically compute gradients

fmincg.m - Function minimization routine (similar to fminunc) 

loadMovieList.m - Loads the list of movies into a cell-array

movie ids.txt - List of movies

normalizeRatings.m - Mean normalization for collaborative filtering

submit.m - Submission script that sends your solutions to our servers 


[⋆] estimateGaussian.m - Estimate the parameters of a Gaussian dis- tribution with a diagonal covariance matrix

[⋆] selectThreshold.m - Find a threshold for anomaly detection

[⋆] cofiCostFunc.m - Implement the cost function for collaborative filtering

[⋆] indicates files with code written by me.


Run ex8 in octave for the Anomaly detection script (detecting anomalous behavior in server computers)

Run ex8 cofi in octave for the Recommender script (a collaborative filtering learning algorithm to recommend movies to users)
