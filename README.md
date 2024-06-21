# Applied Data Science Capstone - IBM

## Overview

Welcome to the repository for the IBM Applied Data Science Capstone Project titled "Winning Space Race with Data Science". This repository contains various resources and materials, including Jupyter Notebooks, Python code snippets, and the final presentation slides.

## Notebooks

To view the notebooks live and properly display interactive elements such as Folium maps, we will use `nbviewer`. Just click on the following links to open the Jupyter Notebooks of this repository in `nbviewer`:

1. [Data Collection - SpaceX API](https://github.com/markuslangus/Applied-Data-Science-Capstone/blob/main/jupyter-labs-spacex-data-collection-api.ipynb)
2. Navigate to the desired notebook file within this repository and copy its URL.
3. Paste the copied URL into the search field on `nbviewer` and click "Go".

## Plotly Dashboard

The Plotly Dashboard requires running on your local machine to be properly viewed. Follow these steps to run it on your machine:

### Instructions to Host the Plotly Dashboard Locally

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
