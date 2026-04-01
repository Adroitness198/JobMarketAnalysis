# 📊 Job Market Analysis — Glassdoor Data

A data analysis project exploring global job market trends using real Glassdoor job listings data. The project uses Python for data cleaning and analysis, and Tableau for interactive visualisation.

🔗 **Live Dashboard:** [View on Tableau Public](https://public.tableau.com/app/profile/sinethemba.mbatha/viz/GlobalJobMarketAnalysis/JobMarketAnalysis)

---

## 📌 Key Insights

- **Project Manager** and **Software Engineer** are the most in-demand roles globally
- **Business Analyst** is the top role in South Africa, followed by Project Manager
- **Internet, IT Services and Staffing & Outsourcing** are the top hiring industries in SA
- South Africa's average company rating (3.54) is slightly below the global average (3.72)
- Mid-size companies (1001–5000 employees) dominate job listings in SA

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|------|---------|
| Python (pandas) | Data cleaning and analysis |
| Matplotlib | Exploratory visualisations |
| Tableau Public | Interactive dashboard |
| Jupyter Notebook | Analysis environment |

---

## 📁 Project Structure

```
Job Market Analysis/
│
├── glassdoor.csv                  # Raw dataset (Glassdoor job listings)
├── glassdoor_cleaned.csv          # Cleaned global dataset
├── sa_jobs_clean.csv              # South Africa specific dataset
├── global_jobs_clean.csv          # Global cleaned dataset for Tableau
├── Job Market Analysis.ipynb      # Jupyter notebook with full analysis
│
└── charts/
    ├── top_jobs.png               # Top 15 global jobs chart
    ├── top_industries.png         # Top industries chart
    ├── top_za_jobs.png            # Top SA jobs chart
    ├── za_company_sizes.png       # SA company sizes chart
    └── ratings_comparison.png     # SA vs Global ratings chart
```

---

## 🚀 How to Run Locally

### Prerequisites
- Python 3.8+
- Jupyter Notebook
- pandas, matplotlib

### Steps

1. **Clone the repository**
   ```bash
   git clone https://github.com/Adroitness198/JobMarketAnalysis.git
   cd JobMarketAnalysis
   ```

2. **Install dependencies**
   ```bash
   pip install pandas matplotlib notebook
   ```

3. **Download the dataset**
   - Download the Glassdoor dataset from Kaggle: [Data Jobs Listing - Glassdoor](https://www.kaggle.com/)
   - Place `glassdoor.csv` in the project folder

4. **Run the notebook**
   ```bash
   jupyter notebook
   ```
   Open `Job Market Analysis.ipynb` and run all cells

---

## 📸 Screenshots
<img width="1654" height="811" alt="Screenshot 2026-04-01 222139" src="https://github.com/user-attachments/assets/d86e02be-868e-41df-af8c-942a294ea590" />



---

## 👤 Author

**Sinethemba Mbatha**
- GitHub: [@Adroitness198](https://github.com/Adroitness198)
- Tableau: [View Profile](https://public.tableau.com/app/profile/sinethemba.mbatha)

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).
