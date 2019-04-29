# Using K-Means Clustering to Design the Best Teams of WNBA Players of All Time
## Bonus: Also includes a data-driven simulated game between the top two teams

I did this project for fun to see what it would look like if the best players on the WNBA played against each other. First, I scraped all WNBA player stats from Basketball-Reference.com. After much thought, I decided the best way to create ranked teams among all WNBA players was to divide all players by position, then cluster players within each position according to that position's best performance metrics, and then combine top ranking clusters into teams. I used K-Means Clustering where k = 8, therefore I created a total of eight teams, each with players from five positions. At the end of my notebook, I simulate a data-driven game between the top two teams. This was a fun project to work on! I'm now a proud fan of the WNBA and will continue contributing to the field of women's sports data. 
