## Introduction

> Wrangling, Univariate, Bivariate and Multivariate Exploratory Data Analysis(EDA) in a trial to answer some questions about the **European Soccer Database** from season 2008 to season 2016 using Python, Pandas, NumPy and Matplotlib. The data source for this project is a SQLite Database that can be found on <a href="https://www.kaggle.com/hugomathien/soccer">Kaggle</a>. This Database contains data for:
>
>> - +25,000 matches.
>>
>> - +10,000 players.
>>
>> - 11 European Countries with their lead championship.
>>
>> - Seasons 2008 to 2016.
>>
>> - Players and Teams' attributes* sourced from EA Sports' FIFA video game series, including the weekly updates.
>>
>> - Team line up with squad formation (X, Y coordinates).
>>
>> - Betting odds from up to 10 providers.
>>
>> - Detailed match events (goal types, possession, corner, cross, fouls, cards etc…) for +10,000 matches.
>
>  The Database contains 7 tables. I will only focus on 2 tables which are 'Player' and 'Player_Attributes' and try to find answer for the following questions:
>
>> What is the relationship between the player's age and his aggression level?
>>
>> What is the relationship between player's BMI(mass(KG)/height^2(M^2)) and shot power?
>>
>> what is the relationship between player's age and his finishing?
>>
>> who was the best under 18 player in this period(based on the overall rating)?
>>
>> what is the average BMI of a soccer player in the period?
>>
>> who was the tallest player played in this period?
>>
>> who is the player who had the most penalties?
>

## Conclusions
> Limitations:
> 
>> The dataset in hand contains data for players between seasons **2008** and **2016** and only for **EU players**.
>> 
>>
>> Results from **bivariate analysis** may slightly change with different datasets in different seasons.
>
> The above analysis for the dataset reveals that:
>
>> Best u18 player in this period was **Yevheniy Konoplyanka** whose rating (based on the overall_rating) in **2007** was **82** when he was only **17** years old
>>
>> average bmi = **23.12**
>>
>> tallest player between 2008 and 2016 is the **2.08m** Belgian goalkeeper **Kristof van Hout**.
>>
>> The English striker **Rickie Lambert** had the heighst number of penalties with **96** penalty.
>>  
>> There is **no relation** between player's **age** and player's **aggression**.
>>
>> There is **no relation** between player's **age** and his **finishing**. 
>>
>> There is **no relation** between player's **BMI** and his **shot power**.
>>
>> In the **EDA**, a **positive relation** between **age** and **overall rating** was found.
