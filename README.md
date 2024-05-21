# Understanding-Flight-Delays

## Goals
1. Investigate the underlying factors contributing to flight delays:
   - Analyze various parameters such as wind speed and direction across a wide range of airports.
2. Conduct an in-depth analysis of arrival and departure patterns:
   - Examine how different aircraft carriers' arrival and departure patterns might impact carrier delay times.
3. Explore correlations between weather-related delays and cascading delays:\
   - Determine if there is any relationship between delays caused by weather conditions and those resulting from the cascading effects of arrival and departure delay times.
 
## How to Run It?
The IPython Notebook provided in this repository serves as our end-to-end code. Each code block can be re-run to view the analysis step by step. Follow these steps to run the notebook:
1. Clone the repository:
```
git clone <repository_url>
cd <repository_directory>
```
2. Install the required dependencies:
```
pip install pandas matplotlib
```
3. Run the Jupyter Notebook
4. Follow the notebook's instructions:
   - The notebook is divided into sections that correspond to different parts of the analysis.
   - Execute each cell to run the code and observe the results step by step.
  
## Project Overview

### Introduction
The escalating demand for air travel has underscored the necessity of scrutinizing flight delays, a pivotal concern for airlines aiming to streamline operations and enhance profitability. This project focuses on understanding the multifaceted nature of weather-related delays and their downstream effects on airline operations.

### Datasets
- Airline On-Time Performance Data from the Bureau of Transportation Statistics (BTS)
- Global Surface Summary Of Day dataset compiled by the National Centers for Environmental Information (NCEI)

### Data Pre-Processing and Feature Selection
Key features utilized include:
- Airline Data: Tail Number, Depature Delay, Arrival Delay, Weather Delay, Origin Airport
- Weather Data: Station ID, Avg. Wind Speed in 2 min, Avg. Wind Direction in 2 min, Peak Gust Time

### Experimental Setup

#### Wind Speed and Direction Analysis
We analyze how different types of winds (headwinds, tailwinds, crosswinds) affect flight delays, especially focusing on domestic flights.

#### Runway Analysis
The project includes a comprehensive analysis of runway configurations and their impact on delays under varying wind conditions.

### Results

#### Flight Delay Analysis for Varying Wind Conditions
We provide detailed histograms and analysis of how wind direction influences delays at various airports.

#### Analysis of Arrival Delay Effect on Departure Delay
The correlation between arrival and departure delays is examined, revealing a robust positive linear relationship.

### Statistical Analysis
A regression analysis quantifies the impact of arrival delay on departure delay, confirming its significance across multiple airports.

### Meta Analysis
The project explores the cascading effects of wind conditions on delays, particularly in colder winter months.

### Conclusion
Our analysis confirms the interdependence between arrival and departure delays, emphasizing the need for strategic planning to minimize the ripple effects throughout the flight itinerary.

### Challenges
- Disentangling the impact of external factors.
- Aligning arrival and departure times accurately.
- Interpreting statistical results for practical relevance.
- Visualizing directional wind data effectively.

## References
- Airline On-Time Data 
- Global Surface Summary of the Day - GSOD 
