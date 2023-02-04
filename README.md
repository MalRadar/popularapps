## The App Popularity Dataset

## Overview

Multinational app stores such as Apple’s iOS App Store host millions of apps, and have a presence in over 150 countries. App developers distribute their apps globally through these stores. This offers the opportunity for a wealth of potential new customers but also involves uncertainty as consumers’ responses may differ across countries. This is reflected in the ranking of apps. When distributed across multiple countries/regions, their popularity (i.e., ranking) can vary significantly across regions. To characterize the app popularity across regions, we harvest a comprehensive dataset of popular apps. We collect data from the iOS App Store, the sole official app marketplace for iOS apps. We monitor the daily app ranking list (i.e., popular apps) for 154 regions throughout a year. After data pre-processing, we obtain a total of 382,335 unique apps across 23 categories. To the best of our knowledge, this is the largest dataset on app popularity in our research community. 

## Data Accessibility

We are happy to share our app popularity dataset. Our dataset is available on [Zenodo](https://zenodo.org/record/7601608#.Y95icOxBy3I) (due to the data size limitation of Github). 

The dataset includes two kinds of files:

(1) Ranking list
This type of files start with "ranking_". They record the chart of popular apps in each market for a year, stored separately by region.

(2) App meta-data
This type of files start with "info_". They record the meta-data for each popular app that is included in the dataset, stored by geographical groups.

We give examples of each kind of file in this repo (ranking-example.csv and info-example.csv).

## Additional Findings

In addition to the results presented in the paper, we also give some supplementary findings in this repo.
