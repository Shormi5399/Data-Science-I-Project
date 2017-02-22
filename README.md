# Data-Science-I-Project
Effect of Economic crisis on Unemployment 

Motivation

The financial crisis in 2007-2009 occurred as a result of risky financial dealings in the real estate market which spilled over into the economy at large (Marshall, 2009). The resulting economic downturn, particularly the periods before and after the collapse of Lehman Brothers in September-October 2008, provides an opportunity to compare impact on different economic measures in different regions of the world. We utilize the financial crisis scenario as a timeframe to analyze the relationships between Consumer Price Index (CPI),  unemployment, and  the unorganized labor force in three major geographic regions.

Research Question

How did CPI change before and after the 2007-2009 financial crisis in the three major geographic regions?

How did employment rates and unorganized labor rates vary before and after the 2007-2009 financial crisis in the three major geographic regions?

Three regions of focus: Euro, South East Asia, USA  indicators.
		 		 	 	 					
Analysis Methods 

1.	Exploratory data analysis.
2.	Time series analysis.
3.	Regression on time series using tslm function.
4.	Tests of significance - Hypothesis testing.

Expected results 

Following the recession, unemployment hit an all time peak. Our research will drill down on unemployment to reveal impact in the unorganized labor sector. Also, we will observe inflation rates through the lens of CPI. The results will tell the reader about the region of the world that was impacted the most in terms of labor and the least in terms of labor in the unorganized sector. CPI as an indicator will reveal analysis about inflation rates in these regions. The results will be supported through examination of what policy reforms, if any, that affect CPI and labor.


Appendix

Datasets involved
●	World Bank Datasets
1.	GDP, in current US$: 
URL: http://data.worldbank.org/indicator/NY.GDP.MKTP.CD
GDP at purchaser's prices is the sum of gross value added by all resident producers in the economy plus any product taxes and minus any subsidies not included in the value of the products. It is calculated without making deductions for depreciation of fabricated assets or for depletion and degradation of natural resources. 
Data are in current U.S. dollars. Dollar figures for GDP are converted from domestic currencies using single year official exchange rates. For a few countries where the official exchange rate does not reflect the rate effectively applied to actual foreign exchange transactions, an alternative conversion factor is used.
2.	Manufacturing, value added (% of GDP): 
URL: http://data.worldbank.org/indicator/NV.IND.MANF.ZS
Manufacturing refers to industries belonging to ISIC divisions 15-37. Value added is the net output of a sector after adding up all outputs and subtracting intermediate inputs. It is calculated without making deductions for depreciation of fabricated assets or depletion and degradation of natural resources. The origin of value added is determined by the International Standard Industrial Classification (ISIC), revision 3. Note: For VAB countries, gross value added at factor cost is used as the denominator.
3.	Minimum wage data:
URL: http://stats.oecd.org/Index.aspx?DataSetCode=RMW
Real hourly and annual minimum wages are statutory minimum wages converted into a common hourly and annual pay period for the 25 countries for which they are available. The resulting estimates are deflated by national Consumer Price Indices (CPI). The data are then converted into a common currency unit using either US $ current exchange rates or US $ Purchasing Power Parities (PPPs) for private consumption expenditures.
Real hourly and annual minimum wages are calculated first by deflating the series using the consumer price index taking 2014 as the base year.  The series are then converted into a common currency unit (USD) using Purchasing Power Parities (PPPs) for private consumption expenditures in 2014.

4.	Net Migration: 
URL: http://data.worldbank.org/indicator/SM.POP.NETM
Net migration is the net total of migrants during the period, that is, the total number of immigrants less the annual number of emigrants, including both citizens and noncitizens. Data are five-year estimates.
5.	Personal Remittance Received:
Source: http://data.worldbank.org/indicator/BX.TRF.PWKR.CD.DT
Personal remittances comprise personal transfers and compensation of employees. Personal transfers consist of all current transfers in cash or in kind made or received by resident households to or from nonresident households. Personal transfers thus include all current transfers between resident and nonresident individuals. Compensation of employees refers to the income of border, seasonal, and other short-term workers who are employed in an economy where they are not resident and of residents employed by nonresident entities. Data are the sum of two items defined in the sixth edition of the IMF's Balance of Payments Manual: personal transfers and compensation of employees. Data are in current U.S. dollars.
6.	Unemployment, total (% of total labor force) (modeled ILO estimate)
Source: http://data.worldbank.org/indicator/SL.UEM.TOTL.ZS
Unemployment refers to the share of the labor force that is without work but available for and seeking employment.
7.	Consumer Price Index: 
Source: http://data.worldbank.org/indicator/FP.CPI.TOTL
Consumer price index reflects changes in the cost to the average consumer of acquiring a basket of goods and services that may be fixed or changed at specified intervals, such as yearly. The Laspeyres formula is generally used. Data are period averages.

●	ILO Datasets:
1.	Occupational Injuries: 
This data has indicators related to fatal and non-fatal occupational injuries. An occupational injury is defined as any personal injury, disease or death resulting from an occupational accident.
http://www.ilo.org/ilostat/faces/oracle/webcenter/portalapp/pagehierarchy/Page3.jspx?MBI_ID=23&_afrLoop=7015786328999&_afrWindowMode=0&_afrWindowId=cdqgs0lv5_1#!%40%40%3F_afrWindowId%3Dcdqgs0lv5_1%26_afrLoop%3D7015786328999%26MBI_ID%3D23%26_afrWindowMode%3D0%26_adf.ctrl-state%3Dcdqgs0lv5_50
2.	Unorganized labor: 
Share of informal employment in total employment by sex, rural/urban, agriculture/non-agriculture (%)	 
http://www.ilo.org/ilostat/faces/oracle/webcenter/portalapp/pagehierarchy/Page27.jspx?subject=EMP&indicator=IFL_XIEM_SEX_GEO_ECO_RT&datasetCode=A&collectionCode=YI&_afrLoop=7630329212533&_afrWindowMode=0&_afrWindowId=null#!%40%40%3Findicator%3DIFL_XIEM_SEX_GEO_ECO_RT%26_afrWindowId%3Dnull%26subject%3DEMP%26_afrLoop%3D7630329212533%26datasetCode%3DA%26collectionCode%3DYI%26_afrWindowMode%3D0%26_adf.ctrl-state%3Dcdqgs0lv5_228

References

Marshall, John. (2009.) The financial crisis inthe US: key events, causes and responses. House of Commons Library.  Retrieved 2/8/2017 from http://www.voltairenet.org/IMG/pdf/US_Financial_Crisis.pdf
