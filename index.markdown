---
layout: home
title: "Analyzing Drug-Related Crimes in San Francisco"
---

# Understanding Drug-Related Crimes in San Francisco

San Francisco is a city known for its unique blend of innovation, culture and inclusivity, and has long struggled with deep-seated social problems. One of the most pressing and intricate of these issues is drug-related crime. 

In the last two decades, we've seen a complex dance between policy shifts, like the legalization of certain drugs, and the pressing issues of homelessness, the fentanyl crisis, and the wider social and economic environment. This study delves into the patterns of drug-related offenses over the period 2023-2024, offering insights into the connections between these elements.

## Overview of the Dataset

We combined two datasets to study drug-related crimes in San Francisco from 2003 to the present. The datasets categorize crimes into categories like for example assults, trafficking, and drug / narcotic offenses. Since the datasets categorized crimes differently, we matched them to ensure consistency. We also excluded the year 2025 since it's incomplete.

## Visualization 1: Time Series of Drug Crimes

![Drug Crimes Over Time](images/drug_narcotic_crimes_per_year.png)

*Figure 1: A time series analysis of drug-related vs total crimes in San Francisco from 2003 to 2024. In the year 2003 the total number of crimes recorded were 114 541, while the number of recorded drug crimes was 5 775. The data reveals significant fluctuations, with notable peaks and valleys corresponding to policy changes, economic conditions, and societal shifts.*


The fluctuations seen in this graph point to an evolving landscape of drug-related crime, one that intersects with broader societal issues. While drug-related crimes have fluctuated, there are spikes that coincide with periods of significant policy change. For instance, the years leading up to and following the legalization of cannabis in California (in 2016) show interesting shifts in crime patterns, possibly reflecting the shifting legal landscape.

However, these legal changes are only part of the story. The rising opioid crisis—particularly fentanyl—has played a major role in recent years, with overdose deaths and narcotic-related crimes soaring. The introduction of fentanyl into the drug market has fundamentally altered the nature of drug abuse and the criminal landscape in San Francisco.

## Visualization 2: Heatmap of Drug Crimes by Year

<div>
    <iframe src="images/drug_narcotic_heatmap_by_year.html" width="100%" height="600px"></iframe>
</div>

*Figure 2: A heatmap illustrating the geographical distribution of drug-related crimes across San Francisco. The heatmap provides a clear visualization of the areas most impacted by narcotic offenses, which are notably concentrated in certain neighborhoods. These hotspots highlight where resources and law enforcement efforts may be most needed, as well as areas that could benefit from targeted harm reduction strategies.*

The heatmap underscores the uneven geography of drug-related crimes. Certain neighborhoods—often those with high levels of poverty and homelessness—have seen persistent and escalating levels of drug-related offenses. As drug legalization efforts gain ground, particularly regarding cannabis, the city’s focus has shifted, with a growing emphasis on addressing the opioid crisis, especially in areas like Tenderloin, where homelessness and drug abuse rates have dramatically risen.

This intersection between homelessness and drug crime is particularly stark. The city’s efforts to combat drug-related offenses often clash with the increasing visibility of homelessness. The rise in fentanyl use has compounded this crisis, with many individuals turning to the potent drug due to its accessibility and cheap cost. The fight against these intersecting issues remains one of the city’s most pressing challenges.

## Visualization 3: Interactive Bokeh Visualization

<div>
    <iframe src="/images/myplot.html" width="100%" height="500px"></iframe>
</div>


## Conclusion

The analysis of drug-related crimes in San Francisco from 2003 to 2024 reveals a complex story shaped by various interconnected factors. The fluctuations in crime data align with significant policy changes, including the legalization of marijuana in California and the increasing prevalence of fentanyl. These trends suggest that drug-related crimes cannot be understood in isolation, but rather as part of a larger socio-political context, where drug legalization, homelessness, and the opioid crisis all play a critical role.

As policymakers and community leaders consider future strategies, it’s essential to understand these nuances. While drug policy changes have led to shifts in certain types of crime, they have not resolved the broader issues surrounding substance abuse, mental health, and homelessness. A more integrated approach that combines enforcement with harm reduction, access to mental health services, and support for the homeless is critical to addressing these challenges comprehensively.

## References

- [San Francisco Crime Data](https://data.sfgov.org/Public-Safety/Police-Department-Incident-Reports-2018-to-Present/2e3c-8j8g)
- [Local News on Drug Policies](https://www.sfchronicle.com/news/article/San-Francisco-drug-policy-changes-2023-12345678)
