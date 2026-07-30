# 🚲 Bike Sharing Data Analysis

## 📌 Project Description
This project is an in-depth Exploratory Data Analysis (EDA) of a Bike Sharing dataset. The primary focus of this analysis is to understand how weather conditions affect the number of rentals and to uncover behavioral differences between casual and registered users.

## 🎯 Business Questions
This project aims to uncover actionable insights and answer the following business questions:
1. How do weather conditions (weather situation, temperature, humidity, windspeed) affect bike rentals, and how can we optimize bike availability accordingly?
2. What are the key differences in behavior between casual and registered users, and how can we increase casual user conversion to registered users?

## 🛠️ Technologies and Libraries Used
- **Programming Language:** Python
- **Main Libraries:** Pandas, NumPy, Matplotlib, Seaborn
- **Environment:** Jupyter Notebook

## 🚀 How to Run the Project

### Setup & Usage (via Google Colab)

To make it easy to run and explore this analysis without setting up a local environment, you can use Google Colab:

1. **Open Google Colab:** Go to Google Colab.
2. **Import the Notebook:** Select the GitHub tab, paste the link to this repository (https://github.com/ML25-DadanRamdani/bike-sharing-data-analysis/tree/main), and open the `Notebook.ipynb` file.
3. **Upload Datasets:** On the left sidebar of Google Colab, click the Files icon (folder shape). Upload the `day.csv` and `hour.csv` files into the Colab environment.
4. **Run the Analysis:** Click on the cells and press `Shift + Enter` to run them sequentially. You can explore the data wrangling process, interact with the visualizations, and read the business insights directly in your browser.

## 📂 Repository Structure
```text
├── data/
│   ├── day.csv          # Bike sharing dataset (daily aggregation)
│   └── hour.csv         # Bike sharing dataset (hourly aggregation)
├── Notebook.ipynb       # Jupyter Notebook containing the full data analysis process
├── README.md            # Repository documentation
└── requirements.txt     # List of required Python libraries
