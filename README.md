# 🧠 EDA_Laptop: Exploratory Data Analysis on Laptop Market Trends

## 📌 Overview

This project delves into the intricacies of the laptop market by performing comprehensive Exploratory Data Analysis (EDA) on a curated dataset. The goal is to uncover patterns, correlations, and insights that influence laptop pricing and specifications. Key areas of focus include:

* **Brand Analysis**: Understanding how different brands position themselves in the market.
* **Laptop Types**: Differentiating between gaming, ultrabooks, and budget laptops.
* **Component Analysis**: Investigating the impact of RAM, storage, processors, and GPUs on pricing.
* **Screen Specifications**: Examining how screen size and resolution affect market trends.
* **Price Distribution**: Analyzing pricing strategies and their alignment with specifications.

## 📊 Dataset

The dataset comprises various attributes such as:

* `Price`: Retail price of the laptop.
* `Brand`: Manufacturer of the laptop.
* `RAM_size`: Size of the RAM in GB.
* `Storage_Type`: Type of storage (e.g., SSD, HDD).
* `Processor`: Processor details.
* `GPU`: Graphics processing unit details.
* `Screen_Size`: Diagonal size of the screen in inches.
* `Resolution`: Screen resolution.
* `Weight`: Weight of the laptop in kilograms.
* `Warranty`: Warranty period in years.

## 🔍 Key Insights

Through the analysis, several noteworthy observations were made:

* **Brand Premium**: Brands like Apple and Microsoft command higher average prices due to premium features and build quality.
* **Component Impact**: Laptops with higher RAM sizes, SSD storage, and dedicated GPUs tend to have higher specifications scores and, consequently, higher prices.
* **Screen Specifications**: Larger screen sizes and higher resolutions are correlated with increased pricing.
* **Touchscreen Trend**: Touchscreen laptops are more prevalent in premium segments.

## 📂 Repository Structure

The repository contains the following files:

* `EDA.ipynb`: Jupyter notebook containing the exploratory data analysis.
* `data_cleaning.ipynb`: Notebook for cleaning and preprocessing the raw dataset.
* `cleaned_laptop.csv`: Cleaned dataset ready for analysis.
* `laptop.csv`: Raw dataset before cleaning.
* `laptop_csv_maker.ipynb`: Script to generate the dataset from raw data.
* `selenium_code.py`: Web scraping script to gather laptop data.

## 🚀 Getting Started

To replicate the analysis:

1. Clone this repository:

   ```bash
   git clone https://github.com/MeghOffical/EDA_Laptop.git
   cd EDA_Laptop
   ```

2. Install the required libraries:

   ```bash
   pip install -r requirements.txt
   ```

3. Run the Jupyter notebooks:

   ```bash
   jupyter notebook data_cleaning.ipynb
   jupyter notebook EDA.ipynb
   ```

## 🧪 Dependencies

* `pandas`: Data manipulation and analysis.
* `numpy`: Numerical computing.
* `matplotlib`: Plotting and visualization.
* `seaborn`: Statistical data visualization.
* `beautifulsoup4`: Parsing HTML pages for web scraping.
* `selenium`: Web scraping.

## 📝 License

This project is open source feel free to contribute it.

---

## 🙋 About the Creator

👤 **Megh Bavarva**  

I'm deeply passionate about **data science** and **data-driven storytelling**.  
This project was built as a way to apply **real-world data analysis** using IPL cricket data, and to showcase how raw CSVs can be transformed into actionable insights through APIs and dashboards.  

My primary interests are:
- **Data wrangling and feature engineering**
- **Building analytics pipelines**
- **Working with Pandas, NumPy, and ML tools**
- **Solving real-world problems using data**

Feel free to fork, star, or collaborate on data-focused projects!

🔗 GitHub: [@MeghOffical](https://github.com/MeghOffical)

