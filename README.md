# Neural_Network_Charity_Analysis

## Overview

Using neural networks, we will design and train models using the Python TensorFlow library to help Beck's, a data scientist and programmer, and Alphabet Soup. Alphabet Soup is a nonprofit foundation. They’re a philanthropic foundation dedicated to helping organizations that protect the environment, improve people’s well-being, and unify the world. Alphabet Soup has raised and donated over 10 billion dollars in the past 20 years. This money has been used to invest in lifesaving technologies and organized reforestation groups around the world. We will analyze the impact of each donation and vet potential recipients to ensure that the foundation’s money is being used effectively. Unfortunately, not every donation the company makes is impactful. In some cases an organization will take the money and disappear. As a result, Alphabet Soup’s president Andy Glad has asked Beck’s to predict which organizations are worth donating to and which are too high risk.We are to create a mathematical data driven solution that can do this accurately. We will design and train a deep learning neural network. This model will evaluate all types of input data and produce a clear decision making result. 

## Results
 
### Data Preprocessing

            What variable(s) are considered the target(s) for your model? The variabe that I considered the target was "Is-Successful". Ultimately this is what we want to know about the funds being used.
         
            What variable(s) are considered to be the features for your model? name, application, type, affiliation, classification, use_case, organization, income_amt, special_considerations, status, and ask_am
            
            What variable(s) are neither targets nor features, and should be removed from the input data? EIN because it is ultimately a duplicate column of information another identifier for the name of the organization. Since special_consideration cannot be catagorized, it is neither a target nor a feature.
            
### Compiling, Training, and Evaluating the Model

            How many neurons, layers, and activation functions did you select for your neural network model, and why?
            Were you able to achieve the target model performance?
            What steps did you take to try and increase model performance?

## Summary
Overall, by increasing the accuracy above 75% we are able to correctly classify each of the points in the test data 75% of the time. And, an applicant has a 80% chance of being successful if they have the following:
-- The NAME of the applicant appears more than 5 times (they have applied more than 5 times)The type of APPLICATION is one of the following; T3, T4, T5, T6, T7, T8, T10, and T19The application has the following CLASSIFICATION; C1000, C2000, C3000, C1200, and C2100.
A good model to recommend is the Random Forest model because Random Forest are good for classification problems. Using this model produces a 78% accuracy. 
