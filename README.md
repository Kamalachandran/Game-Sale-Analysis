# 🎮 Video Game Sales Analysis

This project analyzes video game sales data from an SQLite database (`sale.db`).  
It uses **Python**, **SQLite**, **Pandas**, **Matplotlib**, and **Seaborn** to generate insights and visualizations.

---

## 📊 Dataset Description

The dataset comes from the table `game_sales` in `sale.db`.

| Column        | Description |
|---------------|-------------|
| position      | Position in sales ranking |
| name          | Game title |
| platform      | Console/PC system |
| year          | Release year |
| genre         | Type of game (Action, RPG, etc.) |
| publisher     | Company that released the game |
| na_sales      | North America sales (in millions) |
| eu_sales      | Europe sales (in millions) |
| jp_sales      | Japan sales (in millions) |
| other_sales   | Sales in other regions (in millions) |
| global_sales  | Total worldwide sales (in millions) |

---

## ⚙️ Setup & Requirements

Install dependencies:

```bash
pip install pandas matplotlib seaborn sqlite3 missingno  
```

Ensure you have `sale.db` in the project folder.

Run the script:

```bash
python game_sales_analysis.ipynb
```

---

## 📈 Analysis & Charts

The script generates several charts to visualize the data:

1. **Game Sales by Genre and Region**
   - **Stacked Bar Chart** → Compare how different regions contribute to sales per genre.
   - ![Example](Game%20Sales%20by%20Genre%20and%20Region.png)

2. **Top 5 Games by Global Sales**
   - **Pie Chart** → Show each game’s share of global sales.
   - ![Example](Top%205%20Games%20by%20Global%20Sales.png)

3. **Game Sales by Region**
   - **Donut Chart** → Overall sales distribution across regions.
   - ![Example](Game%20Sales%20by%20Region.png)

4. **Top 10 Wii Games**
   - **Bar Chart** → Compare global sales for the top-selling Wii games.
   - ![Example](Top%2010%20Wii%20Games.png)

5. **Average Global Sales per Genre**
   - **Bar Chart (Seaborn)** → Highlight which genres tend to perform better on average.
   - ![Example](Global%20Sales%20per%20Genre.png)

6. **Global Sales of Popular Games by Year (Before 2000)**
   - **Line Chart with Annotations** → Show sales trends of highly successful older games.
   - ![Example](Global%20Sales%20of%20Popular%20Games%20by%20Year.png)

---

## 📝 Chart Explanation

- **Bar chart** → Compare global sales for each game/genre/platform.  
- **Stacked bar chart** → Show contribution of each region to total sales.  
- **Pie chart** → Show each game’s share of global sales.  
- **Donut chart** → Variant of pie chart for regional share.  
- **Line chart** → Show sales trends across years for selected games.  

---

## 📂 Project Structure

```
├── sale.db                      # SQLite database
├── game_sales_analysis.py        # Python analysis script
├── README.md                     # Project documentation
├── Game Sales by Genre and Region.png
├── Top 5 Games by Global Sales.png
├── Game Sales by Region.png
├── Top 10 Wii Games.png
├── Global Sales per Genre.png
└── Global Sales of Popular Games by Year.png
```

---

## ✅ Conclusion

This project demonstrates how video game sales vary by **region**, **genre**, and **platform**, while also identifying **top-performing games** across time.

---
