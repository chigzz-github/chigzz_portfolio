---
layout: post
title: "NYC Sales Prediction Analysis"
date: 2019-11-05 08:44:38 -0400
category: using-odin
author: mac
short-description: Using PySpark,Python
---

-----

<h4>Introduction</h4>
<ul>
<li>The Zillow Home Value Forecast is Zillow's prediction of what the Zillow Home Value Index (ZHVI) will be one year from now</li>
<li>A House Price Index (HPI) measures the price changes of residential housing as a percentage change from some specific start date</li>
<li>Keeping that in mind, I have predicted the ZHPI and HPI values for NYC city</li>
</ul>


<h4>Dataset Description</h4>
<ul>
<li>The dataset of this analysis is taken from the Zillow website</li>
<li>The target for predictions is the ZHVI and HPI values</li>
<li>The dataset can be viewed from: <a href="https://github.com/chigzz-github/PySpark_DataAnalysis" style="color:#0385F9"><u>Dataset Link</u></a></li>
</ul>


<h4>Dataset Preparation</h4>
<ul>
<li>Making Temporary table to map the dataset for running SQL queries</li>
<li>Converted the pandas dataframe to spark dataframe and vice versa to visualize the dataset</li>
</ul>

<h4>Results</h4>
<ul>
<li>San Mateo County  from the CA county has the highest PeakZHVI value:</li>
<img src="{{site.baseurl}}/assets/ca.png" style="width:750px;height:400px">
<p></p>
<p></p>
<li>Zip_Code numbered 943 has the highest HPI values:</li>
<img src="{{site.baseurl}}/assets/hpi_high.png" style="width:750px;height:400px">
</ul>


<h4>GitHub Link</h4>
<ul>
<li>More information to this analysis can be found in beside link: <a href="https://github.com/chigzz-github/PySpark_DataAnalysis" target="_blank" style="color:#0385F9"><u>GitHub Link</u></a></li>
</ul>