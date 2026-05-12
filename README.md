# Airbnb Data Analysis

A comprehensive exploratory data analysis (EDA) of Airbnb listings data, focusing on pricing patterns, room type distributions, geographic trends, and customer review insights.

## 📋 Project Overview

This project analyzes a large-scale Airbnb dataset containing **102,599 listings** with **26 attributes** to uncover key insights about the short-term rental market. The analysis explores distribution patterns, relationships between variables, and trends across different dimensions.

## 🎯 Research Questions

This analysis addresses the following key questions:

1. **What is the distribution of listing prices?**
   - Understanding price ranges and outliers in the market

2. **How are different room types distributed?**
   - Analyzing the prevalence of entire homes, private rooms, and shared spaces

3. **How are listings distributed across neighborhoods?**
   - Geographic patterns and neighborhood-level trends

4. **What is the relationship between price and room type?**
   - Price variations across different room categories

5. **How has the number of reviews changed over time?**
   - Temporal patterns in customer engagement and listing activity

## 📊 Dataset Information

### Dataset Statistics
- **Total Listings:** 102,599
- **Total Features:** 26 columns
- **Data Types:** 
  - Numeric: 11 columns (int64, float64)
  - Categorical: 15 columns (object)

### Key Features

| Feature | Description |
|---------|-------------|
| `id` | Unique listing identifier |
| `NAME` | Listing title/name |
| `host id` | Host identifier |
| `host_identity_verified` | Verification status of host |
| `host name` | Name of the host |
| `neighbourhood group` | Borough/main area |
| `neighbourhood` | Specific neighborhood |
| `lat`, `long` | Geographic coordinates |
| `room type` | Type of accommodation (Entire home, Private room, Shared room) |
| `price` | Listing price |
| `service fee` | Service fee charged |
| `minimum nights` | Minimum night stay requirement |
| `number of reviews` | Total number of reviews |
| `last review` | Date of last review |
| `reviews per month` | Review frequency |
| `review rate number` | Average rating (1-5) |
| `calculated host listings count` | Number of listings per host |
| `availability 365` | Days available in 365-day period |
| `Construction year` | Year the property was built |

### Data Quality

**Missing Values:**
- `house_rules`: 52,131 missing (50.8%) - *Dropped*
- `license`: 102,597 missing (99.99%) - *Dropped*
- `last review`: 15,893 missing (15.5%)
- `reviews per month`: 15,879 missing (15.5%)
- Other columns: < 1% missing values

## 🛠️ Technologies & Libraries

- **Language:** Python 3
- **Environment:** Google Colab
- **Libraries:**
  - `pandas` - Data manipulation and analysis
  - `numpy` - Numerical computations
  - `matplotlib` - Static data visualization
  - `seaborn` - Statistical data visualization

## 📈 Analysis Performed

### Data Exploration
- Dataset shape and structure analysis
- Data type identification
- Summary statistics (mean, median, standard deviation, quartiles)
- Missing value analysis and imputation strategy

### Data Cleaning
- Removal of columns with excessive missing values (`house_rules`, `license`)
- Identification of data quality issues
- Handling of outliers and anomalies

### Visualization & Insights
The notebook includes visualizations for:
- Price distribution analysis
- Room type frequency distributions
- Geographic neighborhood patterns
- Price vs. room type relationships
- Temporal trends in reviews and availability

## 🚀 Getting Started

### Prerequisites
- Python 3.x
- Jupyter Notebook or Google Colab
- Required libraries: pandas, numpy, matplotlib, seaborn

### Installation

```bash
# Clone the repository
git clone https://github.com/soumensen411/Airbnb-Data-Analysis.git

# Navigate to project directory
cd Airbnb-Data-Analysis

# Install required packages
pip install pandas numpy matplotlib seaborn

```

### Running the Analysis

1. **Using Google Colab:**
   - Open the Jupyter notebook file `Airbnb_data_analysis.ipynb` in Google Colab
   - Mount your Google Drive to access the data file
   - Run all cells sequentially

2. **Using Local Jupyter:**
   - Start Jupyter Notebook
   - Open `Airbnb_data_analysis.ipynb`
   - Ensure the data file path is correctly configured
   - Execute cells from top to bottom

## 📁 Project Structure

```
Airbnb-Data-Analysis/
├── README.md                          # Project documentation
├── Airbnb_data_analysis.ipynb         # Main analysis notebook
└── compressed_data.csv                # Dataset (if available locally)
```

## 🔍 Key Findings

The analysis reveals patterns in:
- **Price Distribution:** Understanding market pricing across different segments
- **Room Type Distribution:** Market composition of different accommodation types
- **Geographic Patterns:** Concentration of listings across neighborhoods
- **Price Elasticity:** How room types influence pricing
- **Review Trends:** Customer engagement and listing popularity over time

## 📝 Data Processing Steps

1. Load data from CSV file
2. Perform exploratory data analysis (EDA)
3. Identify and handle missing values
4. Remove irrelevant columns
5. Generate summary statistics
6. Create visualizations
7. Derive insights and conclusions

## 🎓 Learning Outcomes

This project demonstrates:
- Data cleaning and preprocessing techniques
- Exploratory data analysis best practices
- Data visualization principles
- Statistical analysis methods
- Business intelligence insights from real-world data

##
