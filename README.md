# Lab 2 — Web Data Collection & Visualization 

# YouTube Ice Cream Analysis

## Topic
This project explores how ice cream-related content is discussed on YouTube using three search terms:
- ice cream recipe
- best ice cream shops
- ice cream business

## Motivation
Ice cream represents an intersection of food culture, local businesses, and online entrepreneurship.  
By comparing these search terms, this project examines how different communities talk about ice cream on YouTube.

## Data Collection
Data was collected using a Selenium-based YouTube crawler executed in Google Colab.  
For each search term, multiple pages of video results were scraped, capturing metadata such as:
- video title
- channel username
- view count
- upload time

Due to recent changes in YouTube’s interface and dynamic content loading, **video descriptions were inconsistently available** across results.  
To maintain consistency and reliability, **video titles were used as the primary text source** for analysis.

## Word Cloud Analysis
Word clouds were generated using video titles from each search term.  
However, the resulting word clouds were dominated by channel names and creator identifiers rather than descriptive content.

This outcome reflects the structure of YouTube search results, where video titles frequently emphasize branding, creator identity, or channel recognition rather than detailed descriptions of content. As a result, the word clouds primarily visualize **who is producing ice cream–related content**, rather than what is being discussed in depth.

## Reflection
An unexpected but informative result was the dominance of creator and brand names in the word clouds. This suggests that ice cream–related content on YouTube is strongly driven by individual creators and established channels, highlighting the importance of branding and identity within food-related media.

Future research could improve this analysis by integrating the YouTube Data API to reliably retrieve video descriptions, comments, or transcripts, which would allow for a more content-focused semantic analysis.


## CSV Downloads
- Ice Cream Recipes:  
  https://github.com/vamikag/geoglab02/blob/main/ice_cream_recipe.csv

- Best Ice Cream Shops:  
  https://github.com/vamikag/geoglab02/blob/main/best_ice_cream_shops.csv

- Ice Cream Business:  
 https://github.com/vamikag/geoglab02/blob/main/ice_cream_business.csv

## Word Clouds
<img width="1159" height="928" alt="image" src="https://github.com/user-attachments/assets/290a57a2-1970-40d6-b282-01cca1a08bd6" />
<img width="1141" height="943" alt="image" src="https://github.com/user-attachments/assets/60f6e20d-5a07-4240-97a4-58f4c80a96ce" />




