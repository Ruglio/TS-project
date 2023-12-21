Implementation of SARIMA - Seasonal AutoRegressive Integrated Moving Average - model to forecast and analyse the number of international arrivals to New Zealand, using Rmd (R notebooks).
First the resiuduals are analyzed, using ACF (AutoCorrelation Function) and PACF (Partial AutoCorrelation Function) to be sure that they are stationary.
![ACF and PACF](https://github.com/Ruglio/TS-project/assets/67823727/481d3d35-af6c-44a1-9472-a35aecd1dd05)

Then, the resulting model is tested, to understand how it fits the data.
![fit](https://github.com/Ruglio/TS-project/assets/67823727/b7908e75-13d8-4ddb-b7f0-f32fdb530954)
