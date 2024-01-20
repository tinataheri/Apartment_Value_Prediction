The data cleaning process consisted of checking the types and languages of the datasets and fixing any mismatch between the 2021 and 2023 dataset. One noticeable feature about the dataset was the amount of missing data.

![Picture1](https://github.com/tinataheri/Apartment_Value_Prediction/assets/79693066/de612a57-45fb-4cc4-9b24-42514cb35fa9)

This was fixed by using the mode for the categorical missing values and knnImputing for numerical values such as area and price. 
Upon cleaning the data and saving the important features, the correlation between them is displayed down below.

2021 dataset:
![Picture2](https://github.com/tinataheri/Apartment_Value_Prediction/assets/79693066/e3c775d6-e50f-4f10-b1de-5ea197692191)

2023 dataset:

(The blue lines display bad value as there is a tangible difference between the classes.)
1.0    136787
0.0     33737

![Picture4](https://github.com/tinataheri/Apartment_Value_Prediction/assets/79693066/33ae0b01-73ac-4186-82b8-f5ac5e067fd0)

After analyzing the data and correlations, a regression model was trained on the 2023 data. The following plot displays the most important feature of the model with the highest accuracy.

![Picture5](https://github.com/tinataheri/Apartment_Value_Prediction/assets/79693066/9dead3f5-06c1-48b0-92f8-90aab01efaba)

The same model was fine tuned on the 2021 dataset, although because of it’s high number of missing data, the model’s accuracy was noticeably lower than the 2023 model.

![Picture6](https://github.com/tinataheri/Apartment_Value_Prediction/assets/79693066/56c05dfd-e6ff-4d38-8601-13542470591d)

Afterwards, the 2021 dataset was given to the 2023 model to predict its price in 2023. 

![Picture7](https://github.com/tinataheri/Apartment_Value_Prediction/assets/79693066/d723915f-f5b1-4508-8a33-c6f2b420c2b1)

And 2023 data on the 2021 model.

![Picture8](https://github.com/tinataheri/Apartment_Value_Prediction/assets/79693066/6bb81346-25d4-4d96-9452-492657d57030)


