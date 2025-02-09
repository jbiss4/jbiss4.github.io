Assignment 3 - Replicating a Classic Experiment  
===
**Team Team**<br/>
Jake Bissonette<br/>
Sean Horton<br/>
Victoria Mirecki<br/>
Sam Mora<br/>

## Experiment 
Link: https://jbiss4.github.io/

# Start Page: 
The start page starts with a thank you to those who are completing the experiment and a brief explanation of the goal of what the participant will be doing. Once they click "Start" , it moves on to another page which will depict the Question #, the image, and then a text box which you press "Next" and a new image is generated. On each of these pages there is also the question being asked and an example to explain what you are supposed to do. 

# Bar Graph:
![bar](https://i.imgur.com/1I5cdkT.png)

The image above depicts an example of one of our randomized bar charts that were generated. Each of the bar graphs had 5 bars, which were randomly generated to have a value between 0 and 100. Then two of these bars were randomly selected (as seen with the two circles) to be compared. 

# Pie Graph:
![pie](https://i.imgur.com/vXE9qZh.png)

The image above depicts an example of one of our pie charts that were generated. These pie charts had 5 slices, which were randomly generated to have a value between 0 and 100 each. Then two of the slices were randomly selected to be compared. Because we allowed the value to go to 0, there were occasional instances where there would only be 4 slices, and sometimes the circle would end up between two slices to represent that missing slice (and 0% of the larger one).

# Donut Graph:
![donut](https://i.imgur.com/xU1BS5r.png)

The image above depicts an example of one of our donut charts that were generated. These donut charts had 5 slices, which were randomly generated to have a value between 0 and 100 each. Then two of the slices were randomly selected to be compared. Because we allowed the value to go to 0, there were occasional instances where there would only be 4 slices, and sometimes the circle would end up between two slices to represent that missing slice (and 0% of the larger one). The donut charts very closely resemble the previous pie charts, but without the central area, which could potentially cause it to be more challenging to interpret. 

# Error Graph:
![dot error](https://github.com/jbiss4/jbiss4.github.io/blob/main/img/dot-error.PNG?raw=true)
![error bar](https://github.com/jbiss4/jbiss4.github.io/blob/main/img/error-bar.PNG?raw=true)

The first graph shows the error using the Cleveland-McGill error calculation on the log2 scale, while the second graph shows the bars of the error to help generalize the visualization of the results. It's clear that like in Cleveland-McGill, the pie chart is less effective than the bar chart, and the donut charts are the least effective of the bunch.

## Hypothesis
Our hypothesis involved trials of three graph types to replicate Cleveland and McGIll's experiment of graphical perception, being a bar graph, a pie graph, and a donut graph. For our experiment, we hypothesized that the bar graph would be the easiest to percieve size differences in graph elements. While we wanted to compare the bar to both the pie and donut graphs, we wanted to compare the pie graph against the donut graph as they are very similar. We hypothesized that the pie graph would be easier to perceive size differences than the donut graph, since the donut graph has empty space in the middle, meaning it could be harder to determine the true size of the slice and its respective value.

## Results
Our experiment and error conduction showed us that bar graph was the best graph when it comes to size perception on graphs. Between the pie and donut graphs, the (pie/donut) graph did better, as we hypothesized. It was interesting to see the spread of the errors for each graph, as they seemed much closer than we originally expected.

## Technical Achievements
We used d3, html/javascript, google sheets, ggplot2 and R to complete this assignment. One of the technical things we worked with in our code was placing the dots on each graph in the correct location. We use variables associated with the given graph and svg so that if one wanted to move the location of the pie and donut chart, their dots woould still appear in the correct places. We also had one running Google Sheet where all of the data went after each trial and we did not have to combine multiple csvs. However, the tradeoff to this method is that it is more difficult to notice incorrect answers, like striings. Addiitionally, when a person submits a response, at the same time the type of graph and the actual value of the percent difference were added simultanepusly to the Google sheet. This was a great achievement for us, as it allowed everything to be updated at the same time, without the user having to input all 3 values (which would totally defeat the experiment).


## Design Achievements
We made sure that there was a counter on the top of the webpage to let the participants know how far they had reached in the experiment. We also made sure that all of our chart types were of a similar size to make sure that the differences between chart types were not due to just having bigger / larger charts. We also edited the formatting, where participants originally had to scroll down to see the image and then scroll up to input the answer, the image and answer box were moved next to one another for easier use. Although with this format it was less accessible to see the counter at the top. Using Google Sheets for data storage instead of storing it in a csv and downloading it at the end allowed participants that have lower attention spans to still offer their results because their data would be included regardless of how far along they got. Something we could have changed would have been to edit the text box so that it deletes the text inputted after each submission, since participants had to manually erase the data each time and this caused a couple people to accidentally input incorrectly without realizing. 

## Resources Used
- Pie Chart Example: https://www.tutorialsteacher.com/d3js/create-pie-chart-using-d3js 
- Donut Chart Example: https://www.d3-graph-gallery.com/graph/donut_basic.html
