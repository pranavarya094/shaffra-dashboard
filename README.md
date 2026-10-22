# shaffra-dashboard

Static LinkedIn ads dashboard for Shaffra: spend, leads, cost per lead, CTR, per ad set and daily trends.

## Update the data
1. In LinkedIn Campaign Manager, open the account, set the date range, choose Export, and pick a performance report with a **Daily** breakdown by ad set. Include Spend, Impressions, Clicks and Leads.
2. Save the file as `data/linkedin.csv` in this repo and commit it.
3. The page redraws from that file. You can also drag any export onto the page to view it without committing.

## Publish
Settings, Pages, deploy from the `main` branch root. If the repo is public, the numbers are public. Keep it private unless you want that.

## Later
Replace step 1 with the LinkedIn Marketing API in a scheduled GitHub Action once API access is approved. The page does not change.
