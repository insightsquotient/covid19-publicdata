# COVID-19 Data Repository by InsightsQuotient at UST Global
IQ team is curating the different publicly available datasets and making it available through dashboards and APIs. Following are the different considerations to curate the data and to visualize the data.

**Visual Dashboards:**  
1. [Primary Dashboard](https://covid19live.insightsquotient.com/#/dashboard)
2. [Dashboard](https://senze.insightsquotient.com) using [Senze](https://www.insightsquotient.com/products)
3. [Dashboard](https://superset.insightsquotient.com/superset/dashboard/COVID-19/?standalone=true) using [Superset](https://superset.incubator.apache.org/index.html)

## Data Sources
1. Global case data from [JHU CSSE data](https://github.com/CSSEGISandData/COVID-19)
    - The data source is updated 3 times a day to catch up with any updates during the day.
2. US State & county level data from [The New York Times](https://github.com/nytimes/covid-19-data)
    - The data source is updated 3 times a day to catch up with any updates during the day.
3. US State-level measures data & Forecasting Model Data [IHME Data](http://www.healthdata.org/covid/data-downloads)
    - The data is updated once a day.
4. CovidActNow Forecasting model [CovidActNow](https://covidactnow.org/resources#csv-files)
    - The data is updated once a day.
5. Country-wise Government Measures Dataset[ACAPS COVID-19](https://data.humdata.org/dataset/acaps-covid19-government-measures-dataset)
    - The data is updated once a day.


## Data Quality Observations
1. Global data and US state & county data is refreshed at different times and different sources. Therefore, there is always a discrepancy in data for US in Global and US specific dashboard.
2. For few countries, the **_recovery data is not provided for each region_**. Subsequently the percentage and rank are not derived for these countries. The countries are:
    - **Countries:** _United Kingdom, Netherlands_
3. Data corrections are reported as available and adjusted in source data. For example, if cumulative number of cases (in time series data) is lower than yesterday for some adjustment, it may show as -ve for a day. Though in isolation the data for a day may seem non-sensical but the aggregated or cumulative number will be right.

## Contact Us
If you have questions about the data or licensing conditions, please [contact us](https://www.insightsquotient.com/contact). 

## Terms of Use
1. This website and its contents herein, including all data, mapping, and analysis (“Website”), copyright 2020 UST Global Inc. ("Company"), all rights reserved, is provided solely for public health, educational, and academic research purposes. You should not rely on this Website for medical advice or guidance.
2. For use of the Website by commercial parties and/or in commerce or attribution, please [contact us](https://www.insightsquotient.com/contact). 
3. The Website relies upon publicly available data from multiple sources that do not always agree. The Company hereby disclaims any and all representations and warranties with respect to the Website, including accuracy, fitness for use, reliability, completeness, and non-infringement of third party rights.
4. These terms and conditions are subject to change. Your use of the Website constitutes your acceptance of these terms and conditions and any future modifications thereof.
