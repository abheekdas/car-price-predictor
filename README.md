# car-price-predictor
Linear Regression Project, that can be used to predict prices of car on the basis of make model, km driven, fuel type, year of make.

Price_Predictor.ipynb contains all the code that has been used to create a linear regression model. The data was firstly preprocessed and currated as it was containg some unwanted data. Then Linear regression model has been implemented using sckit-learn and the model is dumped using pickle.

application.py -> contains all the code that acts as web server for the project. The backend is developed using Flask where the dumped model is able to send responses of price prediction of car prices to the client.

Cleaned_Car.csv -> contains curated and processed data.

Files inside templates are used for rendering webpages. Static Folder contains all the static assets such as css used for formating design of the web page.

To run the Project clone the repo, and go to repo directory using terminal/command prompt and start the web server using command python3 application.py

Go to the localhost in your browser listed in the terminal/command prompt and try out the project!
