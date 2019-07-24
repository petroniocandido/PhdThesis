# Scalable Models of Probabilistic Forecasting with Fuzzy Time Series, PhD Thesis
[![Open Source Love png2](https://badges.frapsoft.com/os/v2/open-source.png?v=103)](https://github.com/ellerbrock/open-source-badges/)
[![made-with-python](https://img.shields.io/badge/Made%20with-Python-1f425f.svg)](https://www.python.org/)

* **Author**: Petrônio Cândido de  Lima e Silva  <span itemscope itemtype="https://schema.org/Person"><a itemprop="sameAs" content="https://orcid.org/0000-0002-1202-2552" href="https://orcid.org/0000-0002-1202-2552" target="orcid.widget" rel="noopener noreferrer" style="vertical-align:top;"><img src="https://orcid.org/sites/default/files/images/orcid_16x16.png" style="width:1em;margin-right:.5em;" alt="ORCID iD icon"></a></span> (SILVA, P.C.L)
* **Advisor**: Frederico Gadelha Guimarães <span itemscope itemtype="https://schema.org/Person"><a itemprop="sameAs" content="https://orcid.org/0000-0001-9238-8839" href="https://orcid.org/0000-0001-9238-8839" target="orcid.widget" rel="noopener noreferrer" style="vertical-align:top;"><img src="https://orcid.org/sites/default/files/images/orcid_16x16.png" style="width:1em;margin-right:.5em;" alt="ORCID iD icon"></a></span> (GUIMARÃES, F. G)
* **Co-Advisor**: Hossein Javedani Sadaei  <span itemscope itemtype="https://schema.org/Person"><a itemprop="sameAs" content="https://orcid.org/0000-0002-0848-9280" href="https://orcid.org/0000-0002-0848-9280" target="orcid.widget" rel="noopener noreferrer" style="vertical-align:top;"><img src="https://orcid.org/sites/default/files/images/orcid_16x16.png" style="width:1em;margin-right:.5em;" alt="ORCID iD icon"></a></span> (SADAEI, H. J.)

In case you have any questions, do not hesitate in contact us using the following e-mail: petronio.candido@ifnmg.edu.br

<center>
<table><tr>
<td><a href="https://www.ufmg.br/"><img src="https://www.ufmg.br/marca/ass5.jpg" alt="UFMG - Universidade Federal de Minas Gerais" width="100"/></a></td>
<td>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</td>
<td><a href="https://www.ppgee.ufmg.br/">PPGEE</a></td>
<td>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</td>
<td> <a href="http://www.minds.eng.ufmg.br/"><img src="https://github.com/petroniocandido/pyFTS/raw/master/img/minds_logo_medium.jpeg" alt="MINDS - Machine Intelligence and Data Science Lab" width="100"/></a></td> 
  <td>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</td>
<td><a href="http://www.ifnmg.edu.br"><img src="  https://www.ifnmg.edu.br/arquivos/2016/reitoria/Not%C3%ADcias/ifnmg_vertical_jpg.jpg
" alt="IFNMG - Instituto Federal do Norte de Minas Gerais" width="100"/></a></td>
</tr>
</table>
</center>

## Abstract

On time series forecasting field the most known methods are based on point forecasting. However, this kind of forecasting has a serious drawback: it does not quantify the uncertainties inherent to natural and social processes neither other uncertainties caused by the data capturing and processing. Because this in last years the interval and probabilistic forecasting methods have gaining more attention of researches, specially on environmental and economical sciences. But these techniques also have its own issues due the methods being black-boxes and use stochastic simulations and ensembles of multiple forecasting methods which are computationally expensive.

In other hand, the data volume (number of instances) and dimensionality (number of variables) have reached magnitudes even greater, due to the commoditizing of the capturing and storing computational devices, in a phenom knows as Big Data. Such factors impact directly in the models's training and updating costs, and for time series with Big Data characteristics, the scalability became a decisive factor in the choosing of predictive methods.

In this context emerge the Fuzzy Time Series (FTS) methods, which have growing in recent years due their accurate results, easy to implement, low computational cost and model explainability. The Fuzzy Time Series methods have been applied to forecast electric load, market assets, economical indicators, tourism demand, etc. But there is a lack on FTS literature regarding to interval and probabilistic forecasting.

This thesis proposes new scalable Fuzzy Time Series methods and discuss its application on point, interval and probabilistic forecasting of mono and multivariate time series, for one to many steps ahead. The parameters and hyper-parameters are discussed and fine tunning alternatives are presented. Finally the proposed methods are compared with the main Fuzzy Time Series techniques and other literature approaches using environmental and stock market data. The proposed methods obtained promising results on point, interval and probabilistic forecasting and presented low computational cost, making it useful for a wide range of applications.

## How to execute the code?


<center>
<table><tr>
<td><a href="https://pyfts.github.io/pyFTS/"><img src="https://github.com/petroniocandido/pyFTS/raw/master/img/logo_medium.png" alt="pyFTS - Fuzzy Time Series for Python" width="100"/></a></td>
</tr>
</table>
</center>

## How to reference this work?

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.597359.svg)](https://doi.org/10.5281/zenodo.597359)

 Silva, P. C. L. et al. *pyFTS: Fuzzy Time Series for Python.* Belo Horizonte. 2018. DOI: 10.5281/zenodo.597359. Url: <http://doi.org/10.5281/zenodo.597359>

## MINDS - Machine Intelligence And Data Science Lab

This tool is result of collective effort of [MINDS Lab](http://www.minds.eng.ufmg.br/), headed by Prof. Frederico Gadelha Guimaraes. 
