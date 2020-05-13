# COVID-19 Data Repository by InsightsQuotient at UST Global
IQ team is curating the different publicly available datasets and making it available through dashboards and APIs. Below are the different considerations and actions, we applied to curate the data.

**Visual Dashboards:**  
https://covid19live.insightsquotient.com/#/dashboard
https://senze.insightsquotient.com

## Data Sources
1. Global case data from [JHU CSSE data](https://github.com/CSSEGISandData/COVID-19)
    - The data source is updated 3 times a day to catch up with any updates during the day.
2. US State & county level data from [The New York Times](https://github.com/nytimes/covid-19-data)
    - The data source is updated 3 times a day to catch up with any updates during the day.

## Data Quality Observations
1. Global data and US state & county data is refreshed at different times and different sources. Therefore, there is always a discrepancy in data for US in Global and US specific dashboard.
2. For few countries, the **_recovery data is not provided for each region_**. Subsequently the derived data like mortality and survival rates are not presented for these countries. The countries are:
    - **Countries:** _United Kingdom, Netherlands, France, Tajikistan_
3. Data corrections are reported as available and adjusted in source data. For example, if cumulative number of cases (in time series data) is lower than yesterday for some adjustment, it may show as -ve for a day.

## Contact Us
If you have questions about the data or licensing conditions, please [contact us](https://www.insightsquotient.com/contact). 

## Terms of Use
1. This website and its contents herein, including all data, mapping, and analysis (“Website”), copyright 2020 UST Global Inc. ("Company"), all rights reserved, is provided solely for commercial, public health, educational, and academic research purposes. You should not rely on this Website for medical advice or guidance.
2. For use of the Website by commercial parties and/or in commerce or attribution, please [contact us](https://www.insightsquotient.com/contact). 
3. The Website relies upon publicly available data from multiple sources that do not always agree. The Company hereby disclaims any and all representations and warranties with respect to the Website, including accuracy, fitness for use, reliability, completeness, and non-infringement of third party rights.
4. These terms and conditions are subject to change. Your use of the Website constitutes your acceptance of these terms and conditions and any future modifications thereof.
