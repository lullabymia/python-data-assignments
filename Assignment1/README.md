
# Data Source
This code scrapes the top 250 movies in douban. https://movie.douban.com/top250?start=0&filter=
(also including codes scraping top scorers in FIFA https://www.fifa.com/worldcup/statistics/players/goal-scored
https://www.fifa.com/worldcup/archive/brazil2014/statistics/players/goal-scored.html)
# Data Fields
* names
* rank
* comment
* director
* actor/actress
* release year
* country
* category
# Data Volume
250rows 8 columns
# License
CC 4.0
# Obstacles and Solutions
* Having trouble scraping more pages
solution: define a function and use for loop and format for changing url (assignment1 fixed douban 250.ipynb)
* Having trouble split the infomation of director, actor and countries
solution: split the string at the first place (splitinfo douban250.ipynb)
# Future Work
scraping all data for a split version
