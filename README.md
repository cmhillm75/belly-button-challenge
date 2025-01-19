# Module 14 Challenge - Belly Button Diversity

This project involves analyzing the Belly Button Diversity dataset to understand the presence of bacteria in sample test data. We are using creating javascript and using plotly and D3 to show the results in charts and allowing for choice in
the the individual samples.

## Prerequisites

- Web browser
- Internet connection
- VS Code

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/cmhillm75/belly-button-challenge.git
    ```

2. Open VS Code and use the Explorer panel to navigate to

    ```bash
    cd belly-button-challenge
    ```

3. In the Explorer panel, right click `index.html` and Open with Live Server to view as webpage.

    ```
4. Press \F12\ to open the console, validating no errors exist.

## Usage

Utilize the provided `index.html` file to view the output and `app.js` file to read and visualize the code.
The starter code is based on building 4 functions in which provide the naming and initial lines with the
instructions commented out.

- **Plot**: Create interactive plots using Plotly. Reference for horizontal bar chart and bubble chart
[Plots](https://www.w3schools.com/js/js_graphics_plotly.asp)
- **Variables**: Utilize `const` to build stable variables and `let` only for differing results.

### JavaScript Code Description

The `app.js` file contains the following functions which are partially given to begin and need
to be built out:

- **buildMetadata(sample)**: Reads metadata and displays it in the metadata panel.
- **buildCharts(sample)**: Reads sample data and builds both a bubble and a bar chart.
- **optionChanged(newSample)**: Updates the charts and metadata panel when a new sample is selected.
- **init()**: Initializes the dashboard by populating the dropdown with sample names and builds the initial charts and metadata panel.

## License

This project is licensed under the [GNU General Public License](https://www.gnu.org/licenses/gpl-3.0.en.html)

JSON sample testing data using the D3 library.
