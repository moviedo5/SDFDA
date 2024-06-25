# SDFDA:  Species Distribution using Functional Data Analysis


Poster presented in *International Symposium on Nonparametric Statistics 2024*
(ISNPS 2024), June 25-29, 2024 - Braga, Portugal


## Authors

+ Manuel Oviedo de la Fuente, University of A Coruña, CITIC, MODES group, Spain. manuel.oviedo@udc.es
+ Raquel Menezes,  CMAT, Minho University, Portugal. rmenezes@math.uminho.pt
+ Alexandra A. Silva, MARE / ARNET, Faculty of Sciences, University of Lisbon, Portugal. asilva@ipma.pt

## Title


### *Modeling LPUE  abundance of fish using functional data analysis*

## Abstract 
Forecasting the abundance of landed fish per unit effort (LPUE) is a crucial challenge in competitive fish markets. Previous studies have addressed this issue using various models such as ARIMA, generalized linear models (GLMs), generalized additive models (GAMs), and geostatistical models like continuous Gaussian random fields (GRFs), among others used  to model species distribution in fisheries.

However, this paper proposes an alternative approach based on functional data analysis (FDA). FDA is a statistical branch that focuses on analyzing data consisting of curves or anything else varying over a continuum. We use sensor data monitoring, such as chlorophyll-a concentrations, intensity of ocean currents, Sea Surface Temperature, wind speed, and wind direction curves. 

Furthermore, this paper addresses the challenge of variable selection by employing distance correlation to investigate the relationships between environmental curves (including their derivatives) and other sources of information, such as sale prices at landing, calendar variables, and the scalar response (LPUE). The proposed functional approach, specifically a functional generalized additive model (GAM) with variable selection, has demonstrated promising results when applied to a real dataset LPUE of juvenile sardine during a period with fewer administrative fishing restrictions. 
These findings present decision makers with a valuable tool to advance marine sustainability and conservation efforts by enhancing our understanding of the factors influencing LPUE.



# Poster

+ Poster in PDF: ![`./pdf/poster.pdf`](./pdf/poster.pdf) 


+ Poster in HTML: ![`./html/poster.html`](./html/poster.html)


Poster created by  [posterdown](https://github.com/brentthorne/posterdown).

The [fda.usc](https://github.com/moviedo5/fda.usc) R package  has been used for FDA analysis, including the implementation of the FAM model with variable selection.


Please cite this poster as:


```
@inproceedings{oviedo2024spfda,
  author    = "Oviedo de-la Fuente, Manuel, Menezes, Raquel and Silva, Alexandra",
  title     = "Modeling LPUE abundance of fish using functional data analysis",
  booktitle = "Proc. of the 6th International Symposium on Nonparametric Statistics",
  series    = "NordiCHI",
  year      = 2024,
  pages     = "113",
  address   = "June 25-29, 2024 - Braga, Portugal",
  url       =  "https://github.com/moviedo5/SDFDA"
}
```



# Acknowledgements
This research/work has been supported by MINECO grant MTM2017-82724-R, and by the Xunta de Galicia (Grupos de Referencia Competitiva ED431C-2020-14 and Centro de Investigación del Sistema universitario de Galicia ED431G 2019/01), all of them through the ERDF. Authors also acknowledge the FCT Foundation for funding their research through projects PTDC/MAT-STA/28243/2017, UIDB/00013/2020 and UIDP/00013/2020 and MAR2020 for funding the SARDINHA2020 project (MAR-01.04.02-FEAMP-0009).
