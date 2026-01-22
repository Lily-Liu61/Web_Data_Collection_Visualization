# 📊 YouTube Disaster Discourse Analysis: Tsunami vs. Earthquake

## 1. Research Topic and Search Parameters

This project analyzes how natural disasters are represented on YouTube by comparing search results for two disaster-related keywords: **tsunami** and **earthquake**. These keywords were selected because both represent major geophysical hazards but differ in frequency, visual impact, and media framing.

The data were collected using a Selenium-based web crawler that retrieves publicly available YouTube search results without requiring user login. The following search URLs were used:

- https://www.youtube.com/results?search_query=tsunami  
- https://www.youtube.com/results?search_query=earthquake  

For each keyword, multiple scrolls were performed to load additional search results. The crawler extracted video titles, short descriptions, view counts, upload times, and channel information. The collected results were saved as CSV files and used for subsequent text analysis.

---

## 2. Motivation for the Comparison

Tsunamis and earthquakes are closely related natural disasters, as earthquakes often trigger tsunamis. However, they are perceived and discussed differently in public discourse. This comparison aims to examine whether YouTube content emphasizes different themes, emotions, and informational focuses for these two hazards.

Understanding these differences can provide insights into how disaster risk, severity, and public attention are framed in online video platforms.

---

## 3. Word Cloud Comparison

Word clouds were generated using the combined text from video titles and short descriptions for each search term.

![Earthquake Word Cloud](img/wordcloud-1.png)

![Tsunami Word Cloud](img/wordcloud-2.png)

The tsunami word cloud highlights terms related to coastal environments, large waves, and warning systems, while the earthquake word cloud emphasizes ground shaking, building damage, and emergency response. Despite these differences, both word clouds share common disaster-related terms, reflecting overlapping concerns about human impact and news reporting.

---

## 4. Possible Reasons for Observed Patterns

The observed patterns may be explained by the physical characteristics of the disasters. Tsunamis are visually dramatic and geographically concentrated along coastlines, which may lead to more emphasis on location and imagery. Earthquakes, by contrast, are more frequent and are often described using technical measurements such as magnitude and depth.

Media coverage practices and historical disaster events may also influence the vocabulary used in YouTube content.

---

## 5. Limitations and Future Improvements

This study has several limitations. The data were collected only from YouTube search results, which are influenced by platform algorithms and trending content. Additionally, the analysis relies on word frequency and does not capture sentiment or contextual meaning.

Future research could improve this analysis by:
- Expanding the number of search terms or geographic filters
- Comparing results across multiple social media platforms
- Applying sentiment analysis or topic modeling techniques
- Conducting longitudinal data collection

---

## 6. Unexpected Findings and Observations

One notable observation was the frequent appearance of specific countries, such as Japan, in both datasets. This suggests that past major disasters continue to shape online discourse. Additionally, tsunami-related content appeared more emotionally and visually oriented than earthquake-related content, which tended to be more technical.

---

## 7. Data Access

The datasets used in this project are available for download:

- [Download Earthquake Search Results](https://raw.githubusercontent.com/Lily-Liu61/Web_Data_Collection_Visualization/main/assets/search-result-1.csv)
- [Download Tsunami Search Results](assets/search-result-2.csv)

---
