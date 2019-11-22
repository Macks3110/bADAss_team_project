# Insight into world agriculture production and its links to global hunger
 
## Abstract
According to the Food and Agriculture Organization of the United Nations (FAO), there are approximately 842 million people around the world suffering from chronic hunger. Hunger is a dramatic and complex consequence of a combination of factors. 
Based on the data set “Global Food & Agriculture Statistics” published by the United Nations, which gathers data on primary food production and surface dedicated to agriculture in 200 countries, we aim to provide an insight into the relation between agriculture and hunger in given countries. By enriching the main dataset (Global F&A Stats) with other datasets available on “UNdata” database (http://data.un.org/Explorer.aspx?d=FAO&f=itemCode%3a21033), we hypothesize we could further link food insecurity with environmental and economic aspects (e.g. food exportations) of agriculture and perhaps unveil unknown or neglected factors in most general studies. 

Finally, a rather qualitative prediction of hunger in the coming years will be given, based on the past and actual tendencies of food production shortage. 

## Research questions
* How did the harvested area in each country evolve throughout years?
* Do crops have a stable yield throughout years (e.g. decrease in fileds productivity, …)?
* What are the principal foodstuffs produced in each country/region of the world? Did it change in the last decades?
* Are all countries equal in terms of diversity of foodstuffs harvested? Are there any places where a major part of harvested area is dedicated to only few food products? 
* Which countries are the biggest producers for a given food?
* Can we reveal the impact of natural disasters on crops by observing the production per year in a given country or region?
* Can we link this data to health issues that countries are facing by including other datasets?
* What is the fraction of food that is dedicated to exportations in each country and how does this impact the health of the local population?

## Dataset
* Global Food and Agriculture Statistics
* Suite of Food Security Indicators: Value of food imports in total merchandise exports (percent) (3-year average) 
>(“This indicator provides a measure of vulnerability and captures the adequacy of foreign exchange reserves to pay for food imports, which has implications for national food security depending on production and trade patterns.”)
* Suite of Food Security Indicators: Prevalence of moderate or severe food insecurity in the total population (percent) (3-year average)
* Commodity Trade Statistics Database
* Demographic Statistics Database (population and surface)
* World Meteorological Organization Standard Normals

(We still need to find a specific  database for those 3 last categories of data)

## A list of internal milestones up until project milestone 2
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

## Questions for TAs
* Is the content we have enough to make a good project?
* As we are trying to find additional datasets, could we ask you for help if we are struggling? Do you think we should stick to 2-3 datasets max?

## Update Milestone 2

## After looking deep into our dataset we redefined 

We will focus on Switzerland compared to other european countries. 
We want to know if Switzerland could be self-sufficient in term of food production.
First we will look at the current productions of Switzerland in our dataset. What does it produce and in which quantity?
We will try to find datasets on swiss importations and exportations to know what Switzerland need. We could also look at the consumption trends of the swiss population.
We will also try to compute the switzerland potential in term of agriculture. Does the country use all his land or not? Demography of Switzerland: with the growing population, can we feed everybody with Swiss agriculture in the next few years for example?
How's been the productivity over the years? Is it growing, decreasing? What are the factors correlated with the trend? Temperature rise, fertilizer usage?


Then we will make comparaisons between Switzerland and other european countries. Does CH import more than the average european country (due to its small size ?) ?

Is food selfsuffience of CH realistic ? How many farmer would it need ? 
