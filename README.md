#  Recommended System Project

## Introduction

This repository contains code and documentation related to the kasbino Recommended System Project. The primary objective of this project was to optimize the arrangement of products shown to users, with a focus on ensuring that users are more likely to click on the first products presented to them. Additionally, the project had to address the "cold start" assumption, which meant that user search history couldn't be relied upon.

## Spell Checker


One of the key challenges we faced during the competition was dealing with query searches that contained spelling mistakes. Accurate matching was crucial for improving the relevance of search results. To address this challenge, we designed and implemented a spell checker. This spell checker played a vital role in enhancing the accuracy of search results by identifying and suggesting corrections for misspelled search queries.

### Data Processing Optimization


Processing a large amount of data within an optimized timeframe was another significant challenge. We focused on developing a suitable data processing topology and refining our code to reduce processing time. Despite facing some data processing tasks that took as long as 49 hours, we continuously worked on improving the efficiency of our code.
## Limitations

While we made significant progress in the development of the recommended system, including the integration of a spell checker, time constraints limited our ability to achieve optimal results in the ANN modeling section of the project. Due to the inherent bias in the data, the results of this algorithm may be lower than expected. Nevertheless, our approach presents novel methods for optimizing product arrangements on websites.

## Conclusion


"Our primary objective was to predict the click-through rate (CTR), which represents the proportion of clicks to the number of times a product was displayed in search results. This analysis was especially crucial for popular items, as they typically received more clicks. Subsequently, we utilized this CTR data to estimate ratios for less popular products, which inherently had lower display rates due to bias. Our approach was based on the understanding that user decisions to click on a product are often influenced by its image and associated cost. To achieve this, we harnessed the power of an artificial neural network (ANN) system. This innovative methodology effectively mitigated the bias issues observed in earlier algorithms, where the preferences for clicked products directly impacted the final outcomes."


