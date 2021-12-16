# READme '*Hyp*'

'*Hyp*' contains all *p*-values and reproducible results related to explicitly stated hypotheses from all articles of the 2014-2016 volumes of *ASR*, *AJS*, and *SQ*. The variables in '*Hyp*' are:

1. Article_numb: each article from which information was retrieved was given a number, such that analyses at the article level could easily be done.
2. Article: full name of the article.
3. Author(s): surname(s) of the author(s) of the articles.
4. Journal: full name of the journal the article was published in.
5. Year: year of publication of the article.
6. Issue: issue in which the article was published.
7. Number of hypotheses: number of explicitly stated hypotheses mentioned in the article before results are presented.
8. Belongs to hypothesis: number of the hypothesis the result belongs to.
9. **Statistic**: contains information on which type of test statistic has been extracted. In this case, statistics that were extracted were:
    - *t*
    - *χ*<sup>2</sup>
    - *F*
    - *z*
    - *r*
    - HZ (hazard)
    - IRR (incidence rate ratio)
    - PP
    - Wald
If only *b*, *SE*, and/or *p*-values were extracted, this variable has the value 'NA'. Odds ratios (OR) are mentioned here, since recalculations of *p*-values based on odds ratios different from those based on regression coefficients.
10. b: regression coefficient or odds ratio.
11. SE: standard error.
12. t_stat: value of the test statistic. note that these are filled in only for  *t*-values, *χ*<sup>2</sup>-values, *F*-values, *r*-values and *z*-values.
13. n: the sample size as retrieved from the model the result is from. In case of multilevel models, the sample size of the lowest level was filled in here.
14. IVs: numbers of independent variables as retrieved or manually counted from the model the result is from.
15. df_1: first degrees of freedom.
16. df_2: second degrees of freedom.
17. Reported.Comparison: reported comparison of the *p*-value or reproducible result, which can be '=', '<', '>', or 'ns'. 
18. Reported.P.Value: *p*-value as reported in the article.
19. lb_b:
20. ub_b:
21. lb_se:
22. ub_se:
23. lb_stat:
24. ub_stat:
25. dec_pval_rep: number of decimals of the reported *p*-value.
26. Computed: *p*-value as recalculated manually.
27. P_one_sided_chi:
28.	Error: indicates whether a reported result is erroneous or not.
29. DecisionError: indicates whether a reported result was erroneous in such a way that a wrong conclusion regarding significance was made, assuming *α* = .05.
30. OneTailed: indicates whether one-sided testing was done for *p*-values and reproducible results, where 'TRUE' = yes, 'FALSE' = no, and 'UNKNOWN' was assigned if it was unknown whether one-sided or two-sided testing was done.  
31: Marg.Sig: indicates whether a *p*-value in the range (.05 - .10] was considered marginally significant by authors , where '1' = yes, '0'= no, and 'NA' = result was not a *p*-value in the range (.05 - .10]. We decided that a *p*-value was assigned marginal significance by the authors if:
    - the expressions margin* or approach* were mentioned in relation to its significance, following Ohlsson Collentine et al. (2019).
    - for *p*-values in tables, we considered significance levels of *p* < .10 in captions of tables to be assignment of marginal significance. 
32. Hypothesis: phrasing of the explicitly stated hypothesis from the article.
33. Information from text article used: information from the text of the article used to determine that a result was related to an explicitly stated hypothesis.
34. Comment:
