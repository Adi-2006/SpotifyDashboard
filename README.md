# 🎧 Spotify Listening Dashboard — Power BI Project

This project provides a deep dive into Spotify listening data using **Power BI**, focusing on user behavior across albums, artists, tracks, time patterns, and listening habits.

---

## 📌 Objective

To analyze personal Spotify history using Power BI, uncovering:
- Listening trends over years
- Most played tracks, albums, and artists
- Weekly and hourly listening patterns
- Impact of user behavior (shuffle/skipped)
- Correlation between track frequency and listening duration

---

## 📁 Files Included

| File Name               | Description |
|------------------------|-------------|
| `Spotify Dashboard.pbix` | Power BI dashboard file |
| `spotify_history.csv`    | Cleaned dataset used in Power BI |
| `Page-1.jpg`             | Dashboard - Overview |
| `Page-2.jpg`             | Dashboard - Listening Pattern |
| `Page-3.jpg`             | Dashboard - Detailed Table View |

---

## 🖼️ Dashboard Screenshots

### 🔹 1. Overview Dashboard

Visuals include:
- Albums Played: **7,379**
- Artists Played: **3,834**
- Tracks Played: **12,719**
- Yearly Trend Peak: **2021** for Albums (2,668), Artists (1,796), and Tracks (5,103)
- Latest Year (2024) Comparison:
  - Albums: **1,801** (↓ 20.24% from 2023)
  - Artists: **1,057** (↓ 24.50% from 2023)
  - Tracks: **3,508** (↓ 10.42% from 2023)

#### Top 5 Albums by Count:
| Album          | Count |
|----------------|-------|
| The Beatles    | 1,987 |
| Past Masters   | 1,627 |
| Abbey Road     | 1,360 |
| The Wall       | 1,139 |
| Revolver       | 982   |

#### Top 5 Artists by Count:
| Artist          | Count |
|------------------|--------|
| The Beatles      | 12.9k  |
| The Killers      | 6.1k   |
| John Mayer       | 4.3k   |
| Bob Dylan        | 3.5k   |
| Paul McCartney   | 2.6k   |

#### Top 5 Tracks by Frequency:
| Track Name (Truncated) | Count |
|------------------------|-------|
| Ode To The...          | 180   |
| In the Blood           | 168   |
| Dying Breed            | 164   |
| 19 Days & 50...        | 144   |
| Concerning... / For What It's... | 138 |

![Overview](Page-1.jpg)

---

### 🔹 2. Listening Pattern Analysis

#### ⏰ Listening Hours vs Days (Heatmap):
- Most active hours: **0 AM to 6 AM** and **7 PM to 11 PM**
- Highest single-hour total: **0 AM – 4,015 plays**
- Quietest hours: **10 AM – 579 plays**, **11 AM – 746 plays**

#### 🟢 Scatter Plot:
- Shows correlation between **Avg Listening Time (min)** and **Track Frequency**
- Majority of high-frequency tracks fall under **5 minutes**
- Few tracks are above 15 minutes and rarely played

![Listening Pattern](Page-2.jpg)

---

### 🔹 3. Detailed Table View

A breakdown of **album-wise data** including:
- Total Albums: **7,902**
- Total Artists: **4,111**
- Total Tracks: **13,659**
- Total Listening Time: **19.2 Billion ms (~5,333 hours)**
- Average Listening Time per Track: **2.14 minutes**

| Album Name                         | No. of Tracks | Avg Listening Time (min) |
|-----------------------------------|---------------|---------------------------|
| The Beatles                       | 137           | 1.51                      |
| Les Misérables (Live)             | 41            | 1.42                      |
| Abbey Road                        | 41            | 1.42                      |
| Pressure Machine                  | 29            | 3.37                      |
| Anthology                         | 25            | 1.93                      |
| Sigh No More                      | 25            | 2.39                      |
| Flaming Pie – Archive Collection | 23            | 2.62                      |
| Sticky Fingers                    | 22            | 2.20                      |
| My Love Songs (Expanded)          | 24            | 3.96                      |

![Details Table](Page-3.jpg)

---

## 📈 Key Insights

- 📅 **2021** was the peak listening year across albums, artists, and tracks.
- 🎸 **The Beatles** dominated across albums, tracks, and artist play counts.
- 🕛 Listening spikes occur **late at night and early morning**, especially between **12 AM – 6 AM**.
- 📉 Significant decline in 2024, possibly due to reduced usage or shifting platforms.
- 🔁 Most repeated tracks have shorter durations, typically **under 4 minutes**.
- 🔬 Detailed stats reveal some albums had an **average playtime of ~4 minutes**, suggesting focused listening.

---

## 🛠 Tools Used

- **Power BI** – For dashboard creation and visual storytelling
- **Excel** – For CSV pre-processing


---

## 📌 How to Use

1. Clone or download the repo.
2. Open `Spotify Dashboard.pbix` in Power BI Desktop.
3. Connect it to `spotify_history.csv` if prompted.
4. Use slicers (platform, year, shuffle/skip filter) to explore patterns.

---

## 🧠 Learnings

- Working with real-world streaming data and time series.
- Use of Power BI slicers for interactivity.
- Creating visuals like:
  - KPI Cards
  - Line Charts
  - Heatmaps
  - Scatter Plots
  - Donut Charts
- Deriving trends using DAX and calculated columns.

---

### 🔗 Author

Created by [Adi-2006](https://github.com/Adi-2006)  
📬 Love to hear your thoughts, feedback, or suggestions!

👉 Connect on [LinkedIn](https://www.linkedin.com/in/aditya-kumar-dwivedi-3702552aa/)

---

⭐️ *If you found this project interesting, drop a star and feel free to fork or reuse for your own analysis!*
