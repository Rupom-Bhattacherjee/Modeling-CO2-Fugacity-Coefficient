Fugacity is a fundamental thermodynamical property of gas and gas mixtures to determine their behavior and dynamics in complex systems. 
Fugacity can be deduced experimentally from the measurements of volume as a function of pressure at constant temperature or calculated iteratively using analytical equations of states (EOS). 
Experimental measurement is time-consuming, and analytical models based on EOS are computationally demanding, especially when an approximate but quick estimation is desired. 
In this work, machine learning (ML) is employed as a viable alternative to analytical EOSs for quick and accurate approximation of CO2 fugacity coefficients. 
Five different ML algorithms are used to estimate the fugacity coefficients of pure CO2 as a function of pressure (≤ 2000 bar) and temperature (≤ 1000 °C). 
A combination of experimental and pseudo-experimental (obtained from an analytical EOS) data of CO2 fugacity coefficients is used to train, validate, and test the models. 
The best results were found using the Extreme Gradient Boosting algorithm, which showed a mean square error of only 0.0002 in the validation data and an average deviation of only 1.3% in the test data (pure prediction). To quantify the effectiveness of the machine learning techniques, results from the best-performing model are compared with two state-of-the-art analytical models. The ML model with significantly less computational complexity showed similar accuracy to the analytical models. The estimated fugacity data are then used to compute the CO2 solubility in aqueous NaCl solution of different concentrations, and a maximum deviation of only 3.2% from the experimental data is observed. 
The XGb model is available here under the name XGBModel_phi_rf.sav. 
Check Out the supplementary file to know how to use the model.
To know the details of this work check out our publication: https://doi.org/10.1016/j.ijggc.2023.103971
