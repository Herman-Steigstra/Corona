# Corona
Statistical model for prediction of death after vaccination

Prediction of death caused by the vaccination with mRNA vaccins (in the Netherlands mainly Pfizer) by a statistical model. The model assumes that 1:4800 vaccinations results in death within 2 weeks and a possibility of 1:1850 to die between 4 and 24 months after vaccination. For the boosters the risk seems to be raised to 1:3000. After 5 vaccination (2 primary and 3 boosters) the total risk of death by vaccination is 0,4% or 1 : 250.
A description of the model can be found on this site:

https://www.maurice.nl/2022/12/12/vaccinatiesterfte-gemodelleerd/

Steps in the processing:
1) Correct for undermortality in the next 2 months
2) Create prediction by estimating three factors in the model: a) short term base series b) short term boosters and c) long term factor
