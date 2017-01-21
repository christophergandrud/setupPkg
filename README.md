# setupPkg

> One Function To Install and Load Packages

When working across multiple machines and, similarly for
reproducible research, it can be time consuming to ensure that you have
all of the needed packages installed and loaded. setupPkg provides one
simple function that checks if needed packages are installed, installs them
if missing, and then loads all of the requested packages. Include
`library_install` at the top of all your R source code files to make sure that
all packages needed to run a script are installed and loaded.

## Example

```r
library(setupPkg)

packages <- c('networkD3', 'coreSim')

library_install(packages)
```
