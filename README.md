# ChemIDConvert
An opencpu wrapper of a web-app for ID mapping of chemicals.

Installation instructions - 
* Install R version 3.2.5 or higher. 
* Start the R.
* Copy paste following commands to R-console and press enter. 
```R
install.packages("opencpu")
install.packages("RCurl")
if (!require("devtools"))
  install.packages("devtools")
devtools::install_github("barupal/ChemIDConvert")
library(ChemIDConvert)
library("opencpu")
opencpu$browse('library/ChemIDCovnert/www') 
```

# Other tools 

[PubChem Identifiers exchange service](https://pubchem.ncbi.nlm.nih.gov/idexchange/idexchange.cgi ) is an excellent online tool to convert chemical names and other identifiers  (KEGG etc) to another ones.
