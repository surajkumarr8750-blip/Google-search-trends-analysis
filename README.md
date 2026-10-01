# Google Search Trends Analysis with Python

Analysis of Google search interest for *"Cloud Computing"* using Python and Pytrends: trends over time, regional interest, related queries, and keyword suggestions.

## Objective
Find out when and where interest in a topic peaks, and which related searches go with it.

## Tools Used
- Python
- Pytrends (Google Trends API)
- Pandas
- Matplotlib
- Google Colab

## What the Notebook Does
- Pulls search interest over the last 12 months and over a custom date range
- Ranks the top regions by interest
- Plots a bar chart of the top 10 regions
- Fetches related queries and keyword suggestions

## Key Findings
- Search interest peaked in the week of 22 March 2026 (score 100).
- St. Helena had the highest regional interest (100), followed by Ethiopia (~93) and Nepal (~92). India ranked 4th (~67), ahead of Cameroon, Sri Lanka, and Nigeria.
- Interest is strong across South Asia and Africa.
- Google Trends shows relative interest (0 to 100), not search volume, so small regions can rank high.

## How to Run
1. Open Google_Search_Analysis_with_Python.ipynb in Google Colab.
2. Run the first cell: !pip install pytrends
3. Click Runtime > Run all.

Note: Google may rate-limit requests (error 429). Wait a few minutes and rerun.
