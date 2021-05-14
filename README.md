# rice-btcmp-hw4-pandas
Repository contains Rice Analytics & Visualization Bootcamp's Homework #4 centered on the application of Pandas and Jupyter Notebook.



## Heroes of Pymoli

### Project objective:

Analyze the data for a fantasy game - Heroes of Pymoli. Like many others in its genre, the game is free-to-play, but players are encouraged to purchase optional items that enhance their playing experience. Goal is to generate a report that breaks down the game's purchasing data into meaningful insights.

### Input data: 

The [input file](./Resources/purchase_data.csv) contained the following data:

* `Purchase ID`	column contains individual IDs for each purchase made (data type - integer)	
* `SN`	column contains names of users making the purchase (data type - string)
* `Age`	column contains user age (data type - integer)	
* `Gender`	column contains user gender (data type - string)
* `Item ID`	column contains purchased items' IDs (data type - integer)	
* `Item Name`	column contains purchased items' names (data type - string)	
* `Price`	column contains purchased items' prices (data type - float)Sample

Sample of the input data is provided below, after being imported as Pandas data frame.

<img src="HeroesOfPymoli\Resources\input_data.PNG" style="zoom:75%;" alt="Input data"/>

### Analysis and output:

Below is an output of all of the requested analytic calculations that had to be performed: 

#### Player Count

<img src="HeroesOfPymoli\Resources\player_count.PNG" alt="Total Number of Players" style="zoom:75%;" />

#### Purchasing Analysis (Total)

<img src="HeroesOfPymoli\Resources\purch_an_total.PNG" style="zoom:75%;" />

#### Purchasing Analysis (Gender)

<img src="HeroesOfPymoli\Resources\purch_an_gender.PNG" style="zoom:75%;" />

#### Age Demographics

<img src="HeroesOfPymoli\Resources\purch_an_age.PNG" style="zoom:75%;" />

#### Top Spenders

<img src="HeroesOfPymoli\Resources\top_spenders.PNG" style="zoom:75%;" />

#### Most Popular Items

<img src="HeroesOfPymoli\Resources\pop_items.PNG" style="zoom:75%;" />

#### Most Profitable Items

<img src="HeroesOfPymoli\Resources\profit_items.PNG" style="zoom:75%;" />

Based on the analysis of the provided dataset, three key observations can be made:

* The game is predominantly played by Male players (~84%) who also make the most number of purchases (652, vs 113  for Female and 15 for those whose gender is not declared);  
* However, on average Male players tend to spend $0.18 cents less than Female players and $0.32 cents less than those whose gender is not declared; 
* In terms of age, people between 15 and 29 year old made the most purchases, with 20-24 year olds spending $1,114.06, which was almost as much as a total spend of the remainder of the surveyed players ($1,265.71) .