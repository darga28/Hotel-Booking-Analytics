# Hotel Bookings Cancellation Data Analysis & Dashboard

This project is designed to analyze and visualize hotel bookings cancellation data using Excel. The repository contains the raw dataset and a fully interactive dashboard to help users explore and derive insights from the data.

## 🌟 Project Overview

This project aims to provide a comprehensive analysis of hotel booking trends, guest demographics, and key metrics using a dataset stored in `rawdata.csv`. The analysis is visualized through an Excel dashboard in `Hotel_Bookings_Dashboard.xlsx`, offering a user-friendly interface for data exploration.

### 📁 Repository Contents

- **Hotel_Bookings_Dashboard.xlsx**
  - **Data_Clean**: This sheet contains the cleaned version of the raw data. The data has been processed to remove any inconsistencies or missing values, ensuring accurate analysis.
  - **Pivot**: This sheet includes pivot tables derived from the cleaned data, which serve as the foundation for the dashboard visualizations.
  - **Dashboard**: The final dashboard, providing a visual representation of key metrics and trends related to hotel booking cancellations. It includes various charts and graphs for easy interpretation.

- **rawdata.csv**
  - This file contains the original dataset used in the analysis. The dataset includes 119,390 entries with 36 columns, capturing various attributes related to hotel bookings, such as:
    - `hotel`: Type of hotel (Resort or City Hotel).
    - `is_canceled`: Indicates if the booking was canceled.
    - `lead_time`: Number of days between the booking date and the arrival date.
    - `arrival_date_year`, `arrival_date_month`, `arrival_date_day_of_month`: Booking dates.
    - `adults`, `children`, `babies`: Number of guests.
    - `meal`, `country`, `market_segment`, `distribution_channel`: Customer and booking details.
    - And more, including financial and reservation details.

## 📈 Dashboard Features

The `Hotel_Bookings_Dashboard.xlsx` file includes several features designed to enhance the analysis experience:

- **Interactive Slicers**:
  - **Functionality**: Filter the data dynamically by various criteria such as hotel type, booking dates, and guest demographics.
  - **Customization**: Users can easily modify the slicer settings to tailor the dashboard to specific needs.
  
- **Visualizations**:
  - **Types**: Includes area charts, bar charts, pie charts, and more.
  - **Purpose**: Visualizations help to illustrate trends, distributions, and relationships within the dataset.
  
- **Summary Statistics**:
  - **Key Metrics**: The dashboard highlights important metrics like hotel type, count of cancelled_bookings for each month, and guest type.
  - **Interactive**: These metrics update automatically based on slicer selections.


## Insights & Analysis

The dashboard is designed to provide insights into:

- **Booking Trends**: Analyze how bookings fluctuate over time, across different hotel types, and during various seasons.
- **Guest Demographics**: Understand the geographical distribution of guests and booking preferences.

