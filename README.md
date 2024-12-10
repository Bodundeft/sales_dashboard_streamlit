# sales_dashboard_streamlit
### Turn An Excel Sheet Into An Interactive Dashboard Using Python (Streamlit)

# Excel to Interactive Dashboard

This repository contains a project that converts an Excel sheet into an interactive dashboard using Python and Streamlit. The dashboard allows users to visualize and explore data through interactive charts, graphs, and components.

## Prerequisites

Before you begin, ensure you have the following installed:

- Python 3.7 or higher
- pip (Python package installer)

  Install the required packages:
    ```bash
    pip install pandas openpyxl streamlit plotly
    ```

## Usage

1. Place your Excel file in the `data` directory. Ensure the file is named `data.xlsx`.

2. Run the Streamlit app:
    ```bash
    streamlit run app.py
    ```

3. Open your web browser and go to `http://localhost:8501` to view the dashboard.

## Project Structure

- `Main.py`: Main application file that contains the Streamlit code.
- `data/`: Directory to store the Excel file.
- `README.md`: Project documentation.

## Features

- **Data Filtering**: Use the sidebar to filter data based on different criteria.
- **Key Performance Indicators (KPIs)**: Display important metrics at the top of the dashboard.
- **Interactive Charts**: Visualize data with interactive bar charts and line charts.
