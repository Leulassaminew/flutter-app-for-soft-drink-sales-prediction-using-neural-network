# flutter app for soft drink sales prediction using XGBoost Regressor
## Fine tuned XGBoost regressor



[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://travis-ci.org/joemccann/dillinger)

This app is used to predict sales in specific areas in Ethiopia and then used to calculate best route to market decisions. Also used to allocate resources and estimate demand for production.
Specifically built to predict sales for 
- Coca-Cola
- Sprite
- Fanta
## Model Deployment
    Model deployed to railway as an API
    API=https://api-production-3288.up.railway.app/predict
## R2_score 89%
![r2](https://github.com/Leulassaminew/flutter-app-for-soft-drink-sales-prediction-using-neural-network/assets/88404832/a16df20e-e219-4a5d-83c4-e0dfe6acc2b6)
## Parameters to predict sales

- City
- Latitude
- Longitude
- Distributor
- Brand
- Container Type
- Size
- Price
- Pop

## Training_data
shape of training data=(6376, 10)
![gg](https://github.com/Leulassaminew/flutter-app-for-soft-drink-sales-prediction-using-neural-network/assets/88404832/af78f07e-0a28-4bb1-96f6-505fa21d4a20)
![gg2](https://github.com/Leulassaminew/flutter-app-for-soft-drink-sales-prediction-using-neural-network/assets/88404832/e1cb92a7-818c-4348-a9ec-c5b377dc5482)

The above matrix shows the correlation amongst the parameters
