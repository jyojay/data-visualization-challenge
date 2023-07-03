## data-visualization-challenge
This repository consists of:
- File pymaceuticals_code.ipynb consisting of the code I wrote as a solution and analysis to this challenge using Jupyter notebook.
- Data folder with provided csv files.

# Note:
Jupyter notebook was used for coding

# Assumptions: 
- This program will be using data sorted on timepoints similar to what is currently provided with this challenge
- For generating pie plots showing the distribution of female versus male mice we are considering each iteration of the mice and not just unique number of mice used in the experiments
- The weight of each mice remains constant during the timeperiod of these experiments
- The initial tumor volumes is same across all mice used for these experiments similar to the data that is provided with this challenge
- Note I have tried to create an identical bar graph from both methods working on bar widths and colour alpha gradings. I have also tried to get the shades of the pie charts as close as possible using colour and alpha in wedgeprops

# Acknowledgements:
The below links were referenced:
- https://stackoverflow.com/questions/12589481/multiple-aggregations-of-the-same-column-using-pandas-groupby-agg
- https://matplotlib.org/stable/api/_as_gen/matplotlib.pyplot.bar.html
- https://matplotlib.org/stable/gallery/color/named_colors.html
- https://stackoverflow.com/questions/50536250/matplotlib-pie-chart-wedge-transparency
- https://matplotlib.org/stable/gallery/statistics/boxplot_demo.html
- https://stackoverflow.com/questions/43342564/flier-colors-in-boxplot-with-matplotlib
- https://www.tutorialspoint.com/python-display-only-non-duplicate-values-from-a-dataframe#:~:text=To%20display%20only%20non-duplicated%20values%2C%20use%20the%20duplicated,be%20fetched%20%E2%88%92%20dataFrame%20%5B~%20dataFrame.%20duplicated%20%28%27Student%27%29%5D
