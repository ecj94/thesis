# READme 'AllP'

'AllP' contains all *p*-values extracted by the R statcheck package (Epskamp and Nuijten 2015) from all articles of the 2014-2016 volumes of *ASR*, *AJS*, *SQ*, *JMF*, and *CHQ*, plus manually added information. Variables created by statcheck are indicated below by a boldfaced variable name. The variables in 'AllP' are: 
1. Article_numb: each article from which information was retrieved was given a number, such that analyses at the article level could easily be done.
2. Article: title of the article.
3. Author(s): surname(s) of the author(s) of the articles.
4. Journal: full name of the journal the article was published in.
5. Year: year of publication of the article.
6. **Statistic**: contains information on which type of statistic has been extracted by statcheck. In this case, statistics that were extracted were *t*-values, *χ*<sup>2</sup>-values, *F*-values, and *z*-values. 
7. **Reported.Comparison**: reported comparison of the fully APA-reported result, which can be '=', '<', '>', or 'ns'. Note that *p*-values reported with '&GreaterEqual;' or '&leq;' were therefore not part of this data set.
8. **Raw**: the extracted APA-reported result.
9. Result.Table: contains information on whether an extracted *p*-value was part of a table or not, where '1' = *p*-value was part of a table, and '0'= *p*-value was not part of a table.
10. Reported.Not.Relevant: a score of '1' = relevant and '0' = not relevant. In the following cases, extracted results which were reported as being p-values were not deemed relevant:
    - an extracted *p*-value was not related to a specific result, but was mentioned in the article to indicate which significance levels were used.
    - an extracted *p*-value was actually not a *p*-value.
    - an extracted *p*-value is a duplicate of another extracted *p*-value.
    - There was one case in which the *p*-value was reported as 'Ns' and 'Ns' did not mean non-significant, but meant 'numbers'.  
11.	Not.Reported: contains information on whether a result that was extracted could not be linked 1 to 1 to a result from the article, where '1' = no and '0' = yes. If an extracted result scored '0', it was excluded from analyses.
12. Model.fit: indicates whether a result is a reported *p*-value which belongs to a model fit statistic or not, where '1' = yes and 'NA' = no.
13. Result.Hypothesis: indicates whether an extracted result is (part of) the test of an explicitly stated hypothesis. This variable is coded such that '1' = yes, '0' = no, and 'NA' = result was reported, but not deemed relevant, or was not reported.
14. Marg.Sig: indicates whether a *p*-value in the range (.05 - .10] was considered marginally significant by authors, where '1' = yes, '0'= no, and 'NA' = *p*-value was not in the range (.05 - .10]. Following Ohlsson Collentine et al. (2019), we decided that a *p*-value was assigned marginal significance by the authors if the expressions margin* or approach* were mentioned in relation to its significance.
15. Phrase in which mentioned: contains phrase in which the result was mentioned. This can also be a note underneath a table, or 'NA' if a retrieved result could not be linked 1 to 1 to information in the article.
16. Explicitly stated hypothesis: contains the phrasing of the explicitly stated hypothesis, or is 'NA' when there was no explicitly stated hypothesis.
17. Comments: various notable information on specific  results or the article they were extracted from.

## References
Ohlsson Collentine, Anton, Marcel A. L. M. Van Assen M. and Chris H. J. 	
Hartgerink. 2019. “The prevalence of marginally significant  
&nbsp;&nbsp;&nbsp;&nbsp;results in psychology over time.” *Psychological science*, *30*(4): 576-586.

