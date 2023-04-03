# **Supplementary material**: Chitosan modulates volatile organic compound emission from the biocontrol fungus *Pochonia chlamydosporia*

**Files**:

- `rice_gcms.tsv` and `czapek_gcms.tsv`: It contains the VOCs produced by *P. chlamydosporia* on solid medium (rice) and in liquid medium (Czapek-Dox).  The files contain the following fields:
  - `compound_code`: volatile organic compound ID in `DCX` format.
  - `sample_id`: sample ID.
  - `group`: Treatment factor, if it was treated with chitosan solution (`CH`) or buffer control solution (`BF`).
  - `DAI`(for rice) or `exposure_time` (for Czapek-Dox): Time factor, days after inoculation (`15`, `25` or `35` DAI) or exposure time to chitosan (`24`, `48` or `72`hours).
  - `value`: Peak height.
- `rice_c_to_c.tsv` and `czapek_c_to_c.tsv`: Matching between `compound_code` and compound name (`compound_name`).
- `Pc_VOCs_analysis.Rmd`: Code for exploratory and statistical analysis of data.

## SessionInfo

```

## R version 4.2.3 (2023-03-15 ucrt)
## Platform: x86_64-w64-mingw32/x64 (64-bit)
## Running under: Windows 10 x64 (build 19045)
## 
## Matrix products: default
## 
## locale:
## [1] LC_COLLATE=Spanish_Spain.utf8  LC_CTYPE=Spanish_Spain.utf8   
## [3] LC_MONETARY=Spanish_Spain.utf8 LC_NUMERIC=C                  
## [5] LC_TIME=Spanish_Spain.utf8    
## 
## attached base packages:
## [1] parallel  grid      stats     graphics  grDevices utils     datasets 
## [8] methods   base     
## 
## other attached packages:
##  [1] rmarkdown_2.20  knitr_1.42      INLA_23.03.19   sp_1.6-0       
##  [5] foreach_1.5.2   Matrix_1.5-3    DT_0.27         svglite_2.1.1  
##  [9] reshape2_1.4.4  gridExtra_2.3   UpSetR_1.4.0    lubridate_1.9.2
## [13] forcats_1.0.0   stringr_1.5.0   dplyr_1.1.1     purrr_1.0.1    
## [17] readr_2.1.4     tidyr_1.3.0     tibble_3.2.1    ggplot2_3.4.1  
## [21] tidyverse_2.0.0
## 
## loaded via a namespace (and not attached):
##  [1] Rcpp_1.0.10        lattice_0.20-45    digest_0.6.31      utf8_1.2.3        
##  [5] R6_2.5.1           plyr_1.8.8         MatrixModels_0.5-1 evaluate_0.20     
##  [9] highr_0.10         pillar_1.9.0       rlang_1.1.0        rstudioapi_0.14   
## [13] jquerylib_0.1.4    labeling_0.4.2     splines_4.2.3      htmlwidgets_1.6.2 
## [17] munsell_0.5.0      compiler_4.2.3     xfun_0.37          pkgconfig_2.0.3   
## [21] systemfonts_1.0.4  htmltools_0.5.4    tidyselect_1.2.0   codetools_0.2-19  
## [25] fansi_1.0.4        tzdb_0.3.0         withr_2.5.0        jsonlite_1.8.4    
## [29] gtable_0.3.3       lifecycle_1.0.3    magrittr_2.0.3     scales_1.2.1      
## [33] cli_3.6.0          stringi_1.7.12     cachem_1.0.7       farver_2.1.1      
## [37] bslib_0.4.2        ellipsis_0.3.2     generics_0.1.3     vctrs_0.6.1       
## [41] iterators_1.0.14   tools_4.2.3        glue_1.6.2         crosstalk_1.2.0   
## [45] hms_1.1.3          fastmap_1.1.1      yaml_2.3.7         timechange_0.2.0  
## [49] colorspace_2.1-0   sass_0.4.5
```




