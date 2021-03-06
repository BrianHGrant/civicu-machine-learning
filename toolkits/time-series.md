# Time Series

Time Series are data sets gathered from systems that evolve over time and where time is the main feature of the data set. Modeling (predicting) time series is tricky because it requires a completely different way of looking at the data than most other classification or regression problems.

## Purpose

This toolkit will help you recognize time series data and machine learning problems and become familiar with the tools and techniques you can use to solve those problems. 

## Overview

Time series datasets are features that evolve over time. The inputs (features) for a time series model are typically the feature values for some period of time in the past and the outputs are some of those same features but at times in the future. And the definition of past and future is incrementally moved forward in time to create “rows” of features to feed into a Machine Learning algorithm to produc that model

## Examples

Here are some example applications of machine learning to time series.

Stock Prices: Predict stock prices, asset prices, resource prices
Weather: Forecast weather on Mt Hood
Traffic: Forecast bike traffic across Hawthorne bridge
Finance: Predict Portland bond monthly interest rate payments for next 20 years
Population: Predict Portland or Oregon population for next 20 years
Energy: Predict solar power generation and commercial building consumption to optimally control battery “draw down”

Do these examples help you think of similar examples of time series that might be interesting to model? What about “civic” examples at governments and nonprofits in your neighborhood, Portland as a whole, Oregon, the US, or global organizations like the UN? 

## Details

Modeling and predicting time series data is difficult. The correspondence between inputs (predictive features) and outputs (things you are trying to predict) isn’t obvious. Preparing time series data for Machine Learning requires much more processing, in different ways. Digital Signal Processing (DSP) is a whole electrical engineering speciality dedicated to processing time series using techniques like filtering, windowing, transforming, frequency analysis. And, very often, the outputs are reused as inputs, by shifting them in time. This reuse of the outputs as inputs makes it more difficult to avoiding “cheating” by accidentally giving the model the “answer” in your input features.

However, it’s possible to transform all time series data into a format that can be used for 

## Gotchas

Periodicity (“seasonality”)
Confounding factors (“common response variable", "third variable correlation", "lurking variable")

Time series data is often highly correlated with repeating periodic oscillations in the signals that may subside or grow over time or for short periods of time. This provides several oportunities for transforming your input features with feature engineering to help your machine learning algorithm detect and utilize these periodicities to improve your model’s accuracy.
Opportunities
Transformation from Time Domain to Frequency Domain (FFT, Wavelets): compute the magnitude of a signal in each dominant frequency of the periodic components within a signal.
 Extraction of datetime features (using Pandas)  like `weekday`, season of the year, time of day, whether it’s rush hour or lunch hour or on a holiday, etc.
Dynamic Time Warping

## Projects and Exercises

### Resources

Take a break after any detailed reading of one of these resources in earnest. They are mostly provided as references to be skimmed for ideas and approaches if you ever encounter time series data in your machine learning application.

Portland Crime Incidents 2013-2015. Applications and approaches for ML on time series. Advanced discussion of signal stationarity

Slides: [Machine Learning Strategies for Time Series Prediction](http://www.ulb.ac.be/di/map/gbonte/ftp/time_ser.pdf) by Gianluca Bontempi for CS212 lecture in University course
Applications and approaches for ML on time series. Advanced discussion of signal stationarity

Python: [Time Series / Date](http://pandas.pydata.org/pandas-docs/stable/timeseries.html functionality) 
Pandas methods for processing time series. Think of each method as a possible new feature you could derive from an existing datetime in your dataset.













Podcasts and Videos







This section is where you can organize external resources for reference such as:
Podcasts
Videos
Documentation - can be summary notes from what you covered in class, or case studies/real work examples and problems. 
“Cheat sheet” - List of things that can spark memory when working through exercises or projects. ex.  list of commands, definitions, vocabulary.
Recipes - Think of this like you would when writing a cake recipe.You list what kind of cake, provide a list of ingredients, step by step instructions of how to blend those ingredients, techniques (tips and tricks), and how long to bake the cake.  
Time estimate for each exercise/activity.
For more complex work, suggesting that students take a break after “x” amount of time or to wipe their work and start over from a clean slate is helpful. By taking breaks students are able to walk away from the problem or obstacle and come back with a fresh mind to tackle the project from a different angle. Wiping their previous work and starting from a clean slate gives the student an opportunity to see the progress they are making in learning the subject because they are going back and coding something they have already done.

Self Assessment: Choose one topic from your curriculum that you would like to develop a toolkit for. Use this toolkit as a guide to create your own toolkit. Depending on your experience and if you have created one before expect to spend anywhere from 30 minutes to 2 hours for initial setup, and several hours to verify the resources and exercises. This should take you as much time as your best student to work through.  





