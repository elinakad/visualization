# Data Visualization

## Assignment 2: Good and Bad Data Visualization

### Requirements:

- Data visualizations are important tools for communication and convincing; we need to be able to evaluate the ways that data are presented in visual form to be critical consumers of information 
- To test your evaluation skills, locate two public data visualizations online, one good and one bad  
    - You can find data visualizations at https://public.tableau.com/app/discover or https://datavizproject.com/, or anywhere else you like! 
- For each visualization (good and bad):  
    - Explain (with reference to material covered up to date, along with readings and other scholarly sources, as needed) why you classified that visualization the way you did.
      ```
      Good: The first image I chose is the NFL fans "Which Fans Drink the Most on Game Days." Here the author of the graph is comparing the average blood alcohol content (BAC) of NFL fans for during game days of their favourite football team in the US during the NFL season. What we can easily see from this graph is that Buffalo Bills fans with the highest BAC (~0.075), followed by fans of the Detriot Lions and the Philadelphia Eagles (~0.70). In contrast, the lowest BAC levels are from fans of Cincinnati Bengals (~0.01), followed by the New Orleans Saints and the Tennessee Giants (~0.02). Below the bar graph is a depiction of the USA map where each of the NFL teams are from, and the corresponding dots represent the average BAC of fans for that team. Larger dots represent higher BAC levels while smaller dots represent lower BAC levels. Overall, this graph is easy to understand and is my chosen "good" graph. The image is a 2D layout and has a clean "blank page" design to avoid conveying emotional narritive to the audience by perhaps having the logo of a specific team, that might convey a negative emotional response to the audience of an opposing team. It is clear that the intended audience are NFL fans, with the purpose of highlight BAC levels. This graph is represented by categorical circles which are sequentially aligned from lowest to highest BAC levels and is easily interpreted. However, it may not be factualy neutral as fans from the different NFL teams may feel offended by this data as they might be portrayed as alcoholics. Using the gestalt principles, we can see that the graph uses proximity to group together NFL fans from different teams with similar BAC levels, this reduces the cognitive load that the interpreter needs to compare BAC levels across different teams. Additionally, readers can go and compare raw BAC levels as the author has provided the link to the dataset. https://public.tableau.com/app/profile/bactrack/viz/NFLFansBAC/NFLFans
      
      
      Bad: The second graph that I chose shows the points received for each Formula 1 team during the 2018 season across the different countries. Each team has two members that are shown on the left of the graph with their name and photo. Each team started the season by racing in Australia and the last race of the season ended in the United Arab Emirates. The coloured lines represent the number of points received by the Team during the race in that particular country. The teams which received a higher number of points appear higher on the radial line graph compared to teams which received a lower number of points. On the top left corner of the radial line graph there is a summary graph of the total points received by each time during the whole season. Additionally, we can see the breakdown for the number of points, wins, and podiums each team member received. Overall, I consider this a bad visualizaiton because the aesthetic is overwhelming and has a high cognitive load. The radial line graph is cyclical and continous and the teams that have a lower number of points are difficult to discern. The graph represents an approximation visually, but when you hover over the different lines it shows you the number of points received during the race in that country. The cognitive load is high because your eyes have to track each line as it fluctates in position. https://public.tableau.com/app/profile/alexandervar/viz/Formula12018WorldChampionship_Results/Formula12018


      ```
    - How could this data visualization have been improved?  
      ```
      Good: To improve this visualization, I think that we could use different colours to represent the dot for each team. Also I think that a singular dot to represent average BAC could be modified to show individual data points where the readers can see the upper band and lower band threshold as either a box or violin plot. I think this would be a more honest representation of average BAC as this value can be skewed. Additionally, there is a discrepency between the total number of teams shown in the map and the number of teams where there BAC is represented. To be more neutral, I think the author should show the BAC levels of all teams. Also, I think the graph is too simplistic because there are a lot of variables that can effect BAC levels for example, height, weight, diet, age, previous drinking behaviours and so it might be interesting to correlate BAC levels for some of these mentioned variables. 

      
      Bad: For the Formula 1 graph, the visualization can be improved by changing the graph type to make it more simplistic to look at. Instead of a radial line graph, we can use a stacked bar chart. In this case, we would have countries on the x-axis and points on the y-axis. Each stack in the bar graph would represent the 10 different teams based on their color. The height of each stack would represent the numner of points received during that race and each bar could have the number of points depicted inside. This takes away from the cognitive load of having to visually follow each line in a circular motion. Also because larger bars are easier to see, we can put those on the bottom and the smaller bars near the top. Also i think the individual point breakdown located next to the image of the team member is difficult to see and they are too close together. Therefore, I think that should be removed all-together in this graph. However, if the person really wanted to display this information it should be on a seperate graph. I would personally use a bubble based heat map, where on one axis you have the team member and then on the other axis you have points, wins, and podiums. Each bubble would be coloured in based on its intensity (higher or lower), and this value can be placed in the centre of the bubble, along iwth a heat map legend. 
      

      
      ```
- Word count should not exceed (as a maximum) 500 words for each visualization (i.e. 
300 words for your good example and 500 for your bad example)

### Why am I doing this assignment?:

- This assignment ensures active participation in the course, and assesses the learning outcomes
* Apply general design principles to create accessible and equitable data visualizations
* Use data visualization to tell a story

### Rubric:

| Component               | Scoring   | Requirement                                                 |
|-------------------------|-----------|-------------------------------------------------------------|
| Data viz classification and justification | Complete/Incomplete | - Data viz are clearly classified as good or bad<br />- At least three reasons for each classification are provided<br />- Reasoning is supported by course content or scholarly sources |
| Suggested improvements  | Complete/Incomplete | - At least two suggestions for improvement<br />- Suggestions are supported by course content or scholarly sources |

## Submission Information

🚨 **Please review our [Assignment Submission Guide](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md)** 🚨 for detailed instructions on how to format, branch, and submit your work. Following these guidelines is crucial for your submissions to be evaluated correctly.

### Submission Parameters:
* Submission Due Date: `23:59 - 10/26/2025`
* The branch name for your repo should be: `assignment-2`
* What to submit for this assignment:
    * This markdown file (assignment_2.md) should be populated and should be the only change in your pull request.
* What the pull request link should look like for this assignment: `https://github.com/<your_github_username>/visualization/pull/<pr_id>`
    * Open a private window in your browser. Copy and paste the link to your pull request into the address bar. Make sure you can see your pull request properly. This helps the technical facilitator and learning support staff review your submission easily.

Checklist:
- [ ] Create a branch called `assignment-2`.
- [ ] Ensure that the repository is public.
- [ ] Review [the PR description guidelines](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md#guidelines-for-pull-request-descriptions) and adhere to them.
- [ ] Verify that the link is accessible in a private browser window.

If you encounter any difficulties or have questions, please don't hesitate to reach out to our team via our Slack. Our Technical Facilitators and Learning Support staff are here to help you navigate any challenges.
