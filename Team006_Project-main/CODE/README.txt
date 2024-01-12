----------------------------DESCRIPTION------------------------
We've created an engaging website that allows users to input specific details about a car such as its year, odometer reading, model, drive type, fuel type, and manufacturer, and in turn, receive an estimated price for the vehicle. You can access the website in two ways: 
1. Run the website locally to predict the car's price.
2. Run directly through this website:carpricepredictor.azurewebsites.net

CarPrice-local packages requirement:
Flask
joblib
numpy
pandas
scikit_learn
lightgbm

CarPricePredictor-Azure packages requirement:
Flask
numpy
pandas
scikit_learn


----------------------------INSTALLATION------------------------
First method:
In order to run it locally, follow the steps below:
1. Download python and anaconda.
2. Unzip CarPrice-local.zip (in the CODE folder).
3. Open terminal, navigate to the the unzipped folder. 
4. Run "conda create -n newproject python=3.9".
5. Run "conda activate newproject".
6. Run "pip install -r requirements.txt".
7. Run "FLASK_APP=app.py flask run".
5. Open Chrome, enter "http://127.0.0.1:5000"
Then you will see the website. 

Second method:
You can run directly through this website:carpricepredictor.azurewebsites.net
---------------------------EXECUTION ---------------------------
The website offers a selection of features that users can choose from a list: 
1. manufacturer
2. model
3. drive
4. fuel
And other features require numerical input:
1. year 
2. odometer
All fields are mandatory, and once you complete the form you can click the 'ESTIMATE' button to receive their estimated price. 

