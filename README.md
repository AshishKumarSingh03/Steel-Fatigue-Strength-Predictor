# Steel-Fatigue-Strength-Predictor
As a part of my Degree project, a fatigue strength dataset from the National Institute of Materials Science (NIMS), MatNavi, Japan was extracted. Complex Statistical models and machine learning models are applied to this dataset to fit the dataset without the loss of generality.

The dataset consists of just 437 data points and thus requires an Ensemble Deep Learning Model. This model helps create a general purpose Fatigue Strength Calculator which can be used by experimentalists and Material Scientists to predict fatigue strength values before creating certain strain of steel.
PS: A small recommendation of using low-carbon steel is recommended as the tiny dataset mostly consists of low-carbon steels.

![image](https://github.com/AshishKumarSingh03/Steel-Fatigue-Strength-Predictor/assets/116654089/dff78dbf-c5bc-453c-9acc-843e322961c3)

The Heroku folder consists of the format in which files should be saved and then pushed to git to upload the model onto the backend of a webpage. The models are supposed to be in the main folder with the HTML template for the webpage being in the 'templates' folder.

The file named APP.py contains the Python commands to push the input values from the webpage through the pickle-compressed models and then display the predictions on the same webpage. A few other filler files are also uploaded which need to be saved as is in order for Heroku to download and install the required Python libraries and figure out which file is the main python executable file.
