# <a id="Top-of-Page"> Welcome to the Passive Investment WebApp!</a>
#### A financial database and web application to analyze the performance of a hypothetical fintech ETF.

***
## <a id="Contents">Cotents</a>
[Project Description](#Project-Description)<br>
[Technologies](#Technologies)<br>
[Installation Guide](#Installation-Guide)<br>
[Usage](#Usage)<br>
[Contributors](#Contributors)<br>
[License](#License)<br>
[Bottom of Page](#Bottom-of-Page)<br>

***
## <a id="Project-Description">Project Description</a>
This webapp analyses and visualizes exchange-traded fund (ETF) portfolio performance.

#### A summary of what's under the hood:    
This project aims to analyze and visualize the ETF portfolio by doing the following:
 - Analyze a single asset in the ETF
 - Optimize data access with advanced SQL queries
 - Analyze the ETF portfolio
 - Deploy the notebook as a web application<br>

#### Project layout:
The layout of essentials for this project is show below.
<p><a href="tree.txt"><img src="img/project_tree.png" title="price-dislocation project tree"></a></p>

***
## <a id="Technologies">Technologies</a>
<a href="https://docs.python.org/release/3.8.0/" title="https://docs.python.org/release/3.8.0/"><img src="https://img.shields.io/badge/python-3.8%2B-red">
<a href="https://pandas.pydata.org/docs/" title="https://pandas.pydata.org/docs/"><img src="https://img.shields.io/badge/pandas-1.3.1-green"></a>
<a href="https://jupyter-notebook.readthedocs.io/en/stable/" title="https://jupyter-notebook.readthedocs.io/en/stable/"><img src="https://img.shields.io/badge/jupyter--notebook-5.7.11-blue"></a>
<a href="https://docs.sqlalchemy.org/en/14/" title="https://docs.sqlalchemy.org/en/14/"><img src="https://img.shields.io/badge/sqlalchemy-1.4.22-yellowgreen"></a>
<a href="https://docs.bokeh.org/en/latest/index.html" title="https://docs.bokeh.org/en/latest/index.html"><img src="https://img.shields.io/badge/bokeh-2.3.3-green"></a>
<a href="https://hvplot.holoviz.org/user_guide/Introduction.html" title="https://hvplot.holoviz.org/user_guide/Introduction.html"><img src="https://img.shields.io/badge/hvplot-0.7.3-orange"></a><br>
<a href="./requirements.txt" title="requirements.txt">Requirements List</a>

***
## <a id="Installation-Guide">Installation Guide</a>
### Project Installation
To install <a href="https://github.com/jasonjgarcia24/passive-investment-webapp" title="https://github.com/jasonjgarcia24/passive-investment-webapp">passive-investment-webapp</a>, type <code>git clone https://github.com/jasonjgarcia24/passive-investment-webapp.git</code> into bash in your prefered local directory.<br><br>
Alternatively, you can navigate to the same address (<code>https://github.com/jasonjgarcia24/passive-investment-webapp.git</code>) and download the full <code>main</code> branch's contents as a zip file to your prefered local directory.<br>

***
## <a id="Usage">Usage</a>
### Inputs
Observe passive-investment-webapp with <code>passive-investment-webapp.ipynb</code>. The <code>etf.db</code> database file is required for access to the ETF data.<br>

### Outputs
The tools provides three necessary visualizations for ETF porfolio analysis:
1. An interactive line chart for the selected PYPL daily returns:<br>
<img src="./img/results_daily-returns_PYPL.png" title="PYPL daily returns"><br>

2. An interactive line chart for the selected PYPL cumulative daily returns:<br>
<img src="./img/results_cumulative-daily-returns_PYPL.png" title="PYPL Cumulative daily returns"><br>

3. An interactive line chart for the ETF portfolio's cumulative annualized returns:<br>
<img src="./img/results_cumulative-returns_portfolio.png" title="Average Sale Prices by Neighborhood"><br>
    
Using Voilà, the following screenshot recordings capture the webapp:
<img src="./img/voila_p1.png"><br>

<img src="./img/voila_p2.png"><br>

<img src="./img/voila_p3.png"><br>

<img src="./img/voila_p4.png"><br>

<img src="./img/voila_p5.png"><br>

<img src="./img/voila_p6.png"><br>

<img src="./img/voila_p7.png"><br>

<img src="./img/voila_p8.png"><br>

<img src="./img/voila_p9.png"><br>

<img src="./img/voila_p10.png"><br>

***
## <a id="Contributors">Contributors</a>
Currently just me :)<br>

***
## <a id="License">License</a>
Each file included in this repository is licensed under the <a href="https://github.com/jasonjgarcia24/passive-investment-webapp/blob/586c7f7d1555c5effd9f271418a7cca2e6279a03/LICENSE" title="LICENSE">MIT License.</a>

***
[Top of Page](#Top-of-Page)<br>
[Contents](#Contents)<br>
[Project Description](#Project-Description)<br>
[Technologies](#Technologies)<br>
[Installation Guide](#Installation-Guide)<br>
[Usage](#Usage)<br>
[Contributors](#Contributors)<br>
[License](#License)<br>
<a id="Bottom-of-Page"></a>
    
    

