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


We observe that the number of drug realated crimes have decrease most years since 2003. From 2003 to 2024 number of drug related crimes have decreased by 70.8 %, compared to to total crimes which have just decreased by 31.8%.

The strongest decline was seen between 2008 and 2012, amounting for more then 50% decline. This could be attributed to aftermath of the financial crisis, where police had to dead with budget cuts and wherefore focused more on violent crimes. Furthermore there was also policitcal winds wanting to chagne the drug policy from the hard "war on drugs" approch to a more harm reduction way, which could have eased the rate.

Furthermore, cannabis was legalized in the state of California efficently in 2018, which could have explain the continued decline afterwards.

From 2020 to 2021, drug-related incidents dropped, likely due to COVID lockdowns, less public activity, and reduced police reporting.  

The fentanyl and homelessness crises started around 2018–2019, increasing overdoses but not necessarily arrests, as fentanyl is easier to hide.  

The overall decline likely reflects changes in policing, drug use patterns, and social conditions—not just less drug use.

## Visualization 2: Heatmap of Drug Crimes by Year

<div>
    <iframe src="images/drug_narcotic_heatmap_by_year.html" width="100%" height="600px"></iframe>
</div>

*Figure 2: A heatmap illustrating the geographical distribution of drug-related crimes across San Francisco per year. The heatmap provides a clear visualization of the areas most impacted by narcotic offenses, which are notably concentrated in certain neighborhoods like Downtown San Fransisco*


The heatmap shows clear patterns: over the years, drug-related crimes have become more concentrated in downtown San Francisco. This likely happens because:

– Police focus: Law enforcement puts more resources into downtown areas like the Tenderloin, where drug activity is more visible. This leads to more reports and arrests there, and fewer in other parts of the city.

– Homelessness: As housing gets more expensive, more people without stable housing end up in downtown areas, where services and shelters are available. Many of them use drugs, which increases activity in those neighborhoods.

– Gentrification: Rising housing prices and living costs can lead to gentrification. In areas where this happens and homelessness is less visible, drug-related crimes may decrease. But this can also push more drug activity into downtown, making the concentration even stronger.


## Visualization 3: Interactive Bokeh Visualization

<div style="display: flex; justify-content: center;">
  <iframe 
    src="/images/myplot.html"
    style="width: 90vw; max-width: 1000px; height: 800px; border: none;"
    loading="lazy">
  </iframe>
</div>


## Conclusion

The analysis of drug-related crimes in San Francisco from 2003 to 2024 reveals a complex story shaped by various interconnected factors. The fluctuations in crime data align with significant policy changes, including the legalization of marijuana in California and the increasing prevalence of fentanyl. These trends suggest that drug-related crimes cannot be understood in isolation, but rather as part of a larger socio-political context, where drug legalization, homelessness, and the opioid crisis all play a critical role.

As policymakers and community leaders consider future strategies, it’s essential to understand these nuances. While drug policy changes have led to shifts in certain types of crime, they have not resolved the broader issues surrounding substance abuse, mental health, and homelessness. A more integrated approach that combines enforcement with harm reduction, access to mental health services, and support for the homeless is critical to addressing these challenges comprehensively.

## References

- [San Francisco Crime Data](https://data.sfgov.org/Public-Safety/Police-Department-Incident-Reports-2018-to-Present/2e3c-8j8g)
- [Local News on Drug Policies](https://www.sfchronicle.com/news/article/San-Francisco-drug-policy-changes-2023-12345678)
