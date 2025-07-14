# Steam_Games_Analysis

# SteamDecoded: A Data-Driven Look into Game Trends and Player Behaviour

Welcome to **SteamDecoded**, a comprehensive end-to-end data analytics project built using **Power BI**, **Python**, **SQL**, and **Excel**. This project analyzes over 89K+ games from the Steam platform to uncover what makes a game successful, popular, or engaging.

---

## 📌 Problem Statement

The video game industry is saturated with titles, but only a few stand out in terms of success, popularity, and engagement. This project aims to uncover:

* What characteristics define successful games?
* Do factors like age rating, localization, genre, or release timing affect popularity?
* How do playtime, pricing, and multiplayer features impact engagement?

---

## 🧠 Key Learnings

* Hands-on experience with real-world, unstructured data
* Built and deployed a star + snowflake schema in Power BI
* Developed advanced DAX KPIs and dynamic visuals
* Used Python for data extraction, cleaning, and structuring
* Applied data storytelling techniques to guide business decision-making

---

## 📂 Dataset

The dataset was sourced from **Steam’s March 2025 snapshot**, containing detailed attributes like:

* Game metadata (title, release date, developer, genres, tags)
* Reviews (positive/negative, scores)
* Playtime and ownership estimates
* Supported languages, platforms, multiplayer types, etc.

Original source: [Kaggle Steam Dataset](https://www.kaggle.com/datasets/artermiloff/steam-games-dataset)

---

## 🔄 Data Extraction & Structuring

Raw data was initially messy, containing nested lists, dictionaries, and stringified arrays.

### 🐍 Data Preparation using Python:

* Flattened columns like genres, tags, developers, publishers, platforms, and languages
* Separated each into relational tables using `pandas` and `json` parsing
* Created 8 final tables: `games`, `genres`, `categories`, `tags`, `languages`, `developers`, `publishers`, and `platforms`

The cleaned dataset follows a **star + snowflake schema**, ideal for Power BI modeling.

---

## 📊 Dashboard Overview

The dashboard includes **8 interactive pages**:

| Page                              | Question Addressed                                                     |
| --------------------------------- | ---------------------------------------------------------------------- |
| **1. Overview**                   | What are the top games by ownership and hidden gems by rating?         |
| **2. Ratings & Reviews**          | Which games are loved or criticized most by players?                   |
| **3. Release Timing**             | Does release month or season affect game success?                      |
| **4. Playtime vs Reviews**        | Is there a link between game length and positivity?                    |
| **5. Price & Revenue**            | How does price impact popularity and revenue potential?                |
| **6. Longevity & Yearly Trends**  | Which release years had the highest impact?                            |
| **7. Multiplayer Insights**       | Which formats (PvP, Co-op, MMO) drive higher playtime?                 |
| **8. Localization & Age Ratings** | Do games with more supported languages or teen ratings perform better? |

---

## 📌 Key Insights

* Games with **6–15 supported languages** perform best in terms of reach.
* **Teen-rated games (12–17)** achieve the best balance between ratings and audience size.
* Multiplayer games (esp. Co-op) show **higher retention and engagement**.
* Release timing around **Q4** correlates with stronger performance.
* Longer playtime **does not necessarily** mean better reviews (weak correlation).

---

## 🛠️ Tools & Technologies

* **Power BI**: Visualization, DAX measures, modeling
* **Python (Pandas, Regex, JSON)**: Data cleaning & table generation
* **Excel**: Exploratory analysis
* **SQL** (via pandas & Excel): Filtering & logic building

---

## ⚠️ Disclaimer

> This project is for educational purposes only. Steam and the Steam logo are trademarks of Valve Corporation. This project is not affiliated with or endorsed by Valve.

---

## 💬 My Words

Every project has room to grow — including this one! Feel free to raise connect with me through mail or LinkedIn.

---

**Connect with me:**
LinkedIn - [Click Here](https://www.linkedin.com/in/aditya-sai-veligatla-783b64342/)
