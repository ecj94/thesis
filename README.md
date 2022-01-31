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
- 'SRG': this data set contains information on statistical reporting guidelines for sociology journals mentioned in Clarivate Analytics' Web of Science (2016). More specifically, it contains information on (1) the guidelines to which journals request authors' adherence and (2)  guidelines authors are allowed to follow by journals. This data set was created to see how many sociology journals request that authors use the APA manual, and thus, the APA statistical reporting guidelines.
- 'APA': this data set contains all fully APA-reported results as retrieved from the 2014-2016 volumes of *ASR*, *AJS*, *SQ*, *CHQ*, and *JMF* by Epskamp & Nuijten's R package statcheck. 'APA' was used to study statistical reporting errors.
- 'AllP': this data set contains all reported *p*-values as retrieved from the 2014-2016 volumes of *ASR*, *AJS*, *SQ*, *CHQ*, and *JMF* by Epskamp & Nuijten's R package statcheck. 'AllP' was used to study publication bias, the 'bump' in *p*-values, and marginal significance.
- 'Hyp': this data set contains all manually retrieved *p*-values and reproducible results related to explicitly stated hypotheses. These data were retrieved from the 2014-2016 volumes of *ASR*, *AJS*, and *SQ* and were used to study statistical reporting errors, publication bias, the 'bump' in *p*-values, and marginal significance.
- Article inclusion: data set containing information on which articles from the 2014-2016 volumes of *ASR*, *AJS*, *SQ*, *CHQ* were included in 'Hyp'.


**References**
Clarivate Analytics’ Web of Science. (2016). Journal citation reports: Sociology, 2016.
  com.proxy.library.uu.nl/JCRJournalHomeAction.
Epskamp, S., & Nuijten, M. B. (2016). Statcheck: Extract statistics from articles and recompute p values. Retrieved from   
  https://cran.r-project.org/src/contrib/Archive/statcheck/
