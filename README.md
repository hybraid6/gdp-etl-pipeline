# ETL Pipeline for GDP Data from Archived Wikipedia

## 📌 Project Overview
This project demonstrates an **Extract-Transform-Load (ETL)** process using Python to scrape, clean, and save GDP (Nominal) data from an archived Wikipedia page.

The pipeline:
1. **Extracts** GDP data from a Wayback Machine snapshot of Wikipedia.
2. **Transforms** the raw data by cleaning country names, removing unwanted rows, and converting GDP figures into billions of USD.
3. **Loads** the cleaned data into a CSV file and visualizes the top 10 countries by GDP.

---

## 🛠 Technologies Used
- **Python 3**
- **Pandas** – Data manipulation
- **Requests** – HTTP requests
- **BeautifulSoup4** – HTML parsing
- **Matplotlib** – Data visualization
- **Jupyter Notebook** – Interactive coding environment

---

## 📂 Project Structure
```

gdp-etl-pipeline/
│
├── GDP_ETL_Pipeline.ipynb    # Jupyter Notebook with ETL steps
├── Countries_by_GDP.csv      # Cleaned GDP data (output)
├── etl_project_log.txt       # Log file with ETL process steps
├── README.md                 # Project documentation
└── requirements.txt          # Python dependencies

````

---

## 🚀 How to Run
1. **Clone the Repository**
   ```
   git clone https://github.com/<your-username>/gdp-etl-pipeline.git
   cd gdp-etl-pipeline
   ```

2. **Install Dependencies**

   ```
   pip install -r requirements.txt
   ```

3. **Open in Jupyter Notebook**

   ```
   jupyter notebook
   ```

   Then open `GDP_ETL_Pipeline.ipynb` and run cells step-by-step.

---

## 📊 Example Output

Sample of cleaned GDP data:

| Country       | GDP\_USD\_billion |
| ------------- | ----------------- |
| United States | 25900.00          |
| China         | 17930.00          |
| Japan         | 4230.00           |
| Germany       | 4040.00           |
| India         | 3730.00           |

---

## 📈 Visualization

The notebook includes a **Top 10 GDP Countries** horizontal bar chart for quick insight.

---

## 📝 License

This project is open-source and available under the [MIT License](LICENSE).

---

## 🙌 Acknowledgments

* Data source: [Wikipedia - List of countries by GDP (nominal)](https://en.wikipedia.org/wiki/List_of_countries_by_GDP_%28nominal%29) (archived via Wayback Machine).
* Libraries: Pandas, BeautifulSoup4, Requests, Matplotlib.
