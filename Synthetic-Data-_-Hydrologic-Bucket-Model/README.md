# Synthetic-Data-_-Hydrologic-Bucket-Model
This dataset is a synthetic data generated from a hydrologic bucket model for the purpose of evaluation and comparison of causal discovery algorithms. The data include four variables: rainfall (R), soil moisture (S), interflow (I) and runoff (Q). 

The analysis using this data is provided in the article:
Ombadi, M., Nguyen, P., Sorooshian, S., & Hsu, K. L. (2020). Evaluation of methods for causal discovery in hydrometeorological systems. Water Resources Research, 56(7), e2020WR027251. https://doi.org/10.1029/2020WR027251

There are three types of data matrices:

- det.txt 

              Deterministic simulations with a very small process noise added to the model (Signal to Noise ratio (SNR)= 10,000).  
              The matrix size (l,v). l is the number of simulations, and it is equal to 309,000. v is the number of variables, and it is equal to 4 ordered as (R, S, I, Q).    



- pro_noise_"SNR".txt (SNR values of 2, 3, 4, 5, 10, 20)

               Deterministic simulation with process noise added to the model. Process noise ranges from SNR=2 [dB=3] (high noise) to SNR=20 [dB=13] (low noise).
               The matrix size (l,v). l is the number of simulations, and it is equal to 309,000. v is the number of variables, and it is equal to 4 ordered as (R, S, I, Q). 
               
  
- obs_noise_"SNR".txt (SNR values of 2, 3, 4, 5, 10, 20)

               Deterministic simulation with observational noise added to the model. Process noise ranges from SNR=2 [dB=3] (high noise) to SNR= 20 [dB=13] (low noise).
               The matrix size (l,v). l is the number of simulations, and it is equal to 309,000. v is the number of variables, and it is equal to 4 ordered as (R, S, I, Q). 
  
