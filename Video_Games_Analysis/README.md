# Unlocking the Secrets of Video Game Sales! 

Hey there, fellow gamer and data enthusiast!   
This project is all about diving deep into the fascinating world of video game sales. We’ve got a massive dataset of game sales figures and a neat Jupyter Notebook to help us uncover some cool trends and insights. Ever wondered which games sold the most, or which platforms dominated different eras? Let’s find out!

---

## What’s Inside?

### **1. vgsales.csv**
This is our treasure trove of raw data!  
A CSV file packed with information on over **16,500 video games.** Each row gives you details like:

- **Rank:** The game’s overall sales ranking
- **Name:** The title of the game
- **Platform:** Which console or system the game was released on (e.g., Wii, PS2, PC)
- **Year:** The year of release (data spans from 1980 to 2020!)
- **Genre:** What type of game it is (e.g., Sports, Action, Role-Playing)
- **Publisher:** The company that released the game
- **NA_Sales, EU_Sales, JP_Sales, Other_Sales:** Sales figures in millions for North America, Europe, Japan, and other regions, respectively
- **Global_Sales:** Total worldwide sales in millions

### **2. Video_Games_Analysis.ipynb**
Your interactive Jupyter Notebook!  
This is where we clean, explore, and visualize the sales data to get some awesome insights.

---

##

The notebook starts by prepping the data—dropping rows with missing release years or publishers. That leaves us with **16,291 valid entries**. Then, the real fun begins!

### **Overall Sales & Trends**
- **Global Sales:** Ranges from just **0.01 million** up to a whopping **82.74 million** units!
- **Average Sales:** The typical game sold about **0.54 million** units globally.
- **Timeline:** The data tracks sales from **1980 to 2020**, showing peaks and valleys in the industry over time.

### **Top Games by Global Sales**
Here are the top 3 best-selling games globally:
1. **Wii Sports:** 82.74 million units sold!
2. **Super Mario Bros. (NES):** 40.24 million units sold
3. **Mario Kart Wii:** 35.82 million units sold

### **Top Platforms by Total Sales**
Platforms that raked in the most sales:
- **Wii:** 14.2% of total sales!
- **PS2:** 12.5%
- **PS3:** 8.4%
- **DS:** 8.3%
- **Xbox 360:** 7.9%

### **Popularity of Game Genres by Global Sales**
Gamers’ favorite genres:
- **Action:** 1,748.26 million global sales
- **Sports:** 1,330.93 million
- **Shooter:** 1,037.17 million
- **Role-Playing (RPG):** 923.83 million
- **Platform:** 829.13 million

### **Regional Sales Insights**
Sales can vary a lot by region:
- **NA_Sales (North America):** Often the highest sales
- **EU_Sales (Europe):** Usually the second-largest market
- **JP_Sales (Japan):** A unique market with its own preferences
- **Other_Sales:** Covers the rest of the world

### **Top Publishers**
Nintendo is a major player, appearing as the publisher for many top-selling games, along with:
- **Nintendo**
- **Electronic Arts**
- **Activision**
