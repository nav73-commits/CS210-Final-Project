# Pharmacy Database - Jupyter Notebook Instructions

The project has been converted into a single, comprehensive Jupyter Notebook (`Pharmacy_Database.ipynb`) to align perfectly with data science requirements and to provide an excellent format for your CS 210 oral exam defense.

## Prerequisites

To run this notebook locally, you will need Jupyter installed along with `pandas` for formatting SQL outputs as clean tables.

Open your terminal or command prompt and run the following command to install the necessary packages if you don't already have them:
```bash
pip install jupyterlab pandas
```

## How to Run

### Method 1: Using VS Code (Recommended)
1. Open this `Jupyter_Project` folder in **Visual Studio Code**.
2. Make sure you have the **Jupyter** and **Python** extensions installed in VS Code.
3. Click on the `Pharmacy_Database.ipynb` file to open it.
4. Click the **Run All** button at the top, or run each cell individually by clicking the Play icon next to the cell (or by pressing `Shift + Enter`).
5. A local `pharmacy_database.db` file will automatically be created in this directory as soon as the database initialization cell is run.

### Method 2: Using Jupyter Lab / Jupyter Notebook
1. Open your terminal or command prompt.
2. Navigate to this folder (`Jupyter_Project`).
3. Run the following command:
```bash
jupyter lab
# OR
jupyter notebook
```
4. This will open a browser window. Click on `Pharmacy_Database.ipynb` to open it.
5. Go to the top menu, click **Run > Run All Cells**, or execute them one by one using `Shift + Enter`.

## What's Included in the Notebook
- **Database Initialization**: Automatically creates the SQLite database and all the 3NF tables.
- **Data Management Functions**: Python wrappers for all SQL `INSERT`, `UPDATE`, and `DELETE` commands.
- **Demo Data Population**: Automatically inserts standard test data into all tables for demonstration.
- **Analytics & Queries**: Uses SQL combined with `pandas` to display comprehensive analytical reports (like Total Sales, Most Popular Medicines, and Customer Purchase Histories) in beautiful, easy-to-read data tables. This is highly effective for an oral presentation.

## Note on Cleanliness
This folder contains **only** the `.ipynb` file and these instructions, keeping your workspace clean and professional for your presentation or submission. All database data is stored in the auto-generated `.db` file within this directory when the notebook is run.
