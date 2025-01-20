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

4. Press `F12` to open the console, validating no errors exist.

## Usage

Utilize the provided `index.html` file to view the output and `app.js` file to read and visualize the code.
The starter code is based on building 4 functions in which provide the naming and initial lines with the
instructions commented out. We are using the D3 Library to read in "<https://static.bc-edx.com/data/dl-1-2/m14/lms/starter/samples.json>" of which `samples.json` is included in the Repo for reference in variable names and function construction.

- **Plot**: Create interactive plots using Plotly. Reference for horizontal bar chart and bubble chart
[Plots](https://www.w3schools.com/js/js_graphics_plotly.asp)
- **Variables**: Utilize `const` to build stable variables and `let` only for differing results.

### JavaScript Code Description

The `app.js` file contains the following functions which are partially given to begin and need
to be built out:

- **buildMetadata(sample)**: Fetches metadata for the selected sample from a JSON file and displays it in the metadata panel. It filters the metadata for the selected sample, clears any existing metadata, and appends new HTML elements for each key-value pair in the filtered metadata.  
- **function buildCharts(sample)**: TThis function reads sample data and builds both a bubble chart and a bar chart. It takes the parameter, `sample` which specifies the sample ID to retrieve data. It then utilizes the Plotly library for visualizing the data.  
- **function optionChanged(newSample)**: This function updates the charts and metadata panel to allow for a new sample to be selected. It takes the parameter, `newSample`, which specifies the new sample ID to retrieve data for.  
- **init()**: Takes the 3 functions and outputs to the webpage giving the user choice of sample id's to view. It then displays the bar, bubble charts and `data`.

## License

This project is licensed under the [GNU General Public License](https://www.gnu.org/licenses/gpl-3.0.en.html)

JSON sample testing data using the D3 library.
