# Customer Segmentation Analysis for Irish Furniture Chain
[View Presentation](https://customer-segmentation-fo-4ozzy47.gamma.site/)

## Project Overview
This analysis develops customer segmentation for an Irish furniture retailer using machine learning techniques. The project analyzed purchasing patterns, living situations, and customer interests to identify distinct customer segments and provide actionable marketing recommendations.

### Business Context
- Analysis of customer base using 2021 data
- Focus on furniture and garden product sales
- Integration of survey data and property information
- Goal to enable targeted marketing strategies

## Data Sources

### Customer Dataset (10,000 records)
- Customer identification data 
- Annual purchase amounts
- Property details (apartment/house size, garden size, pool ownership)
- Spending breakdown between furniture and garden products

### Marketing Dataset (30,000 surveys)
- Survey responses from 9,508 unique customers
- Average 3.16 surveys per customer
- Interest indicators for garden, pool, and balcony products
- Survey dates and response patterns

## Methodology

### Data Preprocessing
1. Handled missing values (15-20% in property data)
2. Corrected invalid entries (negative values)
3. Feature engineering and scaling
4. Dataset integration via left merge

### Feature Selection
- Total spending patterns
- Garden spending ratio
- Property characteristics
- Customer interest metrics
- Survey participation rates

### Modeling Approach
Tested multiple clustering algorithms:
- K-means clustering
- Hierarchical clustering
- DBSCAN

Selected K-means based on:
- Strong clustering tendency (Hopkins statistic: 0.898)
- Balanced cluster sizes
- Business interpretability
- Model stability

## Results

### Identified Segments

1. Luxury Home Spenders (38%)
   - Highest total spending (+0.99σ)
   - Focus on premium furniture
   - Moderate garden ratio

2. Garden Enthusiasts (40%)
   - Highest garden spending ratio (+1.05σ)
   - Largest properties (+0.59σ)
   - Garden-focused investments

3. Basic Needs (21%)
   - Lowest total spending (-0.87σ)
   - Minimal garden space (-1.37σ)
   - Value-oriented approach

### Validation Metrics
- Silhouette score: 0.173
- Calinski-Harabasz score: 1938.571
- Davies-Bouldin score: 1.781

## Implementation Recommendations

### Marketing Tactics
- Integrate segments into CRM
- Develop segment-specific landing pages
- Implement omnichannel marketing
- Track segment-specific conversion rates

### Data Collection Needs
- Demographics (age, income, household)
- Online behavior tracking
- Store visit patterns
- External data integration

### Testing & Refinement
- A/B testing of promotions
- Monitor key performance metrics
- Regular model updates (6-12 months)
- Continuous validation

## Technical Details

### Tools & Libraries Used
- Python 3.x
- Pandas for data manipulation
- Scikit-learn for modeling
- Seaborn/Matplotlib for visualization

### Code Structure
- Data preprocessing pipeline
- Feature engineering workflow
- Model selection framework
- Validation suite

## Future Improvements
1. Additional data collection
2. Model refinement opportunities
3. Automated personalization
4. Enhanced feature engineering

## Project Presentation
Full presentation available at: [Customer Segmentation Analysis](https://customer-segmentation-fo-4ozzy47.gamma.site/)

## Contact
Author: Ursina Sanderink
---
Note: This is a data science project focused on business value creation through customer understanding and targeted marketing strategies.
