# How often is [PowerSearch](https://powersearch.sos.ca.gov:3000/) down?

I'm not sure, this scraper is an attempt to figure that out. I'm using Github actions to get the HTTP status code from https://powersearch.sos.ca.gov:3000/. The scraper runs every five minutes and commits the status if it has changed. I plan to use [`git-history`](https://datasette.io/tools/git-history) to do the analysis.

## What is PowerSearch?
It's the California Secretary of State's advanced search tool for campaign finance data. It's OK. But the larger problem is that its just offline alot.
