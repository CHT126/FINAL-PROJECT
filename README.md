# FINAL-PROJECT
Group 56 Jiayi Huang jih151@pitt.edu, Charles Tran cht126@pitt.edu, Jack Zhang yuz173@pitt.edu 

For our final project, we are determing the best neighborhood based on safety and cleanliness.

Our final jupyter notebook is the Group.ipynb inside the Final Group Notebook folder.

# Charles Tran
First, Charles Tran will be determining which neighborhoods have a high ratio of people completely vaxed, booster and all. When talking about cleanliness, we have to make sure everybody is healthy and vaccinated for any sickness to come 

The main data set I used was vaccination in neighborhoods set. This told me how many people were vaccinated andhow many doeses they received. 

# Jiayi Huang
Next, I will analyze the neighborhood police incidents dataset to see which neighborhood has the least occurence of police arrests. The dataset records the total number The neighborhoods with the least number of police arrests will be nominated as the safest neighborhoods.

# Jack Zhang
Lastly, Jack Zhang will analyze the smart trash containers in the Pittsburgh neighborhood. The environment of a neighorhood is important to the living quality of people in the neighborhood and the living quality of people the most important factor that determines a good neighborhood. Some neighborhood in large cities like San Francisco and Los Angeles are heavily polluted by people throwing their trash on the ground. This can be caused by the lacking of trash can in the neighborhood. A simple smart trash container can have a huge impact on a city's environment. It can decrease the level of pollution of a neighborhood which can ended up improve people's living quality. The metric will measure the bestness of Pittsburgh neighborhood based on the ratio between the count of the smart trash containers and the population of the neighborhood. If the ratio is high, it means that the people can have access to the smart trash container in the neighborhood and people can have a place to throw out their trash to the trash container instead of throwing it to somewhere else that damages the enviorment. The small_trash_container.csv file contains the data of the location of the city of Pittsburgh's smart trash containers. There are 8 attribute in this dataset: container_id, receptacle_model_id, assignment_date, group_name, address, city, state, zip, neighborhood, dpw_division, council_district, ward, fire_zone, x, y. The useful attribute for this project will be the neighborhood because the metric need to group the count of the containers by neighborhood. The population.csv contains the population of the Pittsburgh neighborhood in different time period from 2010 to 2020. In this project, the useful attributes is the lastest total population which is 2020_total_population.
