# Critique By Design - MTG Pauper Challenge Results

## Original Data Visualization

I enjoy playing the card game Magic: The Gathering (MTG) and often look at mtggoldfish.com for reports on recent tournaments. In this game players can build their own decks of cards, but generally gravitate towards a few successful strategies. This website posts weekly articles on the current 'metagame' (what decks are popular and how those decks are performing). A common series of charts is taken from performance in a weekly tournament, the Pauper Challenge. This data is collected by the Castle of Commons discord and is freely available at https://docs.google.com/spreadsheets/d/1vMIA_qU5YCpv74hdiGgTqxmUpvY20yRIhtDBcUzxA88/edit#gid=1470099066.
Article Link: https://www.mtggoldfish.com/articles/the-power-of-pauper-inside-and-out
These three charts show the most important information for a tournament: Play %, Win%, and Top 8 performers.

![](meta.png)

## Critique

These charts are simple and effective. Additionally, they have the benefit of being a chart consistently produced in the same format so enfranchised players should be familiar with the format. Seeing as this is niche information that would not be accessible to most viewers, two target audiences should be kept in mind.
1) Heavily enfranchised players who want to keep up with the weekly tournaments.
2) New players who want to see popular decks as they get into the game.

My biggest issues with these charts are the following:
1) Not exciting. The color palette and form is a bit bland and uninteresting. It does not draw attention to the data or any key insights.
2) Inefficient use of space. The current format uses three different charts and a lot of space to give very simple information.
3) Doesn't Tell the full story. Showing number of pilots (players that played the deck) without including the number of players in the tournament is odd.

## Wireframing Solutions

### Attempt 1: Pie Chart

![](IMG_0196.jpg)

### Attempt 2: Colored Text Chart

![](IMG_0197.jpg)

### Attempt 3: Circle Chart

![](IMG_0198.jpg)

### Attempt 4: Top 8 Flow

![](IMG_0199.jpg)

## Testing the Solution

I shared my wireframes with two other students and got the following feedback.

### Student 1: Male 26, Familiar with MTG

### Student 2: Female 26, Unfamiliar with MTG

### Reflection on Feedback

## Recreated Data Visualization

While I was most interested in producing a final version of wireframe #4, I had no idea how to approach this using the software we covered in class. I settled on reproducing a simpler form of wireframe #3 using Tableau. When publishing there was a consistent issue with information in the 'Golgari' portion disappearing, but this information will still display when hovered over.

<div class='tableauPlaceholder' id='viz1695263486603' style='position: relative'><noscript><a href='#'><img alt='MTG Pauper Challenge 16-Sep-2023Total Players: 48 ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;MT&#47;MTGPauperChallenge&#47;Sheet1&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='MTGPauperChallenge&#47;Sheet1' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;MT&#47;MTGPauperChallenge&#47;Sheet1&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>                
<script type='text/javascript'>                    
var divElement = document.getElementById('viz1695263486603');                    
var vizElement = divElement.getElementsByTagName('object')[0];                    
vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                    
var scriptElement = document.createElement('script');scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    
vizElement.parentNode.insertBefore(scriptElement, vizElement);                
</script>

### Self-Critique and Comparisons to Original Visualization

1) asdf
2) 
