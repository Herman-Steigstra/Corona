# Corona
Statistical model for prediction of death by vaccination

Prediction of death caused by the vaccination with mRNA vaccins (in the Netherlands mainly Pfizer) by a stastical model. The model assumes that 1:4800 vaccinations results in death withn 2 weeks and a possibility of 1:1850 to die between 4 and 24 months after vaccination. For the boosters the risk seems to be raised to 1:3000.
A description of the model can be found on this site, as of December 12 2022:

https://www.maurice.nl/2022/12/12/vaccinatiesterfte-gemodelleerd/

Steps in the processing:
1) correct for undermortality in the next 2 months
2) Create prediction by estimating thee factors in the model: a) short term base series b) short term boosters and c) long term factor
