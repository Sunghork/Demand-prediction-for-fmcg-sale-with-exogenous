# Demand-prediction-with-exogenous
| Dataset        | % Split | Days Count |
|----------------|---------|------------|
| Training Set   | 70%     |    1277    |
| Validation Set | 15%     |    274     |
| Test Set       | 15%     |    274     |


## Project road map
![1](https://github.com/Sunghork/Demand-prediction-for-fmcg-sale-with-exogenous/blob/main/Report/image.png)

## Feature engineering to include the exogenous variable by using binary encoding
![1](https://github.com/Sunghork/Demand-prediction-for-fmcg-sale-with-exogenous/blob/main/Report/image-1.png)

## Using 30 days rolling forward to predict the next day and repeat this process until all the test period are predicted
![1](https://github.com/Sunghork/Demand-prediction-for-fmcg-sale-with-exogenous/blob/main/Report/image-2.png)

## LSTM model processing
![1](https://github.com/Sunghork/Demand-prediction-for-fmcg-sale-with-exogenous/blob/main/Report/image-3.png)

## TFT model processing
![1](https://github.com/Sunghork/Demand-prediction-for-fmcg-sale-with-exogenous/blob/main/Report/image-4.png)

## Result of TFT model
TFT model with exogenous variable illustrate the less error magin with the ability to capture the spike in the demand sales better with 12.7%(Std +/- 0.3)
![1](https://github.com/Sunghork/Demand-prediction-for-fmcg-sale-with-exogenous/blob/main/Report/image-5.png)
