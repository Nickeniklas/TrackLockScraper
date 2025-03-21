# TrackLockScraper

Scrape match data from the website tracklock.gg for a specific player

Process the data, and export it as a CSV file.

### currently output
A CSV file containing match data with columns:
- Result (Win/Loss)
- Date (Date played)
- Duration (Match length)

## IPython Notebook content

- Invidual scrape examples
- converting to Pandas DataFrame 
- exporting as csv
- Functions for actual scraping

### Functions
pages = pullTracklockPages(playedId)
data = scrapeTracklock(pages)
exportData(data, playerId)

