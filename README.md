# Bat Pollinator Migration Analysis

Geospatial analysis of lesser long-nosed bat (*Leptonycteris yerbabuenae*) migration 
patterns, built from live GBIF occurrence data.

## Overview
This project pulls real-time species sighting data from the GBIF API and analyzes 
migratory patterns for a key agave-pollinating bat species — connecting conservation 
data to agricultural relevance (this species pollinates agave used in tequila/mezcal 
production).

## What's inside
- **Data source:** GBIF Occurrence API (295 cleaned records, 2017–2026)
- **Geospatial map:** Interactive map (folium) plotting the migratory corridor from 
  Arizona through Mexico into Guatemala/Nicaragua
- **Seasonal analysis:** Monthly sighting patterns showing two migration peaks 
  (April, August–September)
- **Yearly trend:** Sighting counts by year (2017–2026)
- **Regional breakdown:** Sightings by country and US state

## Key findings
- Sightings trace a clear north-south migratory corridor consistent with this 
  species' known "nectar corridor" behavior
- Two seasonal peaks align with spring northward migration and late-summer 
  maternity colony activity
- Mexico and the US account for nearly all sightings (153 and 138 respectively); 
  within the US, Arizona alone accounts for 136 of 138 records

## Tools
Python, pandas, folium, matplotlib, GBIF API

## Notebook
[GEOSBatPollinators.ipynb](./GEOSBatPollinators.ipynb)

## Caveats
GBIF data is citizen-science/observational — sighting volume reflects reporting 
effort as much as true population trends.
