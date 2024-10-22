
# 📈 Multi Criteria Decision Analysis (MCDA) + Deep Learning : Final Project


This repository contains the Final Project for ECE NTUA course Multi Criteria Decision Analysis (MCDA)

## Description:

Multiple-Criteria Decision analysis (MCDA) techniques enhanced with Deep Learning Techniques to solve a Securities Selection (Stocks) problem

## What is interactive multiobjective optimization?
There exist many methods to solve multiobjective optimization problems. Methods which introduce some preference information into the solution process are commonly known as multiple criteria decision making methods. **Multiple-criteria decision analysis (MCDA)** is a sub-discipline of operations research that explicitly evaluates multiple conflicting criteria in decision making. Conflicting criteria are typical in evaluating options: cost or price is usually one of the main criteria, and some measure of quality is typically another criterion. 

## What is this Project about?
The goal of this project is to analyze stocks of a specific sector and apply MCDA techniques to select a kernel (subset) of them based on specific criteria. We seek
* *high returns* 
* *low risk*

The initial perspective of this project was the implementation and the application of the following MCDA methods in a pool of stocks (∼ 50) of a sector of our preference and analyzed upon criteria also of our preference, to select a kernel (subset) of them based on specific criteria (*high returns, low risk, investing horizon*):
* **ELECTREE I with veto**
* **TOPSIS**
* **PROMETHEE**

However the project was expanded. We firstly estimated and eliminated stocks based on their [risk performance](https://www.investopedia.com/terms/r/riskmeasures.asp). We also applied [Deep Learning Techniques](https://towardsdatascience.com/predicting-stock-price-with-lstm-13af86a74944) to enhance the criteria <img src="http://www.sciweavers.org/tex2img.php?eq=x_1%2C...%2C%20x_n&bc=White&fc=Black&im=jpg&fs=12&ff=arev&edit=0" align="center" border="0" alt="x_1,..., x_n" width="76" height="15" /> used for each stock (*Technical Analysis*) and last but not least we used [Group Decision Making Method](https://www.seedsforchange.org.uk/shortconsensus) to reach a consensus upon the stocks used from multiple sources based on these criteria. We therefore applied [MCDA techniques](https://www.wikiwand.com/en/Multiple-criteria_decision_analysis) to reach a kernel of stocks in which we should invest in. Check *report* section for further analysis of the process.

## How did we work?
<img src="https://raw.githubusercontent.com/jimmyg1997/NTUA-Multi-Criteria-Decision-Analysis/master/photos/system.png" alt="https://raw.githubusercontent.com/jimmyg1997/NTUA-Multi-Criteria-Decision-Analysis/master/photos/system.png">
