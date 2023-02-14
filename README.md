# Where should I build my Paddle Court?

### As a Businessman who will move to Australia, I keep thinking that to create a Paddle club would be an amazing opportunity.

We need to decide where we should build it, to be able to assess the costs. Because the biggest cost will be associated to the rent of the place.

## STEP 1: Companies data and population

Downloaded the data about the companies and its offices, so I can have a distribution and concentration of the offices in Australia. That will help me understand where I will find more active people who will be willing to play.

After some extraction and calculations (contained in the file “2_office_concentration_aus. ipynb” ) I managed to create a heat map of Australia, where we can see that the highest concentration is in the New South Wales state. More precisely in Sydney.

![Concentration of Offices](https://raw.githubusercontent.com/SergiColl5/paddle_court_location/main/images/aus_office_concentration.png)

I also wanted to double check if the population was also higher in Sydney, so I quickly made a bar chart to check it.

![Population Autralia](https://raw.githubusercontent.com/SergiColl5/paddle_court_location/main/images/aus_population_states.png)


## STEP 2:  What are the districts?

I need to know what all the districts in Sydney are. To do so, I downloaded the geojson of all the districts, so I have the coordinates forming them. We can see all the districts below. 

![Districts of Sydney](https://github.com/SergiColl5/paddle_court_location/blob/main/images/districts_sydney.png)

## STEP 3: What do we have in Sydney?

Once we know that Sydney has the higher number of companies and population. We need to know what it has to offer. 
As a businessman looking to build a paddle court club, I would weight the following items on the list in percentages:

-	Tennis court - 35% weight, as it is the main and essential feature of a paddle court club.
-	Parking - 20% weight, as having a convenient and comfortable parking area close to the paddle court club is important.
-	Public transport - 10% weight, as proximity to public transportation can be a consideration for the accessibility of the paddle court club.
-	Tennis store - 5% weight, as a nearby store selling tennis equipment and supplies can be a convenience for players.
-	Social club - 10% weight, as having a nearby social club can enhance the overall playing experience.
-	Gym - 5% weight, as a nearby gym can be a complementary addition for paddle court players.
-	Physiotherapy - 5% weight, as physiotherapy services can be a complementary addition for paddle court players.
-	Bar - 3% weight, as a nearby bar can offer an additional option for entertainment and socialization after playing.
-	Residential - 2% weight, as proximity to a residential area can be a consideration for accessibility and comfort.
-	University - 1% weight, as proximity to a university can be a consideration for accessibility and comfort.
-	Park - 1% weight, as proximity to a park can be a consideration for accessibility and comfort.''' 

I looked in 4sq for all the places for each category in Sydney, taking the central point the physical centre of Sydney. With a radius of 30 km.

## STEP 4: Which district has the higher score?

Once I have all the geo information of all the places and the districts. I need to know for each district, what venues it has. And after that, give it a score depending on the number of venues and its category. 

In the end, I get a ranking of districts based on the score. And the winner is Sydney Centre.

![Ranking of Districts](https://raw.githubusercontent.com/SergiColl5/paddle_court_location/main/images/ranking_districts.png)

Here we have all the venues displayed in a map to see what we will be having nearby.

![Map of places](https://github.com/SergiColl5/paddle_court_location/blob/main/images/places_sydney_center.png?raw=true)
