# World Happiness Report 2021


> [dataset available on kaggle](https://www.kaggle.com/)


* [World-Happiness-Repot-2021](https://www.kaggle.com/ajaypalsinghlo/world-happiness-report-2021) has 149 rows and 20 columns :

| Column | Description |
| :- | -: |
|Ladder score |Happiness score |
|Logged GDP per capita |The GDP-per-capita|
|Social support|Social support refers to assistance or support provided by members of social networks to an individual|
|Healthy life expectancy| the average life in good health|
|Freedom to make life choices | Freedom to make life choices is the national average of binary responses to the GWP question “Are you satisfied or dissatisfied with your freedom to choose what you do with your life?”|
|Generosity | the residual of regressing national average of response to the GWP question “Have you donated money to a charity in the past month?” on GDP per capita|
|Perceptions of corruption |The measure is the national average of the survey responses to two questions in the GWP: “Is corruption widespread throughout the government or not” and “Is corruption widespread within businesses or not?”|
|Ladder score in Dystopia |Dystopia as a benchmark against which to compare contributions from each of the six factors|




## Exploratory Data Analysis :

* Relationships between Variables

![image](https://user-images.githubusercontent.com/71708747/150448470-74151322-99c5-42b4-94d9-5d7a0c33d6a0.png)

1. Logged GDP per capita, social support, Healthy life expectancy  & ladder score has  high correlation (above 60%)
2. Healthy life expectancy & Logged GDP per capita are the highest correlation (86%)
3. between *generosity*,*proportion of corruption* and other variables, they have the lowest correlation



* Top 5 Happiness & Unhappiness Country 2021 by Ladder Score

![image](https://user-images.githubusercontent.com/71708747/150448637-18ae317c-0029-47de-8266-ca6e1ee3630e.png)
![image](https://user-images.githubusercontent.com/71708747/150448658-90eef58a-0d0b-4331-86ed-23651317412c.png)

1. `Findland` is the happiest country in 2021 while `Afghanistan` has the lowest happiness score
2. The top 5 countries have above average scores Meanwhile, the bottom five countries are scores below the average


* Regions Happiness Rank 

![image](https://user-images.githubusercontent.com/71708747/150448758-635035ea-3a80-4783-a629-477a1e465f88.png)

1. Looks like `Western europe` has a highest score and `south asia` is the lowest
2. `Western Europe`, `Noth America and ANZ`, `East Asia` & `Central and eastern Europe` have a score above the average
3. `Latin America and the Caribbean` also has a score above the average but with the outliers



*  Logged GDP per capita and Ladder score

![Screenshot from 2022-01-21 11-11-46 (1)](https://user-images.githubusercontent.com/71708747/150456341-e628b4c4-df0d-4dbb-b923-6de4ec4d8e5b.png)


1. The scatter plot shows that a region with a high logged GDP per capita has a higher Ladder score.
2. `Western Europe` has the highest logged GDP per capita and ladder score, while `Sub-Saharan Africa` has the lowest logged GDP per capita and ladder score.


* Logged GDP per capita & Healthy life expectancy 

![image](https://user-images.githubusercontent.com/71708747/150455716-94dc494c-6bd6-4095-8b43-d2403b9183ce.png)

1. Notice that a region with a high logged GDP per capita has a higher Healthy life expectancy.
2. `Western Europe` has the highest logged GDP per capita and healthy life expectancy, while `Sub-Saharan Africa` has the lowest.



* Healthy life expectancy & Perceptions of corruption

![Screenshot from 2022-01-21 11-12-04](https://user-images.githubusercontent.com/71708747/150456396-e49d6477-c8f8-4161-aa54-d3ba15e48ee4.png)


1. First, on the left side, the plot shows that the higher the value of `healthy life expectancy`, the higher the `ladder score`.
2. while on the right side: plot shows that the lower absence of corruption (`preceptions_of_corruption`), `ladder score` will decrease.
3. so, a region with a high `healthy life expectancy` and `preceptions_of_corruption` has a high `Ladder score`.



* Happiness Country by Health Life Expectancy

![Screenshot from 2022-01-21 11-12-27](https://user-images.githubusercontent.com/71708747/150456453-c23d494c-e113-4acd-b33b-460ddf51e60e.png)


1. Pie chart shows that the country in `Western europe` has the higher healthy life expectancy
2. while country in `Sub-saharan africa` has the lowest
3. in the other region also has the lowest healthy life expectancy like Haiti, Yemen, Afganistan etc.


 
## Conclusion : *What makes the world’s happiest countries so happy?*

* Western Europe has a very high ladder score(with an average of 69%).
* The plot above shows that the country with a high ladder score has a high logged GDP per capita. So it means that the high logged GDP per capita, the high Ladder score.
* Social support refers to assistance or support provided by members of social networks to an individual. North America & ANZ is the region with very high social support.
* Singapore and Hongkong have a very high healthy life expectancy, the same as each country in western Europe.
* The pie chart shows that; Countries with bright colors have a high life expectancy and social support values, while countries with darker colors have low scores.
* Southeast Asia has a very high Freedom score. It means that most Southeast Asia is satisfied with their freedom to choose what they do with their lives.
* Southeast Asia also has a very high Generosity compared to other regions.
 * Generosity has a low correlation with the other variables.
 * A country with a high ladder score and healthy life expectancy mostly has a high Perception of corruption.it means that happy countries have fewer corrupt people.


Based on the analysis results, people in a country will be happy if they have a high logged GDP per capita, social support, healthy life expectancy. Also, If a country has a trim level of corruption ( high Perceptions of corruptions) and the community has a high level of freedom, then the community will be happier.

