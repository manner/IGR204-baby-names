# Results

## Visualization 1
### Sketches
- a 
For this visualization we used 1a sketch. We used interactive visualization with 3 components. The main component is stacked area chart in which every area is encoding
one name (and each area is coloured differently). It is showing number of occurences of top 50 most popular names in France (overall popular - including all the data).
This chart allows us to see popularity of most common names in France through years. With mouseover, we can see which are is encoding which name. It is allowing us to see for each name some periods when it was more or less popular. In the same time, for a chosen name there is a histogram under the chart showing popularity of that name over time. Here it is easier to see exact numbers of occurences through the years. Above the chart there is another histogram showing most popular names in selected range of years. On the stacked area chart we can select an interval of years and the histogram shows most popular names and their occurences in that period.

- b
Second idea for visualization 1 which we haven't implemented includes stagered histogram of name popularity over the years. Here, every histogram is encoding one name and showing its popularity through years. In this idea, we can not use as many names as in 1a (max 20 names). Additionally, in 1a stacked are chart it is much easier to compare popularity of two names at the same time. 

### Implementation: 1a

## Visualization 2
### Sketches
- a 
For visualization 2 we used 2a sketch. It is interactive visualization with 2 components. One of them is a map and another histogram. Those 2 components are mutually interactive, so they would be able to answer all the questions needed. When we choose area in the map, the histogram shows number of occurences of the top 35 names in that department  (Q: Are some names more popular in some regions?). Histogram is also interactive. When we choose a bar from histogram, the map turns into a heatmap of percentage of chosen name through the departments (Q: Are popular names generally popular across the whole country?). The map is showing percentages of names because if more children are born in some departments, it also affects the heatmap and we wanted to show only popularity not affected by natality.
    
- b
Second idea for visualization would be map on which we can choose an area. Under the map there is a histogram showing relative occurence of most popular overall names in whole of France and in a chosen department. That visualization answers the question: "Are popular names generally popular across the whole country?", but it doesn't answer the question: "Are some names more popular in some regions?".
### Implementation: 2a

## Visualization 3
### Sketches
- a 
First sketch shows log-ratio of female vs male name usage through the years. We used log-ratio because otherwise, chart would be biased depending if we choose men vs women ratio or women vs men ratio. Every name is encoded with a colour. We didn't use this idea because there is no sense in encoding names with colours because it would be either too few names or it would be impossible to read encodings.
- b
We used second sketch for this implementation. It shows the same thing as the first and third idea, but it shows the average ratio of all names used for both genders. We used this implementation because the other two show extra information which are not relevant regarding the questions and both were very messy. This one is the most clear one.  
- c
For the third sketch we showed all names without colour encodings (one blue line for each name). In theory, we thought that this idea would be best to answer all the questions. The idea is to see when are the lines more concentrated around zero (name equally used for both genders) and when it is far away from zero and on which side. It would be also interesting to use mouseover to see which line is encoding which name and to see how the name was used for both genders during the years. Unfortunately, this chart was very messy and not as informative as 1b.
### Implementation: 3c
