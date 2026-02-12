# Data Visualization

## Assignment 3: Final Project

### Requirements:
- We will finish this class by giving you the chance to use what you have learned in a practical context, by creating data visualizations from raw data. 
- Choose a dataset of interest from the [City of Toronto’s Open Data Portal](https://www.toronto.ca/city-government/data-research-maps/open-data/) or [Ontario’s Open Data Catalogue](https://data.ontario.ca/). 
- Using Python and one other data visualization software (Excel or free alternative, Tableau Public, any other tool you prefer), create two distinct visualizations from your dataset of choice.  
- For each visualization, describe and justify: 


    > What software did you use to create your data visualization?

    For my first visualization, I used Graphpad Prism. Graphpad is a tool that I use often during my graduate studies and I really like it because it has a lot of different options for choosing which visualization style you like. Also you can conduct different statistical analysis which is useful for my data to determine whether there is any significance or not. Graphpad not only allows you to pick the style of graphs, but you can customize the font sizes, colours, and legends. The graph that I chose for my first visualization is a bar chart. 

    For my second visualization, I used Matplot on Jupyter notebook, where I used coding lessons from the classroom to make the figure on my own from scratch. This one is more technically involved because you have to know what kind of visualization you want and how you want it to look. The graph that I chose for my visualization here is a line chart. 

    > Who is your intended audience? 

    My intended audience for both visualizations are Canadian bee keepers or beekeepers in other countries who are interested in determining how have production amounts of honey changed from 1980 to 2025 in Canada. If the beekeepers are not from Canada they can use this information to compare how honey production in their country compares. Another intended audience could be ecologists who are interested in knowing how the honey bee population is doing based on the output of honey. This can be used to approximate the health of bee colonies in Canada as severely lower productions could trigger a large investigation/ rescue operation. 

    > What information or message are you trying to convey with your visualization? 

     For both visualizations, I am trying to show the tonnes of honey that has been produced in Canada from 1980 to 2025. However, this data is being dislayed using two different styles, which can vary how the data is being interpreted. 
    
    > What aspects of design did you consider when making your visualization? How did you apply them? With what elements of your plots? 

        For both plots, I first considered the size of the plots so that they were not too small and could easily be seen. Next, I considered the colour of the plots and went with a black and yellow theme to represent a bee. To make sure they were visually accessible, I made sure that the size of the axes labels and numbers were large enough for people to see. I also included a figure caption to explain to people what they are looking at for accessibility. For my graphpad prism graph, I included a horizontal line to show the baseline honey production from 1980 and added a vertical line in 2008 where the honey production was the lowest. For my graphpad prism bar graph, I also adjusted the border size of each bar graph to make sure that it wasnt too thick so that the bars appeared black. For the matplot line graph I also adjusted the thickness of the line graph so that the line was easily visable. Also for my line graph, I added a grid line on the background so the readers can see exactly where each data point measures too. 

    > How did you ensure that your data visualizations are reproducible? If the tool you used to make your data visualization is not reproducible, how will this impact your data visualization? 

        Graphpad prism is simple to use, as long as the data inputed is the same then it should output a similar graph type. You can change the graphtype, colour, and axes legends easily but you would have to annotated the document to explain to people how you designed it. Additionally, people may be less likely to use Graphpad as it is a paid service, which you need a license for and students or other organizations might not be willing to do so. 

        For Matplot, I made sure to run my code several times to ensure that there were no syntax errors. As long as people have public access to my code, they will be easily able to reproduce it. I think that the more accessible and easier that people can follow the design aspect of a visualization, the more likely that they are able to use it. For matplot the person needs to have the appropriate python environment to replicate this visualization. 
    
    > How did you ensure that your data visualization is accessible?  

     For both graph types, I made sure that the colors were not associated with colour-blindness. I also chose colours that are visually striking so people can see easily.  I also included a figure caption. I made sure that font sizes of the axis and titles were large enough. For the bar chart, I included dashed lines to highlight the baseline (black) and a red dashed line to show the year honey production amounts were very low in comparsion to other years. For my matplot line graph, i made sure to include a grid to easily access what tonnes of honey were produced for that year. 
    
    > Who are the individuals and communities who might be impacted by your visualization?  

        This chart would mostly influence beekeepers and individuals who care a lot about bees. For example in 2010, we can see that the tonnes of honey produced was at an all time low of 2081. There could be a lot of reasons why it was low but there isnt enough informatino on this graph to provide context. This could lead to a lot of assumptions by the reader as to what happened during that year. Also for the bar chart, the dip in tonnes of honey produced does not seem as dramatic as the line graph which shows a sharp decrease. This could influence how people feel impacted by this information as when we look at bar charts, we tend to look from the bottom up, but when we look at line graphs we tend to follow the trace of the line which in this case starts from the top down to 2010. 

    
    > How did you choose which features of your chosen dataset to include or exclude from your visualization? 

        On my x and y axis I decided to not include all the years from 1980-2025 as well as all numerals of the tonnes for both graphs. This would overwhelm the reader and make it difficult to see the numbers. In this case, for my matplot figure, the x and y axis values are spaced out evenly whereby the x axis goes up in decades and the y-axis goes up 1000 tonnes at a time. This reduces the visual load for the reader. For my graphpad bar chart, the x axis foes up by 5 years at a time and the y-axis goes up a 1000 tones at a time, with additional ticks for the reader to find inbetween values. 

    
    > What ‘underwater labour’ contributed to your final data visualization product?

        What font sizes, font types, spacing, size to use that would be the easiest visually. The size of the overall graph. The type of line to pick (dotted, dashed) for the main graph, the colour and thickness of the line. The size of the bars, the thickness and colour of the bars. 


- This assignment is intentionally open-ended - you are free to create static or dynamic data visualizations, maps, or whatever form of data visualization you think best communicates your information to your audience of choice! 
- Total word count should not exceed **(as a maximum) 1000 words** 
 
### Why am I doing this assignment?:  
- This ongoing assignment ensures active participation in the course, and assesses the learning outcomes: 
* Create and customize data visualizations from start to finish in Python
* Apply general design principles to create accessible and equitable data visualizations
* Use data visualization to tell a story  
- This would be a great project to include in your GitHub Portfolio – put in the effort to make it something worthy of showing prospective employers!

### Rubric:

| Component         | Scoring  | Requirement                                                                 |
|-------------------|----------|-----------------------------------------------------------------------------|
| Data Visualizations | Complete/Incomplete | - Data visualizations are distinct from each other<br>- Data visualizations are clearly identified<br>- Different sources/rationales (text with two images of data, if visualizations are labeled)<br>- High-quality visuals (high resolution and clear data)<br>- Data visualizations follow best practices of accessibility |
| Written Explanations | Complete/Incomplete | - All questions from assignment description are answered for each visualization<br>- Explanations are supported by course content or scholarly sources, where needed |
| Code              | Complete/Incomplete | - All code is included as an appendix with your final submissions<br>- Code is clearly commented and reproducible |

## Submission Information

🚨 **Please review our [Assignment Submission Guide](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md)** 🚨 for detailed instructions on how to format, branch, and submit your work. Following these guidelines is crucial for your submissions to be evaluated correctly.

### Submission Parameters:
* Submission Due Date: `23:59 - 11/02/2025`
* The branch name for your repo should be: `assignment-3`
* What to submit for this assignment:
    * A folder/directory containing:
        * This file (assignment_3.md)
        * Two data visualizations 
        * Two markdown files for each both visualizations with their written descriptions.
        * Link to your dataset of choice.
        * Complete and commented code as an appendix (for your visualization made with Python, and for the other, if relevant) 
* What the pull request link should look like for this assignment: `https://github.com/<your_github_username>/visualization/pull/<pr_id>`
    * Open a private window in your browser. Copy and paste the link to your pull request into the address bar. Make sure you can see your pull request properly. This helps the technical facilitator and learning support staff review your submission easily.

Checklist:
- [ ] Create a branch called `assignment-3`.
- [ ] Ensure that the repository is public.
- [ ] Review [the PR description guidelines](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md#guidelines-for-pull-request-descriptions) and adhere to them.
- [ ] Verify that the link is accessible in a private browser window.

If you encounter any difficulties or have questions, please don't hesitate to reach out to our team via our Slack. Our Technical Facilitators and Learning Support staff are here to help you navigate any challenges.
