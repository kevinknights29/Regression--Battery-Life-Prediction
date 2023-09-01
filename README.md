# Regression--Battery-Life-Prediction

This project uses a regression algorithm to predict the battery life of Li-Ion batteries using the NASA Batteries PCoE dataset

## Dataset

Batteries
Experiments on Li-Ion batteries. Charging and discharging at different temperatures. Records the impedance as the damage criterion. The data set was provided by the NASA Prognostics Center of Excellence (PCoE).

Download Mirror: [nasa batery dataset zip](https://phm-datasets.s3.amazonaws.com/NASA/5.+Battery+Data+Set.zip)

Data Set Citation: B. Saha and K. Goebel (2007). "Battery Data Set", NASA Prognostics Data Repository, NASA Ames Research Center, Moffett Field, CA

Dataset URL: [dataset](https://www.nasa.gov/content/prognostics-center-of-excellence-data-set-repository)

## Results

We implemented models to predict two metrics RUL and SOH.

### Whats RUL?

The concept of Remaining Useful Life (RUL) is utilised to predict life-span of components (of a service system) with the purpose of minimising catastrophic failure events in both manufacturing and service sectors.

#### RUL Deep Learning Model Performance

![image](https://github.com/kevinknights29/Regression--Battery-Life-Prediction/assets/74464814/f02ca10c-2518-4c0c-8bb8-cb79237f675b)

### Whats SOH

The state of health (SOH), defined as the ratio of existing capacity to rated capacity or the present resistance to that of a fresh battery, is a key index for evaluating the health status and serviceability of batteries. As a result, one of the most critical responsibilities of prognostic and health management (PHM) is to accurately estimate the SOH of the battery in order to guide maintenance and assure safe usage.

#### Model comparision for SOH predictions

![image](https://github.com/kevinknights29/Regression--Battery-Life-Prediction/assets/74464814/5740ea52-5274-411f-ab1e-2c9419cc91a5)

## Conclusions

After carrying out the investigation, it was possible to conclude that the prediction of the useful life of lithium-ion batteries is a complex issue with many variables to consider. However, promising results were achieved using the deep learning method for battery life prediction.

It was observed that machine learning and statistical models are useful tools in predicting the useful life of batteries. It is important to highlight that the deep learning model is not only capable of predicting the useful life of the batteries, but it can also help to identify patterns and factors that may be influencing their degradation.

The results obtained in this research show that the use of deep learning methods for the prediction of the useful life of lithium-ion batteries can be a promising tool in optimizing their performance and prolonging their useful life. It is necessary to continue with future research, including the comparison of both computational and physical-mechanical models, in order to improve the accuracy of the predictions.
