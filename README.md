# Gewicht - Wochenübersicht

A single-file weight tracker that visualizes weekly averages from [openScale](https://github.com/oliber/openScale) CSV exports.

## Features

- Drag & drop or select a CSV file
- Calculates weekly average weight (ISO calendar weeks)
- Shows week-over-week delta
- Mini bar chart of the trend
- Summary stats: current weight, average weekly change, total change
- Handles quoted CSV fields (comments with commas)
- No server, no dependencies - just open the HTML file

## Usage

1. Export your data from openScale as CSV
2. Open `weight-tracker.html` in a browser
3. Drop your CSV file onto the upload zone

The CSV must contain `DATE` and `WEIGHT` columns. An example file is included as `openscale-example.csv`.

## License

This project is licensed under the GNU General Public License v3.0 - see the [LICENSE](LICENSE) file for details.
