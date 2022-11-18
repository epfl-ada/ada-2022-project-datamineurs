# ada-2022-project-datamineurs
How did the political system influence the response of the populations to the lockdown policies following covid pandemics ?
Abstract: 

The coronavirus disease (COVID-19) pandemic was, and still is of a scale most people alive today have never seen. It has marked our lives forever. People had to endure the lockdown measures of their respective countries, and their reaction to these measures were quite different.
We have heard in the media, and some of the members of this group even experienced and respected (or not), lockdowns in different countries around the world. We asked ourselves whether democratic, liberal countries have had their citizens respect these lockdowns more than the authoritarian regimes, and wanted to put this idea to the test. We wanted to see if  and to what extent a political regime influenced the response of the populations to lockdowns measures. Moreover, we asked ourselves what would interest people more : What is accessible (Cooking, Reading, Movies…) ? or What is prohibited (Travel, Countries far away…) ? Do prohibiting travelling, sports etc… increase people’s interest in these or do people have more down-to-earth preoccupation when locked at home ?


Research Questions: 

Our study should answer two main questions:
    Is there a link between citizens’ respect for containment and the level of democracy in countries?

    Do the more obedient populations in times of lockdown do more research on what is inaccessible during such a period (like if they were dreaming about it) or, on the contrary, on activities and interests that are more accessible in times of lockdown (cooking, reading…) ?

Proposed additional dataset : The Democracy Index, by the Economist Intelligence Unit (EIU)

    We will focus on the versions of Wikipedia that we can associate fairly unambiguously with a country. For example, we can estimate that the Italian version of Wikipedia is mainly used by users living in Italy. However, it does not seem appropriate to make such an association for the English, Spanish and French versions, since these are three wide-spread languages around the globe. 
    
    For the versions associated with a specific country, we are going to use the democracy index, which is calculated by the Economist Intelligence Unit (EIU), the research division of the Economist Group (the group that publishes The Economist). We will use the indices calculated in 2020, the year on which our study on the effect of lockdown policies will focus.
    
    Considering the low number of versions/countries that we have to consider, we will manually report the different values, obtained from the report published by the EIU : “Democracy Index 2019 : A year of democratic setbacks and popular protest”. 
    
    For the countries considered in our study (without considering the widespread languages), the indices range from 6.41 to 9.87, on a scale of 0-10.

**Methods :**

We will divide our work into several steps :

Step 0 : Obtaining additional data 
Precisely define which versions can be unambiguously associated with a country, and retrieve the values of the 2019 Democracy Index for these countries.

Step 1 : Lockdown compliance and its link with the level of democracy
-In each country, identify a baseline level of mobility, using data from the months prior to lockdown. 
-Compare the level of mobility during lockdown to the baseline.
Note: We will use the containment dates contained in the interventions.csv file.
-Also possible to analyze how quickly mobility increases again at the end of the lockdown.
-The relative change in mobility (lockdown_mobility/reference_mobility) will define the so-called “lockdown compliance”. Calculate the correlation between lockdown compliance and the democracy index.

    Step 2 : Pageviews variations during lockdown on “lockdown-friendly” topics or “inaccessible” topics
-Identify the topics related to things that are inaccessible during the period of confinement (far away places, sports…), and those that are related to lockdown-friendly activities (reading, cooking…).
-For each country, and each type of topic, measure the evolution of their page views during the lockdown. To do this, it is important to take into account the overall evolution of the number of searches on Wikipedia during the lockdown period.



    Step 3 : Link between shift in attention for these kinds of topics and the types of lockdown policies
Calculate the correlations between the evolutions of pageviews of:
	-Lockdown-friendly topics
	-Lockdown-inaccessible topics
and
	-The democracy index
	-The lockdown compliance

In case the latter two variables appeared to be correlated in step 1, a similar result should be obtained by calculating correlations with both of them.



Proposed timeline
From 21/11 to 27/11 → Homework 2
From 28/11 to 04/12 → Step 1
From 05/12 to 11/12 → Step 2
From 12/12 to 16/12 → Step 3
From 17/12 to 23/12  → Putting results into perspective and writing the data story

Organization within the team:
Each of us will be “leader” at a certain point. The leader is responsible for ensuring that the project progresses properly but is assisted by the other members of the group.
Member
Valentin : Step 0 and 1 (beginning)
Bechara : Step 1
Mériadec : Step 2
Louis : Step 3


Questions for TAs

What does the “m'' mean in the keys of the time series? For example, what is the difference between “fr-m” and “ fr” ?

