MODISTools4LateFrost
=======
R package - retrieving & using MODIS data from NASA LPDAAC archive
---------

MODISTools4LateFrost is an R package forked from [MODISTools](https://github.com/seantuck12/MODISTools) and crudely hacked in order to directly return a downloaded subset instead of saving it to a CSV file. Passing MODIS downloads around is much faster than saving them in text files and then loading them again (expecially when dealing with 100+ MB files).
LateFrost is an ongoing project to map year 2016 late frost damages to Italian beech forests.
For a full description of MODISTools package, please head to its GitHub [repository](https://github.com/seantuck12/MODISTools) or to [CRAN](https://cran.r-project.org/web/packages/MODISTools/index.html).

```
install.packages("devtools")
library(devtools)
```

Then use `install_github`, with this repository name, to install `MODISTools4LateFrost` straight from GitHub.
```
install_github("mbask/MODISTools", build_vignettes=FALSE)
```
