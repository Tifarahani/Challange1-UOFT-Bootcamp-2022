# Challange 1_UofT-Bootcamp
# kickstarter-analysis

## 1. Overview of Project
As Louise’s play Fever came close to its fundraising goal we want to demonstrate the theatre funding goals in relation to their launch dates and also show her the outcome of "Play" subcategory based on different goal ranges and rate of success, failure and cancelation.
## 2. Analysis and Challenges
- These are the two charts we came across. 

![Theater_Outcomes_vs_Launch](https://github.com/Tifarahani/UofT-Bootcamp/blob/main/Resources/Theater_Outcomes_vs_Launch.png.png)

![Outcomes_vs_Goals](https://github.com/Tifarahani/UofT-Bootcamp/blob/main/Resources/Outcomes_vs_Goals.png)

---

- One of the challange I encountered was converting the date to the format I could filter the months and years. I found the convert unix Timestamp to readable format very useful.
- The Challange of calculating the percentage if the result is zero was wone of the challanges that I faced. I used "IFERROR" command to solve this proplem. Also extracting subcategory of "Play" seemed to be a challange at first but knowing there needs to be two time filtering was a good way to get the result needed.
- Challenges or difficulties that were encountered, and how they were overcome, are well explained. If there were no difficulties, describe any possible challenges or difficulties that could be encountered


## 3.Results
1. Two conclusions are made about the Theater Outcomes by Launch Date
   - Between the months of the year, May had the highest rate of succession for Theatre with total of 111 successful counts.
   - In December rate of succession and Failure were almost the same.
2. One conclusion is made about the Outcomes based on Goals
   - AS the goal amount increased rate of succession increase and failure decreased (There was a direct relation between increase of goal amount and succsess rate) and in "Play" subcategory rate of cancellation is zero.

3. limitations of the dataset, and recommandation  for additional tables or graphs
-Limitations:The relational data model doesn't fit in with every domain
-Recommendation: We could also use quartes,central tendency for plays and "Histogram"chart to check the outliers and validate out database.


