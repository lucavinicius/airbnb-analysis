# Seattle Airbnb Analysis
**Summary**

I am currently writing this from an Airbnb next to Olympic National Park. I became curious about the
popularity of Airbnbs in Washington, especially because of Airbnb’s increasing popularity and the
resurgence of travel post-pandemic. This analysis targets trends in tourism in Seattle, and uses machine
learning to predict where the most profitable Airbnbs will populate in the future. The results can be used by
hosts to help boost their ratings and increase the number of bookings, and can help analyze Seattle’s
tourism economy as a whole. As an economics major, I am also currently exploring how Airbnb is affecting
our local economy; with the regulations being implemented on Airbnbs in New York, I believe it would be
interesting to identify whether it’s possible that Seattle would face similar legal challenges. I chose to focus
on Seattle specifically in the interest of computer storage and time. Once my code runs successfully, I hope
to expand it to multiple cities in order to be able to identify national trends.

1. Which neighborhoods in Seattle are the most popular for Airbnbs?
2. Which neighborhoods in Seattle contain the most expensive Airbnbs?
3. Given different factors, which Airbnbs are predicted to be popular?
4. Does having a profile picture affect the popularity of a host's listing?

# Challenge Goals
In addition to a csv and geodataframe, I am using a geojson for my map, which we did not use in class and
is considered messy data. Additionally, I hypothesize that having a host profile picture will increase the
number of bookings for their listing. I will be using altair in order to create interactive datasets. I hope to
create results that are user-friendly to be used by hosts in order to help them easily understand what factors
increase the popularity of Airbnb listings, and for city planners and policymakers to understand trends in
Airbnbs throughout Seattle. I have never used this libraries, but the interactive graph at the end of our
education assignment intrigued me, and I would like to learn how to do something similar.
Additionally, I will be using machine learning to predict the most popular Airbnbs on a longitude-latitude
map. I will be using scikit-learn to compare three different classification methods: LinearSVC, Decision Tree
Classification, and Random Forest.

# Data Setting and Methods
I first imported all of my libraries and functions. Then, I loaded in my listings as both a csv and a
GeoDataFrame, as well as a map of Seattle as a geojson. I also changed the formats of price to exclude
dollar signs so they could be used as a float. In methods, the dataset may be manipulated (such as adding
columns), but the specifications above are the only ones consistent throughout all of the code.
I have separated my graphs and answers to research questions into different methods. Additionally, there is
more analysis in project_code that I opted not to include here due to relevancy and organization. In
project_code.ipynb, the last code cell contains a short explanation of each method, as well as a
commented line that can be uncommented to run the method. This helps keep my code organized and run
efficiently, as opposed to running all code at once. The methods are a combination of number comparisons,
graphs, maps, and machine learning classification methods.
