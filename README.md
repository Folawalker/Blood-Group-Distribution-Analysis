# Blood-Group-Distribution-Analysis
This is an analysis I carried out to explore the distribution of blood groups across the world, variations within continents and regions. And also to explore whether geographic blood type data can support smarter, data-driven decisions in healthcare logistics. This dataset and analysis could be used to guide national blood policies, support emergency preparedness and inform donor recruitment campaigns.
# Table of Content
- Project Overview
- Dataset
- Data Inspection
- Data Cleaning
- Exploratory Data Analysis
  - Overview of the Data
    - Descriptive Statistics
    - Data Type Verification
    - Checking for Duplicates
  - Descriptive Analysis
    - Distribution Across Countries
    - Distribution Across Continents
    - General Distribution
- Insights
- Contributions

# Project Overview
The main purpose of this analysis is to help determine the most effective advertisement channels after the completion of a campaign. This is supposed to help make more effective targeted ads next time.

# Dataset
- `Country`: Country in view
- `Continent`: Continent where the country is located
- `Population`: Population of country in view
- `O+`: Percentage of the population with O+ blood group
- `A+`: Percentage of the population with A+ blood group
- `B+`: Percentage of the population with B+ blood group
- `AB+`: Percentage of the population with AB+ blood group
- `O-`: Percentage of the population with O- blood group
- `A-`: Percentage of the population with A- blood group
- `B-`: Percentage of the population with B- blood group
- `AB-`: Percentage of the population with AB- blood group
# Data Inspection
Data information was checked using `.info()` function on python and it helped confirm there were no missing values, also confirmed the datatypes, number of rows and columns.

# Data Cleaning
The dataset had been cleaned from excel before importing to python

# Exploratory Data Analysis
## 1. Overview of the Data
### 1. Descriptive Statistics:
Used the `.describe()` function to check the basic statistical distribution of the dataset(mean, median, mode, max and min values, etc..)

### 2. Data Verification:
Checked if the changes I made during the cleaning process from Excel took effect(TRIM, data type, etc..) 

### 3. Checking for Duplicates:
I checked for the presence of duplicates, or rather, the lack thereof.

## 2. Descriptive Analysis
### 1. Distribution Across Countries:
Checked for the distribution of each blood group in various countries and filtered for the top 10 and bottom 10 countries.

### 2. Distribution Across Continents:
Checked for the distribution of the blood groups according to continents.

### 3. General distribution:
Checked the general distribution of the blood groups worldwide.

# Insights
- The O+ blood group was observed to be globally dominant, appearing in 37.32% of the population.

- AB- is on the opposite end of the spectrum from O+, as it is the rarest blood group in the population, appearing in just 0.39%.

- Europe appears to have the highest concentration of Rh- blood groups, leading in all Rh- types except O-, where Australia takes the lead.

- Japan has an unusually high population of A+ blood type, whereas other Asian countries predominantly have B+.

- Countries in the Americas (North and South America) appear to dominate the O+ blood group chart, with 8 out of the top 10 countries from the region. The remaining 2 spots are occupied by African nations. Ecuador tops the chart, with 75% of its population having the O+ blood group. These countries exhibit unusually high percentages for this blood group, as no other blood group dominates a single nation as significantly as O+ does in these countries. The dominance of the O+ blood group in American countries could be down to genetic ancestry, limited genetic mixing and evolutionary selection.

- Countries in Europe appear to dominate the A+ blood group chart, with 9 out of the top 10 countries from the region. The only spot left is occupied by Japan, an Asian nation. Armenia tops the chart, with 46.30% of its population having the A+ blood group. Japan’s population has unique genetic characteristics influenced by both East Asian and indigenous (Jomon) ancestry. The higher frequency of A+ in Japan might be due to founder effects or selective pressures unique to East Asia.

- B+ appears to be the dominant blood group in Asian countries, as they occupy all ten spots in the top 10. This could be due to the historical intermixing within Asia and also due to the fact that B+ is rare in other regions.

- The O− blood group appears to be more evenly distributed across continents compared to other blood groups, which tend to show regional dominance.

- This analysis shows that blood group distribution is not random, it follows geographic, genetic, and historical patterns. This proves that medical systems need to plan blood reserves not just based on population size, but based on blood group prevalence per region.




# Contributions
Contributions are welcome! Please open an issue or submit a pull request for any features, bug fixes, or enhancements.
