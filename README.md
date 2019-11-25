# Insight into world agriculture production and its links to global hunger
 
## Milestone #1

### Abstract
According to the Food and Agriculture Organization of the United Nations (FAO), there are approximately 842 million people around the world suffering from chronic hunger. Hunger is a dramatic and complex consequence of a combination of factors. 
Based on the data set “Global Food & Agriculture Statistics” published by the United Nations, which gathers data on primary food production and surface dedicated to agriculture in 200 countries, we aim to provide an insight into the relation between agriculture and hunger in given countries. By enriching the main dataset (Global F&A Stats) with other datasets available on “UNdata” database (http://data.un.org/Explorer.aspx?d=FAO&f=itemCode%3a21033), we hypothesize we could further link food insecurity with environmental and economic aspects (e.g. food exportations) of agriculture and perhaps unveil unknown or neglected factors in most general studies. 

Finally, a rather qualitative prediction of hunger in the coming years will be given, based on the past and actual tendencies of food production shortage. 

### Research questions
* How did the harvested area in each country evolve throughout years?
* Do crops have a stable yield throughout years (e.g. decrease in fileds productivity, …)?
* What are the principal foodstuffs produced in each country/region of the world? Did it change in the last decades?
* Are all countries equal in terms of diversity of foodstuffs harvested? Are there any places where a major part of harvested area is dedicated to only few food products? 
* Which countries are the biggest producers for a given food?
* Can we reveal the impact of natural disasters on crops by observing the production per year in a given country or region?
* Can we link this data to health issues that countries are facing by including other datasets?
* What is the fraction of food that is dedicated to exportations in each country and how does this impact the health of the local population?

### Dataset
* Global Food and Agriculture Statistics
* Suite of Food Security Indicators: Value of food imports in total merchandise exports (percent) (3-year average) 
>(“This indicator provides a measure of vulnerability and captures the adequacy of foreign exchange reserves to pay for food imports, which has implications for national food security depending on production and trade patterns.”)
* Suite of Food Security Indicators: Prevalence of moderate or severe food insecurity in the total population (percent) (3-year average)
* Commodity Trade Statistics Database
* Demographic Statistics Database (population and surface)
* World Meteorological Organization Standard Normals

(We still need to find a specific  database for those 3 last categories of data)

### A list of internal milestones up until project milestone 2
* Load / read data (**data exploration**)
* Handle weird and missing datas (**data preprocessing**)
* Illustrate what is in our first dataset by plotting some graphs before searching links with others datasets. (studying our principale data set) (**data visualization**)
* Research to interpret the datas and our future results
* Find complementary datasets (**data enrichment**)
* Research on malnutrition / hunger 
* What are the causes and consequences ? (wars, bad economy, politics, embargo...)
  * on individuals
  * on regions
  * on nations.
* Learn how to use folium to implement interactive maps 

### Questions for TAs
* Is the content we have enough to make a good project?
* As we are trying to find additional datasets, could we ask you for help if we are struggling? Do you think we should stick to 2-3 datasets max?

## Milestone #2 - Project Updates

### Abstarct - More realistic project 

In the wake of the the years 2007-08, food self-sufficiency policies have gained increased attention in a number of coutries following the international food crisis that triggered great volatilities on the world food markets causing important economic and social damages. <br>
Since then, diverse countries have expressed interest in improving their levels of food self-sufficiency arising controversy into a massive economically connected world.

On the 23th september of 2018, in the small country of Switzerland, the debate is materialized into a popular referendum submitted to its population asking wherever a food self-sufficiency politic should be adopted or not. Such a politic could have unexpected consequences considering a country as Switzerland with many neighbours and such a small area capacity. <br>
This paper aims to analyse the questions surrounding the debate over food self-sufficiency in Switzerland. 

We will therefore focus on Switzerland compared to its neighbours. We would like to know if Switzerland could be self-sufficient in term of food production.
First we will look at the current productions of Switzerland in our dataset. What does it produce and in which quantity?
We will try to find datasets on swiss importations and exportations to know what Switzerland need. Does CH import more than its neighbours (due to its small size ?) ? We could also look at the consumption trends of the swiss population.
We will also try to compute the switzerland potential in term of agriculture. Does the country use all his land or not? Demography of Switzerland: with the growing population, can we feed everybody with Swiss agriculture in the next few years for example?
How's been the productivity over the years? Is it growing, decreasing? What are the factors correlated with the trend? Temperature rise, fertilizer usage?
Is food selfsuffience of CH realistic ? How many farmer would it need ? 

### Plan for milestone #3

1. Defining what is food self-sufficiency
    1.  SSR = Production * 100 / (Production + Imports - Exports) to develop
    2. Addapt it to the Swiss case : take a look to what we import (basic needs ?), export (top exports ? by far ?) and production graphs *(Already started)*
    3. __[Ref. Paper "Food self-sufficiency: Making sense of it, and when it makes sense" By Jennifer Clapp](https://www.sciencedirect.com/science/article/pii/S0306919216305851#b0240)__. <br> Summary : __[Summary by Clapp's "Resilience" website](https://www.resilience.org/stories/2018-03-13/food-self-sufficiency-does-it-make-sense/)__
    4. Compare our results with other sources just to know if we share the same results (e.g. selfsufficiency switzerland on wikipedia __[List of countries by food self-sufficieent rate](https://en.wikipedia.org/wiki/List_of_countries_by_food_self-sufficiency_rate)__

    
2. Food situation of Switzerland from 1986 to 2017.
    1. Is/was it food self-sufficient ? SSR scores over the years.
    2. Compare SSR score to neighbour countries. Hence, can Switzerland increase its SSR to 

    
3. Predictive model
Will it be **physically** possible for Switzerland in a near future to be food self-sufficient (in the sense of the 2018 initiative bc we have seen that definition is relative)? 
This model will have the following features and would predict the total production for a given agricultural good:
    1. Area harvested (actual ratio and estimation of its evolution). Can the harvested area be increased enough given Switzerland small  superficy?
    2. Demography
    3. Temperature (correlation between temperature and productivity )
    4. Environment (use of fertilizers needed ? depends on productivity)
    
    The model should return the percentage of land that could be allocated for each element in addition of the already existing lands. To compute this, the model will take into account the different food elements, the available land for agriculture, the temperatues and the demography. <br> Once we get this percentage, we can add it to the land already used for each country and calculate the increase in production for each food elements. Thus we could see if the importations can be reduce and conclude about the self food sufficiency of Switzerland. This model will be run on every years until 2030. 

In order to answer all those questions, we will go further into the "correlation study" of our data.
