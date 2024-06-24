# SDFDA
 Modelling Species Distribution Using Functional Data Analysis"



## Modeling LPUE  abundance of fish using functional data analysis


Poster presented in *International Symposium on Nonparametric Statistics 2024*
(ISNPS 2024), June 25-29, 2024 - Braga, Portugal

Please cite this paper as:

```
@article{oviedo2024spfda,
  title={Modeling LPUE  abundance of fish using functional data analysis},
  author={Oviedo de-la Fuente, Manuel, Menezes, Raquel and Silva, Alexandra},
  year={2024}
}
```

Authors: 

+ Manuel Oviedo de la Fuente, University of A Coruña, CITIC, MODES group, Spain. manuel.oviedo@udc.es
+ Raquel Menezes,  CMAT, Minho University, Portugal. rmenezes@math.uminho.pt
+ Alexandra A. Silva, MARE / ARNET, Faculty of Sciences, University of Lisbon, Portugal. asilva@ipma.pt

\afil{\textsuperscript{a} CITIC, University of A Coruña\\
	\textsuperscript{b} CMAT, Minho University, Guimar\~aes\\
	\textsuperscript{c} Portuguese Institute for the Sea and Atmosphere (IPMA), Lisboa\\%Division of Modelling and Management of Fishery Resources, IPMA, Lisboa\\
         \textsuperscript{d} }


## Abstract 
Forecasting the abundance of landed fish per unit effort (LPUE) is a crucial challenge in competitive fish markets. Previous studies have addressed this issue using various models such as ARIMA, generalized linear models (GLMs), generalized additive models (GAMs), and geostatistical models like continuous Gaussian random fields (GRFs), among others used  to model species distribution in fisheries.

However, this paper proposes an alternative approach based on functional data analysis (FDA). FDA is a statistical branch that focuses on analyzing data consisting of curves or anything else varying over a continuum. We use sensor data monitoring, such as chlorophyll-a concentrations, intensity of ocean currents, Sea Surface Temperature, wind speed, and wind direction curves. 

Furthermore, this paper addresses the challenge of variable selection by employing distance correlation to investigate the relationships between environmental curves (including their derivatives) and other sources of information, such as sale prices at landing, calendar variables, and the scalar response (LPUE). The proposed functional approach, specifically a functional generalized additive model (GAM) with variable selection, has demonstrated promising results when applied to a real dataset LPUE of juvenile sardine during a period with fewer administrative fishing restrictions. 
These findings present decision makers with a valuable tool to advance marine sustainability and conservation efforts by enhancing our understanding of the factors influencing LPUE.


# Installation  

## 1. `fda.usc` package
To install `fda.usc.devel` package (devel version of `fda.usc`) from Github with (2023/03/29):

```{r , eval = FALSE}
# install.packages("devtools")
require(devtools)
devtools::install_github("moviedo5/FRMFR/pkg/fda.usc.devel")
```


## 2. `posterdow` package
Poster created by  [posterdown](https://github.com/brentthorne/posterdown)

# Poster

+ `./html/poster_v1.html`: html version (dynamic)
+ `./html/poster_v1.pdf`: html version (static)

![poster](html/poster_v1.html)

aaaw hich indeed convert into

<image src="/pdf/poster_v1.pdf"/>
in the html.

ccc

```{r image-ref-for-in-text, echo = FALSE, message=FALSE, fig.align='center', fig.cap='Some cool caption', out.width='0.75\\linewidth', fig.pos='H'}
knitr::include_graphics("./pdf/poster_v1.pdf")
```

bbb

<embed src="./pdf/poster_v1.pdf" type="application/pdf">

eee

![Image Title](./html/poster_v1.html){height=200%}

<p align="center">
  <img src="./pdf/poster_v1.pdf" alt="" width="350" height="350">
</p>


<p align="center">
  <img src="./html/poster_v1.html" alt="" width="350" height="350">
</p>