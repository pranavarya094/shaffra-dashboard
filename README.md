# shaffra-dashboard

Password-protected LinkedIn ads dashboard for Shaffra (spend, leads, cost per lead, trends per ad set).

The data lives in `linkedin.enc.json`, encrypted in the browser-compatible format (PBKDF2 + AES-GCM). The page decrypts it after the password is entered. No plain data is stored in this repo.

## Update the data
1. Open the dashboard, enter the password, click **Update data**.
2. Drop a fresh Ad Set Performance CSV exported from LinkedIn Campaign Manager.
3. The page previews it and downloads a new `linkedin.enc.json`.
4. Upload that file to this repo, replacing the old one. "Last updated" shows the export's generation time.
