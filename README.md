# Read the Docs data dashboard

In this example, I show how to use Vizro-AI to generate Plotly charts to visualize documentation traffic. I build those charts into a Vizro dashboard, with some professional-looking results. 

## What is this code for?
You can find the blog post that accompanies this code here:

## What's in the repo?

* `LICENSE`: "You can do whatever you want with this code".
* `README.md`: This file.
* `dashboard.ipynb`: The main example code. See section below.
* `data_generation.ipynb`: As the blog post describes, I use a set of fake CSV traffic data, and this code generates it. The fake data has the same fields as genuine RTD data so you can download and use the dashboard with the data downloaded from your own RTD dashboard (just update the Notebook to load your CSV or rename your downloaded data and replace `website_traffic_data.csv`.
* `website_traffic_data.csv`: The output of the `data_generation` Notebook.


## How to use the `dashboard.ipynb` Notebook
To run the Notebook successfully, you need to be set up to use Vizro-AI. The best way to achieve this is to follow the blog post linked in the "What is this code for?" section? It'll walk you through the steps needed to:

* [Set up Vizro inside a virtual environment containing Python 3.9 or greater](https://vizro.readthedocs.io/projects/vizro-ai/en/latest/pages/user-guides/install/).
* `pip install jupyter` if you don't already it, so you can run the Notebook.
* [Set up an API key for OpenAI](https://platform.openai.com/signup)
* [Add the API key to your environment](https://vizro.readthedocs.io/projects/vizro-ai/en/latest/pages/user-guides/install/#set-up-access-to-a-large-language-model)
* Ensure you have updated the Notebook to point to the RTD data you want to analyse. If you just want to experiement with the fake data, there's nothing to do. Otherwise, change the first cell in the Notebook to load your preferred CSV file.
