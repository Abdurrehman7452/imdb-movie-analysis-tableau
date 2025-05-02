# IMDb Movie Analysis & Tableau Visualization

This project involves a comprehensive analysis of the IMDb Top 1000 Movies dataset. The data was preprocessed using Python (Pandas), and multiple dashboards were created using Tableau to uncover patterns related to directors, genres, actors, and overall trends in ratings and gross revenue.

## 📁 Project Structure

- `MoviesData.csv` – Cleaned dataset after preprocessing
- Tableau Dashboards – Visualizations and stories created in Tableau (exported or linked separately)
- `report.docx` – Full analysis report describing steps, insights, and visualizations

## 📊 Tableau Dashboards

Three main dashboards and a story were developed in Tableau:

### Dashboard 1 – Directors Analysis
- **Top 10 Directors by Gross**
- **Directors with Most Votes**
- **Directors with Highest Meta Scores**

### Dashboard 2 – Genre & Star Insights
- **IMDB Ratings of Genres (1934–2014)**
- **Gross of Leading Stars in Top 5 Genres**
- **Runtime of Top 3 Genres (2000–2005)**

### Dashboard 3 – Series, Gross Trends & Certificates
- **Top 10 Series by IMDB Rating**
- **Gross Revenue Trends Over Time**
- **Certificate vs. Gross**
- **Audience Engagement with Leading Stars**

### Story – Combined Insights
- Combines key insights from all three dashboards into an interactive story format.

## 🧹 Data Preprocessing Steps

Performed using Pandas in Python:

- Dropped irrelevant columns (e.g., `Poster_Link`, `Overview`)
- Handled missing values with appropriate methods (mode, placeholders)
- Removed outliers and non-numeric entries
- Converted data types for consistency (`int`, `float`)
- Exported the cleaned dataset to CSV for Tableau analysis

## 🔧 Tools Used

- **Python (Pandas, NumPy)** – For data preprocessing
- **Tableau** – For visualization dashboards
- **Microsoft Word** – For report documentation

## 📌 How to Use

1. Clone this repository.
2. Open `MoviesData.csv` in your preferred tool or Tableau.
3. Load Tableau dashboards or recreate them using the report instructions.
4. Review the insights and visualizations for understanding trends in movie data.

## 📄 Author

**Muhammad AbdurRehman**  
BS Data Science – FAST NUCES  

---

