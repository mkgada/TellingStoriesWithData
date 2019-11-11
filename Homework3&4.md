# Homework 3 and 4

# Choice of Data Visualization and Reason
I have chosen the "Save Success Rate (% of Shots saved Target faced)" visualization published in an article by The Guardian.
It talks about the surprising performance decline of Europe's top goalkeepers in the 2018/19 season compared to 2017/18. 
Here is the link to the article: https://www.theguardian.com/football/who-scored-blog/2018/nov/29/europe-top-de-gea-courtois-ter-stegen-neuer

<img src='https://github.com/mkgada/TellingStoriesWithData/blob/master/HW4_4.PNG'/>

The reasons for choosing this visualization are:
- I am an avid football(soccer) lover and used to play the sport professionally in high-school.
- I follow all kinds of footballing action that happens in Europe and am updated about the performance levels of most top players in various teams
- Sometimes, I might be not aware of the correct information and thus I research about the statistics online to be up-to-date. I came across this article published by Guardian talking about goalkeeper's performance. I looked at it and was mislead with the arrangement of the bars that overlapped and a couple of other factors led me to choose this visualization.

# Intended Target Audience
The target audience for this piece of information fall into the following broader categories:
- Football followers (people like me)
- Football pundits (who analyse players and teams and talk about it on sports shows)
- Team Scouts (Each team has a scout who looks for potential players who would fit better in their team)

# First observations and possible recommendations
A bar graph is used to show a year on year comparison of % of shots saved by a goal keeper. Also, it aims to point out that top keepers from 2017/18 season such as David De Gea, Courtois, Neuer, Marc Andre ter Stegen have struggled in the 2018/19.
The things that stood for me are:
-	Data represents 2017/18 season and 2018/19 season. The manner in which they have been represented is misleading. For example, the 2018/19 season statistics have been shown with green bars and 2018/19 season statistics have been shown in semi-transparent color. Both the bars have been overlapped on top of each other for each goalkeeper.
-	The scale of the % shots saved on the y-axis has been truncated. It starts from 45%
-	This is misleading because the 2017/18 statistics in the semi-transparent bars have been shown on the right hand side for each goal keeper where the 2018/19 season statistics are on the left. Human read from left-to-right which and this arrangement would mislead them to think that the left bar in green in 2017/18 season and the transparent one is for 2018/19 season.
-	Further, the chart required a significant amount of eye travel to fully understand that for top goalkeepers, their % shots saved has decreased from the previous year for the top keepers from 2017/18. However, with the previous year bar appearing on the right-hand side of the chart for each keeper, it appears as if there is an increase in the % of shot saved year-on-year.


The things I would do differently are as follows:
-	Firstly, I would arrange the bar chart in such as way such that the 2017/18 statistics appear side by side to the 2018/19 statistics and not overlapping. Also, 2017/18 on the left and other on the right for each goal keeper
-	To highlight the dip in performance for the top keepers in 2017/18, I would proceed by arranging them in such a way in the chart such that the top keepers from previous years appear before the top keepers in 2018/19 season
-	The scale of the chart has been truncated and starts at 45% on the y-axis. I would proceed to start the scale from 0% on the y-axis
-	For all keepers with statistics from 2017/18 as well as 2018/19, I would proceed with graying the bar with the lower performance out of the two seasons. For example, David De Gea’s has lower performance in 2018/19, so that would be grayed but Buffon’s performance has increased in 2018/19 and the lower out of the two values is of 2017/18, so for Buffon that would be gray. Basically, the better performance years from the two would be in green and lower performance in gray to highlight the change

# Wireframing and User reviews
To proceed with trying to improve the overall readability of the visualization, I proceeded with developing a two wireframes and getting feedback from two individuals to incrementally improve the visualizations

Wireframe No.1 
This is my first take on developing a possible solution for the visualization.
- I decided to remove the overlapping bars for different years. Instead, they are represented side by side
- I proceeded with ordering the appearance of the goalkeepers in a way that 6 keepers whose performance slipped in the 2018/19 appear first and the ones performing better than them in 2018/19 appear later.
- Also, there are two bars associated with each goalkeeper. The left-hand side bar represents their performance in the 2017/18 and the right hand side bar represents the 2018/19 number.
- I have color coded the 2018/19 performance in a way such that, for the goalkeepers whose performance dipped from the previous year have a red bar and otherwise they have green bar to highlight the difference in performance year-over-year.

