# Links

* Version 1: https://public.tableau.com/profile/christopher.buss#!/vizhome/tableau_v1/Story?publish=yes
* Version 2: https://public.tableau.com/profile/christopher.buss#!/vizhome/tableau_v2/Story?publish=yes

# Summary
I have chosen the Prosper Loan Data, a data set that includes information on more than 100,000 consumer loans in the US in the time period 2005-2014. The aim of the visualization is to give the viewer a good overview of the main time trends in the data and differences between US States concerning several key variables - interest rate, loan status, credit score and volume of loans. This information can be used by an entrepreneur to decide in which state he should start with his new loan-business.

# Design
I decided to focus on four key variables in the data set - interest rate, loan status, credit score and volume of loans. Overall, proceed from very general and aggregated statistics to more fine-grained and detailed graphs to lead the reader through the data exploration. Furthermore, I tried to highly some diverse aspects of the data set with a variety of visualization types - from line charts, maps, scatterplots and bubble charts to pie charts, to keep the analysis interesting and visually appealing.

In a first step, I illustrate the main time trends. The first graph shows the development of the interest rate on a monthly basis. The monthly scale is a good compromise between too broad quarterly data and to detailed weekly data that hides the main trends. In the second graph on this page I show the volume of all loans by their status. Here is becomes evident that the data is not a random sample from all loans but includes much more data points for more recent month. Concerning the status, I decided to summarize some of the categories for better readability.

In the second step, I proceed with a more detailed look at differences between states. The map is a nice way to visualize interest rates. To give the viewer more information without overwhelming him or her, I added some more context information on each state in the mouse-over. Additionally, the drop down allows the viewer to select individual years. All key information for each state are accessible in this way early on. The second graph on this page highlights top & bottom 10 States in respect to interest rates.

In the third step, I proceed from a univariate to a multivariate analysis. The scatterplot displays nicely the relationship between three key statistics - total credit score, interest rate and total loans. For the viewer it is easy to identify the strong correlation between the former two, but also outliers. The bubble chart in the second graph is a nice way to show quantities, in this case the amount of loans per state. I use color to introduce an additional variable - the dept/income rate per state. The slider on this page can be used to filter some states, based on a minimum amount of loans. The idea is, that some viewers might be interest in only those states with a high volume of transactions.

In the fourth step, the analysis becomes even more detailed with a specific look at individual states. To minimize information overload, I focus on five states that are most interesting for the analysis. The first graph mirrors graph 1 on page 1, showing interest rates over time. Only this time, focusing on individual states. Below, the viewer gets information on two other important features for a business decision - the distribution of the interest rate and the distribution of the employment status.

# Feedback
I had three rounds of feedback with my wife. First, we discussed my first broad idea and findings. Second, I made scetches of the visualizations I wanted to make. I recieved the feedback that they were to detailed and that I should focus on the main findings. Therefore, I reduced the information in some charts. Third, I made a first draft of the vizualisation and recieved the following feedback:

* Explain the story behind the analysis in more detail
* Adapt the headlines so that they better describe what is shown
* Adapt some axis-labels, e.g. add $-sign
* Use same terms on all pages, e.g. use always "interest rate" and not borrower rate
* The pie chart was too small
* The chart with the distribution on page 4 was not well explained and had no labels
* The drop-down menus are not really visible and need highligting. 

I changed the visualization accordingly. In particular, I added more text to highly the most important findings. I added labels and adjusted the size of the pie chart. To highlight the drop-down menues I added test in red that guids the viewer.

# Ressources
I mainly relied on the Tableau manual (https://www.tableau.com/support). Furhermore, I used the Tablea forum, for example:

* https://community.tableau.com/thread/193592
* https://community.tableau.com/thread/211805
* http://onlinehelp.tableau.com/current/pro/desktop/en-us/maps.html

