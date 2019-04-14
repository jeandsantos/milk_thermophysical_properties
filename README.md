# Modeling of the Thermophysical Properties of Milk
**Predicting the Heat Capacity, Thermal Conductivity and Density of Milk with Temperature, Water and Fat Content**

The objective of this document is to develop statistical models that predict the heat capacity, thermal conductivity and density of milk with various concentrations of fat and water. Various polynomials functions were trained and tested on a training set using best subset regression and assessed using R-squared, adjusted-R-squared and cross-validation statistics using leave-one-out cross validation (LOOCV). The final models selected were assessed on a hold-out test set.

The data used for this project was obtained from the research paper [*Influence of Temperature and Water and Fat Contents on the Thermophysical Properties of Milk*](https://pubs.acs.org/doi/pdfplus/10.1021/je025546a), Minim et al., Journal of Chemical & Engineering Data 2002 47 (6), 1488-1491.

A report with the exploratory data analysis, modeling and model validation is available on [RPubs](https://rpubs.com/jeandsantos88/milk_thermophysical_properties).

A online app for the prediction of the thermophysical properties is [available online](https://jeandsantos.shinyapps.io/App_Milk_Thermophysical_Properties/) hosted by ShinyApps.
