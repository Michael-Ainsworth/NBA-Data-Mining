# NBA-Data-Mining

---------------------

### Project Description
This project uses data from the National Basketball Association (NBA) collected from Basketball-Reference.com. The datasets include advanced individual statistics and advanced team statistics from 10 different seasons (2009 through 2019).

The goal of this project is to identify trends in the individual statistics that are highly correlated with team win percentage and team playoff chances. Using machine learning and data mining techniques, I aim to find the most important individual statistics in relation to team success, the ideal number of "superstar" calibur players to sign, and the best metrics to look for when assembling an NBA roster.

---------------------

### The files in this repository include:
- NBA-Regression: Uses the VORP statistic to measure how "superstar" players in the modern NBA impact win rate using polynomial regression
- NBA-Classification: Attempts to identify the ideal number of "superstar" players required to make the playoffs using various classification techniques
- NBA-Deep-Learning: Uses a 4 layer ANN to show how aggragate stats of a team's top players can predict overall win percentage

---------------------

### Dependencies:
- Tensorflow (v '2.2.0')
- Scikit-learn (v '0.22.1')
- Numpy (v '1.18.1')
- Seaborn (v '0.10.0')
- Pandas (v '1.0.1')
