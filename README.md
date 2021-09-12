# matplotlib-challenge
Honoring the sacrifice of mice in the pursuit of anti-cancer pharmaceuticals.

9/9/2021 5:48pm Initial Creation
Currently exploring the data sets, merging them and trying to git rid of duplicates.

9/11/2021 8:00pm First Commit
- Learned a lot with this work. Got a better sense of making the different types of graphs and how to label them.
- Took time to compare & contrast using matplot or pandas to create graphs. Trying to understand their structure.
- Got a better sense of using pandas to create filtered dataframes. Worked with groupby and aggregating as a shortcut.
- Had some struggle understanding the boxplot section, wasn't very clear what was being asked.
- Finally I was proud of an extra step taken to randomly select a mouse each time for the line plot, interested in allowing a user to input a specified drug their interested in.

Need to still do:
- Double check annotations and cleaniless of the code/presentation.
- Write 3 observations at the top.

9/11/2021 8:27pm Final Commit
- Made some minor changes formatting and moving things around.
- Added in my observations, put them here for ease:

Observations: 1) Based on the boxplot and individual line plot Capomulin appeared to be one of the more effective drugs. Within the bloxplot only Ramicane had slightly lower Tumor Volume levels and both experienced much more consistent results with similarly smaller IQR's compared to the other treatments. Randomly selecting mice, nearly every mouse that took Capomulin survived to have data collected at the 45 Timepoint and saw their Tumor Volume's (mm3) decrease dramatically.

2) The data seemed to imply that the tests were conducted well and had predictable results. There was only 1 potential outlier detected within the boxplots and looked at the standard deviations across the drugs they seemed reasonably small (no heavy skewing).

3) Finally looking at the scatterplots Mice Weight and thus size seemed to be a good predictor of Tumor Volume. A r-value of 0.84 reflects a decently strong, positive correlation between the variables. Furthermore a r^2 of 0.71 tells us that 71% of a mouse's overall tumor volume is explained by its own mass. Could tell us a lot about the management of cancer and the effect a subjects weight (or possibly being overweight) having an impact on treatments.
