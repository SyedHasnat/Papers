[![PWC](https://img.shields.io/endpoint.svg?url=https://paperswithcode.com/badge/multi-horizon-short-term-load-forecasting/univariate-time-series-forecasting-on-aep)](https://paperswithcode.com/sota/univariate-time-series-forecasting-on-aep?p=multi-horizon-short-term-load-forecasting)

[![PWC](https://img.shields.io/endpoint.svg?url=https://paperswithcode.com/badge/multi-horizon-short-term-load-forecasting/multivariate-time-series-forecasting-on-aep)](https://paperswithcode.com/sota/multivariate-time-series-forecasting-on-aep?p=multi-horizon-short-term-load-forecasting)

# DOI
[![DOI](https://zenodo.org/badge/643206708.svg)](https://zenodo.org/badge/latestdoi/643206708) 

## Title
#### Multi-Horizon Short-Term Load Forecasting Using Hybrid of LSTM and Modified Split Convolution
## Abstract
Precise Short-Term Load Forecasting (STLF) plays a crucial role in the smooth operation of power systems, future capacity planning, unit commitment, and demand response. However, due to its non-stationary and its dependency on multiple cyclic and non-cyclic calendric features and non-linear highly correlated metrological features, an accurate load forecasting with already existing techniques is challenging. To overcome this challenge, a novel hybrid technique based on long short-term memory (LSTM) and a modified Split-Convolution (SC) neural network (LSTM-SC) is proposed for single-step and multi-step STLF. The concatenating order of LSTM and SC in the proposed hybrid network provides an excellent capability of extraction of sequence-dependent features and other hierarchical spatial features. The model is evaluated by the Pakistan National Grid load dataset recorded by the National Transmission and Dispatch Company (NTDC). The load data is pre-processed and multiple other correlated features are incorporated into the data for performance enhancement. For generalization capability, the performance of LSTM-SC is evaluated on publicly available datasets of American Electric Power (AEP) and Independent System Operator New England (ISO-NE). The effect of temperature, a highly correlated input feature, on load forecasting is investigated either by removing the temperature or adding a Gaussian random noise into it. The performance evaluation in terms of RMSE, MAE, and MAPE of the proposed model on the NTDC dataset are 500.98, 372.62, and 3.72\% for multi-step while 322.90, 244.22, and 2.38\% for single-step load forecasting. The result shows that the proposed method has less forecasting error, strong generalization capability, and satisfactory performance on multi-horizon.
## Network Architecture
Hybrid of LSTM and Modified Split Convolution (LSTM-SC)
![alt text](https://github.com/SyedHasnat/Papers/blob/main/Figure%205%20complete_model.png)
## Datasets Used
- Independent System Operator New England (ISO-NE)
- American Electric Power (AEP)
- National Transmission and Dispatch Company (NTDC)
## Forecasting
single-step and multi-step STLF
## Code Files
All the code files for the paper "Multi-Horizon Short-Term Load Forecasting Using Hybrid of LSTM and Modified Split Convolution" are availible in the folder "PeerJ" as well in Code-Files, both the folders have the same code.
## Installation
To run code for paper, follow these steps:

1. Clone the repository: `git clone https://github.com/[SyedHasnat]/[Papers].git`
## Contributing
Contributions are welcome! If you find any issues or have suggestions for improvements, please feel free to open an issue or submit a pull request.
## Contact
If you have any questions or need further assistance, you can reach me via:

- Email: [eng.syed.its@gmail.com](mailto:eng.syed.its@gmail.com)
- LinkedIn: [Syed Muhammad Hasanat](https://www.linkedin.com/in/syed-muhammad-hasanat-a56562204/)



