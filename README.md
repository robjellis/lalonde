## Forked copy of the Lalonde dataset in CSV format

### Used by MatchIt in R:
https://gking.harvard.edu/matchit 
https://cran.r-project.org/web/packages/MatchIt/index.html

### Obtained as follows (using R):
`library(MatchIt)`

`data("lalonde")`

`write.csv(lalonde,file='lalonde_data.csv')`

### Details from [here](https://rdrr.io/cran/MatchIt/man/lalonde.html):
A data frame with 614 observations (185 treated, 429 control). 
There are 10 variables measured for each individual: 
- `treat` is the treatment assignment (1=treated, 0=control). 
- `age` is age in years. 
- `educ` is education in number of years of schooling. 
- `black` is an indicator for African-American (1=African-American, 0=not). 
- `hispan` is an indicator for being of Hispanic origin (1=Hispanic, 0=not). 
- `married` is an indicator for married (1=married, 0=not married). 
- `nodegree` is an indicator for whether the individual has a high school degree (1=no degree, 0=degree). 
- `re74` is income in 1974, in U.S. dollars. 
- `re75` is income in 1975, in U.S. dollars. 
- `re78` is income in 1978, in U.S. dollars.
