# Data and Visualization

This project focuses on analyzing Airbnb listings in Amsterdam, filtering by price and visualizing their locations on a map using Streamlit and Plotly.

## Description

This Streamlit application reads Airbnb listing data from a CSV file (`Airbnb_Amsterdam_listings.csv`). It filters listings based on a maximum price criterion (GBP £100 per night in this case), formats the data, and visualizes it using Plotly Express to display locations on a map.

## Installation

To run this project locally, ensure you have Python installed along with the necessary libraries:

```bash
pip install pandas plotly streamlit
```

## Usage

1. Clone the repository.
2. Navigate to the directory containing `app.py`.
3. Run the Streamlit app:
   ```bash
   streamlit run app.py
   ```
4. The application will open in your default web browser.

## File Descriptions

- **app.py**: Main Streamlit application script.
- **Airbnb_Amsterdam_listings.csv**: CSV file containing Airbnb listing data.

## Data Processing

- Reads and filters Airbnb listings based on a price threshold.
- Formats price values and modifies location data for visualization.

## Visualization

- Displays filtered listings in a DataFrame.
- Shows a scatter map using Plotly Express, with locations color-coded based on the chosen location relative to a specified point.
- Uses Mapbox for mapping with a terrain style.
