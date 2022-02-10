# `README.md` for [tukesian-goldfinch](https://github.com/Ai-Yukino/tukesian-goldfinch)

This is a project for a homework assignment for Tech Talent South's 2022 data science course. The assignment focused on doing light EDA on a dataset of our choice. Here's what I did:

- manually find LinkedIn profiles with "data engineer" roles
- make sure those roles had detailed experience descriptions (i.e. bullet points for specific tasks and responsbilities)
- for each relevant role, I counted the number of tasks in specific categories
  - e.g. ETL workflow in general, optimizing SQL queries, migrating databases, cloud work with AWS, Azure, etc.
- I made a very rough report based on histograms of my data variables (i.e. columns)

The report is in `report/report.pdf`, the csv data is in `data/de`, and the plots are in `report/plots`.

## Running the Jupyter Lab notebook

If you do not already have Jupyter **Lab** in your python virtual environment, then follow the instructions [here](https://jupyter.org/install) to install it.

Next, add Mito to your python virtual environment by following the instructions [here](https://docs.trymito.io/getting-started/installing-mito/installing-mito-inside-a-virtual-environment). Please note that the free version of Mito has telemetry that you cannot disable. Moreover, you will have to sign-up for an account (inside the Jupyter Lab interface) the first time your run Mito.

The spreedsheets are in the `data` folder if you would prefer to modify them in another way (e.g. LibreOffice or Google Sheets).
