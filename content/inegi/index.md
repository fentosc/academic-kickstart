---
title: 
summary: Bases de datos
date: "2022-08-11"

# Optional header image (relative to `static/img/` folder).
header:
  caption: ""
  #image: "tijuana.jpg"
---

# Economic Census dummy data

The National Institute of Statistics and Geography (**INEGI**) provides examples of Economic Census databases with altered values to show the characteristics of the databases and to test algorithms. These examples can be found <a href="http://en.www.inegi.org.mx/programas/ce/2014/#Microdata">here</a>.

I am working on a more *realistic* set of **.dta** files that simulate the Economic Census with real industrial and geographical codes and random values for all variables. These **.dta** are useful to test complex algorithms that require large variation across many characteristics of establishments such as geographical codes or industries.

These simulated databases are useful for users that are planning to go to the Microdata Laboratory or will work remotely. The files are:

- <p style="color:blue;">Insumo1994.dta</p>
- <p style="color:blue;">Insumo1999.dta</p>
- <p style="color:blue;">Insumo2004.dta</p>
- <p style="color:blue;">Insumo2009.dta</p>
- <p style="color:blue;">Insumo2014.dta</p>
- <p style="color:blue;">Insumo2019.dta</p>
- <p style="color:blue;">correspondencias_1994-2014.dta</p>


<p> 
<a href="https://www.dropbox.com/sh/hw1tlonxnin6d3o/AAA9ogUJnjSLQvTqc_xFagUAa?dl=0">  <b> You can download these DTA files from this link    </b> </a> <img style='display:inline;' src='https://upload.wikimedia.org/wikipedia/commons/f/f5/Stata_2015_logo.gif' width="60" height="20"/> </p>


The file **correspondencias_1994-2014.dta** is a simulation of the identifiers developed by [Busso, Fentanes and Levy (2018)](https://publications.iadb.org/en/longitudinal-linkage-mexicos-economic-census-1999-2014) to longitudinally link the Economic Censuses from 2009 and before.

I will try to improve these databases to add more realistic features in the future, for instance, to make sure that the variables follow the definitions by INEGI (e.g. q000a=q100a+q200a+...).

(Latest version: 19/Sep/2022)
