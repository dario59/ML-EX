# ML-EX

The objective of this analysis is just to mess with data. I've downloaded a dataset with historic weather data for my city, then calculated the proabilities for apply the Hidden Markov Model. Then ofc I've apply it, to see what the prediction for weather will look like. 

**What's inside this branch**

-*Dataset stazioni.csv*: A dataset which basically is a Look Up for all the sensors for the Region, you can use it to quickly filter the website to search for data if you want records for a specific location;

-*Dataset prec_TOS19000077.csv*: the dataset i'll use to make the analysis, it contains record for my city; Data are in .csv format, field separator is ";", decimal separator is ",". Values "-9999", "@" stands for NA. Values "V" shows that data is cross validated, "P" it's an empirical data acquired by the sensors.


All the code is written in Python 3.X, in a Collab Notebook, using Tensorflow. Dataset is from Open Data provided by SIR - Regione Toscana. You can find all the data here: http://www.sir.toscana.it/consistenza-rete 
Code for model is mainly taken from Tensorflow documentation
