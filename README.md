
##### Table of Contents  
- [Project Motivation](#project-motivation)
- [Questions answered](#questions-answered)
- [Libraries used:](#libraries-used-)
- [Files in the Repository](#files-in-the-repository)
- [Blog Post Link](#blog-post-link)
- [Summary of Analysis](#summary-of-analysis)
      - [Does price have any impact on review scores in Seattle and Boston?](#does-price-have-any-impact-on-review-scores-in-seattle-and-boston-)
      - [How do Seattle and Boston homeowners describe their houses? Is there a difference in the way top reviewed houses are described?](#how-do-seattle-and-boston-homeowners-describe-their-houses--is-there-a-difference-in-the-way-top-reviewed-houses-are-described-)
      - [What are the best neighbourhoods to stay in Seattle and Boston?](#what-are-the-best-neighbourhoods-to-stay-in-seattle-and-boston-)
- [Acknowledgements](#acknowledgements)


## Project Motivation
>This project is being done as a part of the Udacity's Data Scientist Nano Degree program Term 2. The project is later used to convey the results using a Blog post.

>The questions I intended to answer does not need any Data science models to be explored and hence, I've left them out for this particular project. The emphasis has been laid upon presenting the data as clearly and meaningfully as possible. While, there have been others who worked on the same data, I have purposefully, avoided to answer regular questions and tried to look at unusual questions.

## Questions answered
We will explore the Airbnb Seattle and Boston data and answer 3 major questions
  - Does price have any impact on review scores in Seattle and Boston?
  - How do Seattle and Boston homeowners describe their houses? Is there a difference in the way top reviewed houses are described?
  - What are the best neighbourhoods to stay in Seattle and Boston?

## Libraries used:
1. [Numpy](https://www.numpy.org/)
2. [Pandas](https://pandas.pydata.org/)
3. [Matplotlib.pyplot](https://matplotlib.org/api/_as_gen/matplotlib.pyplot.html)
4. [Seaborn](https://seaborn.pydata.org/)
5. [PIL.Image](https://pillow.readthedocs.io/en/stable/reference/Image.html)
6. [wordcloud](https://amueller.github.io/word_cloud/generated/wordcloud.WordCloud.html)

## Files in the Repository
1. Seattle_listings.csv - Raw Seattle listings data as of February 09, 2019 provided by Inside Airbnb team. Data can be found [here](http://insideairbnb.com/get-the-data.html)
2. Boston_listings.csv - Raw Boston listings data as of February 09, 2019 provided by Inside Airbnb team. Data can be found [here](http://insideairbnb.com/get-the-data.html)
3. Seattle_cleaned.csv - Cleaned csv file generated after few modifications done on the original data set of Seattle listings.
4. Boston_cleaned.csv - Cleaned csv file generated after few modifications done on the original data set of Boston listings.
5. Exploration.ipynb - Jupyter notebook containing all the data exploration and analysis done for the 3 questions I intended to answer.
6. Exploration.html - The HTML file of the jupyter notebook. It is always advisable to save your work as HTML for future reference and to share with those who do not have jupyter notebook running in their systems.

## Blog Post Link
https://medium.com/@yvsajay/3-airbnb-insights-that-will-make-you-smarter-on-your-next-seattle-or-boston-booking-13995cd281bc 

## Summary of Analysis
##### Does price have any impact on review scores in Seattle and Boston?
>As the prices go up, the review ratings also remain high. 

>This implies that at higher prices, listings generally are able to satisfy the higher demands and expectations of the travelers staying in the rooms.

##### How do Seattle and Boston homeowners describe their houses? Is there a difference in the way top reviewed houses are described?
>**Seattle Discussion**
>At an aggregate level for overall listings within Seattle, the summaries seem to have the following words at a higher frequency: beautiful, comfortable, private home, being near downtown, things being available at walking distance. Capitol Hill area also seems to be very popular.

>When you compare it against the top 25 percentile homes in Seattle (75th percentile for review ratings in Seattle is 99), majority of the words are similar. However, there are few interesting words which had higher frequency amongst those with high ratings. These are neighborhood, kitchen, large, and downtown.

>**Boston Discussion**
>At an aggregate level for overall listings within Boston, the summaries seem to have the following words at a higher frequency: downtown, Back bay location, beautiful, park, South end, private home, and park.

>When you compare it against the top 25 percentile homes in Boston (75th percentile for review ratings in Boston is 98), majority of the words are similar. However, there are few interesting words which had higher frequency amongst those with high ratings. These are neighbourhood, located, being near restaurant, and close. Being close to happening places, seem to be the major driver behind getting higher ratings in Boston as per the word cloud.

##### What are the best neighbourhoods to stay in Seattle and Boston?
>In Seattle, Southeast Magnolia is the best neighborhood for Airbnb rooms.

>Unlike Seattle, in Boston, there is no clear one neighbourhood but rather few choices depending on what one wants. The balanced choices are between Jamaica Plain and South Boston Waterfront which have relatively high number of listings and high review ratings. However if one wants to go purely by highest review rating scores, then he/she has to look at Roslindale and West Roxbury neighbourhoods.

## Acknowledgements 
1. [Inside Airbnb](http://insideairbnb.com/get-the-data.html) for providing us the data.
2. Udacity for giving the direction and scope of the project
