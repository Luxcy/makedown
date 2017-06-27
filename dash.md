Dash by plotly
一、Installation
In your terminal, install several dash libraries. These libraries are under active development, so install and upgrade frequently. Python 2 and 3 are supported.

1.	pip install dash==0.17.7  # The core dash backend
2.	pip install dash-renderer==0.7.3  # The dash front-end
3.	pip install dash-html-components==0.6.2  # HTML components
4.	pip install dash-core-components==0.5.1  # Supercharged components
5.	pip install plotly==2.0.11  # Plotly graphing library used in examples

二、Dash App Layout

import dash
import dash_core_components as dcc
import dash_html_components as html
import plotly.graph_objs as go
import pandas as pd

2.1	Generating HTML with Dash

generates a Table from a Pandas dataframe   pip install pandas

2.2	Data Visualization in Dash



2.3	Markdown

2.4	Core Components

2.5	Calling help

三、Interactivity

3.1	Fundamentals

3.2	Multiple Inputs

3.3	Multiple Outputs

3.4	Graph Crossfiltering

