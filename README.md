# Thesis statistical reporting practices in sociology

### Topics
Multiple aspects of statistical reporting practices in sociology were studied in this thesis:

- statistical reporting guidelines
- statistical reporting errors
- publication bias/*p*-hacking
- bump in *p*-values
- marginal significance


### Data sets
For different topics, different data sets were used. Here is a list of the different data sets and what kind of information they contain:

- 'SRG': contains information on statistical reporting guidelines for sociology journals mentioned in Clarivate Analytics' Web of Science (2016). More specifically, it contains information on (1) the guidelines to which journals request authors' adherence and (2)  guidelines authors are allowed to follow by journals. This data set was created to see how many sociology journals request that authors use the APA manual, and thus, the APA statistical reporting guidelines.
- 'APA': contains all fully APA-reported results as retrieved from the 2014-2016 volumes of *ASR*, *AJS*, *SQ*, *CHQ*, and *JMF* by Epskamp & Nuijten's R package statcheck. 'APA' was used to study statistical reporting errors.
- 'AllP': contains all reported *p*-values as retrieved from the 2014-2016 volumes of *ASR*, *AJS*, *SQ*, *CHQ*, and *JMF* by Epskamp & Nuijten's R package statcheck. 'AllP' was used to study publication bias, the 'bump' in *p*-values, and marginal significance.
- 'Hyp': contains all manually retrieved *p*-values and reproducible results related to explicitly stated hypotheses. These data were retrieved from the 2014-2016 volumes of *ASR*, *AJS*, and *SQ* and were used to study statistical reporting errors, publication bias, the 'bump' in *p*-values, and marginal significance.
- inclusion_Hyp: contains information on which articles from the 2014-2016 volumes of *ASR*, *AJS*, and *SQ* were included in 'Hyp'.

Note: the articles used for this study are not part of this archive, since these articles are not publicly available. Therefore, if one wishes to fully reproduce our study, one will have to download the 2014-2016 volumes of the sociology journals included in our study. 


### Ethics, permisson & access
This study is a systematic review in which journals, articles, and results from articles were units of analyses. Thus, no human participants were involved in the study. Data will be made available to all possible parties through the following Github repository: https://github.com/elisecj94/thesis/tree/development. The storage of data at Utrecht University will be in accordance with the faculty protocol of the Faculty of Social & Behavioral Sciences. The author is responsible for the publicly available research archive. 


### References
Clarivate Analytics’ Web of Science. (2016). Journal citation reports: Sociology, 2016. com.proxy.library.uu.nl/JCRJournalHomeAction.\
Epskamp, S., & Nuijten, M. B. (2016). Statcheck: Extract statistics from articles and recompute p values. Retrieved from   
&nbsp;&nbsp;&nbsp;&nbsp;https://cran.r-project.org/src/contrib/Archive/statcheck/
