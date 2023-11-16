# Data_Collection_Challenge: All about Mars...
Challenge 11
## Part 1
In this section, we are going to scrape the titles and article previews from the [Mars Planet Science](https://static.bc-edx.com/data/web/mars_news/index.html) index page and store the results in a Python list of dictionaries.
<br>
The code can be found in the _part_1_mars_news_ file.



## Part 2
In this section, we are going to scrape the content of an html [table](https://static.bc-edx.com/data/web/mars_facts/temperature.html) containing weather data collected by the Nasa Mars rover between 2012-08-16 and 2018-02-27.
<br>

We will then convert the data to a Pandas datafram, condition the data, and start analysing it. <br>
We can see that the data is tagged as coming from 12 discrete Mars months, and that there are 1867 dicrete entries reported by Curiosity. <br>

An analysis of the average minimum temperatures shows that the coldest month is the 3rd Mars month with an average temperature of -83.3C, and the warmest is in average the 8th months with an average temperature of -68.4C (figure 1).
<br>
Figure 1:<br>


<br><br>
An analysis of the atmospheric pressure indicates that the 6th month has in average the lowest pressure with 745Pa and the 9th moth the highest with 913Pa (figure 2).
<br>
Figure 2:<br>

<br><br>
A representation of the minimum temperature over time indicate a periodicity that can be seen over almost three cycles. From this representation, we can visually infer that a Mars year corresponds to about 675 to about 680 days (from the number of the daily entries from the Curiosity rover). We can support this estimation by looking at the row data behind the graph and by estimating the time delta between the corresponding Earth collection dates.
<br>
Figure 3:<br>

<br><br>
The code can be found in the _part_2_mars_weather_ file.






