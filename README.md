Monash Boot camp Challenge Week 21

Code: Mark Peck

Starter Code: edX

Overview

    This challenge was designed to create a neural network to predict the success of funding applicants to the fictional group "Alphabet Soup".
    In simple terms, this machine learning program should learn from the supplied data and be able to predict whether a funding applicant may be successful in the future.

Results

    Data Preprocessing:
        Target: IS_SUCCESSFUL
        Features: All columns except EIN and NAME
        Removed Variables: EIN, NAME

    Model Structure:
        Neurons and Layers:
        Three layers were used in the initial model, with the initial two using ReLU and with 64 neurons each. The final layer uses Sigmoid with a single neuron.
        Later, KerasTuner was used to ensure that more paramaters could be explored in a shorter amount of time.
        
        Performance: In short, even KerasTuner couldn't acheive an accuracy rating of 75%. 
        
        Optimization Steps: During previous attempts, which are not recorded, different features (DataFrame columns) were dropped, different bins tried, 
        and different activation functions with extra layers were trialed. None of these differences changed the outcome
        of the KerasTuner results, with generally the highest accuracy rating achieved being %72-73.

Summary

    Overall Results: The neural network seems to be underperforming with this data. 
    Recommendation: The author of this ReadMe has few recommendations that appear useful.
