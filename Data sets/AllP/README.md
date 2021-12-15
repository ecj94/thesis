# READme '*AllP*'

*AllP* contains all *p*-values extracted by the R statcheck package (Epskamp and Nuijten 2015) from all articles of the 2014-2016 volumes of *ASR*, *AJS*, *SQ*, *JMF*, and *CHQ*, plus manually added information. Variables created by statcheck are indicated below by a boldfaced variable name. The variables in '*AllP*' are: 
1. Article_numb: each article from which information was retrieved was given a number, such that analyses at the article level could easily be done.
2. Article: full name of the article.
3. Author(s): surname(s) of the author(s) of the articles.
4. Journal: full name of the journal the article was published in.
5. Year: year of publication of the article.
6. **Statistic**: contains information on which type of statistic has been extracted by statcheck. In this case, statistics that were extracted were *t*-values, *χ*<sup>2</sup>-values, *F*-values, and *z*-values. 
7. **Reported.Comparison**: reported comparison of the fully APA-reported result, which can be '=', '<', '>', or 'ns'. 
8. **Raw**: the extracted APA-reported result.
9. Result.Table: contains information on whether an extracted *p*-value was part of a table or not, where '1' = *p*-value was part of a table, and '0'= *p*-value was not part of a table.
10. Reported.Not.Relevant: in the following cases, extracted results which were reported as being p-values were not deemed relevant:
    - an extracted *p*-value was not related to a specific result, but was mentioned in the article to indicate which significance levels were used or to refer to multiple results.
    - an extracted *p*-value was actually not a *p*-value.
    - an extracted *p*-value is a duplicate of another extracted *p*-value.
    - There was one case in which the *p*-value was reported as 'Ns' and 'Ns' did not mean non-significant, but meant 'numbers'.
11.	Not.Reported: contains information on whether a result that was extracted could be found in linked 1 to 1 to information in the article the article, where '1' = no and '0' = yes. If an extracted result scored '0', it was excluded from analyses.
12. 20. Result.Hypothesis: indicates whether an extracted result is (part of) the test of an explicitly stated hypothesis. This variable is coded such that '1' = yes, '0' = no, and 'NA' = result was either reported, but not deemed relevant, or was not reported.

