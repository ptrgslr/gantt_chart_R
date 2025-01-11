# Gantt Chart R
This repository contains an R script designed to create a basic Gantt chart for thesis planning.

## Features
Generates a simple Gantt chart to visualize thesis tasks and milestones.
Customizable task durations and milestones.
Outputs the Gantt chart in a clear, easy-to-understand format.

## Installation
Clone the repository:
`git clone https://github.com/ptrgslr/gantt_chart_R.git`

Navigate to the project directory:
`cd gantt_chart_R`

Install required R packages:

Ensure that you have the necessary R packages installed. You can install them using the following commands in your R console:

R
```install.packages("ggplot2")
install.packages("dplyr")
install.packages("lubridate")```

## Usage
Prepare your data:

Gantt_tasks.csv: Contains the list of tasks with their start and end dates.
Gantt_milestones2.csv: Contains the list of milestones with their dates.
Ensure these CSV files are formatted correctly and placed in the project directory.

Run the script:

Open the gantt.qmd file in RStudio and execute the code. This will generate the Gantt chart based on the data provided in the CSV files.

View the output:

The script will produce a Gantt chart displaying your thesis plan, which you can view within RStudio or export as needed.

## Contributing
Contributions are welcome! If you have suggestions for improvements or encounter any issues, please open an issue or submit a pull request.

## License
This project is licensed under the MIT License.
