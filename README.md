# Coding-Challenge---Athinia
This repository shows the analysis of challenge given by Athinia


# 2021 Coding Challenge: Data Engineer

```
COVID-19 is a respiratory disease caused by SARS-CoV-2, a new coronavirus discovered in 2019.
Many of the pre-existing conditions that increase the risk of hospitalization in those with COVID-19 are
the same diseases that are affected by long-term exposure to air pollution.
Please investigate whether long-term average exposure to low air quality environments is associated
with an increased risk of COVID-19 hospitalization in the United States.
```
## Data

```
The data is hosted in a publicly accessible S3 bucket (no AWS credentials required). You can also
access the data through the official data sources linked below.
```
### Air Quality Index (AQI)

```
Time frame: 1980 - 2021
Records: 11,570,
File size: 36,762,558 bytes (943,967,046 bytes uncompressed)
Number of files : 42
Location: s3://emd-coding-challenge/covid-19-
aqi/aqi/daily_aqi_by_county_1980.csv.bz2 to s3://emd-coding-challenge/covid-19-
aqi/aqi/daily_aqi_by_county_2021.csv.bz
```
### COVID-19 Case Surveillance Public Use Data with Geography

```
Time frame: 2020-01-01 to 2021-11-
Records: 37,532,
File size: 109,903,673 bytes (5,304,693,020 bytes uncompressed)
Location: s3://emd-coding-challenge/covid-19-aqi/covid19/cases.csv.bz
```
## Questions

```
Did the lockdown result in a noticable improvement in air quality? Most notably in what regions?
Is there a correlation between Air Quality Index (AQI) and COVID-19 hospitalization rate?
Are there any confounding factors you should control for?
How would you present the results visually? How do you label your axes?
How did you treat missing data?
```
## Success Criteria

```
Every step of the analysis is documented
Cite any additional data sources you pulled in to answer the questions
```

2/13/23, 2:33 PM 2021 Coding Challenge: Software Engineer

https://emd-coding-challenge.s3.us-east-2.amazonaws.com/covid-19-aqi/ 2 / 2

```
Support results with labeled facts and figures
```
## Bonus Points

```
Provide solution as an R or Jupyter Notebook
Use a charting library such as Plotly or Seaborn
```

