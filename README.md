# analysis-engine
A data analysis server for processing and evaluating Twitter user data.

## Purpose
This service analyzes Twitter user data collected by external scrapers to compute various metrics and insights. The analysis engine processes data stored in a database to evaluate account quality and other meaningful metrics.

## Features
- Processes scraped Twitter user data from database
- Computes account quality scores
- Generates user behavior metrics
- Provides analysis results via API endpoints

## Data Flow
1. External scrapers collect Twitter user data
2. Data is stored in database
3. Analysis engine retrieves data for processing
4. Computed metrics are stored and made available via API

## Planned Metrics
- Account Quality Score
  - Account age
  - Follower/Following ratio
  - Tweet frequency
  - Engagement rates
- User Behavior Analysis
  - Posting patterns
  - Content type distribution
  - Interaction patterns
