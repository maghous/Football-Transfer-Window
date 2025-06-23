# 🌍 2025 Summer Football Transfer Window Dataset

This dataset contains all **professional player transfers** completed during the **Summer 2025 window**, just before the upcoming **2025 FIFA Club World Cup**.

## 📌 Dataset Overview

- 🔁 Total Transfers: 1208
- 🌐 Global Coverage: Top-tier, second-tier, and regional leagues
- 📥 Data Source: Scraped from Transfermarkt

## 📊 Features

| Column          | Description                                      |
|-----------------|--------------------------------------------------|
| `name`          | Player’s full name                               |
| `position`      | Playing position (e.g., CB, LW, CAM)             |
| `age`           | Player’s age at the time of the transfer         |
| `market_value`  | Estimated pre-transfer market value              |
| `country_from`  | Country of the player’s former club              |
| `league_from`   | League of the former club                        |
| `club_from`     | Previous club name                               |
| `country_to`    | Country of the new club                          |
| `league_to`     | League of the new club                           |
| `club_to`       | New club name                                    |
| `fee`           | Transfer fee (if publicly disclosed)             |
| `loan`          | Boolean flag indicating if the transfer is a loan|

## 📈 Use Cases

- Analyze pre-Club World Cup transfer trends  
- Visualize global player flows between clubs/leagues  
- Rank clubs by transfer activity  
- Compare loan vs. permanent deals  
- Study correlation between market value and fee  
- Build scouting models or transfer forecasts  

## 📊 Upcoming:
A full EDA (Exploratory Data Analysis) notebook will be shared, including visuals and network analysis.

---

**Data Source**: Transfermarkt (via web scraping)
