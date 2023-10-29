# Chart_Generator 📊
by [Your Name] <br>
[Your Institution/Organization Name]


## Description
Chart_Generator is an interactive command-line tool designed in Rust, enabling users to visualize their data seamlessly. Users can import CSV datasets and generate various types of charts, all displayed in an intuitive manner. Additionally, it offers an option to export these visualizations as PNG images for better accessibility and sharing.

## Features
Here's a quick glance at the Chart_Generator:

![Chart Generator Main Menu](screenshots/main_menu.png)

___

#### 1. Bar Chart
![Bar Chart](screenshots/bar_chart.png)

This feature allows users to:
 * Visualize categorical data with rectangular bars
 * Compare different categories based on their values

Input Expected: CSV with columns 'Category' and 'Value'.
___

#### 2. Scatter Plot
![Scatter Plot](screenshots/scatter_plot.png)

This feature displays:
 * Data points on a two-dimensional axis
 * Relationships between two variables from two separate CSVs

Input Expected: Two CSVs with columns 'X1', 'Y1' and 'X2', 'Y2' respectively.
___

#### 3. Pie Chart
![Pie Chart](screenshots/pie_chart.png)

This visualization showcases:
 * Proportional representation of categories
 * Circular statistical graphic split into slices

Input Expected: CSV with columns 'Category' and 'Percentage'.
___

#### 4. Line and Area Chart
![Line and Area Chart](screenshots/line_area_chart.png)

This chart is optimal for:
  * Displaying information as a series of data points
  * Understanding trends over intervals or time

Input Expected: CSV with columns 'Date' and 'Value'.
___

#### 5. Radar Chart
![Radar Chart](screenshots/radar_chart.png)

This feature displays:
 * A multi-variable data set on a two-dimensional plane
 * Comparative analysis across different categories

Input Expected: CSV with columns 'Label' and 'Value'.
___

#### 6. Interactive User Interface
| ![Initial Prompt](screenshots/initial_prompt.png) | ![File Input Prompt](screenshots/file_input.png) |
| -------- | -------- |
| Initial Chart Selection Menu | User Prompt for File Name |

This interface is designed to be user-friendly, guiding users through the entire process of chart generation. From selecting the chart type to entering the desired output filename, every step is made simple.
___

#### 7. Output Previews
![Output Preview](screenshots/output_preview.png)

Upon successful generation:
 * Preview the chart output
 * Save it locally in PNG format

___

#### 8. Error Handling
![Error Handling](screenshots/error_handling.png)

The application is built to handle:
 * Incorrect file names or paths
 * Unsupported data format in CSVs
 * Any other potential errors during the visualization process

Ensuring a smooth user experience throughout.

___

For those looking to bring their data to life, Chart_Generator is the perfect tool, bridging the gap between raw data and insightful visualizations.
