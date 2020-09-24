# FMODEL_OccupationVsAccumulation
A simulation of the effects of movement tortuosity and frequency on lithic assemblage densities and cortex ratios. Built using the [NetLogo (6.1.2)](https://ccl.northwestern.edu/netlogo/) and analyzed using [R (4.0.2)](https://cran.r-project.org/) and [R Studio (1.1.383)](https://rstudio.com/), this model is used in a forthcoming publication:

Davies, B., M. Douglass, S. J. Holdaway, and P. C. Fanning. Resilience and reversibility: engaging with archaeological record formation to inform on past resilience. Submitted to
*Archaeological Review from Cambridge*.

This simulation is based on [FMODEL](https://github.com/b-davies/FMODEL), which is originally published here: 

Davies, B., Holdaway, S. J., and P. C. Fanning, 2018. Exploring relationships between space, movement, and lithic geometric attributes in the formation of archaeological landscapes. *American Antiquity* Published online. DOI: 10.1017/aaq.2018.23  [[Journal](https://doi.org/10.1017/aaq.2018.23)] [[Preprint](https://doi.org/10.17605/OSF.IO/92NYB)] [[Data and Supplementary Files](https://github.com/b-davies/FMODEL)]

Model details are provided in the [ODD document](https://github.com/b-davies/CortexDensity/blob/master/FMODEL_OccVsAcc%20ODD.pdf).To reproduce the results of the analysis, download the program files, as well as the required software ([NetLogo](https://ccl.northwestern.edu/netlogo/), [R](https://cran.r-project.org/), [R Studio](https://rstudio.com/)) and follow these steps:

- Open the [FMODEL_OccupationVsAccumulation.nlogo](https://github.com/b-davies/CortexDensity/blob/master/FMODEL_OccupationVsAccumulation.nlogo) file in NetLogo
- Select Tools > BehaviorSpace
- For each model in the Behaviorspace window, select the model and click Run. Select Table Output and the number of cores you would like to run the model over (up to the maximum available on your machine), then click OK. Save the results using the default file name in the same location as the program files. *Note: occasionally NetLogo will not save these files using the default ".csv" suffix. If this occurs, wait until simulations are done, then edit filenames to include .csv suffix.*
- Open the [CORTEX_DENSITY.Rmd](https://github.com/b-davies/CortexDensity/blob/master/CORTEX_DENSITY.Rmd) in R Studio
- Select Run > Run All 
