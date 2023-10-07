# 911-project
Analyzing implications of rurality in cardiac arrests

## Story
What is the impact of rurality on the outcome of cardiac arrests? Is there a decreased chance of survival compared to urban areas? 

We assume that the close proximity to hospitals in urban areas has a more favorable outcome on the chance of survival. 

We will seek to answer this question and eliminate any bias by using appropriate algorithms to fill in missing data. We can visualize the relationship between urban-rural settings and the chance of survival with the collected data, and another version of the data set that is corrected by filling in missing values.

## Approach

Phase 1: gain access to data, understand data structure and relationships, tidy the data if necessary, identify the extent of missing data

Phase 2: exlore the relationships between the independent variables, urban and rural settings, on the chances of survival. Examples - plots of the distribution of chances of survival, scatter plots for linear regression, map that has a color graded visualization corresponding to cardiac arrest survival rate

Phase 3: Apply algorithms such as MICE and missforest to fill in the missings values

Phase 4: visualize the relationships again between urban and rural settings on the chance of surival. Is there a significant compared to the original data set?