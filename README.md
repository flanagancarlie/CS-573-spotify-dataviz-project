# CS 573 Data Visualization Final Project

## Data

The data I have visualized for my final project is the *Spotify Top 10000 Streamed Songs* dataset on [Kaggle](https://www.kaggle.com/datasets/rakkesharv/spotify-top-10000-streamed-songs). 

## Final Deliverable
[![image](https://github.com/flanagancarlie/CS-573-spotify-dataviz-project/blob/final/final/final-1.png?raw=true)](https://vizhub.com/flanagancarlie/c0e594f80f3a4bedb4f7ba4af3365a72)
[![image](https://github.com/flanagancarlie/CS-573-spotify-dataviz-project/blob/final/final/final-2.png?raw=true)](https://vizhub.com/flanagancarlie/c0e594f80f3a4bedb4f7ba4af3365a72)
[![image](https://github.com/flanagancarlie/CS-573-spotify-dataviz-project/blob/final/final/final-3.png?raw=true)](https://vizhub.com/flanagancarlie/c0e594f80f3a4bedb4f7ba4af3365a72)

## Sketches

![image](https://github.com/flanagancarlie/CS-573-spotify-dataviz-project/blob/final/sketches/scatterplot-sketch.png?raw=true)
This is my initial sketch, sketch plotting the peak position of each artist vs. the number of times the artist has had a song in the top 10,000. This data is visualized as a scatterplot.
For action items, I imagine the user being able to adjust the y-axis via dropdown. The default will be peak position, but I think it will also be valuable to view other attributes, including peak streams and total strems. The x-axis may also be changed to narrow down the range, for example shortening the view from artists with songs in the top 10,000 to artists with songs in the top 1000, 100, etc, or songs with rank 1.

I also imagine that each point on the scatterplot will have a tooltip on hover or click, which will show the artist(s) as well as the x and y values. For example, when the scatterplot is of peak position vs. frequency of songs in the top 10k, hovering over a point would show an artist, their peak position, which songs are in the peak position, and their count of songs in the top 10k.



## Prototypes

I’ve created a proof of concept visualization of this data. It's a scatterplot that utilizes a logarithmic scale and it shows the peak position of each artist vs. the number of times the artist has had a song in the top 10,000.

[![image](https://github.com/flanagancarlie/CS-573-spotify-dataviz-project/blob/final/prototypes/scatterplot-prototype.png?raw=true)](https://vizhub.com/flanagancarlie/e0735266df4444bf9ce07f3badc48903)

## Questions & Tasks

The following tasks and questions drove the visualization and interaction decisions for this project:

 * Is there a correlation between the quantity of songs each artist has in the top 10,000 and their peak position? What about the quantity of streams?
 * Which artists/songs have reached #1?
 * What is the total number of streams (total or peak) for each artist?
 * Which artist has reached position #1 most often?
 * What are the top positions of each artist?
 * How does peak position correspond to peak or total streams? 

## Milestones

* Add color, try to remove white space.
[![image](https://github.com/flanagancarlie/CS-573-spotify-dataviz-project/blob/final/prototypes/color-prototype.png?raw=true)](https://vizhub.com/flanagancarlie/fb9dcd09241143aaa69636cc7649a2c7)

* Add interactive dropdown for x-axis to narrow down the scale, and dropdown for y-axis to change the attribute being plotted.
[![image](https://github.com/flanagancarlie/CS-573-spotify-dataviz-project/blob/final/prototypes/dropdown-prototype.png?raw=true)](https://vizhub.com/flanagancarlie/01207e3fed074a0fa0a17db29fa6f3a9)

* Implement tooltips and interactions on hover to view the artist and song data.
[![image](https://github.com/flanagancarlie/CS-573-spotify-dataviz-project/blob/final/prototypes/interactions-prototype-2.png?raw=true)](https://vizhub.com/flanagancarlie/ab94c929755e4aa7872e8e2adacf3779)
[![image](https://github.com/flanagancarlie/CS-573-spotify-dataviz-project/blob/final/prototypes/interactions-prototype.png?raw=true)](https://vizhub.com/flanagancarlie/ab94c929755e4aa7872e8e2adacf3779)

* Create a visualization that uses small multiples, displaying artists with songs at #1 position.
[![image](https://github.com/flanagancarlie/CS-573-spotify-dataviz-project/blob/final/prototypes/small-multiples-prototype.png?raw=true)](https://vizhub.com/flanagancarlie/5d5f1e44a75346cdb7ed021cc85f8d20?mode=full)

* Add a second view to compare the attributes of all songs, e.g. comparing peak position to total streams.
[![image](https://github.com/flanagancarlie/CS-573-spotify-dataviz-project/blob/final/prototypes/bar-chart-prototype.png?raw=true)](https://vizhub.com/flanagancarlie/c0e594f80f3a4bedb4f7ba4af3365a72)



## Future Work
Some other ideas I had for this dataset included the following: 
* 
