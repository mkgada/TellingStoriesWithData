<h1>New Delhi: Capital of India? Or Toxic gas chamber?</h1>
This project is aimed to address the aggravating air pollution issue in New Delhi, India. It is a data-driven walk through the potential causes of the problem, effects of bad air quality and finally a potential policy change as a call-to-action.

The project has been developed following an iterative process of making artifacts, collecting user feedback and making improvement till the delivery of the final project. 

<h2>Part 1: Project Proposal</h2>

<h3>Outline</h3>
<h4> Summary </h4>
For this project, I have chosen to address the issue of depreciating Air Quality in New Delhi, the capital of India. It is going to look at the history of air quality index in the city and the possible causes that has led to this issue. 

<h4>Approach</h4>

- Historic Significance of New Delhi
- Growth of population 
- Growth of vehicular traffic
- Top contributors to bad air quality
- Effects of bad air quality
- Proposed Policy change

<h4> Call to Action </h4>
Propose a potential change in policy to local government looking at the possible causes of the adverse air quality in New Delhi.

<h3>Data</h3>
For this project, the primary data source is public dataset "Historical Daily Ambient Air Quality Data" available on data.gov.in.
Data.gov.in is the open government data portal for India. It is used by the Government of India to make available datasets, documents, reports, surveys gathered by them to the general masses of India.

Historical Ambient Air Quality Data is collected on the a daily basis by the Ministry of Environment and Forests along with the Central Pollution Control Board. This daily data is available for the years 1987 onwards uptill 2015. Since the data is collected on a daily basis for a particular year, I have proceeded to calculate the average Air Quality for a particular year and use it for a time-series analysis.

I am also going to use population data of New Delhi from http://statisticstimes.com/demographics/population-of-delhi.php to obtain the growth in population of New Delhi over the time period in consideration

Apart from this, I am also going to use the data about the number of vehicles registered provided by the Ministry of Statistics and Programme Implementation. Note that this dataset is state-wise data and we would focus on state of Delhi for the project. The link to the website is as follows: http://mospi.nic.in/statistical-year-book-india/2018/189

Here are the links to the data
[Pollution Data](https://raw.githubusercontent.com/mkgada/TellingStoriesWithData/master/AirPollution.xlsx)

[Vehicles](https://raw.githubusercontent.com/mkgada/TellingStoriesWithData/master/NoVehicles.xlsx)

# Method and Medium
For this project, to drill down to the possible causes of the deteriorated air quality, I am going to proceed with adopting the sequential approach to reach to a root cause and derive possible recommendation that could help alleviate the situation.
The stepwise plan to address the issue is detailed below:

- Historic Significance of New Delhi
- Document the growth of population and the associated problems 
- Attribute the growth of vehicular traffic to population growth
- Top contributors to bad air quality due to vehicular emissions
- Effects of bad air quality 
- Proposed Policy change

<h3>Tools</h3>
I have three primary data sources, and I am going to visualize them using DataWrapper and Tableau. I plan on using Colorbrewer to choose custom made color-schemes to the visualizations.

Medium for final deliverable: Shorthand website

<h2> Part 2:User Research</h2>
Part 1 of the final project involved identifying the cause I wanted to address and a particular call to action to help alleviate that problem. It also involved sourcing the appropriate data to support my argument and use effective visualizations to convey the underlying message.

In Part 2, I have proceeded with actually creating a digital storyboard to bring the opportunity to real life and collected user feedback by medium of interviews with 3 anonymous users and further refining my storyboard in accordance with their feedback.

Here is my initial take on the sketches developed as a part of Part 1 of the Project

![wire1](https://raw.githubusercontent.com/mkgada/TellingStoriesWithData/master/Wireframes1.jpg)

The actual file consisting of the interview feedback is attached below.
[User Feedback](https://github.com/mkgada/TellingStoriesWithData/blob/master/User%20Feedback.xlsx?raw=true)

The interviews consisted of asking users specific questions related to the digital storyboard created like:

- What do you think is the intended audience for this story?
- Is there logical flow in the storyboard created? 
- What elements of the story stand out for you?
- What elements of the story are not helpful?
- Are the data visualizations helpful? Are they in congruence with the underlying message to convey?
And so on...


Key Takeaways from User Feedback:
- The storyline does not have smooth transitions from one section to another. There are abrupt breaks between sections
- The blue background of the textual content is misleading 
- The visualizations are apt and convey the message but they need to refined further

Changes in Iteration 2:
- Defined clear section breaks in the form of pages
- Eliminated the blue background and converted it to transparent background
- Fixed the flow of the storyboard and also the left-right formatting
- Used powerful imagery as background to set the tone of the corressponding section

![wire21](https://raw.githubusercontent.com/mkgada/TellingStoriesWithData/master/Wireframe_v2_1.png)



________________________________________________________________________________________________________________________________________





![wire22](https://raw.githubusercontent.com/mkgada/TellingStoriesWithData/master/Wireframe_v2_2.png)


<h2>Part 3-Final Data Story</h2>
Using the approach outlined above, I have managed to create a story about the air pollution in Delhi, posing possible causes that led to it backed by data evidence represented using effective visualizations.
The final story has been delivered using Shorthand website. 

<h4> Intended Audience </h4>
It is intended to appeal the policy makers to address the mentioned problem but at the same time it is an eye opener for the residents for Delhi to reconsider their transport choices and promote usage of public transport to reduce emissions.

<h4> Summary- Design Decisions </h4>
This project has been developed using a constant feedback loop from the intended consumers of the story. This approach led to make the deliverable more mature, understandable and appealing. The user feedback helped me with key design decisions for the final project as well as the visualizations. They are listed as follows:

- The background color of the shorthand website text parts was changed from blue to translucent. This change was done after receiving feeback that the blue color mislead the reader's thought.
- The data visualizations were changed in accordance with the feedback. The color schemes of the visualization as well the chart types were changed to make them more readable and understandable supporting the background story
- The data sources as well the image sources were cited adequately to back the truthfulness of data as well as avoid copyright issues
