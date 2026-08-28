# Airbnb Hotel Booking Analysis

A data analysis project exploring Airbnb listing data to understand the
factors that influence booking demand and pricing.

## Problem Statement

- Airbnb listings vary widely in price, location, room type, and availability.
- It is difficult to understand which factors influence guest bookings and pricing the most.
- Hosts and travel platforms need data-driven insights to price listings competitively.
- This project analyzes historical Airbnb listing data to identify booking and pricing trends.
- The goal is to deliver insights that support better hosting, pricing, and booking decisions.

## Dataset

The dataset contains Airbnb listing details, including:

| Column | Description |
|---|---|
| `neighbourhood_group` | Borough / region |
| `neighbourhood` | Specific neighbourhood |
| `room_type` | Entire home/apt, Private room, or Shared room |
| `price` | Nightly price (USD) |
| `minimum_nights` | Minimum nights required to book |
| `number_of_reviews` | Total number of reviews |
| `reviews_per_month` | Average reviews per month |
| `availability_365` | Days available per year |

> Replace `Airbnb_Open_Data.csv` with your assigned dataset before running the analysis.

## Tools Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn

## Project Structure

```
airbnb-hotel-booking-analysis/
├── airbnb_analysis.py       # Main analysis script
├── Airbnb_Open_Data.csv     # Dataset (add your assigned dataset here)
├── requirements.txt         # Python dependencies
├── README.md
└── outputs/                 # Generated charts
    ├── price_distribution.png
    ├── room_type_counts.png
    ├── avg_price_by_neighbourhood.png
    ├── price_by_room_type_boxplot.png
    ├── availability_vs_price.png
    ├── reviews_vs_price.png
    ├── top_neighbourhoods.png
    └── correlation_heatmap.png
```

## How to Run

```bash
pip install -r requirements.txt
python airbnb_analysis.py
```

## Key Insights

- Entire home/apartment listings command the highest average price, followed by private rooms and shared rooms.
- Price varies significantly by neighbourhood group, with central/high-demand areas priced well above outer areas.
- Listings with more reviews tend to cluster in the lower-to-mid price range, suggesting affordability drives booking volume.
- Availability throughout the year shows no strong linear relationship with price on its own.

## Demo Link

[GitHub Repository](#) <!-- paste your repo link here, and in your PPT -->
