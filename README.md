Group #2: Data_Slack{ers}=False

Members: Ben Schatz | Sean Daily | Vraj Patel | Ashley Cooper

Goal:  Our goal was to decided between a predetermined list of ten cities, which one would be the best to live in long term, based on a certain criteria.

Hypothesis:  Nashville is the best city to live in

Cities to investigate:: Atlanta, Austin, Boston, Chicago, Denver, Los Angeles, Nashville, New York, San Diego and Tampa

Questions to answer:
1.)	  Do we want to live in a large (population) city or small?
2.)   As the population increases in the city how does it affect the walk score?
3.)   As the population increases in the city how does it affect the transit score?
4.)   As the population increases in the city how does it affect the bike score?
5.)   As the population increases in the city how does it affect the total cost of living?
6.)   As the population increases in the city how does it affect the total crime for the city?

Datasets Used:
Cost of Living in the US (kaggle.com)
United States Crime Rates By City Population (kaggle.com)
US Cities Urban Connectivity (kaggle.com)
Population of all US Cities 2024 (kaggle.com)

Project Overview:
For this project we choose 10 cities and wanted to decide which city would be the best to live in based on different critera that was set by the group members.
The different criteria were population (2024) crime rate, urban connectivity, and cost of living for each city.  Urban connectivity was also divied into the 
three sub categories: walk score, bike score and transit score.  Large datasets in csv version were pulled from kaggle.com for each of these categories.
Each data set was the stripped down to only the essential data and given a ranking column for each city.  Bar charts and scatter plots were made for each category 
and regression analysis was done for each category against the population for 2024.  Pearson R-values were created for each sub category of urban connectivity, crime rate
and the cost of living regression analysis.  After all of the EDA and visualzations were complete we made a final ranking data frame.  This gave us a final city rank using
all the rankings from our categories.  We used this final city rank to form our conclusion.

Conclusion:
New York and Tampa came out tied for the best city to live in.  This is interesting becuase they were the most and least populated cities that we chose to anazlyze.

Leanring Experiences and Limititations:
Finding relative data sets that match our project goals.
Cleaning data from a certain data set to allow for merging of datasets.
Merging code between partners - some dataframes and variables were originally given generic names that messed up the code process and gave wrong information.

Things To be added or altered:
Subcategories could have been used for all three of our major categories.
More major categories such as education, weather adn tax rates could have been choosen.
A larger number of initial cities could have and should have been used to give a better represenation of the true correlations.