<img src='https://github.com/mkgada/TellingStoriesWithData/blob/master/HW4_11.jpg'/>img {
    image-orientation: from-image;
}


Wireframe No.2 
This is my second take on developing a possible solution for the visualization.
- I changed the alignment of the bar chart to horizontal. This was done to reduce the amount of eye-travel.
- I proceeded with ordering the appearance of the goalkeepers in a way that 6 keepers whose performance slipped in the 2018/19 appear first and the ones performing better than them in 2018/19 appear later.
- Also, there are two bars associated with each goalkeeper. The upeer bar represents their performance in the 2017/18 and the lower bar represents the 2018/19 number.
- I have color coded the 2018/19 performance in a way such that, for the goalkeepers whose performance dipped from the previous year have a red bar and otherwise they have green bar to highlight the difference in performance year-over-year.

<img src='https://github.com/mkgada/TellingStoriesWithData/blob/master/HW4_22.jpg'/>


After making preliminary sketches, I proceeded by showing them to two different kind of people(a football fan and non-football fan). The aim for this review was to obtain insights into the ease of readability of my visualization and obtain potential suggestions to make it better.

Review 1
Reviewer: Rahul Jindal 
Type of Person: Football Fan
- Can you tell me what you think this is?
This chart shows the comparative performances of top goalkeepers across Europe in 2017/18 and 2018/19 seasons
- Can you describe to me what this is telling you?
This chart is telling me that for certain goalkeepers, the performance dipped in 2018/19 and for some of them the performance improved.
- Is there anything you find surprising or confusing?
I am confused about why there are two colors used for representing performance in 2018/19 
- Who do you think is the intended audience for this?
According to me, this visualization is aimed at fellow football fans like me, football pundits and also possibly the team scouts
- Is there anything you would change or do differently?
It is very difficult to compare performance of two goalkeepers, since the bars for different years are placed beside each other. I would rather show performance of 2017/18 and 2018/19 separately

Review 2
Reviewer: Salil Deshpande
Type of Person: Non-Football Fan
- Can you tell me what you think this is?
I think this chart shows the performances of different goalkeepers across Europe
- Can you describe to me what this is telling you?
This chart is conveying that some keepers are better than others. The ones who are considered really good goalkeepers have had a dip in their performance in 2018/19
- Is there anything you find surprising or confusing?
I am confused when I want to compare two goalkeepers for their performances for a particular year because of the side-by-side bars
- Who do you think is the intended audience for this?
According to me, this visualization is for football fans, football experts.
- Is there anything you would change or do differently?
I would love to have a horizontal bar chart because it would reduce the amount of time to read the entire chart from left to right when it is vertical. 

Reflection
- I felt the user reviews were really helpful for me in deciding the final design of the solution
- I absolutely second the thought that it is difficult to compare the performance of the goalkeepers for a particular year. I would want to separate them.
- The horizontal chart idea seems really helpful because it will help me reduce the eye-travel for the reader
- I also felt that the main idea of the chart was to show the struggle of the top goalkeepers but it was not perceived by the users.
- I would proceed with incorporating these suggestions in my final design

Here is my final solution

<img src='https://github.com/mkgada/TellingStoriesWithData/blob/master/HW4_33.jpg'/>

Comments on the solution:
- I proceeded with two-sided bar chart for the solution. The left-hand side of the bar chart shows the performance for the 2017/18 seasons and the right hand side shows the performance of 2018/19 season.
- This way we can easily compare performances of each goalkeeper year-over-year and also against each other easily
- I have color-coded the bars for 2018/19 in such a way such that the ones whose performances dipped are red and the ones with improvement are in green.
- Further, to highlight the main idea of struggles of the top goalkeepers in 2017/18 in 2018/19, I have encircled the top goalkeepers in a box of red as well as the title of the visualization was changed to potray that.


# Thank you! 



