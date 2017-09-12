# Package `GetTDData`

Information regarding prices and  yields of bonds issued by the Brazilian government can be downloaded manually as excel files from the [Tesouro Direto website](http://www.tesouro.fazenda.gov.br/tesouro-direto-balanco-e-estatisticas). However, it can be painful to aggregate all of this data into something useful as the files don't have an uniform format and are all divided by year and asset code.

Package GetTDData makes the process of importing data from Tesouro direto much easier. All that you need in order to download the data is the name of the assets (LFT, LTN, NTN-C, NTN-B, NTN-B Principal, NTN-F) and the desired dates of maturity (e.g. 2016-01-01). 

# Installation

```
# from CRAN
install.package('GetTDData')
```

# How to use GetTDData

See [vignette](https://cran.r-project.org/web/packages/GetTDData/vignettes/gtdd-vignette.html).