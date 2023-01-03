# R Code

The .Rmd file in this folder contains the code used to obtain the results in our study for 'APA', 'AllP', and 'Hyp'. The layout of the file looks somewhat like this:

1. Preliminary procedures:
    - loading packages, among which statcheck (Epskamp & Nuijten, 2016)
    - checking for dependencies
    - extracting results from articles using statcheck
2. Data set 'APA', which contains information retrieved using statcheck on:
    - statistical reporting errors: descriptive results, testing H1 and H2
3.  Data set 'AllP', which contains information retrieved using statcheck on:
    - publication bias: descriptive results, testing H3a and H3b
    -  marginal significance: descriptive results, testing H4
4. Data set 'Hyp', which contains manually retrieved information on *p*-values and reproducible results related to explicitly stated hypotheses:
    - selection process articles 'Hyp', including code used to create flowchart 
    - statistical reporting errors: descriptive results 
    - publication bias: descriptive results 
    - bump in *p*-values: descriptive results 
    - marginal significance: descriptive results, independent *z*-test two proportions


Note that the script can be run in order of presentation. Software used was Rstudio Version 1.3.959.

### **References**
Epskamp, S., & Nuijten, M. B. (2016). Statcheck: Extract statistics from articles and recompute p values. Retrieved    
&nbsp;&nbsp;&nbsp;&nbsp;from https://cran.r-project.org/src/contrib/Archive/statcheck/
