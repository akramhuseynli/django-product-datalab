# Django Product DataLab

A small Django project for working with product data from Excel and CSV files.

I built this project while practicing Django, pandas, data processing, and basic data visualization.

## What it does

- Upload product data from Excel or CSV files
- Clean and normalize uploaded data with pandas
- Save product records to a SQLite database
- List and filter products by date, category, name, and quantity
- Export product data to Excel
- Download an empty Excel template for product uploads
- Calculate monthly and quarterly income
- Show statistics by product category
- Find top products by revenue
- Show products with low stock
- Display statistics with Chart.js charts

## Tech used

- Python
- Django
- pandas
- SQLite
- openpyxl
- Chart.js
- HTML/CSS

## Main pages

- Dashboard
- Product list
- Product upload
- Statistics

## Running the project

Install the dependencies:

```bash
pip install -r requirements.txt
```

Go to the Django project directory:

```bash
cd datalab
```

Run the migrations:

```bash
python manage.py migrate
```

Start the development server:

```bash
python manage.py runserver
```

Then open:

```text
http://127.0.0.1:8000/
```