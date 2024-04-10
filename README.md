# Twitter Data into SQLite Database

This repository hosts the Final Database Project, which explores processing and analyzing a dataset of tweets collected over a single day. The project demonstrates data retrieval, database operations, data analysis, and exporting data in various formats, all within a Python notebook.

## Project Overview

The project is conducted in a single Jupyter notebook that covers:

- Data retrieval from a web source
- Population of an SQLite database with tweets
- Analysis of tweet data using SQL queries
- Exporting data into JSON and CSV formats for comparison

## Getting Started

### Prerequisites

Before running the notebook, ensure you have the following:

- Python 3.x installed
- Access to Jupyter notebooks (via Jupyter Lab, Jupyter Notebook, or another similar tool)
- SQLite3 for database operations
- The Pandas library for data manipulation
- The Requests library for HTTP requests
- Matplotlib for generating plots

### Installation

Clone this repository to your local machine to get started:

```bash
git clone https://github.com/your-username/final-database-project.git
cd final-database-project
```

### Data
s
The dataset consists of tweets from one day, available at [One Day of Tweets](http://dbgroup.cdm.depaul.edu/DSC450/OneDayOfTweets.txt). This dataset needs to be downloaded separately.

## Usage

Open the `final_database_project.ipynb` notebook in your Jupyter environment to start working with the project. The notebook is self-contained and guides you through each step of the project, from data retrieval to analysis and exporting.

## Notebook Structure

The notebook is structured into parts that sequentially guide you through the project:

1. **Data Retrieval:** Download tweets and save them locally.
2. **Database Population:** Insert tweets into an SQLite database.
3. **Data Analysis:** Perform SQL queries to analyze the data.
4. **Data Exporting:** Export the analyzed data into JSON and CSV formats.

## Contributing

Contributions are welcome. Please fork the repository, make your changes, and submit a pull request.

## License

This project is open source and available under the [MIT License](LICENSE.md).
