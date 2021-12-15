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
    - an extracted *p*-value was not related to a specific result, but was mentioned in the article to indicate which significance levels were used.



