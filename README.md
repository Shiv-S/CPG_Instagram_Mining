# CPG_Instagram_Mining
Various data mining techniques and machine learning algorithms (in R) used to discover patterns in instagram posts of CPG companies. This is done with a goal to determine combination of factors which can increase engagement. Engagement is calculated using the below mentioned formula: 
𝑬𝒏𝒈𝒂𝒈𝒆𝒎𝒆𝒏𝒕 = ((Post Likes + Post Comments)/Total Number of Followers)*100.

The following features of a post were used to determine their affect on engagement:

Time of the post,
Day of the post,
Daypart of the post (Morning, Afternoon, Evening and Night),
Whether post has a person,
Number of Likes,
Number of comments,
Words in Caption,
Number of Hashtags

The datamining techniques used were the following:

Multi-Variable linear regression,
Recursive Feature Elimination (Backward Elimination),
Decision Tree,
Random Forests,
Association Rule mining

The input of the algorithms can be modified according to the dataset on which analysis is be conducted. It's of utmost important to install and load all the packages which are mentioned in the "datamining.txt". If the packages are not installed or loaded properly, the algorithms would not work and the results would not be accurate, irrespective of the scenario where R doesn't show any errors.

For more information or concerns, please contact via email - shivam01university@gmail.com 
