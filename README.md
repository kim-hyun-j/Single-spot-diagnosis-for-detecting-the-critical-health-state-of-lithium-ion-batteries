# Single-spot-diagnosis-for-detecting-the-critical-health-state-of-lithium-ion-batteries


The code in this repository shows how to utilizing the data associated with the paper 'Single-spot diagnosis for detecting the critical health state of lithium ion batteries' by Hyunjae Kim, Inwoo Kim, Minsoo KIM et al. The data is available at . There you can also find more details about the data.

This analysis was originally performed in python

The data utilizing codes can be grouped into one of three categories: delta Q0.2C-1C related data, summary data, and DCIR@SOC5 at EOL data, regression.

delta Q0.2C-1C related data: Extracting  Q0.2C-1C(V), Var (delta Q0.2C-1C(V)) in every RPTs

summary data: Extracting 0.2C, 1C capacity, DCIR@SOC50, dQdV &dVdQ of 0.2C and 1C charging curves in every RPTs

DCIR@SOC5 at EOL data: Extracting DCIR@SOC5 at EOL data from GITT at EOL.

Regression: Machine learning code for estimating/predicting deg-SL and 2nd lifetime.
