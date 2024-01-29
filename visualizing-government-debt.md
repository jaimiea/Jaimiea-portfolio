| [home page](https://jaimiea.github.io/Jaimiea-portfolio/) | [visualizing debt](visualizing-government-debt) | [critique by design](critique-by-design) | [final project I](final-project-part-one) | [final project II](final-project-part-two) | [final project III](final-project-part-three) |

# 2021 General Government Debt
Here we took the OECD website's original bar graph for general government debt by country. The graph has been filtered only to show data for the year 2021.

<iframe src="https://data.oecd.org/chart/7klb" width="860" height="645" style="border: 0" mozallowfullscreen="true" webkitallowfullscreen="true" allowfullscreen="true"><a href="https://data.oecd.org/chart/7klb" target="_blank">OECD Chart: General government debt, Total, % of GDP, Annual, 2021</a></iframe>

# 1995-2021 Government Debt by OECD Country
For this example, we used a heat map to visualize each OECD country's government debt as a % of its annual GDP. 

<script type='module' src='https://prod-useast-b.online.tableau.com/javascripts/api/tableau.embedding.3.latest.min.js'></script><tableau-viz id='tableau-viz' src='https://prod-useast-b.online.tableau.com/t/jaimiea/views/VisualizingGovtDebt/Sheet1' width='1396' height='665' hide-tabs toolbar='bottom' ></tableau-viz>

# 2021 Government Debt by OECD Country 
Here we filtered the data to focus on the annual government-debt-to-GDP ratio for each OECD country. The countries with the highest % are highlighted in red while countries with lower percentages are in green.

<script type='module' src='https://prod-useast-b.online.tableau.com/javascripts/api/tableau.embedding.3.latest.min.js'></script><tableau-viz id='tableau-viz' src='https://prod-useast-b.online.tableau.com/t/jaimiea/views/VisualizingGovtDebt/Sheet2' width='1711' height='854' hide-tabs toolbar='bottom' ></tableau-viz>


I attempted to make two graphs using the provided data. For the first graph, I used a treemap to display the countries with the highest debt to the lowest, going from left to right. I used a red to-green color scale to represent the debt range and made my center value 100. I wanted red to represent the countries with high debt and green for countries with lower debt. I like that the treemap allows you to visualize the values by square size and color, and allows enough space for both the country and value labels. This enables users to see what data point corresponds to which country without having to scroll over each square. 

# U.S. Debt Versus the OECD Average 
Based on available data from 2007-2021, we compared the U.S. debt-to-GDP ratio with the annual average among all OECD countries.      

<script type='module' src='https://prod-useast-b.online.tableau.com/javascripts/api/tableau.embedding.3.latest.min.js'></script><tableau-viz id='tableau-viz' src='https://prod-useast-b.online.tableau.com/t/jaimiea/views/VisualizingGovtDebt/Sheet3' width='1396' height='665' hide-tabs toolbar='bottom' ></tableau-viz                 


For the second graph, I wanted to tell a story about the U.S. debt-to-GDP ratio compared to the average for all OECD countries. Since there was only data for select years, I filtered the graph to only show data for 2007-2021. Here I utilized a circle view graph to show the comparison. I color-coded the blue circles to represent the U.S. and the orange circles to represent the OECD average. I also included a color legend.  Then I added labels to show the exact value for each data point. I think the circle graph worked well for this comparison since it makes it easy for the audience to determine that the U.S. debt is consistently higher than the average for the years 2007-2021. The graph also informs users that the U.S. debt-to-GDP ratio seems to consistently increase over time.                                                                                                                                                    
