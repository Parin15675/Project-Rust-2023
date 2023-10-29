# Rust Chart Generator

This program is a command-line based utility for generating different types of charts from CSV data using Rust.

## Features
- Generate 5 types of charts:
  - Bar Chart
  - Scatter Plot
  - Pie Chart
  - Line and Area Chart
  - Radar Chart

## How to use

1. Launch the program.
2. You will be presented with a menu to choose the type of chart you want to generate.
3. Follow the prompts to provide necessary inputs such as CSV filenames and output file names.
4. The program will generate the chart and save it as a PNG or SVG file.

### Supported CSV Formats for Each Chart:

- **Bar Chart**: Expected Columns: 'Category', 'Value'
- **Scatter Plot**: Expected Columns for two CSVs: 'X1', 'Y1' and 'X2', 'Y2'
- **Pie Chart**: Expected Columns: 'Category', 'Percentage'
- **Line and Area Chart**: Expected Columns: 'Date', 'Value'
- **Radar Chart**: Expected Columns: 'Label', 'Value'

## Prerequisites

Ensure you have the necessary Rust libraries and dependencies installed.

## Installation

1. Clone the repository.
2. Navigate to the project directory and run `cargo build --release`.
3. Use the generated executable in the `target/release` directory.

## Feedback & Contribution

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
[MIT](https://choosealicense.com/licenses/mit/)
