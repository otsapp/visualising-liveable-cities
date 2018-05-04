# Visualising liveable cities 

There are a number of cities around the world becoming increasingly attractive for expats, so I have decided to see which would be the most attractive based on things I find important:

* Climate.
* Air Pollution.
* City Buzz (culture, activity, global relevance etc.).
* Cost of living.

It turns out Buenos Aires and Barcelona fit the bill best!

![liveable-cities](https://user-images.githubusercontent.com/26570786/39625624-253f57f6-4f96-11e8-861e-f8c24e1e3e16.JPG)

## The dataset

`city`
There's a few emerging tech hubs like Austin, Medellin, Prague and Beirut to mix it up with the big boys like SF, London, NYC, Singapour, Shanghai and Tel Aviv. It would be nice to grow the list a bit based on A.T. Kearney's 'potentials index'. (Bali has been included for it's popularity with expats even if it's not a city itself).

| Full List      | cont..         | cont..		   | cont..         |
| -------------- | -------------- | -------------- | -------------- |
| Austin         | Jerusalem      | San Diego      | Tokyo          |
| Bali	         | London         | San Francisco  | Toronto        |
| Barcelona      | Medellin       | Santiago       | Vancouver      |
| Beirut         | Melbourne      | Shanghai       |                |
| Berlin         | New York       | Singapour      |                |
| Buenos Aires   | Oslo           | Stockholm      |                |
| Chicago        | Paris          | Sydney         |                |
| Copenhagen     | Prague         | Tel Aviv       |                |

`cost_of_living_index` 
A somewhat unscientific index by Expatistan, where each city is compared by % cost relative to Prague, so cost of living in New York City is 133% higher than in Prague.[ https://www.expatistan.com/cost-of-living/index ]. 

`air_pollution` 
Average annual volume of dangerous PM2.5 particles, latest figure measured by the WHO. Note, Bandung volume used for Bali (assuming living near an urban area). [ http://www.who.int/phe/health_topics/outdoorair/databases/cities/en/ ]

`av_temp` 
Average annual temperature °C. [ www.weatherbase.com ]


`global_cities_index` 
An interesting ranking by A.T. Kearney from public data to measure current performance of cities. Score breakdown:

* Business Activity (30%).
* Human Capital (30%).
* Information Exchange (15%).
* Cultural Experience (15%).
* Political Engagement (10%).

The score itself only seems available for the top 25, so the actual rank has been used.

[ The report: https://www.atkearney.com/documents/10192/12610750/Global+Cities+2017+-+Leaders+in+a+World+of+Disruptive+Innovation.pdf/c00b71dd-18ab-4d6b-8ae6-526e380d6cc4 ]

* Caveat: not all cities were available, so I matched the following cities:

| Missing Cities  | Substitutes   |
| --------------- | ------------- |
| Bali		      | Jakarta		  |
| Medellin	      | Bogota		  |	
| Oslo	          | Copenhagen    |
| Stockholm	      | Copenhagen    |
| Beirut	      | Tunis		  |
| San Diego	      | LA            |  
| Austin	      | Houston       |
| Jerusalem 	  | Tel Aviv      |
