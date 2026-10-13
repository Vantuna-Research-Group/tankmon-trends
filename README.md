# TankMon trends

Trend charts for the VRG Marine Aquarium monitor, published with GitHub Pages:
https://vantuna-research-group.github.io/tankmon-trends/

`index.html` is generated. Don't edit it here. It comes from the trends page in
`sheet_archive.gs` in the private `Vantuna-Research-Group/tankmon` repo:

    python3 tools/make_trends_page.py <the Sheet web app /exec address> ../tankmon-trends/index.html

The page loads readings from the Google Sheet's web app (`/exec?hours=24`) without a
Google sign-in. That avoids the "unable to open the file" error that Apps Script pages
show on phones signed in to more than one Google account.
