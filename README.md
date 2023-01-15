# Weather Analysis Website

Data becomes more powerful when you share it with others! That’s because people can use your data only if they can access it. So, I will use HTML and CSS to create a dashboard featuring the Latitude vs. X analysis of weather.

As I build this dashboard, I will create a page for each plot and a way to navigate among these pages. These pages will contain the visualizations and the descriptions. I will also create two more pages. One will be a landing page that provides a comparison of all the plots. The other will be a page that presents the data used to build the plots.

![image](https://user-images.githubusercontent.com/100399092/201246166-22f65c3d-bebf-4499-a5fd-685dc02e74f6.png)

## My website will consist of seven pages as follows:
1. A Landing page that contains:
    - An explanation of the project
    - A link to each visualization page
2. Four (4) Visualization Pages, each with the following elements:
    - A descriptive title and a heading tag
    - The visualization for the selected comparison
    - A paragraph describing the visualization and its significance
3. A Comparisons Page that does the following:
    - Contains all the visualizations on the same page so that people can easily compare them
    - Use a Bootstrap grid for the visualizations
4. A Data Page that displays a responsive table containing the data that the visualization use, as follows:
    - The table that will be a Bootsrap table component
    - The data will come from either exporting or converting the CSV file to HTML
    
At the top of every page, my website will have a navigation bar that does the following:
  - Contains the name of the site , allowing users to return to the landing page from any page
  - Contains a drop-down menu, named Plots, that contains a link to each visualization page
  - Provides two more text links on the right side: Comparison, which links to the comparisons page, and Data, which links to the data page
  - Is responsive (via media queries)
    
## Tools used
Python-Pandas, HTML, CSS, Bootstrap, Jupyter Notebook
