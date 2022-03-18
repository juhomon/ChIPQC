# ChIPQC

This is a fork of ChIPQC in bioconductor/shengqh. Error: "names' attribute [x] must be the same length as the vector [x]" should be fixed. In my case due to blacklist regions being 0-start (out of bound in the context of GRanges) added seqlength implementation and trimming to counter this.

Installation
```
library(devtools)
install_github("juhomon/ChIPQC")
```
