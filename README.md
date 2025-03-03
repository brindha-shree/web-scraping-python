# web-scraping-python
A web scraping project using Python and  BeautifulSoup to extract data from wikipedia
Here’s a **README.md** file for your **Wikipedia Web Scraping Project** that you can upload to GitHub.  

---

# **📌 Wikipedia Web Scraping | Largest US Companies by Revenue**  

## **📝 Project Overview**  
This project scrapes data from **Wikipedia's "List of Largest Companies in the United States by Revenue"** page using **Python, BeautifulSoup, and Pandas**. The extracted data is cleaned and stored in a structured format for analysis.  

---

## **🚀 Technologies Used**  
- **Python** 🐍  
- **BeautifulSoup** (for web scraping)  
- **Requests** (for HTTP requests)  
- **Pandas** (for data handling & exporting)  

---

## **📂 Project Structure**  
```
wikipedia-web-scraping/
│── data/                   # Folder for storing scraped data
│   ├── Companies.csv       # Output CSV file
│── scripts/                # Python script for scraping
│   ├── scraper.py          # Main web scraping script
│── README.md               # Project documentation
│── requirements.txt        # Python dependencies
```

---

## **⚙️ Setup & Installation**  
### **1️⃣ Clone the Repository**  
```bash
git clone https://github.com/your-username/wikipedia-web-scraping.git
cd wikipedia-web-scraping
```

### **2️⃣ Install Dependencies**  
```bash
pip install -r requirements.txt
```

### **3️⃣ Run the Scraper**  
```bash
python scripts/scraper.py
```

---

## **📊 Sample Output (First 5 Rows)**  
| Rank | Name  | Industry | Revenue (USD billions) | Employees | Headquarters |  
|------|------|----------|------------------|------------|--------------|  
| 1    | Walmart | Retail | $611.3 | 2,300,000 | Bentonville, Arkansas |  
| 2    | Amazon  | E-commerce | $502.2 | 1,540,000 | Seattle, Washington |  
| 3    | ExxonMobil | Oil & Gas | $413.7 | 62,000 | Irving, Texas |  

📌 The full dataset is saved as **Companies.csv** in the `data/` folder.  

---

## **📌 Key Features**  
✔ Scrapes **real-time data** from Wikipedia.  
✔ Extracts structured tabular data using **BeautifulSoup**.  
✔ Cleans and **saves data in CSV format** using Pandas.  
✔ Can be extended to **scrape other Wikipedia tables**.  



