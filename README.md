# Swire-Capstone

### Business Problem and Objective

Swire Coca-Cola is seeing a meaningful rate of cart abandonment within the MyCoke360 platform. Abandoned purchase windows reduce order volume and signal friction in the digital workflow. The goal of the broader project was to measure behavioral patterns within Google Analytics data and determine which actions predict whether a customer completes or abandons an order window.

### My Contribution

I focused on analytical methods that quantified user behavior at scale. My work included association rule mining, logistic regression, with initial attempts at hierarchical clustering and Gaussian mixture modeling. These methods were used to detect recurring event sequences, structural patterns in user interactions, and behavior groups that correlate with abandonment outcomes. I also contributed to EDA, feature engineering and regression modeling. This involved constructing event-level predictors, cleaning timestamp structures, and assessing the strength of behavioral signals.

### Group Solution

Our team integrated Google Analytics events with customer, order, sales, and product data to reconstruct purchase windows. This unified dataset allowed us to compare behavior across abandoned and completed windows. We identified patterns such as repeated searching, high cart modifications, and prolonged browsing loops that correlate strongly with abandonment. Clustering and rule mining helped isolate friction behaviors that appear frequently across customers.
The combined analysis provided a clear picture of how users navigate the platform and where the ordering process breaks down.

### Business Value

The analysis produces measurable insight into the behavioral drivers of abandonment. Swire Coca-Cola can use these findings to improve search relevance, refine product discovery, and streamline cart interactions. Small improvements in these areas can recover significant revenue, given the scale of MyCoke360 activity. The unified dataset and modeling framework also support ongoing monitoring and controlled experimentation on the platform.

### Project Difficulties

The project required substantial data preparation. GA events had missing fields, inconsistent item mappings, and timestamp adjustments that depended on customer time zones. Some purchase windows lacked anchor dates or cutoff times, which reduced usable rows and required careful filtering. Aligning GA cart events with the orders table also introduced complexity because items and timestamps did not always match. Working through these issues strengthened the reliability of the final dataset and improved the interpretability of the models.

### What I Learned

I gained experience building structured pipelines from unstructured behavioral data. This involved joining large fact tables, engineering temporal and event-based features, and validating models against real operational constraints. I also strengthened my ability to communicate technical insights in a business context. The project highlighted how behavioral analytics can inform platform design and operational decision making.

### Files in this repository
The `Ind Modeling.RMD` is a compilation of my contributed work to the group modeling. This does not include all insights and analyses gleaned from our group's modeling, just my individual coding contributions. 
`Individual EDA` is all of the notes and coding I contributed to our group exploratory data analysis. There are some headers in there left blank for the purpose of denoting EDA was performed, but it was not by me.
