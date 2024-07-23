# About Me
### Contact Information
Reese Hamilton (BA Economics, BS Data Science)<br>
Salem, OR <br>
Cell: (360) 306-9799<br>
Email: <a href="mailto:rahamilton.bus@gmail.com">rahamilton.bus@gmail.com</a><br>
LinkedIn: <a href="https://www.linkedin.com/in/rahamilton19" target="_blank">www.linkedin.com/in/rahamilton19</a>

### Bio
I am a Master of Data Science candidate at Willamette University School for Computing and Information Sciences. I have a passion for higher education and aspire to utilize the power of data science to improve various aspects of organizational practices within higher ed.

### [Resume](pdf/Reese_Resume_Mock_Interviews.pdf)
<img src="images/resume.png?raw=true"/>

# Projects

---

## [2021 Masters Dashboard](https://aweirth.shinyapps.io/masters_dashboard/) Fall 2023
Click on the project title to explore the dashboard for yourself!<br><br>
For this project I worked with my classmate Alex Weirth to create a platform for deeper analysis of performance stats within professional golf than currently exists.<br><br>
We consolidated all of the scores and availible statisics from the 2021 Masters and created a Shiny App (R) so that users could explore the statistics from the tournament themselves.<br>
<br>
The users click on a players name on the leaderboard to bring up a couple visualizations that explore "strokes gained" statistics. The are considered some of the best statistics for evaluating performance in golf.<br><br>
<img src="images/Masters_dashboard_lb_sc.png?raw=true"/>
<img src="images/Masters_Dashboard_stats.png?raw=true"/>

These visualizations allow users to examine how player performed in different aspects of the tournament that likely led to their successes or failures in a way that looks clean and is easy to interpret.


---

## [Salem, Or - Real Estate Dashboard](https://app.powerbi.com/links/JArbpZ0gY0?ctid=46bc6c40-368d-4a20-9b1b-c1842f786542&pbi_source=linkShare&bookmarkGuid=19b0d8c7-5929-48f0-b682-fa31649761e5) Spring 2024
Click on the project title to access the full PowerBi file. <br><br>
For my Data Engineering class, my group and I scraped real estate data for the city of Salem, OR from a Zillow api for a little over one month. <br> <br>
We then used the data we scraped to create a few dashboards in PowerBi. We wanted to present a way for people to assess the housing market (homes for sale or rent). <br> <br>
We created a page for houses for sale, houses for rent, and approximate mortgages that calculated monthly mortgage payments that they could compare with rent prices. <br><br>
The filters on each page allow users to customize their search based on their preferences in real estate.

<img src="images/Salem_dash_pages.png?raw=true"/>
<img src="images/Salem_real_estate_dash.png?raw=true"/>

The ultimate goal was to create a way for users to assess the housing market and make a decision if they should buy or rent based on the relative costs. <br><br>
This was by no means a perfect way to guide users decisions but rather a way to get a general grasp on the market that could provide a preliminary idea on what they should do.

---

## [NFL Playcall Predictive Model](http://example.com/) Spring 2024
For this project we found an NFL python package that contained all of the statistics from the last 20 years.<br><br>
We used a random forest algorithm to predict playcalls based on features such as: down, yards to first down, yards to touchdown, score, quarter, etc. <br><br>
Our model aimed to predict pass, run, punt, kick, kneel, or spike based on the features mentioned above.<br><br>
Below are some measures of performance for our model. We generated a confusion matrix to see where our model correctly and incorrectly predicted outcomes as well as percentages of correct predictions by prediction type.<br><br>
We tried multiple types of models as well as different parameter tunings before ultimately landing on this random forest as our best.

<img src="images/NFL_playcall_randomforest.png?raw=true"/>

We were happy with about 70% accuracy because on first and second down especially, it is incredibly random what plays will be called.

---

