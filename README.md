This github repository hosts the support files for my dissertation titled,
*A National Study Comparing Charter and Traditional Public Schools Using Propensity
Score Analysis*. For more contact me by email at [jason@bryer.org](mailto:jason@bryer.org).

* The `multilevelPSA` package is available on [CRAN](http://cran.r-project.org/web/packages/multilevelPSA/index.html), hosted on [Github](https://github.com/jbryer/multilevelPSA), and documented on [my website](http://jason.bryer.org/multilevelPSA/).

* The `naep` package is hosted on [Github](https://github.com/jbryer/naep) and documented on [my website](http://jason.bryer.org/naep/). It can be installed directly from Github using the `devtools` package using the `devtools::install_github('naep','jbryer')` command.

* [Dissertation](https://github.com/jbryer/Dissertation/blob/master/LaTeX/Bryer.Dissertation.pdf?raw=true)

* Dissertation [Proposal](https://github.com/jbryer/Dissertation/blob/master/LaTeX/Bryer.Proposal.pdf?raw=true) and [slides](https://github.com/jbryer/Dissertation/blob/master/LaTeX/Bryer.Proposal.Slides.pdf?raw=true).



#### Abstract

The concept of school choice within the United States is not new. Private schools have been educating students since the founding of the United States. However, in 1988, Ray Budde proposed an alternative approach to school choice that has come to be known as charter schools (Kolderie, 2005). Unlike their private school counterparts, charter schools receive public funding, but they are relieved of many of the bureaucratic and regulatory constraints public schools adhere to, but are still held accountable for student performance. Despite claims by charter school advocates that charter schools are performing as well if not better than the public school counterparts (see e.g. Allen, Consolettie, & Kerwin, 2009), studies provide mixed results with regard to charter school performance (see e.g. Braun, Jenkins, & Grigg, 2006a; Center for Research on Education Outcomes, 2009; Hubbard & Kulkarni, 2009). Ultimately, there is agreement that more research is necessary to address the question of whether charter schools provide substantially better academic experiences for students.This study includes development of new methods designed for observational data analysis to investigate the question of whether students who attend charter schools outperform their public school counterparts on two key academic domains: reading and mathematics. The new methods represent extensions of modern methods for propensity score analysis and aim to reduce if not eliminate selection bias in the context of clustered data. Charter schools are, by definition, schools of choice, and this means that observational data methods are preferred for comparing such schools with others. In observational data contexts, simple comparisons of two groups such as traditional public and charter schools cannot help but ignore the inherent and systematic differences between the two groups. However, given well-designed observational studies and appropriate analysis methods, the effects of the selection bias can be reduced, if not eliminated. The end result is that the usual simple comparisons of two independent groups are replaced by comparisons that make adjustments for covariate differences.
This is done utilizing a class of statistical procedures introduced by Rosenbaumand Rubin (1983) called propensity score analysis. Propensity score analysis has seen considerable increased use in the social sciences within the last few years (Arpino & Mealli, 2008). However, its use in situations where multilevel, or clustered data are of interest have been limited (Thoemmes & Kim, 2011). Using data from the 2009 National Assessment of Educational Progress (NAEP) for mathematics and reading at grades four and eight, estimates of the differences between charter and public schools will be calculated at two levels, namely at the state and national levels. Given the variability of charter schools laws across states, it is important to consider the impact of clustering. Analyses will be conducted using the newly developed multilevelPSA package (Bryer, 2011) in R (R Development Core Team, 2008). Specifically, propensity scores will be estimated within each state and these will be used for matching or stratification of students within each state. Comparisons of specific students, or groups of students, will in all cases be done within states. Effects will then be aggregated to provide state and national effect estimates.As with all propensity score analyses, it is preferable to utilize multiple methods for estimating propensity scores (see e.g. Stuart, 2010; Rosenbaum, 2012). Doing so can help to provide confidence that results reflect what the data have to say, and is not merely an artifact of model specification or method choice. This study will utilize three overall approaches to propensity score analysis, namely stratification, matching, and multilevel stratification. Lastly, the use of graphics will be employed to evaluate balance and outcome differences using methods (functions) found in Helmreich and Pruzek (2009).