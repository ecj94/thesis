'APA' contains all information extracted by the R statcheck package (Epskamp and Nuijten 2015) from all articles of the 2014-2016 volumes of *ASR*, *AJS*, *SQ*, *JMF*, and *CHQ*, plus analytical and explanatory information added by the authors. Variables created by statcheck are indicated below by a boldfaced variable name. The variables in the data set are:

1. Article_numb: each article from which information was retrieved was given a number, such that analyses at the article level could easily be done.
2. Article: full name of the article.
3. Author(s): surname(s) of the author(s) of the articles.
4. Journal: full name of the journal the article was published in.
5. Year: year of publication of the article.
6. **Statistic**: information on which type of statistic has been extracted by statcheck. Statistics that were extracted were *t*-values, $\chi^2$-values, *F*-values, and *z*-values. 
7. **df1**: first degree of freedom
8. **df2**: second degree of freedom
9. **Test.Comparison**: contains only '=' signs, since the purpose of recalculating results is to see whether recalculated *p*-values are equal to their reported counterparts.
10. **Reported.Comparison**: reported comparison of the fully APA-reported result, which can be '=', '<', '>', or 'ns. 
11. **Reported**: p-value as reported in the article.
12. **Computed**: p-value as recalculated by statcheck.
13. **Raw**: the extracted APA-reported result.
14.	**Error**: indicates whether a reported result is erroneous or not.
15. **DecisionError**: indicates whether a reported result was erroneous in such a way that a wrong conclusion regarding significance was made, assuming *??* = .05.
16. **OneTail**: indicates whether one-tailed or two-tailed significance testing was performed.
17. **OneTailedInTxt**: indicates whether one of the following words were found in the article's text: "sided", "tailed", and/or "directional". If so, a reported result was considered directional, i.e., it was assumed that a one-sided significance test was performed for this result.
18. **APAfactor**: proportion of *p*-values that belongs to a fully APA reported result for each article.
19. Result.Hypothesis: indicates whether an extracted result is (part of) the test of an explicitly stated hypothesis. This variable is coded such that '1' = yes, '0' = no, and 'NA' = result belongs to a table, not to the text of an article.
20. Comments: contains other, relevant information on individual results. Here, it is indicated whether a result was a model fit statistic. These results were taken into account, but results belonging to tables were not. These were indicated as 'NA' in Result.Hypothesis for this reason.