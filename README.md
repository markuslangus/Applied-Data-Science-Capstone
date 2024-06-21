# :rocket: Applied Data Science Capstone - IBM

## :page_facing_up: Overview

Welcome to the repository for the IBM Applied Data Science Capstone Project titled "Winning Space Race with Data Science". This repository contains various resources and materials, including Jupyter Notebooks, Python code snippets, and the [final presentation slides](https://github.com/markuslangus/Applied-Data-Science-Capstone/blob/main/AppliedDataScienceCapstone_IBM.pdf).

## :page_facing_up: Notebooks

To view the notebooks live and properly display interactive elements such as Folium maps, we will use `nbviewer`. Just click on the following links to open the Jupyter Notebooks of this repository in `nbviewer`:

1. [Data Collection - SpaceX API](https://nbviewer.org/github/markuslangus/Applied-Data-Science-Capstone/blob/main/jupyter-labs-spacex-data-collection-api.ipynb)
2. [Data Collection - Web Scraping](https://nbviewer.org/github/markuslangus/Applied-Data-Science-Capstone/blob/main/jupyter-labs-webscraping.ipynb)
3. [Data Wrangling](https://nbviewer.org/github/markuslangus/Applied-Data-Science-Capstone/blob/main/labs-jupyter-spacex-Data%20wrangling.ipynb)
4. [EDA with Data Visualization](https://nbviewer.org/github/markuslangus/Applied-Data-Science-Capstone/blob/main/jupyter-labs-eda-dataviz.ipynb)
5. [EDA with SQL](https://nbviewer.org/github/markuslangus/Applied-Data-Science-Capstone/blob/main/jupyter-labs-eda-sql-coursera_sqllite.ipynb)
6. [Build an Interactive Map with Folium](https://nbviewer.org/github/markuslangus/Applied-Data-Science-Capstone/blob/main/lab_jupyter_launch_site_location.ipynb)
7. [Predictive Analysis - Classification](https://nbviewer.org/github/markuslangus/Applied-Data-Science-Capstone/blob/main/SpaceX_Machine_Learning_Prediction_Part_5.jupyterlite.ipynb)

## :page_facing_up: Plotly Dashboard

The Plotly Dashboard requires running on your local machine to be properly viewed. Follow these steps to run it on your machine:

### :information_source: Instructions to Host the Plotly Dashboard Locally

1. Ensure you have `Python` and `pip` installed. Then install the required packages by running the following command in your command shell:

    ```bash
    pip install dash pandas plotly
    ```

2. Download the [python file](https://github.com/markuslangus/Applied-Data-Science-Capstone/blob/main/spacex_dash_app.py) and save it locally on your machine.
3. In your command shell, navigate to the directory containing the downloaded `.py` file and run the script using the following command:

    ```bash
    python spacex_dash_app.py
    ```

4. This will start a local server. The terminal will display a URL (usually http://127.0.0.1:8050/). Open this URL in your web browser by holding `Ctrl` and clicking on the URL. When you are finished, stop the local server by pressing `Ctrl` + `C` in your command shell.

You should now be able to view and interact with the dashboard.
