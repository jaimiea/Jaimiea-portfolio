| [home page](https://jaimiea.github.io/Jaimiea-portfolio/) | [visualizing debt](visualizing-government-debt) | [critique by design](critique-by-design) | [final project I](final-project-part-one) | [final project II](final-project-part-two) | [final project III](final-project-part-three) |

# Makeover Monday
Graph selected for the redesign: [2022/W35: Top 10 Countries by Military Spending Summary](https://data.world/makeovermonday/2022w35/workspace/project-summary?agentid=makeovermonday&datasetid=2022w35)

Original article: [VisualCapitalist](https://www.visualcapitalist.com/ranked-top-10-countries-by-military-spending/)

![Screenshot of original graph](https://www.visualcapitalist.com/wp-content/uploads/2022/08/top-10-countries-military-spending.jpg)

I chose this graph for my redesign because I liked the topic and aesthetics of the original visualization. Like the OECD graphs generalizing government debt, I wanted to create a visualization that offered comparative data for the U.S. and other countries. I also liked that the visualization could be targeted at diverse audiences. This allowed me to use the source data to create a graph that could be insightful for audiences interested in topics such as the U.S. military or global economies. The story I wanted to tell highlights the growing cost of global military expenditure.

# Redesign Process

**Sketch 1:**

![Sketchbook -7](https://github.com/jaimiea/Jaimiea-portfolio/assets/150535493/80052b3e-0c12-44b2-bc2a-383ace411832)
<br>
I made a rough draft of a pie graph for my initial redesign. In my critique of the original visualization, I discussed how the different shapes make it hard to compare the difference in military expenditure. The original graph also states that the U.S. and China accounted for more than 50% of the global military spending but this was not obvious or accurately depicted. I considered the visualization's truthfulness and intuitiveness, as I tried to restructure the data using a pie graph. Now that the shapes were the same, I thought this would help readers easily gauge the relationship between size increase and higher expenditure. Since the source article focuses a lot on the Russia-Ukraine conflict and its influence on global military spending I brainstormed ways to depict this. I initially colored the U.S. slice as green, China as yellow, Russia as red, and everything else as grey. However, I realized the data analyzed is from 2021 (before the invasion) and is not relevant in this context. Thus, I decided not to move forward with this type of redesign since it would be misleading. 

**Sketch 2:**

![Sketchbook -8](https://github.com/jaimiea/Jaimiea-portfolio/assets/150535493/3b83947d-74c8-49dc-9326-61717d11ec23)
<br> 
For my second sketch, I drew a bar chart with vertical bars. I used a very generic title that informs the audience that the country of focus is the U.S. compared to the rest of the world. I liked that the bar graph also uses the same rectangular shape to make the graph's perceptibility more clear. In this redesign, I used red for the U.S. bar and black for the other nine countries to draw the audience's attention to the U.S. and draw a clear comparison. I also ordered the bars in descending order. 

**critiques:**
- **student, early 20s:** This student explained that the bar graph makes it abundantly clear that the U.S. government spends more on its military than any other country in the world. The student shared that she grew up in a military family and found this topic to be of personal interest. She also stated that this graph could be targeted at a wide-reaching audience or used to comment on a wide variety of news stories and topics. They did recommend changing the title to something that isn't a question. They also advised including a color legend for the chart.
- **adult, mid-50s:** This individual found the graph the be straightforward and clear. They appreciated the simple design and stated that it was to the point and great for busy readers. They stated that this graph seems relevant to anyone who follows politics or is involved with the military. They did advise putting country abbreviations for each bar to make it easier to read.

**Tableau Graph 1:**

<div class='tableauPlaceholder' id='viz1707266534339' style='position: relative'><noscript><a href='#'><img alt='Highest Military Spending Across the Globe  ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Mi&#47;MilitarySpendingMap2&#47;Sheet22&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='MilitarySpendingMap2&#47;Sheet22' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Mi&#47;MilitarySpendingMap2&#47;Sheet22&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /></object></div>
<script type='text/javascript'>
  var divElement = document.getElementById('viz1707266534339');
  var vizElement = divElement.getElementsByTagName('object')[0];
  vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';
  var scriptElement = document.createElement('script');
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';
  vizElement.parentNode.insertBefore(scriptElement, vizElement);
</script>

<br>


**critiques:**
- **student, early 20s:** The student described the map graph to be visually appealing but less clear about its intent. She explained that the whole country being filled in with color made it more obvious which countries were included on the top ten list. They also stated that the colors referring to dollar expenditure rather than country name in the key felt more informative, and better highlighted where each country fell on the spectrum. However, she felt the title didn't make it obvious that the U.S. had the highest military expenditure as the other graph did. They also recommended increasing the color range if possible since red-green color blindness is pretty common.  
- **adult, mid-50s:** The second user found the map visualization to be informative geographically but not as impactful as the previous draft. They explained that the map took more time to understand and didn't like having to scroll over each country to obtain further information. They also disliked that some of the country titles did not fit into each country on the map. They advised it would be more appealing with a simpler design that could show all the data at one glance. 
 
**Insights from user feedback:**
- I noticed that both critics preferred a simpler design. They both emphasized perceptibility and intuitiveness over an overly complex design.
- One important thing I learned from the student feedback was to consider accessibility when choosing colors for my visualization. Her comments on color blindness made me realize I often use red and green to represent a positive or negative trend in my graphs. Moving forward, I will reconsider my color choices more carefully.
- Both critics stressed the importance of an interesting title that guides the audience's attention.
- Lastly, small details can significantly improve a graph's perceptibility. Including things like a caption, labels, or legend can dramatically improve its effectiveness. 

# Final Visualization 

<div class='tableauPlaceholder' id='viz1707270212804' style='position: relative'><noscript><a href='#'><img alt='2021 Top Global Spenders: U.S. Reigns SupremeGlobal conflict has influenced military spending and technology. Military expenditure includes the developing, exporting, and deploying of military personnel and weaponry costs. 2021 data confirms that global ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Fi&#47;FinalRedesign&#47;Sheet1&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='FinalRedesign&#47;Sheet1' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Fi&#47;FinalRedesign&#47;Sheet1&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /></object></div>
<script type='text/javascript'>                    
  var divElement = document.getElementById('viz1707270212804');
  var vizElement = divElement.getElementsByTagName('object')[0];                    
  vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                    
  var scriptElement = document.createElement('script');                    
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    
  vizElement.parentNode.insertBefore(scriptElement, vizElement);                
</script>

<br>

**Redesign:**
-what your redesigned data visualization shows, 
-what you attempted to show or do differently. describe changes (horizontal bars, simplified label to Spending (USD), better title, caption, legend, used blue and grey, axis labels, 
-(describe changes, troubleshooting, excel data revisions)
challenges: could not use 2021 data to tell story about the article's take on global conflict and china and Russia. Seemed irrelevant (USEFULLNESS, completeness 
Excel data showed Billons and thousands and tableau could not read the values correctly. Needed to change raw data to billions for accurate visualization

ultimately opted for a simple redesign. 
