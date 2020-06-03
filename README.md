# Ufc-data-and-machine-learning

After reviewing different informative datasets, we stumbled across UFC fight data on kaggle. 
The task presented itself: build a machine learning model that would predict which corner would win, the red or the blue?
But how – and the steps toward machine prediction began

- Questions to start
0 Which model to use to help predict who’s going to win?
What are some factors for the model – what does the data tell us? Age | weight | height | Win Streak
What visualizers can we use to paint a picture? (visualizations such as Matplotlib)
How can we interact with the data?

- The steps
Search for a dataset that can be used
Choose visualizers to build from the data
Select the machine learning model and save the model
Utilize flask app for interaction
Deploy our model and find our prediction

- The data
We found our dataset on kaggle: https://www.kaggle.com/calmdownkarma/ufcdataset?select=data.csv
With over 800 columns and multiple empty spaces we analyzed, wrangled with and cleaned the data using jupyter notebook and pandas. 
Reducing the data to 10 columns. For each corner: Previous wins, win streaks, age, height and weight

- Visualizations
Some visualizations used included: Matplotlib & Plotly
Exploring our data population we created some summary visualizations: (Note* weight=kg)
Grouped box plots comparing age, streak and winner
Something we ran into: large datasets can be difficult to summarize
After cleaning the data: summarizing results

- Models used:
Logistic Regression
Grid Search
Tensor Flow 
- Saving the Model:
Saved the model using JSON and h5 so we could load it post-trained and apply to a new dataset for predictions

