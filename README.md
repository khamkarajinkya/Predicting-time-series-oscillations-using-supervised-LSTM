# Predicting-time-series-oscillations-using-supervised-LSTM
Predict choppy trends in Unemployment rate from a lagged GDP series using long short term memory networks

It is difficult to model trends and oscillations, due to their inconsistent and volatile behaviour. But this task becomes relatively easy using a supervised learning approach with a secondary series whose oscillations are comparable to the original series. This project is an extension to an existing academic report I made for the course of exploratory data analysis. The challenge then was to identify a series which closely followed the unemployemnt time series. 

![git](https://user-images.githubusercontent.com/29556523/27756326-8e9a4d24-5dc4-11e7-8510-f14446a56f2c.png)

It can clearly be inferred R-GDP rate follows a lagged inverse relationship with the unemployment series. 

For the purpose of this project I have used long short term memory networks, they are an extension to recurrent neural networks and perform an excellent job at remembering sequences. The goal was to understand whether my model fed with the GDP series could understand the inconsistencies in the unemployment series. As you will find at the end of the report, my model does an excellent job of using Rreal-GDP series to closely follow the unemployment time series

```
Data- 2 time series R-GDP and unemployment rate are available under the data folder
Model- Jupyter notebook of the model is available under the model folder
Report- The original report for the academic assignment is available under EDA folder, the report for this project is embedded into the model notebook. The code for the original academic report is available under the EDA Folder 
```
HTML format report with the embedded model

https://rawgit.com/khamkarajinkya/Predicting-time-series-oscillations-using-supervised-LSTM/master/report/LSTM_Implementation.html
