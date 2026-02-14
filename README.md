# 🎵 Music Track Popularity Analysis

## 📌 Project Overview
This project explores the factors influencing music track popularity using exploratory data analysis (EDA) and statistical hypothesis testing.  
The goal is to understand whether musical attributes such as genre, energy, and danceability meaningfully impact track success and how these insights can support playlist curation decisions.

---

## 🎯 Objectives
- Analyze the distribution and characteristics of music track popularity
- Identify relationships between popularity and audio features
- Validate observed patterns using statistical hypothesis testing
- Translate analytical findings into actionable business insights

---

## 📊 Dataset Description
The dataset contains ~28,000 music tracks with:
- Track metadata (artist, album, release date)
- Audio features (danceability, energy, loudness, tempo, etc.)
- Playlist information (genre, subgenre)
- Popularity score (target variable)

---

## 🧹 Data Cleaning & Preprocessing
- Handled minimal missing values appropriately
- Standardized mixed date formats
- Verified valid ranges for all audio features
- Retained meaningful outliers representing real-world extremes

---

## 🔍 Exploratory Data Analysis (EDA)

### 🔹 Univariate Analysis
- Track popularity shows a right-skewed distribution (long-tail behavior)
- Audio features exhibit non-normal distributions
- Genre distribution is balanced, reducing bias
- High-cardinality categorical features treated as identifiers

### 🔹 Bivariate Analysis
- Genre shows statistically significant but practically small differences in popularity
- Weak linear correlations between popularity and individual audio features
- Musical mode (major/minor) has minimal impact on popularity

### 🔹 Multivariate Analysis
- Tracks with **moderate energy** and **higher danceability** tend to perform better
- Strong inter-feature correlations observed (e.g., energy–loudness)
- Popularity is influenced by combined effects rather than a single feature

---

## 🧪 Statistical Hypothesis Testing

### Tests Performed
- One-Way ANOVA (Genre vs Popularity)
- One-Way ANOVA (Energy Levels vs Popularity)

### Key Findings
- Genre and energy levels show statistically significant differences (p < 0.05)
- Effect sizes are small to moderate, indicating limited practical dominance
- Statistical significance does not imply strong business impact

---

## 💡 Key Business Insights
- Genre alone is not a strong predictor of track success
- Balanced musical attributes outperform extreme values
- Moderate energy and higher danceability increase engagement potential
- Popularity is multifactorial and influenced by external exposure factors
- High-performing tracks exist across all genres

---

## 🎧 Playlist Curation Recommendations
- Prioritize tracks with balanced energy and engaging rhythm
- Maintain genre diversity to maximize reach
- Monitor early performance signals to identify breakout tracks
- Combine data insights with editorial judgment

---

## 🛠 Tools & Libraries
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- SciPy, Statsmodels

---

## 📌 Conclusion
This project demonstrates a complete data analyst workflow—from data cleaning and EDA to statistical validation and business storytelling.  
The analysis highlights that music popularity is driven by complex, interacting factors rather than isolated audio characteristics.

---

## 👤 Author

**Hitesh Sirswa**
