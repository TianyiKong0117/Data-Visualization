# Xiaohongshu Data Visualization Project  

## Overview  
This project analyzes **Xiaohongshu user data** using **Dash** to explore spending behavior and engagement trends. The interactive dashboard provides visual insights into **revenue distribution, user engagement, and gender-based purchasing behavior**.  

## Installation Instructions
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
import dash
from dash import html, dcc, dash_table, Input, Output
import plotly.express as px

To run the Dash graph, once the app is running, open this URL:
http://127.0.0.1:8050/

### Usage Guide
The project consists of five interactive visualizations to explore user spending behavior on Xiaohongshu:
1.	Revenue Distribution (Histogram)
- Displays how users are spending, highlighting popular spending ranges.
2.	User Engagement vs. Revenue (Box Plot)
- Compares spending behavior of engaged vs. non-engaged users.
3.	Gender-Based Revenue Trends (Dash Bar Chart)
- Analyzes differences in spending between male and female users.
4.	Lifecycle vs. Total Revenue (Bar Chart)
- Examines how spending varies across user lifecycle stages (6 months, 1 year, 2 years).
5.	Interactive Dashboard
- Allows real-time filtering by gender and engagement status for deeper insights.
