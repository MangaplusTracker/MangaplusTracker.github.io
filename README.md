## Mangaplus View Count Tracker

### Overview
So, I noticed there wasn't any solid data for mangaplus view counts when i was looking for who gained the most views like last month, so I decided to do it myself.
Started by trying to scrape data from the platform's official rankings, but it was all over the place and not updated regularly. So, I am tracking it myself more accurately.

### How It Works
Right now, I'm scraping data from the daily updates page (https://mangaplus.shueisha.co.jp/updates) everyday at 11:59pm jst using Selenium, grabbing info on the top 50ish manga series that pop up so if some data looks missing its cause it did not appear on the updates page. Saving the data to a db and using plotly to visualize the chart.

### How to Use
1. Visit the website and order by magazines, click and double click on series to view them by themselves or compare them with others
2. The code isn't all that great nor that special so just sharing the html which was generated with plotly but if some deranged soul wants it (I don't recommend it) feel free to reach out
   

### Future Plans
- Don't know really. Didn't think I'd get this far
- Maybe work on cool statistics
