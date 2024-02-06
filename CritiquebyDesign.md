# Critique By Design: February 6th, 2024

**Original visualization: [the $730,000 gender pay gap in US World Cup bonuses](https://www.theguardian.com/football/ng-interactive/2019/jun/28/revealed-the-731003-gender-pay-gap-in-us-world-cup-bonuses)**

Source: the Guardian. “Revealed: The $730,000 Gender Pay Gap in US World Cup Bonuses,” June 28, 2019. http://www.theguardian.com/football/ng-interactive/2019/jun/28/revealed-the-731003-gender-pay-gap-in-us-world-cup-bonuses.

I selected this visualization because I am a huge fan of the US Women's National Team. I recently watched their Under Pressure docuseries on Netflix and cried most of the way through it. I grew up playing soccer and have always admired these women. It is important to me that they receive the compensation they deserve. The visualization in this article is impactful, but I felt I could create a visualization that is quicker to read and entices the reader to learn more. It takes too long to get to the main point of the visualization. I think it would elicit a much stronger emotional response if all of the data could be presented in one pane. This is what I want to work for throughout my redesign.

# The Redesign Process
## The First Draft
I began with some sketches of potential visualizations that would emphasize the size of the pay gap. At first, I considered pursuing a line chart to show how the pay changes throughout each world cup phase. After a couple drawings and exploring tableau, I realized this might not be the most effective way to convey this information because of the way the pay gap moves with lump sums throughout each phase. If this was a continuous data set and the space between each phase held more meaning, then a line chart would have been more useful. But, that doesn't apply to this data set. After hitting a wall with that idea, I decided to do some research on pay gap visualizations. I then found a stacked bar chart that I felt was more impactful. I took to tableau and began testing out some visualizations. It took awhile for me to figure out how to create this visualization in tableau the way I had imagined it in my head. After some work, I felt I was at a point where feedback would be helpful.
## Feedback 1
 I knew I wasn't done, but it felt like a good time to check in. I showed the participants the visualization below: ![image](https://github.com/evianambarnes/portfolio/assets/156966766/80f02074-60af-489c-be3f-5e26d79068c8)
 My participant (student, late 20s) was not very familiar with soccer. But, they quickly identified this was a comparison of pay. The most constructive feedback from this student came when they asked, "What does the sum of these values mean?" Unfortunately, my answer was, "nothing." I hadn't realized that my stacked bars were summing. I was attempting to create the visualization in a way that layered the bars on one another, not summed them. The sum of each gender's average earnings at each phase is a useless value. When I talked to my second participant (adult, early 50s), they immediately thought this model involved costs and expenses of World Cup participation. When I asked why, they said the colors made them think that. These two pieces of feedback sent me back to the drawing board. After this conversation, I felt like I had taken three steps forward and two steps back. I knew I was on the right track, but had some more refining to do. While this felt like the most critical takeaways from my conversations, below is a rough transcript of each interview for this round of review:
 
### Participant 1: student, late 20s
 Q: Can you tell me what you think this is?
 
 A: It looks like a wage comparison.
 
 Q: Can you describe to me what this is telling you?
 
 A: How low the pay of the red group is compared to the pay of the green group.
 
 Q: Is there anything you find surprising or confusing?
 
 A: I'm not following what the meaning is of the two bars summed together, and I understand this is about soccer, but I feel like I'm missing something.
 
 Q: Who do you think is the intended audience for this?
 
 A: Probably policy makers, or a committee in charge of equitable pay.
 
 Q: Is there anything you would change or do differently?
 
 A: I would note what the sum means, and add a meaningful title.
 
### Participant 2: adult, early 50s
 Q: Can you tell me what you think this is?
 
 A: I see information on the world cup, and it seems like this is maybe a cost breakdown, or income and expense comparison.
 
 Q: Can you describe to me what this is telling you?
 
 A: I see now on the y-axis there is information about average income per player, but I'm not sure what the two groupings of color are telling me.
 
 Q: Is there anything you find surprising or confusing?
 
 A: I'm confused by the two groups of color, I don't know what they represent. 
 
 Q: Who do you think is the intended audience for this?
 
 A: Maybe FIFA?
 
 Q: Is there anything you would change or do differently?
 
 A: I think the two groups need explicit labels.
 
## Feedback 2
After spending some time working on getting the height of the bar at the male players' pay, not the sum of the values, I realized this still might not be the best way to show the pay gap. After all, my main goal in redesign was to emphasize the **gap**. So, I moved towards a bar chart that would display the pay levels in separate bars, but right next to each other in each world cup phase. When I felt ready, I sought out feedback on this visualization: ![image](https://github.com/evianambarnes/portfolio/assets/156966766/6cf7deff-22d4-4b38-aed2-1784b227a8c8)
One participant (adult, early 50s) was able to very quickly recognize exactly what I was showing. They said, "The eye is drawn to the blue, emphasizing how low women's pay is." My other participant (student, late 20s) asked if this was an international average. This question led me to revisit my title to make it more specific. This feedback was helpful, and I was glad I chose grey for men's pay, but I still felt I could elicit a more emotional response. Here is a rough transcript of each interview for this round of review:

### Participant 1: student, late 20s
 Q: Can you tell me what you think this is?
 
 A: A gender wage comparison for soccer players.
 
 Q: Can you describe to me what this is telling you?
 
 A: That on average women soccer players earn a lot less than men.
 
 Q: Is there anything you find surprising or confusing?
 
 A: I was curious if this is an international average, and if so, if the measurement is in USD.
 
 Q: Who do you think is the intended audience for this?
 
 A: I'm not sure who is in charge of world cup pay - maybe FIFA? Or if the pay is by country then each country's legislators in charge of equitable wages.
 
 Q: Is there anything you would change or do differently?
 
 A: I would note what countries are included in this analysis in the title.
 
### Participant 2: adult, early 50s
 Q: Can you tell me what you think this is?
 
 A: It looks like how average income per player differs between men and women throughout each phase of the world cup.
 
 Q: Can you describe to me what this is telling you?
 
 A: Women soccer players are paid a lot less than men, and the gap gets worse as you advance further into the World Cup.
 
 Q: Is there anything you find surprising or confusing?
 
 A: Based on my knowledge of global soccer, I can assume that this is a comparison for the US teams, but I am not 100% sure of this.
 
 Q: Who do you think is the intended audience for this?
 
 A: FIFA, fans, and if this is US data, then the US policymakers who could make a change for more equitable wages.
 
 Q: Is there anything you would change or do differently?
 
 A: I think it needs to be made clear if this is US data.

## Final Touches
After trying out different colors and titles, I found myself with a visualization that just felt right. 

<div class='tableauPlaceholder' id='viz1707245525885' style='position: relative'><noscript><a href='#'><img alt='Gender Pay Gap Grows Throughout World Cup Advancement ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;HW&#47;HW34_17072455000270&#47;Sheet1&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='HW34_17072455000270&#47;Sheet1' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;HW&#47;HW34_17072455000270&#47;Sheet1&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>                
<script type='text/javascript'>                    
var divElement = document.getElementById('viz1707245525885');                    
var vizElement = divElement.getElementsByTagName('object')[0];                    vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                    
var scriptElement = document.createElement('script');                    
scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';  
vizElement.parentNode.insertBefore(scriptElement, vizElement);                
</script>


I changed the women's pay to red, a color both signifiying alarm and is heavily present on both teams' uniforms. The title helps the reader use their eye travel to watch how the gap grows as you read the visualization from left to right, and makes it clear that we are looking at US data. I feel comfortable with my visualization now, I'm proud of it. This process was frustrating, humbling, and rewarding. 

## Concluding Thoughts
I believe my final visualization choice is stronger at emphasizing the gap than the original visualization. I did like the original, but it wasn't a visualization that was easy to quickly view. I think it was important to make this a visualization that was visible in one pane because it is not common knowledge that the US Women's National Team is underpaid. By remaking this visualization with less eye travel, I think I created something that raises awareness for the gender pay gap in US soccer. My final visualization is better off than my first attempt because it is more intuitive and draws the eye immediately to the pay gap. Additionally, I like the use of red better in my final visualization compared to the soft blue of my second attempt. I like the interactive aspect of the original visualization, but I do believe I have created a product that is a great way to utilize the data to make the audience find the pay gap faster. Thus, my visualization is eliciting an emotional response and, hopefully, rallying a new advocate for equitable professional soccer wages.

## Next Time
As I continue learning through this course, I want to explore dashboards. I think it could have been even more impactful to add in information through text about how the US women's team has won the world cup 4 times, and the men have never won. Additionally, it could have been strong to quantify the marginal increases throughout each phase in an additional visualization. I played around with the dashboard for awhile, but I couldn't create something that felt as strong as the visualization I had already created. But, I'm sure by the end of this course, I will be able to knit all of these together!
