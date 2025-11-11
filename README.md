# Week 11: Python Data Science Labs
## CSC 2053 - Platform Based Computing - Lab 12

This week, we're diving deep into **data science with Python**. You'll learn how to analyze, visualize, and map real sports radio affiliate data using industry-standard tools: **Pandas**, **Matplotlib**, **Seaborn**, and **Folium**.

---

## 📊 The Labs

### Part 1: Python & Pandas Foundations
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/CSC-2053-100-Fall25/python-datascience-template/blob/main/Lab1_Python_Pandas_Foundations.ipynb)

**What You'll Learn:**
- Advanced Python concepts (list comprehensions, lambda functions)
- NumPy for numerical computing
- Introduction to Pandas DataFrames
- Loading and exploring real datasets

---

### Part 2: Pandas Deep Dive - Sports Radio Analysis
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/CSC-2053-100-Fall25/python-datascience-template/blob/main/Lab2_Pandas_Data_Analysis.ipynb)

**What You'll Learn:**
- Filtering and selecting data with boolean indexing
- Grouping and aggregation for insights
- Sorting and ranking data
- String operations on text fields
- Complex multi-condition queries

**Real Questions You'll Answer:**
- Which teams have the most affiliates?
- What ownership groups dominate sports radio?
- Which formats are most popular?
- How are stations distributed geographically?

---

### Part 3: Data Visualization - Sports Radio Dashboard
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/CSC-2053-100-Fall25/python-datascience-template/blob/main/Lab3_Data_Visualization.ipynb)

**What You'll Learn:**
- Matplotlib fundamentals for plotting
- Pandas built-in plotting methods
- Seaborn for beautiful statistical graphics
- Professional styling and customization
- Creating multi-panel dashboards

**What You'll Create:**
- Bar charts of ownership groups and formats
- Geographic distribution visualizations
- Power distribution histograms
- Comprehensive sports radio dashboards

---

### Part 4: Interactive Mapping - Visualizing Sports Radio Networks
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/CSC-2053-100-Fall25/python-datascience-template/blob/main/Lab4_Interactive_Mapping.ipynb)

**What You'll Learn:**
- Creating interactive maps with Folium
- Custom markers with popups and tooltips
- Layer controls for complex data
- Advanced features: clustering, heatmaps, coverage circles
- Mapping team-specific affiliate networks

**What You'll Create:**
- Interactive maps of all station locations
- Team affiliate network visualizations
- Power-based coverage area maps
- Multi-sport broadcasting empire dashboards
- Maps you can save and share as HTML files

**Estimated Time:** 90 minutes

---

## 🏈 Choose Your Sport!

Each lab lets you pick your favorite sport and analyze its radio affiliate data:

- **MLB** - Major League Baseball (821 stations)
- **NHL** - National Hockey League (209 stations)
- **NFL** - National Football League (845 stations)
- **NBA** - National Basketball Association (252 stations)

Simply change the `sport` variable in the first code cell:
```python
sport = "MLB"  # or "NHL", "NFL", "NBA"
```

---

## 📁 The Dataset

All labs use real RadioLand affiliate data covering:

### Columns
- **frequency** - Station frequency (MHz)
- **callsign** - Station call letters (e.g., "WXPN", "KROQ")
- **state** - State/province abbreviation
- **city** - City name
- **erp** - Effective Radiated Power (kW)
- **lat/lon** - Geographic coordinates
- **new_format** - Radio format (Sports, News/Talk, Country, etc.)
- **owner** - Broadcasting company
- **market** - Nielsen market designation
- **population** - Market population
- **mlb/nhl/nfl/nba** - Team affiliations

### Data Source
All CSV files are hosted in this repository:
- [MLB.csv](https://raw.githubusercontent.com/CSC-2053-100-Fall25/python-datascience-template/main/MLB.csv)
- [NHL.csv](https://raw.githubusercontent.com/CSC-2053-100-Fall25/python-datascience-template/main/NHL.csv)
- [NFL.csv](https://raw.githubusercontent.com/CSC-2053-100-Fall25/python-datascience-template/main/NFL.csv)
- [NBA.csv](https://raw.githubusercontent.com/CSC-2053-100-Fall25/python-datascience-template/main/NBA.csv)

---

## 🚀 Getting Started

### Option 1: Google Colab (Recommended)
1. Click any "Open in Colab" badge above
2. The notebook will open in Google Colab
3. Select your sport in the setup cell
4. Run the cells in order (Shift+Enter)
5. Complete the exercises marked with `# YOUR CODE HERE`

### Option 2: Local Jupyter
1. Clone this repository
2. Install dependencies: `pip install pandas numpy matplotlib seaborn folium`
3. Launch Jupyter: `jupyter notebook`
4. Open any lab notebook
5. Follow the instructions

---

## 📚 What You'll Master

By completing these labs, you'll gain real-world skills in:

### Data Analysis
- Loading and cleaning datasets
- Filtering and selecting relevant data
- Aggregating and summarizing information
- Finding patterns and insights

### Data Visualization
- Creating professional charts and graphs
- Choosing the right visualization for your data
- Building comprehensive dashboards
- Telling stories with data

### Geographic Analysis
- Mapping spatial data
- Creating interactive visualizations
- Analyzing geographic patterns
- Building web-based map dashboards

### Python Libraries
- **Pandas** - The standard for data analysis
- **NumPy** - Fast numerical computing
- **Matplotlib** - Foundational plotting library
- **Seaborn** - Beautiful statistical graphics
- **Folium** - Interactive web mapping


---

## 📝 Submission

1. Save your notebook
2. Download as `.ipynb` file (File → Download → Download .ipynb)
3. Submit to your GitHub repo

---
