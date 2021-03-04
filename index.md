## Wine Prediction

We chose to analyze wine quality and how machine learning can detect whether a selected wine can be classified as “good quality” or “bad quality” based on certain physio-chemical characteristics of the wine.

Opinion on wine is very subjective, some prefer a certain kind over another based on their taste preferences, palets, and/or their preset beliefs about a certain brand, cork vs screw top or price tag. Machine learning can play a role in providing an objective result based on the composition of the wine rather than sensory result provided by a human.

The dataset selected from Kaggle contains data about red and white wine variants of the Portuguese "Vinho Verde" wine. The data contains features of wine to be used for this project to predict an output of “good”or “bad” quality based on a preset scale: 0-10.

Features: fixed acidity, volatile acidity, citric acid, residual sugar, chlorides, free sulfur dioxide, total sulfur dioxide, density, pH, sulphates, and alcohol.

Output variable (based on sensory data): quality.

The dataset was described as containing ordered classes meaning there are very small amounts of very bad and very good wine and the majority are normal wines.


### Checking the Quality of Data & Plots
![Image](https://github.com/eggsnbacon97/BUTLER-PROJECT3-GROUPC/blob/main/images/quality_bar.png?raw=true)

### Outliers in Dataset:
![Image](https://github.com/eggsnbacon97/BUTLER-PROJECT3-GROUPC/blob/main/images/alcohol_plotly_boxplot.png?raw=true)
![Image](https://github.com/eggsnbacon97/BUTLER-PROJECT3-GROUPC/blob/main/images/boxplots.png?raw=true)

## Visualizations

#### Histogram
![Image](https://github.com/eggsnbacon97/BUTLER-PROJECT3-GROUPC/blob/main/images/histograms.png?raw=true)

#### Correlation Model
![Image](https://github.com/eggsnbacon97/BUTLER-PROJECT3-GROUPC/blob/main/images/correlation_model.png?raw=true)

#### Bar Chart
![Image](https://github.com/eggsnbacon97/BUTLER-PROJECT3-GROUPC/blob/main/images/bar_charts.png?raw=true)

### Findings:
Good quality wines have higher levels of alcohol on average, have a lower volatile acidity on average, higher levels of sulphates on average, and higher levels of residual sugar on average.

### Check out our Colab!
https://colab.research.google.com/drive/1nBkQZLPH-ttunvwxlyRUp0bu3uFL0MrE?usp=sharing
