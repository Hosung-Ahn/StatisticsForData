![Python](https://github.com/gedeck/dmba/actions/workflows/build.yml/badge.svg)

# Code repository
<table width='100%'>
 <tr>
  <td><img src='/images/OReilly-korean.jpg' width=300></td>
  <td>
   <b>Practical Statistics for Data Scientists:</b>

50+ Essential Concepts Using R and Python

by Peter Bruce, Andrew Bruce, and [Peter Gedeck](https://www.amazon.com/Peter-Gedeck/e/B082BJZJKX/)

- Publisher: [O'Reilly Media](https://oreil.ly/practicalStats_dataSci_2e); 2 edition (June 9, 2020)
- ISBN-13: 978-1492072942
- Errata: http://oreilly.com/catalog/errata.csp?isbn=9781492072942
    </td>
  </tr>
</table>

# Setup R and Python environments
## R
Run the following commands in R to install all required packages
```
if (!require(vioplot)) install.packages('vioplot')
if (!require(corrplot)) install.packages('corrplot')
if (!require(gmodels)) install.packages('gmodels')
if (!require(matrixStats)) install.packages('matrixStats')

if (!require(lmPerm)) install.packages('lmPerm')
if (!require(pwr)) install.packages('pwr')

if (!require(FNN)) install.packages('FNN')
if (!require(klaR)) install.packages('klaR')
if (!require(DMwR)) install.packages('DMwR')

if (!require(xgboost)) install.packages('xgboost')

if (!require(ellipse)) install.packages('ellipse')
if (!require(mclust)) install.packages('mclust')
if (!require(ca)) install.packages('ca')
```

## Python
We recommend to use a conda environment to run the Python code.
```
conda create -n sfds python
conda activate sfds
conda env update -n sfds -f environment.yml
```

## 출처
practical-statistics-for-data-scientists-master are copied from [github-gedect](https://github.com/gedeck/practical-statistics-for-data-scientists).   
All source code was written with reference to that book.