# CS 573 Data Visualization Final Project

## Data

The data I have visualized for my final project is the *Spotify Top 10000 Streamed Songs* dataset on [Kaggle](https://www.kaggle.com/datasets/rakkesharv/spotify-top-10000-streamed-songs). 


## Final Deliverable
### [YouTube](https://youtu.be/WoxZ7YFbKEs")
### View 1: Spotify Artist Scatter Plot
[![image](https://github.com/flanagancarlie/CS-573-spotify-dataviz-project/blob/final/final/final-1.png?raw=true)](https://vizhub.com/flanagancarlie/c0e594f80f3a4bedb4f7ba4af3365a72)
### View 2: Top 10 Artists
[![image](https://github.com/flanagancarlie/CS-573-spotify-dataviz-project/blob/final/final/final-2.png?raw=true)](https://vizhub.com/flanagancarlie/c0e594f80f3a4bedb4f7ba4af3365a72)
### View 3: Artists' Streams Per Song
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

## Milestones & Prototype Iterations

* Week 7 - Added color, aimed to remove the white space present in initial prototype.
[![image](https://github.com/flanagancarlie/CS-573-spotify-dataviz-project/blob/final/prototypes/color-prototype.png?raw=true)](https://vizhub.com/flanagancarlie/fb9dcd09241143aaa69636cc7649a2c7)

* Weeks 8, 9 - Added interactive dropdowns: one for x-axis to narrow down the scale, and one for y-axis to change the attribute being plotted.
[![image](https://github.com/flanagancarlie/CS-573-spotify-dataviz-project/blob/final/prototypes/dropdown-prototype.png?raw=true)](https://vizhub.com/flanagancarlie/01207e3fed074a0fa0a17db29fa6f3a9)

* Week 10 - Implemented tooltips and interactions on hover to view artist data in detail.
[![image](https://github.com/flanagancarlie/CS-573-spotify-dataviz-project/blob/final/prototypes/interactions-prototype-2.png?raw=true)](https://vizhub.com/flanagancarlie/ab94c929755e4aa7872e8e2adacf3779)
[![image](https://github.com/flanagancarlie/CS-573-spotify-dataviz-project/blob/final/prototypes/interactions-prototype.png?raw=true)](https://vizhub.com/flanagancarlie/ab94c929755e4aa7872e8e2adacf3779)

* Week 11 - Created a scatterplot that uses small multiples, displaying streaming data for each of the top 10 artists' songs.
[![image](https://github.com/flanagancarlie/CS-573-spotify-dataviz-project/blob/final/prototypes/small-multiples-prototype.png?raw=true)](https://vizhub.com/flanagancarlie/5d5f1e44a75346cdb7ed021cc85f8d20?mode=full)

* Week 12 - Created a bar chart to compare the top 10 artists by streams.
[![image](https://github.com/flanagancarlie/CS-573-spotify-dataviz-project/blob/final/prototypes/bar-chart-prototype.png?raw=true)](https://vizhub.com/flanagancarlie/c1759d3256174d1880cc9b82e67991b5)


## Future Work

Some other ideas for this dataset included the following: 
* Add a comparison view of [View 3](https://github.com/flanagancarlie/CS-573-spotify-dataviz-project/edit/final/README.md#view-3-artists-streams-per-song), allowing the user to compare two artists' songs side-by-side.
* A bar chart of the most frequent words/phrases in song titles. ![image](https://github.com/flanagancarlie/CS-573-spotify-dataviz-project/blob/final/sketches/common-words-sketch.png?raw=true)
* A pie chart of the most common languages of song/artist names. ![image](https://github.com/flanagancarlie/CS-573-spotify-dataviz-project/blob/final/sketches/language-sketch.png?raw=true)
* Bar chart comparison of total vs peak streams for each artist/song, including what percentage of streams were peak streams. ![image](https://github.com/flanagancarlie/CS-573-spotify-dataviz-project/blob/final/sketches/streams-sketch.png?raw=true)


## Acknowledgements 

I would like to thank Professor Curran Kelleher for developing VizHub, where each of these visuals is hosted, as well as teaching an incredibly engaging and educational course. I am also grateful to my fellow students with whom I have had the pleasure to work during this course. 

My final visualization utilizes a multi-view layout inspired by [Eri Kim's MoMA Artworks](https://vizhub.com/IeKimI/19352f8c88a1407ba2ec27940469a1a2?edit=files&file=index.js), and simple tooltips on hover inspired by [Ming Liu's Greater Boston Map](https://vizhub.com/mingliu815/3b85e5f4e65d40f6883447cfc8fedea7?edit=files&file=index.js).
