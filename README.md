# Data Visualization Project

## Data

The data I propose to visualize for my project is the top 10,000 songs on Spotify. This dataset came from [Kaggle](https://www.kaggle.com/datasets/rakkesharv/spotify-top-10000-streamed-songs).

## Prototypes

I’ve created a proof of concept visualization of this data. It's a scatterplot that utilizes a logarithmic scale and it shows the peak position of each artist vs. the number of times the artist has had a song in the top 10,000.

[![image](https://github.com/flanagancarlie/CS-573-spotify-dataviz-project/blob/proposal/image.png?raw=true)](https://vizhub.com/flanagancarlie/e0735266df4444bf9ce07f3badc48903)

## Questions & Tasks

The following tasks and questions will drive the visualization and interaction decisions for this project:

 * Is there a correlation between the quantity of songs each artist has in the top 10,000 and their peak position? What about the quantity of streams?
 * Which artists/songs have reached #1?
 * What is the total number of streams (total or peak) for each artist?
 * Which artist has reached position #1 most often?
 * What are the top positions of each artist?
 * What song was at #1 position for the longest period of time?
 * How does peak position correspond to peak or total streams? 
 * How many songs in the top 10,000 have never reached the top 10, 100, etc.?

## Sketches

![image](https://github.com/flanagancarlie/CS-573-spotify-dataviz-project/blob/proposal/sketch.png?raw=true)
This is a sketch plotting the peak position of each artist vs. the number of times the artist has had a song in the top 10,000. This data is visualized as a scatterplot.
For action items, I imagine the user being able to adjust the y-axis via dropdown. The default will be peak position, but I think it will also be valuable to view other attributes, including peak streams and total strems. The x-axis may also be changed to narrow down the range, for example shortening the view from artists with songs in the top 10,000 to artists with songs in the top 1000, 100, etc, or songs with rank 1.
I also imagine that each point on the scatterplot will have a tooltip on hover or click, which will show the artist(s) as well as the x and y values. For example, when the scatterplot is of peak position vs. frequency of songs in the top 10k, hovering over a point would show an artist, their peak position, which songs are in the peak position, and their count of songs in the top 10k.
This relates to the tasks as the user will be able to visualize each of these questions by modifying the viz.

## Open Questions
 * My visualization so far feels too dull. I want to add color to categorize my data somehow, but I'm not sure where this would be useful.
 * Even after changing my scale from linear to logarithmic, there is still a significant amount of white space. What can I do about this?

## Milestones

Week 7 - Add color, try to remove white space.

Week 8 - Add interactive dropdown button for x-axis to narrow down the scale.

Week 9 - Add interactive dropdown button for y-axis to change the attribute being plotted.

Week 10 - Implement tooltips on click or hover to view the artist and song data.

Week 11 - Create a visualization that uses small multiples, displaying artists with songs at #1 position.

Week 12 - Add a second view to compare the attributes of all songs, e.g. comparing peak position to total streams.

Week 13 - Add interactions and tooltips to second view. 

Week 14 - Finalize visualizations using professor and student feedback. Make a video presentation demonstrating my project.

