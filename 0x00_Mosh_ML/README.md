# Introduction To Machine Learning

This repository shows the basics of Machine Learning written with Python Programming Language and the use of the Jupyter Notebook.

The lesson used 2 data sets namely: [music.csv](music.csv) and [vgsales.csv](vgsales.csv). And several Machine Learning techniques were treated in this lesson with these data.

## Data Set
- [x] Video Game Sales
    - Files used include: 
        - [mosh_tutorial.ipynb](mosh_tutorial.ipynb) The jupyter notebook
        - [vgsales.csv](vgsales.csv) The data set
    - Topics Discussed include:
        - **The use of shortcut keys**
        - **The use of pandas and its methods**: They include(.shape, .describe(), .values)

- [x] Music
    - Files used include: 
        - [music_store.ipynb](music_store.ipynb) The jupyter notebook
        - [music.csv](music.csv.csv) The data set.
        - [music-recommender.joblib](music-recommender.joblib) A saved Machine Learning Model
        - [music-recommender.dot](music-recommender.dot) File that is used to preview the decision tree of a model
    - Topics Discussed include:
        - **Splitting data set**: Data sets are split into 2 types `Output set` that contains the prediction values and `Input Set` used to train the model. 
        - **The use of Decision trees**: sklearn was the decision tree library used.
        - **Calculating Accuracy of the Model**: The `Input Set` should be split into 80% for training the model and 20% for testing the model's prediction Accuracy.
        - **Model Persistence**: Using joblib to save a trained model and using a saved model to make predictions.
        - **Visualizing Decision Trees**: The [music-recommender.dot](music-recommender.dot) was created and was previewed on VSCode using the `Graphviz (dot) language support for Visual Studio Code` By `Joño Pinto` to view the prediction tree. Also download `Auto-open markdown preview` on VSCode to help view the decision tree.


## References
This lesson was done under the tutelage of [Mosh Hamedani](https://www.youtube.com/watch?v=7eh4d6sabA0).





