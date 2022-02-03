# R Code

The .Rmd file in this map contains the code used to obtain the results in our study for 'APA', 'AllP', and 'Hyp'. The layout of the file looks somewhat like this:
1. Preliminary procedures:
   - loading packages, among which statcheck (Epskamp & Nuijten, 2016)
   - extracting results from articles using statcheck*
2. Data set 'APA', which contains the following information retrieved using statcheck:
   - statistical reporting errors: descriptive results (tables), testing H1 and H2
3. Data set 'AllP', which contains the following information retrieved using 'statcheck:
   - publication bias: descriptive results (tables, histograms), testing H3
   - bump in *p*-values: descriptive results (tables, histograms)
   - marginal significance presented: descriptive results (tables), testing H4
4. Data set 'Hyp', which contains manually retrieved information on *p*-values and reproducible results related to explicitly stated hypotheses:
   - selection process articles 'Hyp', with flowchart 
   - statistical reporting errors: descriptive results (tables)
   - publication bias: descriptive results (tables, histogram)
   - bump in *p*-values: descriptive results (tables, histogram)
   - marginal significance: descriptive results (tables) 

Note: * Information on this part still has to be added for it to be complete.

**References**\
Epskamp, S., & Nuijten, M. B. (2016). Statcheck: Extract statistics from articles and recompute p values. Retrieved\  
&nbsp;&nbsp;&nbsp;&nbsp;from https://cran.r-project.org/src/contrib/Archive/statcheck/
