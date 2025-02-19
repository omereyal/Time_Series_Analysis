# Time Series Analysis of Carbon Fluxes in the Tapajós National Forest
Author: Omer Eyal

**Overview:**\n
This project analyzes time series data from the BR-Sa1 measurement site in the Tapajós National Forest, Brazil, as part of the Large-Scale Biosphere-Atmosphere Experiment in Amazonia (LBA). The study focuses on the Net Ecosystem Exchange (NEE) of CO₂, Vapor Pressure Deficit (VPD), and Temperature, using exploratory data analysis, gap-filling techniques, and time series decomposition.

The dataset originates from the FLUXNET network, which integrates regional observations of carbon, water, and energy fluxes using the Eddy Covariance technique.

**Objectives:**
* Perform exploratory analysis on key environmental variables.
* Identify and handle outliers using the Interquartile Range (IQR) sliding window method.
* Compare gap-filling techniques:
* FLUXNET default gap-filling method.
* Machine Learning approach (Random Forest).
* Conduct time series analysis, including:
* Resampling to monthly averages for trend analysis.
* Fourier Transform (FFT) for frequency analysis and seasonal decomposition.
* Comparison between classical and FFT-based seasonal decomposition.
* Moving average smoothing to remove noise.
* Autoregressive modeling (ARIMA) for time series prediction.
* Cross-correlation analysis between VPD, temperature, and NEE.
* Stationarity testing (Augmented D
