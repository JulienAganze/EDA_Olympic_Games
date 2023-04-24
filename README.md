
# Study Of data related to Olympic games
## Exploratory Data Analysis Project
### Brief introduction
This project is generally about the Exploratory Data Analyssis(EDA), meaning getting a general overview or understand about the data, with the aim of finding its main characterisitcs, identifying patterns and visualizations.
And my case, I will be exporing the data related to exploring data related to Olympic games.

## introduction of data
The data we are going to holds 120 years of Olympic history including personal information about the athletes as well as the game they participated in. The file athlete_events.csv contains 271116 rows and 15 columns; Each row corresponds to an individual athlete competing in an individual Olympic event.
And the columns available in the dataset are as follows:

    1. ID - Unique number for each athlete;
    2. Name - Athlete's name;
    3. Sex - M or F;
    4. Age - Integer;
    5. Height - In centimeters;
    6. Weight - In kilograms;
    7. Team - Team name;
    8. NOC - National Olympic Committee 3-letter code;
    9. Games - Year and season;
    10. Year - Integer;
    11. Season - Summer or Winter;
    12. City - Host city;
    13. Sport - Sport;
    14. Event - Event;
    15. Medal - Gold, Silver, Bronze, or NA.

## Study methodology
To perform the required studies we will follow the following steps:

#### 1. Importing data into the dataframe
This is done using pandas [read_csv](https://pandas.pydata.org/pandas-docs/stable/generated/pandas.read_csv.html) method. And all needed information about how to use this can be obtained from the later provided link.
#### 2. Collecting basic information about the dataset
I need to need how the data looks like for me to be able to make sens out of it. SO for this reason we will explore additional pandas function like [head](https://pandas.pydata.org/pandas-docs/stable/generated/pandas.DataFrame.head.html) used to look at data in a tabular form, [describe](https://pandas.pydata.org/pandas-docs/stable/generated/pandas.DataFrame.describe.html) performs descriptive statistics, [isnull](https://pandas.pydata.org/pandas-docs/stable/generated/pandas.DataFrame.isnull.html) used to find out if there are null values in different columns
#### 3. Cleaning and Completing the data
After knowing how our data looks like, the next step will now bw about dealing with missing values. And for this purpose the following operations will be performed:

● Exclude all records from data where we don’t have any information about medals.\
● Fill missing age values with average age of other athletes.\
● Fill missing height values for women and men with average height of women and
men athletes respectively.\
● Fill missing weight values for women and men with average weight of women and
men athletes participating in same sports
#### 4. Data visualizations analysis
Visualizing data in different type of graphs will provide us with greater insights into our data. We will explore different options on visualizing our data and find out any patterns within it.We will use here pandas library ass well as other concepts like seaborn and matplotlib.

● And we will base our analysis by looking at the following points\
● Gold medals in gymnastic over age\
● Medals won by China over years\
● Gold medals won by china in summer olympics in sports\
● Height of male athletes over years\
● Height of female athletes over years.\
● Top 5 countries with most medals\
● Number of athletes in each olympic game\
● Age distribution of male/female in Olympic games\
● Variation of age for female over time\
● Height and weight ratio of athletes\
● Average age of medal winners in olympic games.\

### Project details
All the project details and analysis will be in the project notebook.

[Olyimpic_games_Analysis](https://github.com/JulienAganze/EDA_Olympic_Games/blob/master/EDA_Olympic_Games.ipynb)

![Analysis](https://github.com/JulienAganze/EDA_Olympic_Games/blob/master/Analysis.png)

### Source of the used data
The data we used in this project can be obtained from here [data_source](https://github.com/noraiz-anwar/exploratory-data-analysis)

## Used libraries
The following libraries will be used in our analysis

● [Numpy](http://www.numpy.org/)
NumPy is a library for the Python programming language, adding
support for large, multi-dimensional arrays and matrices, along with a
large collection of high-level mathematical functions to operate on
these arrays.

● [Pandas](https://pandas.pydata.org/)
Pandas is a python package providing fast, flexible, and expressive
data structures designed to make working with “relational” or “labeled”
data both easy and intuitive. It aims to be the fundamental high-level
building block for doing practical, real world data analysis in Python.
Additionally, it has the broader goal of becoming the most powerful and
flexible open source data analysis / manipulation tool available in any
language. It is already well on its way toward this goal.

● [Seaborn](https://seaborn.pydata.org/)
Seaborn is a Python data visualization library based on matplotlib. It
provides a high-level interface for drawing attractive and informative
statistical graphics.

● [Matplotlib](https://matplotlib.org/)
Matplotlib is a Python 2D plotting library which produces publication
quality figures in a variety of hardcopy formats and interactive
environments across platforms.
