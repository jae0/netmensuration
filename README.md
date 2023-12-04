# netmensuration

Utilities to interoperate with net mensuration data streams and determine touchdown/lift off and associated statistics.
 

External dependency: INLA ( http://www.r-inla.org/download )

## Installation


To install, run the following:

```r
  remotes::install_github( "jae0/aegis")  # helper functions
  remotes::install_github( "jae0/netmensuration")
``` 

You probably will want to have an Rprofile set up properly such as:

```r
homedir = path.expand("~")
code_root = file.path( homedir, "bio" )   ### replace with correct path to the parent directory of your git-projects
data_root = file.path( homedir, "bio.data" )   ### replace with correct path to your data

require( aegis )
require( netmensuration )

```
 