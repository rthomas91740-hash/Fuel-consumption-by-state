# Fuel & Distance by State

A MyGeotab add-in that reports fuel used and distance driven in each state (and Canadian province) for the database you are logged into. Pick a period, click **Run report**, and it fills in headline totals, two bar charts, a full state table, and a CSV download.

- **Distance** comes from MyGeotab fuel tax (IFTA) jurisdiction records (odometer based).
- **Fuel** is the cumulative "Total fuel used (since telematics device install)" counter; fuel burned between a vehicle entering and leaving each state is credited to that state.
- Only vehicles that report fuel are counted. Vehicles with no fuel data are left out of every figure and the page says how many.
- For tax filing, use Geotab's official Fuel Tax Report.

## Install in MyGeotab

1. Administration > System > System Settings > Add-Ins.
2. Turn on "Allow unverified add-ins" if it is off, then click New Add-In.
3. Paste the contents of `config.json` into the Configuration tab and save.
4. Refresh MyGeotab. "Fuel and Distance by State" appears under the Activity menu.

Hosted with GitHub Pages from the `main` branch. If the repo name or account differs, update the `url` in `config.json`.
