# Model Card

See the [example Google model cards](https://modelcards.withgoogle.com/model-reports) for inspiration. 

## Model Description

**Input:** Describe the inputs of your model 

https://github.com/hodsong/25_3/blob/main/data_sheet.md

**Output:** Describe the output(s) of your model

Prediction of credit worthiness of an individual where no pre-existing credit report exists.

**Model Architecture:** Describe the model architecture you’ve used

Baseline Notebook : The model selected in the baseline code is Random Forest Regressor with optimised hyperparameters {'criterion': 'absolute_error', 'max_depth': None, 'max_features': None, 'min_samples_leaf': 2, 'min_samples_split': 5, 'n_estimators': 10, 'random_state': 42}

Optimised Notebook(s) : 

Further information is available in the respective notebooks.

## Performance

Give a summary graph or metrics of how the model performs. Remember to include how you are measuring the performance and what data you analysed it on. 

Baseline Notebook : 

The baseline code performs as follows :

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

Optimised Notebook(s) : 

Further information is available within the respective notebooks.

## Limitations

Outline the limitations of your model.

Optimised Notebook(s) : 

## Trade-offs

Outline any trade-offs of your model, such as any circumstances where the model exhibits performance issues. 

Optimised Notebook(s) : 
