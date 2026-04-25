# 🌐 Data Science Projects

A collection of data analysis projects exploring real-world datasets, built with Python and pandas as part of my data science learning journey.

---
## 📁 Projects

### 1. 🌍 World Internet Users Analysis (`internet_analysis.ipynb`)

- Global internet user growth from 3 million (1990) to 5.3 billion (2022)
- Percentage of world population connected to the internet each year
- The year global internet usage crossed the 50% mark
- Internet penetration breakdown by continent over time

---
## 🔍 Key Findings

- Internet users grew from **3 million in 1990** to over **5.3 billion in 2022**
- It took only **7 years** (by 1997) to reach 100 million users
- The world crossed **50% internet penetration in 2019**
- **Europe** leads with ~87% penetration, while **Africa** remains the lowest at ~40% as of 2021

## 📁 Project Structure

```
├── data/
│   ├── world-internet-users.csv
│   ├── historical-world-population.csv
│   ├── extension-internetusers-by-continent.csv
│   └── extension-historicalpopulation-by-continent.csv
├── data-visualize1.ipynb
├── .gitignore
└── README.md
```

---

## 🛠️ Libraries Used

- `pandas` — data loading, merging, cleaning, and analysis
- `matplotlib` — line charts and visualizations

---

## ▶️ How to Run

1. Clone the repository
   ```bash
   git clone https://github.com/Saurav-kr7/your-repo-name.git
   cd your-repo-name
   ```

2. Create and activate a virtual environment
   ```bash
   python -m venv .venv

   # Windows
   .venv\Scripts\activate

   # Mac/Linux
   source .venv/bin/activate
   ```

3. Install dependencies
   ```bash
   pip install pandas matplotlib jupyter
   ```

4. Launch the notebook
   ```bash
   jupyter notebook internet_analysis.ipynb
   ```

---

## 📚 Data Sources

Datasets were sourced from the **Cisco Networking Academy** Data Science Essentials course and are included in the `/data` folder.

---

## 👨‍💻 About

This repo documents my self-learning journey into data science. I started 20 days ago and completed the **Cisco NetAcad Data Science Essentials with Python** certification, practicing pandas and matplotlib hands-on. More projects will be added here as I keep learning.