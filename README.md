# Data Science Alogrithm for Analysis of an Expo Dataset

This Algorithm plots out all your Data into 3 different Forms:
- Scatter Plots. This shows you the spread of your Data, and enables you to see what kind of impression you left on the visitors

- Density Plots: This visualises the density spread of the data and allows you to see what answered were the most chosen

- Linear Regression: This allows you see the Linear correlation of your Data. This can help you with any predictions you want to make.

## Installation

Use the package manager [pip](https://pip.pypa.io/en/stable/) or [conda](https://conda.io/projects/conda/en/latest/user-guide/tasks/manage-pkgs.html) to install the libraries.

Libraries needed:
- pandas
- numpy 
- matplotlib
- seaborn
- sklearn.model_selection
- pandas.core.common
- sklearn.linear_model


## Usage
To use this alogotithm with your Data you need to complete a couple of steps.

1. Import your data.
Here edit this line of code to import your own data.

```python
    # bring the data into dataframe
    df = pd.read_csv("Robotik_Expo4.csv",sep=';', header=[0])
```
Change the "Robotik_Expo4.csv" file to the File with your Data

2. edit the axis and titles of the Graph
Edit these lines of code to change the axis labels

```python
    plt.scatter(df['Alter'], df['Frage_1'], color = 'lightcoral')
    plt.title('Frage 1')
    plt.xlabel('Alter')
    plt.ylabel('Feedback Werte')
```
The First Line changes the Data. This is the place where you specify the coloumns that you are plotting in your data set.
the second line changes the title of the graph.
The third and fourth lines change the labels of the axes.




## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## Credit
Vedant Pandey or @babybro06 on GitHub
