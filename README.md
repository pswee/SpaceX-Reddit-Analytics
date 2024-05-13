# SpaceX Sentiment Analysis

## Project Overview
This project performs a sentiment analysis on public discussions about SpaceX from Reddit. By analyzing posts and comments collected over the month of July 2023, this analysis aims to understand public sentiment and the main topics of discussion related to SpaceX. The insights gathered could serve as valuable feedback for strategic decision-making and public relations enhancements for SpaceX.

## Data Collection
Data was collected using the Reddit API, focusing on the SpaceX subreddit. We extracted posts and comments from July 1st to July 31st, 2023, resulting in a dataset of 922 mentions (56 posts and 866 comments).

## Technologies Used
- **Python**: Primary programming language.
- **PRAW (Python Reddit API Wrapper)**: Simplified interaction with Reddit's API.
- **Jupyter Notebook**: For running Python code and immediate results visualization.

## Repository Structure
- **SpaceX-sentiment-analysis.ipynb**: Jupyter notebook containing the full analysis.
- **data/**: Directory containing the collected data (if included).
- **figures/**: Directory containing plots and figures generated in the analysis.

## How to Run
Open the `SpaceX-sentiment-analysis.ipynb` in a Jupyter environment and execute the cells sequentially to reproduce the analysis.

## Analysis Results
The sentiment analysis demonstrated a predominantly positive sentiment across both posts and comments on the SpaceX subreddit, reflecting a favorable public perception of SpaceX. The analysis also identified specific peaks in sentiment that corresponded with particular dates. These peaks are likely linked to major SpaceX events or announcements, indicating periods of heightened public interest and engagement.

## Conclusion
Reddit offers valuable data for analyzing public sentiment, particularly beneficial for companies like SpaceX. This sentiment analysis reveals a generally positive perception of SpaceX on Reddit, highlighting public enthusiasm and areas for improvement. Although competitors are less frequently mentioned, their presence in discussions underscores the competitive nature of the aerospace industry. Proactive engagement with these insights can help SpaceX enhance its brand image and maintain its industry leadership.

## Acknowledgments
- Data provided by Reddit through their API.
- Libraries and tools that supported this analysis: PRAW, NLTK, Matplotlib.
