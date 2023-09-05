<h1 align=center> MAURO GONZALO PINI
<h1 align=center> HENRY LABS - DATA SCIENCE COHORT 06
<h1 align=center> INDIVIDUAL PROJECT #3

## **Context**

The scenario of this activity simulates a request from a client who wants to venture into the MOOCs (Massive Open Online Courses) industry. You can read the detailed instructions in the CONSIGNA.md file, but in summary, the requirement was to perform an analysis of various databases, analyze the industry, present a data analysis, and suggest a KPI (Key Performance Indicator) for the client's use.

## **Documentation and Description of the Process**

Initially, I conducted an in-depth exploratory analysis and data transformation, which is explained and detailed step by step in the EDA.ipynb file. As a result, I obtained individual tables for each client and a general table that simulates market behavior.

As required by the client, the following documentation is provided in the repository:

* EDA --> EDA.ipynb
* Dashboard --> Dashboard-maurogpini
* Word clouds of most repeated words among the names (also in the EDA file) --> archivos.png
* Requirements for running the .ipynb file correctly --> requirements
* Clean and analysis-ready tables --> .csv files
* Written report --> developed below in the README as requested.

## **Report - Executive Summary**

As seen on the dashboard, an analysis was conducted on the most relevant categories of each of the three companies individually, obtaining indicators and features of their performance.

Subsequently, specific queries regarding the sales amounts were addressed, leading to the following specific conclusions:

#### Price
* There are certain price levels associated with a higher quantity of course sales: 200/500/490. Between these prices, more than 40% of the market's sales are concentrated.
* Regarding sales measured in USD, different price points are associated with higher revenue: 990/1990/1490.

It seems effective to set prices above the hundredth digit of the price.

#### Language

The industry is completely dominated by courses in English, both in terms of course quantity and gross revenue. Approximately 95% of the sampled content is in English. There appears to be a second niche in the Spanish-speaking market, but it remains distant.

This effect can be explained by the obvious fact that most people worldwide are proficient in English, so courses in that language have a wider reach and can be consumed by a broader range of customers.

It seems to be of utmost importance that course content is in English. However, when investigating the depth of the market beyond the sample, we believe that there may be significant potential for a Spanish-language content platform.

#### Rating and Level

There seems to be a strong correlation between sales, both in quantity and amount, and higher user ratings.
Regarding the complexity level of the courses, more than 80% of the market is dedicated to introductory-level and all-level courses.
It is worth noting that 15% of the content is aimed at intermediate-level courses, which also relates to individuals with more experience willing to invest in further education, even paying higher prices for such training. It is key to remember that the more expensive courses have a higher relative share of total revenue compared to cheaper courses.

#### Duration

This extra feature became of interest when analyzing the data. There is clear evidence that courses longer than the average seem to be the most requested. Likewise, extremely long courses have the highest percentage of benefits.

#### You can check the online report and interact with it by clicking ➡️[here](https://www.novypro.com/project/reporte-sobre-moocs-varias-p%C3%A1ginas/)⬅️ or by followinng this URL: https://www.novypro.com/project/reporte-sobre-moocs-varias-p%C3%A1ginas.


