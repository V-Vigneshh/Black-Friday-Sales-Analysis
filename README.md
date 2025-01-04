# Black Friday Sales Analysis Project

This project focuses on analyzing customer purchasing behavior during Black Friday sales. The goal is to uncover insights about customer demographics, spending patterns, and preferences.

## Dataset
The dataset used for this project contains transactional data, including details like customer ID, age, gender, occupation, product category, and purchase amount.

## Features
- **Analysis Conducted:**
  - Customer segmentation based on demographics (e.g., age, gender, and occupation)
  - Spending behavior analysis across different product categories
  - Insights into high-revenue customer groups
- **Tools and Techniques Used:**
  - Data cleaning and preprocessing using Python libraries (`pandas`, `numpy`)
  - Data visualization using `matplotlib` and `seaborn`
  - Statistical analysis for identifying trends

## Installation and Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/black-friday-sales-analysis.git
   cd black-friday-sales-analysis
   ```
2. Install the required libraries manually if needed (e.g., `pandas`, `numpy`, `matplotlib`, `seaborn`).

## Running the Project

1. Ensure the dataset is in the same directory as the code and named `black_friday_data.csv`.
2. Run the analysis script:
   ```bash
   BlackFridaySalesAnalysis.ipynb
   ```
3. The script will:
   - Load and preprocess the dataset
   - Perform the analysis
   - Generate visualizations and save them in the `output/` directory

## Results
- Identified key customer groups driving sales during Black Friday.
- Visualizations showcasing:
  - Spending trends by age and gender
  - Revenue contribution by product categories
  - Top-performing customer segments

## Future Improvements
- Explore predictive models to forecast sales trends.
- Integrate additional datasets to enhance analysis, such as customer satisfaction scores.
- Develop a dashboard for dynamic exploration of sales data.

## Folder Structure
```
.
├── BlackFriday.csv
├── BlackFridaySalesAnalysis.ipynb
└── README.md
