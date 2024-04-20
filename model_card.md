# Model Card

See the [example Google model cards](https://modelcards.withgoogle.com/model-reports) for inspiration. 

## Model Description

**Input:** Describe the inputs of your model 

https://github.com/hodsong/25_3/blob/main/data_sheet.md

**Output:** Describe the output(s) of your model

Prediction of credit worthiness of an individual where no pre-existing credit report exists.

**Model Architecture:** Describe the model architecture you’ve used

The model selected in the baseline code is the Random Forest Regressor model. 

## Performance

Give a summary graph or metrics of how the model performs. Remember to include how you are measuring the performance and what data you analysed it on. 

The baseline performs as follows :

Best Estimator performance for Training set: 
- Mean Absolute Error: 754.1680
- Mean Absolute Percentage Error: 0.1220
- Mean Squared Error: 2336573.7760
- Root Mean Squared Error: 1528.5860

Best Estimator performance for Test set:

- Mean Absolute Error: 768.3270
- Mean Absolute Percentage Error: 0.1250
- Mean Squared Error: 2269981.5160
- Root Mean Squared Error: 1506.6460

## Limitations

Outline the limitations of your model.

## Trade-offs

Outline any trade-offs of your model, such as any circumstances where the model exhibits performance issues. 
