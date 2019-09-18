# Critique By Design

This week, we were assigned to critique and redesign a visualization that we found in the wild, wild West of the Internet. I found this visualization that highlighted movies' release year, number of jump scares, and their imdb movie scores:

 ![original visualization](https://i.redd.it/uo99n4hxnhv11.png)


## Critique
I analyzed this visualization using Stephen Few's effectiveness evaluator and found it to have strong completeness and aesthetics, but lacking in coherency.

This visualization saught to capture a lot of elements, and used the scatterplot's colors, x, and y axis to illustrate the data. However, there is no apparent trend that emerges from this data. I think the color palette was appropriate for the subject, and can see how the creator was trying to represent data. 

However, some points are confusing; If a movie (represented by a single point) had the same number of jump scares and came out in the same year as another movie, wouldn't they overlap? I would eliminate films from before 1970 to allow more space for this. I also would consider switching the axis/colors, so that the Y axis represents imdb rating and color represents the number of jump scares; potentially size, as well, or instead of color. I would also use the title to help tell the story presented.

# Redesign Approach
From the critique method, I learned that it was important to identify a story in this data that can be highlighted and supported. Changing the y-axis was the best way to do this, and while I wireframed by experimenting with different mapping elements, it became clear very quickly that the y-axis should convey IMDB score as opposed to the number of jump scares (because of potential overlap). Color and size told the story much more clearly.

![first wireframe](https://i.imgur.com/BUblZCy.png)


## Audience Feedback
While receiving feedback, I learned that individuals wanted specific movies highlighted that are easily recognizable or are significantly outlying to provide context. Those I spoke to also wished I had kept more of the original color palette with a black background, to retain some of the spirit of the original visualization and horror themes. They wanted to see the red against the black background, and I easily agreed. We did have an interesting conversation about why I chose diverging colors as opposed to a straight color scale; dividing up the "jump count" measure between "fewer jump scares" and "more jump scares." In the end, I determined that it was much easier to see the patterns in the data when diverging as opposed to a simple scale.

I look forward to getting feedback on my final design, which I feel is still slightly overcomplicated. I think it works best as an interactive visualization, since a lot of the lables overlap points, and vice-versa. My redesigned visualization shows the trend of movies over the years, how many had fewer or greater jump scares, and where these fell along IMDB's rating scale. It uses labels to highlight case examples and exceptions, as well as contextualizing hits.

# The Final Design

![final visualization](https://i.imgur.com/nzgZh7O.png)

And that's it! The funniest thing about all of this is that I cannot stand scary movies- I don't mind creepiness, but jump scares are the worst! I was excited to find the website this data comes from so that I can see jump-scare-light films. John Carpenter's The Thing is absolutely my favorite scary movie.

With that- enjoy, and let Halloween roll around, already!
