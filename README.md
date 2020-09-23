#  **COVID-19 Outcomes in Washington State:**

Analyzed Covid-19 data from Washington State to understand the relationship between income, poverty, political affiliation, and age with three Covid-19 outcomes: cases, hospitalizations, deaths.

Extracted data from the CDC, Census, and usa.com to assemble a dataset of over 50,000 cases.

Linear regression, Chi-Square, outlier analysis, and visualizations conducted using Python, Pandas, Plotly, and Matplotlib.

The full presentation of the project can be found here: [Covid-19 Presentation](https://github.com/mocchicone/Covid-19-Outcomes-in-Washington-State/blob/master/COVID-19%20Presentation.pptx)

## **Summary:** 

Our team was interested in exploring some lesser studied predictor variables for Covid-19 outcomes.  We decided to focus our research to Washington State to limit the scope of the project.  

## **Hypotheses:**

H1A: Washington counties grouped by political affiliation will show a significant difference in Covid-19 outcomes (cases, hospitalizations, and deaths).

H2A: Mean household income will negatively correlate to Covid-19 outcomes (cases, hospitalizations, and deaths).

H3A: Poverty rate will positively correlate to Covid-19 outcomes (cases, hospitalizations, and deaths).

Additionally, age and Covid-19 outcomes were examined visually.    

## **Initial Visualizations**

After sourcing, cleaning, and merging the data, we reviewed the summary statistics and created several visuals to get a first look at the data.  Some examples are presented below:

**Washington State: Mean Income by County**  
Here we can see how mean household income is spread accross the state, with more urban areas having a higher mean income.  Created using Plotly.   
![Income Heatmap](https://github.com/mocchicone/Covid-19-Outcomes-in-Washington-State/blob/master/Data%20Visualization/Visuals/Household%20Income%20Median.png)    
   
   
**Washington State: Political Affiliation by County**  
A map displaying majority political affiliation by county, based on the most recent sate senate election.  Created using Plotyly.  
![Political Affiliation Map](https://github.com/mocchicone/Covid-19-Outcomes-in-Washington-State/blob/master/Data%20Visualization/Visuals/politics_map.png)    
    
**Washington State: Age Categories by Covid-19 Outcomes**
Bar graphs for each of the three Covid-19 outcome variables: cases, hosptalizations and deaths.  We can see here that while younger people make up a higher perecentage of cases, older people make up a higher pecentage of deaths.  
![Covid Outcomes by Age Bar](https://github.com/mocchicone/Covid-19-Outcomes-in-Washington-State/blob/master/Data%20Visualization/Visuals/Age%20Bar%20Graphs.PNG)    






## **Analysis and Results**

![Chi_Square Pie](https://github.com/mocchicone/Covid-19-Outcomes-in-Washington-State/blob/master/Data%20Visualization/Visuals/Chi-Square.PNG)
![Outlier1](https://github.com/mocchicone/Covid-19-Outcomes-in-Washington-State/blob/master/Data%20Visualization/Visuals/Outlier%20Analysis.PNG)
![Outlier2](https://github.com/mocchicone/Covid-19-Outcomes-in-Washington-State/blob/master/Data%20Visualization/Visuals/Outlier%20Analysis2.PNG)
![Income vs Outcomes](https://github.com/mocchicone/Covid-19-Outcomes-in-Washington-State/blob/master/Data%20Visualization/Visuals/Income%20vs%20Outcomes.PNG)
![Population Density vs Outcomes](https://github.com/mocchicone/Covid-19-Outcomes-in-Washington-State/blob/master/Data%20Visualization/Visuals/Population%20Density.PNG)

## **Conclusions and Insights**

Revisiting our hypotheses, we conclude that: 

*H1A: Washington counties grouped by political affiliation will show a significant difference in Covid-19 outcomes (cases, hospitalizations, and deaths).*
- A significant difference was found between counties that voted majority republican vs majority democrat, in that republican majority counties has a signficantly higher rate of COVID-19 cases.

*H2A: Mean household income will negatively correlate to Covid-19 outcomes (cases, hospitalizations, and deaths).*
-   For democrat leaning counties income was significantly and positively correllated to all three Covid-19 outcomes.  This was the opposite direction of the effect that we predicted.  We investigated one potential confounding predictor variable, population density, which did show as significant positive correlation with hospitalizations.  


H3A: Poverty rate will positively correlate to Covid-19 outcomes (cases, hospitalizations, and deaths).


    a) for democrat leaning counties income was significantly and positively correllated to all three outcomes.


    a) for democrat leaning counties poverty rate was significantly and negatively correllated to hospitalizations



a) a significant difference was found for cases (Republican leaning counties > Democratic leaning counties)
