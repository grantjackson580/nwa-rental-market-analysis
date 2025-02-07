# Northwest Arkansas Rental Market Analysis

## Overview
This project analyzes the Northwest Arkansas rental housing market using microeconomic principles to understand pricing dynamics and market efficiency. The analysis focuses on 2,000 rental property observations to investigate price relationships with property characteristics, location effects, and seasonal patterns.

## Key Findings
- Strong evidence of location-based pricing variations between cities
- Significant economies of scale in property size
- Independent value attribution to bedroom count
- Modest seasonal effects in rental pricing

## Data
The analysis uses a dataset of 2,000 rental property observations from Washington County, including:
- Property characteristics (size, bedrooms, location)
- Pricing information (list price, deposit)
- Temporal data (availability dates)
- Geographic indicators

## Methods
### Data Cleaning
- Price standardization
- Square footage normalization
- Date standardization
- Missing value treatment
- Feature engineering

### Analysis Techniques
- Linear regression for size-price relationships
- ANOVA for geographic variation
- Time series analysis for seasonality
- Multiple regression for bedroom value analysis

## Key Results
1. Size-Price Relationship
   - Negative correlation (coef = -0.0002, p < 0.001)
   - R² = 0.10
   - Supports economies of scale theory

2. Geographic Variation
   - Significant differences (F = 10.12, p < 0.0001)
   - Higher prices in Bentonville/Fayetteville
   - Clear location-based patterns

3. Seasonal Effects
   - Modest impact (F = 2.79, p = 0.0389)
   - November peak identified
   - 3-5% seasonal variation

4. Bedroom Value
   - $61.36 premium per bedroom (p < 0.001)
   - $0.56 per sq ft base effect
   - Model R² = 0.413

## Setup Instructions

### Prerequisites
- Python 3.8+
- pip package manager

### Installation & Usage
```bash
git clone https://github.com/grantjackson580/nwa-rental-market-analysis.git
cd nwa-rental-market-analysis
pip install -r requirements.txt
```

## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments
- Northwest Arkansas Regional Planning Commission
- Washington County Property Records Database
- Local real estate professionals who provided insights
