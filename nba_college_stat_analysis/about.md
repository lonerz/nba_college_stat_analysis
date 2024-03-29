## Summary

In the age of technology, the amount of National Basketball Association (NBA) and college (NCAA) player statistics online grows even more each year. This presents a great opportunity to analyze trends and come up with models, focusing a lot on player positions/roles, using this data.

## Background

The National Basketball Association (NBA) is the men's professional basketball league in North America, composed of 30 teams. It is considered the "premier basketball league in the world." The NBA has an annual draft, called the NBA draft, which NBA teams can draft eligible players into the league. These players are typically college players, but international players are also eligible to be drafted. **My project only considers players who were drafted into the NBA.**

The game of basketball is rather complex, with 5 players on each team competing on the court to make as many points as possible while trying not to commit fouls. Each of the 5 players usually play different positions: point guard, shooting guard, small forward, power forward, and center. If you are not familiar with these positions, read more about it [here](https://en.wikipedia.org/wiki/Basketball_positions).

Many statistics are measured about a player, like their field goal percentage, three-point shot percentage, rebounds, assists, and so on. [Here](https://www.basketball-reference.com/about/glossary.html) is a glossary of every possible statistic and what they mean. For this project, one of my focuses will be on modelling a player's NBA position using their college/NCAA player statistics.

## The Data

The data for players in the NBA is scraped from [Basketball Reference](https://www.basketball-reference.com). The college player statistics is scraped from [Sports Reference College Basketball](https://www.sports-reference.com/cbb/). My scraper scraped over 4000 different players, their NBA statistics and corresponding college basketball statistics and matched them together. I used BeautifulSoup for majority of the webpage processing. The matching process required me to manually match 100 different players (their NBA statistics with their college statistics). You can find the scraping code on my Github [here](https://github.com/lonerz/nba_college_stat_analysis/tree/master/scraper_stuff).

## About Me: Joshua Pan

I'm currently a sophomore at Harvard University, studying Computer Science with a focus in theoretical computer science and systems programming. You can find me on [LinkedIn](https://www.linkedin.com/in/joshuadpan/) and [GitHub](https://github.com/lonerz). Would love to connect with you!

## Source Code

You can check the source code out on [GitHub](https://github.com/lonerz/nba_college_stat_analysis/). You can also watch my video below and read my [paper](https://joshuapan.shinyapps.io/nba_college_stat_analysis/report.pdf)!
