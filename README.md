# Airbnb Data Analysis: Berlin vs. Munich

## Overview
This project analyzes Airbnb listings in Berlin and Munich, comparing prices, host types, room availability, and language use. The goal is to uncover trends in Airbnb usage across both cities using data visualization and geospatial analysis.

## Key Features
- Data Cleaning & Preprocessing
- Handling missing values, standardizing formats, and enriching data with host details.

### Exploratory Data Analysis (EDA)
- Price distribution by city, room type, and host type.
- Seasonal pricing trends and booking availability over time.
  
### Natural Language Processing (NLP)
- Host gender classification based on name analysis.
- Language detection and translation of German listing names.
- Word frequency analysis of listing names in English and German.
- Word cloud visualization of common listing descriptions per city.

### Folium Maps
- Choropleths of average price, English listings, and host type distributions.
- Side-by-side choropleth comparisons of key metrics between Berlin and Munich.

## Results & Insights
### Pricing
- Munich is more expensive than Berlin, with Altstadt-Lehel and Ludwigsvorstadt-Isarvorstadt showing the highest prices.
- Berlin’s highest-priced listings are in Mitte and Charlottenburg-Wilmersdorf, but still lower than Munich’s top areas.
- Multi-Listings (by the same host) does not affect pricing within neighbourghoods.
### Room Types
- Most listings are entire homes in both Berlin and Munich, followed by private rooms.
- The price distribution is greater for shared and hotel rooms in Berlin compared to Munich.
### Host Characteristics
- In both citires, commercal hosts charge the highest.
- In Munich, female hosts charge comparably less to male, family and commercial hosts, while in Berlin, female, male and family hosts charge approximately the same amount.
### Listing Names & Descriptions
- English-speaking listings are more prevalent in central areas and are associated with higher prices.
- Listings in Berlin commonly advertise their BnBs with words associated with casual and modern living, like "urban", "comfortable" or "friendly".
- Listings in Munich commonly advertise their BnBs with words associated with high-end living, like "concierge", "deluxe" or "gym".

## Data Sources & Attribution
- Data from Inside Airbnb
- Data accessed on 28/02/2025
- Note: The dataset itself is not republished, in compliance with Inside Airbnb’s policies.
