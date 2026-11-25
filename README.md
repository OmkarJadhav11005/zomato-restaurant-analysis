# Zomato Restaurant Analysis

Exploratory data analysis of Bangalore restaurant data using Python.

## Objective
Understand restaurant distribution, ratings, cost and customer preferences across Bangalore.

## Dataset
- `zomato.csv`: Bangalore restaurant listings
- Columns include: rate, num of ratings, avg cost, online_order, table booking, cuisines type, area

## Tools Used
- Python (Pandas, Matplotlib)
- Jupyter Notebook

## What I Did
- Cleaned the data (duplicates, inconsistent values)
- Compared restaurants across areas and restaurant types
- Found the most common cuisines
- Analysed ratings, average cost, online ordering and table booking
- Created charts with Matplotlib

## Key Insights
- Dataset has 7,105 restaurants after cleaning (no duplicates; 68 missing ratings and 57 missing costs).
- Average rating is 3.51 and median cost for two is ₹400.
- Byresandra/Tavarekere/Madiwala has the most restaurants (798), followed by Bannerghatta Road (552) and Brookefield (477).
- Quick Bites is the most common type (2,840, about 40%), then Casual Dining (1,634).
- North Indian (3,237), Chinese (2,438) and South Indian (1,464) are the top cuisines.
- Among areas with 30+ restaurants, Brigade Road has the highest average rating (3.68), then Lavelle Road and Malleshwaram (3.63).
- Restaurants with online ordering are rated slightly higher (3.55 vs 3.47) and are cheaper on average (₹488 vs ₹599).
- Restaurants with table booking have much higher ratings (4.04 vs 3.45) and cost about 3x more (₹1,355 vs ₹444).
- Cost and rating show a moderate positive correlation (0.38).

## Files
- `Zomato_Restaurant_Analysis.ipynb`: full analysis
- `zomato.csv`: dataset
