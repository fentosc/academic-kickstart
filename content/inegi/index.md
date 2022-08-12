---
title: INEGI Tools
summary: Bases de datos
date: "2022-08-11"

# Optional header image (relative to `static/img/` folder).
header:
  caption: ""
  #image: "tijuana.jpg"
---

# Economic Census dummy data

The National Institute of Statistics and Geography (INEGI) provides examples of Economic Census databases with altered values to show the characteristics of the databases and to test algorithms. They can be found <a href="http://en.www.inegi.org.mx/programas/ce/2014/#Microdata">here</a>.

However, these examples contain only few observations and they are not useful to test complex algorithms that require large variation across many characteristics of establishments such as geographical codes or industries.

I am working on a more *realistic* set of **.dta** files that simulate the Economic Census with real industrial and geographical codes and random values for all variables.

These simulated databases are useful for users that are planning to go to the Microdata Laboratory or will work remotely. They can be downloaded here:

- [Insumo1994.dta](/inegi/Insumo1994.dta)
- [Insumo1999.dta](/inegi/Insumo1999.dta)
- [Insumo2004.dta](/inegi/Insumo2004.dta)
- [Insumo2009.dta](/inegi/Insumo2009.dta)
- [Insumo2014.dta](/inegi/Insumo2014.dta)
- [Insumo2019.dta](/inegi/Insumo2019.dta)
- [CORRESPONDENCES_1999_2014.dta](/inegi/correspondencias_1994-2014.dta)

The file **CORRESPONDENCES_1999_2014.dta** are a simulation of the identifiers developed by [Busso, Fentanes and Levy (2018)](https://publications.iadb.org/en/longitudinal-linkage-mexicos-economic-census-1999-2014) to link longitudinally the Economic Censuses previous to 2009.

I will try to improve these databases to add more realistic features in the future, for instance, to make sure that the variables follow the definitions by INEGI (e.g. q000a=q100a+q200a+...).

(Latest version: 04/08/2022)
