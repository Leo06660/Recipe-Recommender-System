# Meal Planning Problem
<em>This project is also published at [my portfolio website](https://yilichen-leoportfolio-f709a-7d1d9.stackbit.app/blog/Recipe-Recommendation-System/) </em>

<div id="header" align="left">
    <p>A recipe recommendation system that can help users to customize the meal by desired preference</p>
    <img src="https://github.com/Leo06660/Recipe-Recommender-System/blob/master/chart/Flowchart.png?raw=true" height="250" />
</div>

### Introduction
<ul>
    <li>A recipe recommendation application was built for users to customize their cooking schedule, nutrition requirements, budget control, and ingredients selection. </li>
    <li>The whole process was a combination of two techniques:
      <ul>
        <li> A recommender system (gather data, complete the matrix, and recommend the highest rated recipe for users)</li>
        <li> An optimization problem</li>
      </ul>
    </li>
</ul>

### Techniques
<ol>
    <li><strong>Web Scraping</strong><br>The dataset was scraped the website by using Selenium and BS4 from “Food.com”</li>
    <li><strong>Data Manipulation</strong><br>The scraped result was stored as a `dataframe`, using `dictionary` as the data structure for nutrition and personal ratings, and `array` as the data structure to store ingredients</li>
    <li><strong>Matrix Completion</strong><br>An open-source `soft_impute.py` online that implements matrix completion by solving a convex optimization program:</li>
</ol>

### Result
<div id="header" align="left">
    <ul>
        <li>Optimized meal planning for these two persons</li>
        <li>The number in the colored bar represents the index of the recipes</li>
        <li>The length of the bar is the estimated total time (cooking + preparing)</li>
        <li>Weekdays are segmented by red dotted line- 2.5 hours per day for cooking only</li>
        <li>The below <strong>Cooking Schedule Figure</strong> tells which person should cook what on which day</li>
        <li>The below <strong>Recommended Recipes for each day Figure</strong> shows the dishes they can have for each day</li>
    </ul>
    <img src="https://github.com/Leo06660/Recipe-Recommender-System/blob/master/chart/Single%20Solution%20Figure.png?raw=true" height="300" />
</div>

### Conclusion
<div id="header" align="left">
    <ul>
        <li>This project is a combination of three different skills: web scraping, recommender system, and optimization problem modeling.s</li>
        <li>Optimized user-based weekly meal planning system using Pyomo library with ~90% level of satisfaction</li>
</div>

### Future work
<div id="header" align="left">
    <p>Website Develop</p>
    <img src="https://github.com/Leo06660/Recipe-Recommender-System/blob/master/chart/future_work.png" />
</div>
