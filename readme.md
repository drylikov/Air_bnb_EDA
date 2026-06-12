# Airbnb Listings EDA Project (Python).

## 📌 Project Overview
In this project i performed a complete **Exploratory Data Analysis (EDA)** on a large **Airbnb listings dataset (20,000+ rows)**.  

The goal of this project is to practice **data cleaning, exploration, visualization, and insight generation** using Python and its popular libraries.

---

## 🛠️ Tech Stack & Libraries
- **Python** (Jupyter Notebook)  
- **Pandas** → Data manipulation & analysis  
- **NumPy** → Numerical computations  
- **Matplotlib** & **Seaborn** → Data visualization  
- **Power of EDA** → Statistical analysis, cleaning & insights  

---

## 📂 Dataset
- **Name**: `New York Airbnb Listings`  
- **Size**: ~20,770 rows × 22 columns  
- **Features include**:  
  - `id, name, host_id, host_name`  
  - `neighbourhood_group, neighbourhood, latitude, longitude`  
  - `room_type, price, minimum_nights, number_of_reviews`  
  - `reviews_per_month, availability_365, bedrooms, bathrooms`  

📥 The dataset can be downloaded from file `dataset.csv`.

---

## 📑 Step-by-Step Workflow
1. **Import dependencies** (`pandas`, `numpy`, `matplotlib`, `seaborn`)  
2. **Load dataset** (`pd.read_csv`)  
3. **Initial exploration** (head, tail, shape, info, describe)  
4. **Data cleaning**  
   - Handle missing values  
   - Remove duplicates  
   - Fix data types (IDs, host IDs → objects)  
5. **Univariate Analysis**  
   - Price distribution (histogram, boxplot)  
   - Availability distribution  
6. **Bivariate Analysis**  
   - Price vs Neighbourhood  
   - Reviews vs Price (scatter plot)  
   - Room types across neighbourhoods  
7. **Feature Engineering**  
   - Create `price_per_bed` column  
   - Groupby analysis (`neighbourhood_group` & `price per bed`)  
8. **Advanced Visualizations**  
   - Pair plots (multivariate relationships)  
   - Geospatial scatter plots (latitude vs longitude)  
   - Correlation heatmaps  

---

## 📊 Key Insights
- Most Airbnb listings are priced between **$10 – $400**, with outliers above $1,000.  
- **Manhattan & Brooklyn** have the highest average prices.  
- **More reviews** tend to appear on lower-priced listings.  
- **Price and number of bedrooms** show strong positive correlation.  
- Geospatial plots reveal dense clusters of Airbnb listings in NYC neighborhoods.  

---

## 🚀 How to Run
1. Clone this repo:
   ```bash
   git clone https://github.com/your-username/airbnb-eda.git

2. Install Dependencies:
    ```bash
    pip install pandas numpy matplotlib seaborn

3. Open Jupyter Notebook and run the AirBNB_EDA file

---