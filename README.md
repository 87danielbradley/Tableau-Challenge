# Citi Biki Data Visualization for 2019

## Data Sources:
https://www.citibikenyc.com/system-data
Stored as CSV in `CustomerData` file and `Citi Bike Data` file

## Tools:
Tableau<br>
Jupyter Notebook (python)

## Data Preparation:
Cleaned Column names and merged all years in `Citi Bike Data`
Cleaned Column names and merged 2018-2020 in `CustomerData`
Areas of interest did not contain missing values.

## Output: 
https://public.tableau.com/profile/daniel.bradley1709#!/vizhome/citi_bike_public/Story?publish=yes


## Observations
### 1. Age and Gender
	-There are ~3x more male-user trips than female .
	-There is a high usage of citi bikes in Summer-time across all age groups.
	-Highest usage for ages range between 25-35 for 2019.
<div class='tableauPlaceholder' id='viz1594324162025' style='position: relative'><noscript><a href='#'><img alt=' ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;ci&#47;citi_bike_public&#47;Story&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='citi_bike_public&#47;Story' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;ci&#47;citi_bike_public&#47;Story&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en' /></object></div>                
### 2. User Trips
	-Users are primarily subscribers.
	-Customers are spending more time per ride.
	-The median trip for customers has been growing closer to the 30 min limit(before overage fees), with a current median of ~25min.
	-3:00AM and 2:00PM are the median usage peaks suggesting primary use is commuting.
	<div class='tableauPlaceholder' id='viz1594324320835' style='position: relative'><noscript><a href='#'><img alt=' ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;ci&#47;citi_bike_public&#47;UserType&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='citi_bike_public&#47;UserType' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;ci&#47;citi_bike_public&#47;UserType&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en' /></object></div>                

### 3. Growth
	-New annual subscriptions as been relatively consistant.  However, the average day passes has shown constistant growth around 25%.
	-Average Daily trips have shown consistant growth each year.
	<div class='tableauPlaceholder' id='viz1594324473772' style='position: relative'><noscript><a href='#'><img alt=' ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;ci&#47;citi_bike_public&#47;Growth&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='citi_bike_public&#47;Growth' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;ci&#47;citi_bike_public&#47;Growth&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en' /></object></div>                

### 4. Popular Stations
	-Top 10 starting AND stopping stations are all located in New Jersey.
	<div class='tableauPlaceholder' id='viz1594324503711' style='position: relative'><noscript><a href='#'><img alt=' ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;ci&#47;citi_bike_public&#47;PopularStations&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='citi_bike_public&#47;PopularStations' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;ci&#47;citi_bike_public&#47;PopularStations&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en' /></object></div>                