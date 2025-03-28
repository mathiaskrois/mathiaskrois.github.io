---
layout: home
title: "Analyzing Drug-Related Crimes in San Francisco"
---

# Understanding Drug-Related Crimes in San Francisco

San Francisco is a city known for its unique blend of innovation, culture and inclusivity, and has long struggled with deep-seated social problems. One of the most pressing and intricate of these issues is drug-related crime.

In the last two decades, we've seen a complex dance between rising housing prices and living costs, policy shifts, like the legalization of certain drugs, the fentanyl crisis, and the wider social and economic environment. This study delves into the patterns of drug-related offenses over the period 2023-2024, offering insights into the connections between these elements.

## Overview of the Dataset

We combined two datasets to study drug-related crimes in San Francisco from 2003 to the present. The datasets categorize crimes into categories like for example assults, trafficking, and drug / narcotic offenses. Since the datasets categorized crimes differently, we matched them to ensure consistency. We also excluded the year 2025 since it's incomplete.

## Visualization 1: Time Series of Drug Crimes

![Drug Crimes Over Time](images/drug_narcotic_crimes_per_year.png)

*Figure 1: A time series analysis of drug-related vs total crimes in San Francisco from 2003 to 2024. In the year 2003 the total number of crimes recorded were 114 541, while the number of recorded drug crimes was 5 775. The data reveals significant fluctuations, with notable peaks and valleys corresponding to policy changes, economic conditions, and societal shifts.*


### Decline in Drug-Related Crimes

We observe a significant decrease in drug-related crimes over the years since 2003. Between 2003 and 2024, drug-related crimes have decreased by **70.8%**, compared to a **31.8%** decrease in total crimes.

#### Period of Strongest Decline

The most pronounced decline occurred between 2008 and 2012, with a **50%** decrease. This could be attributed to the aftermath of the financial crisis, which led to budget cuts for police departments, causing them to focus more on violent crimes. Additionally, there was a shift in political winds towards a more harm reduction-oriented drug policy, which may have contributed to the decline.

#### Impact of Cannabis Legalization

The legalization of cannabis in California in 2018 likely contributed to the continued decline in drug-related crimes.

#### COVID-19 Pandemic and Its Effects

From 2020 to 2021, drug-related incidents dropped, likely due to COVID lockdowns, reduced public activity, and decreased police reporting.

#### Fentanyl and Homelessness Crises

The fentanyl and homelessness crises, which began around 2018-2019, have led to an increase in overdoses but not necessarily arrests, as fentanyl is easier to conceal.

#### Reflections on the Decline

The overall decline in drug-related crimes likely reflects changes in policing strategies, drug use patterns, and social conditions, rather than simply a decrease in drug use.

## Visualization 2: Heatmap of Drug Crimes by Year

<div>
    <iframe src="images/drug_narcotic_heatmap_by_year.html" width="100%" height="600px"></iframe>
</div>

*Figure 2: A heatmap illustrating the geographical distribution of drug-related crimes across San Francisco per year. The heatmap provides a clear visualization of the areas most impacted by narcotic offenses, which are notably concentrated in certain neighborhoods like Downtown San Fransisco*

The heatmap reveals a striking trend: drug-related crimes have become increasingly concentrated in downtown San Francisco over the years, especially the last 10 years. This phenomenon can be attributed to several factors:

### Police Focus
Law enforcement agencies allocate more resources to downtown areas like the Tenderloin, where drug activity is more pronounced. This results in a higher number of reports and arrests in these areas, while other parts of the city see fewer incidents.

### Homelessness
As housing costs continue to rise, individuals without stable housing are more likely to congregate in downtown areas, where essential services and shelters are readily available. Unfortunately, many of these individuals struggle with drug addiction, contributing to the increased drug activity in these neighborhoods.

### Gentrification
The surge in housing prices and living costs can lead to gentrification. In areas where gentrification occurs and homelessness becomes less visible, drug-related crimes might decrease. However, this process can also displace drug activity into downtown areas, further intensifying the concentration of drug-related crimes.


## Visualization 3: Interactive Bokeh Visualization

<div style="display: flex; justify-content: center;">
  <iframe 
    src="/images/crime_coocc_map.html"
    style="width: 90vw; max-width: 1000px; height: 700px; border: none;"
    loading="lazy">
  </iframe>
</div>

*Figure 3: Interactive heatmap showing spatial co-occurrence between DRUG/NARCOTIC incidents and selected focus crimes in San Francisco. Each grid cell (~100 m²) is colored by the number of hours during the week in which both crimes occurred simultaneously at that location. Users can select which crime to compare using the dropdown menu.*

<h3>Spatiotemporal correlation with DRUG/NARCOTIC incidents (presence-based, Pearson r)</h3>
<table>
  <thead>
    <tr>
      <th>Crime Type</th>
      <th>Correlation</th>
    </tr>
  </thead>
  <tbody>
    <tr><td><b>WEAPON LAWS</b></td><td>0.195</td></tr>
    <tr><td><b>ASSAULT</b></td><td>0.176</td></tr>
    <tr><td><b>ROBBERY</b></td><td>0.152</td></tr>
    <tr><td><b>STOLEN PROPERTY</b></td><td>0.140</td></tr>
    <tr><td><b>PROSTITUTION</b></td><td>0.071</td></tr>
    <tr><td><b>VANDALISM</b></td><td>0.069</td></tr>
    <tr><td><b>BURGLARY</b></td><td>0.030</td></tr>
    <tr><td><b>LARCENY/THEFT</b></td><td>0.029</td></tr>
    <tr><td><b>VEHICLE THEFT</b></td><td>0.009</td></tr>
  </tbody>
</table>
The correlation metric quantifies how often DRUG/NARCOTIC incidents and another crime type occur simultaneously across space and time. It is calculated as the Pearson correlation coefficient between two binary presence vectors, each representing whether a given crime was recorded in a specific hour and grid cell. A higher value indicates stronger spatiotemporal alignment between the two crime types.

## Conclusion

The analysis of drug-related crimes in San Francisco from 2003 to 2024 reveals a complex story shaped by various interconnected factors. The fluctuations in crime data align with significant policy changes, including the legalization of marijuana in California and the increasing prevalence of fentanyl. These trends suggest that drug-related crimes cannot be understood in isolation, but rather as part of a larger socio-political context, where drug legalization, homelessness, and the opioid crisis all play a critical role.

As policymakers and community leaders consider future strategies, it’s essential to understand these nuances. While drug policy changes have led to shifts in certain types of crime, they have not resolved the broader issues surrounding substance abuse, mental health, and homelessness. A more integrated approach that combines enforcement with harm reduction, access to mental health services, and support for the homeless is critical to addressing these challenges comprehensively.

## References
- [Website Repository](https://github.com/mathiaskrois/mathiaskrois.github.io)
- [Assignment 2 Code Repository](https://github.com/mathiaskrois/-socialdata2025-MMC-/tree/main/Assignments/A2)
- [San Francisco Crime Data](https://data.sfgov.org/Public-Safety/Police-Department-Incident-Reports-2018-to-Present/2e3c-8j8g)
- [Local News on Drug Policies](https://www.sfchronicle.com/news/article/San-Francisco-drug-policy-changes-2023-12345678)
