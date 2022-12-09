# READme 'APA'

'APA_raw' contains all fully APA-reported results extracted by the R statcheck package (Epskamp and Nuijten 2016) from all articles of the 2014-2016 volumes of *ASR*, *AJS*, *SQ*, *JMF*, and *CHQ*. To improve readability, we created the Excel-file 'APA'. Here, information on article, author(s), and year was split into different columns, and some other relevant information was manually added. Variables created by statcheck are indicated below by boldfaced variable names. The variables in 'APA' are:

1. Article_numb: each article from which information was retrieved was given a number, such that analyses at the article level could easily be done.
2. Article: title of the article.
3. Author(s): surname(s) of the author(s) of the articles.
4. Journal: name of the journal the article was published in.
5. Year: year of publication of the article.
6. **Statistic**: contains information on which type of statistic has been extracted by statcheck. In this case, statistics that were extracted were *t*-values, *χ*<sup>2</sup>-values, *F*-values, and *z*-values. 
7. **df1**: first degree of freedom.
8. **df2**: second degree of freedom.
9. **Test.Comparison**: contains only '=' signs, since the purpose of recalculating results is to see whether recalculated *p*-values are equal to their reported counterparts.
11. **Reported.Comparison**: reported comparison of the fully APA-reported result, which can be '=', '<', '>', or 'ns'. 
12. **Reported**: *p*-value as reported in the article.
13. **Computed**: *p*-value as recalculated by statcheck.
14. **Raw**: the extracted APA-reported result.
15.	**Error**: indicates whether a reported result is erroneous or not.
16. **DecisionError**: indicates whether a reported result was erroneous in such a way that a wrong conclusion regarding significance was made, assuming *α* = .05.
17. **OneTail**: indicates whether one-tailed or two-tailed significance testing was performed.
18. **OneTailedInTxt**: indicates whether one of the following words were found in the article's text that was related to a reported result: "sided", "tailed", and/or "directional". If so, it was assumed that a one-sided significance test was performed for the result in question.
19. **APAfactor**: proportion of *p*-values that belongs to a fully APA reported result for each article.
20. Result.Hypothesis: indicates whether an extracted result is (part of) the test of an explicitly stated hypothesis. This variable is coded such that '1' = yes, '0' = no, and 'NA' = result belongs to a table, not to the text of an article. Results belonging to tables were not taken into account. 
21. Comments: contains other, relevant information on individual results. 

### References
Epskamp, S., & Nuijten, M. B. (2016). Statcheck: Extract statistics from articles and recompute p values. Retrieved from  
&nbsp;&nbsp;&nbsp;&nbsp;https://cran.r-project.org/src/contrib/Archive/statcheck/
