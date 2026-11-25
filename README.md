# u19-basketball-social-media-analytics
# 🏀 U-19 Girls Basketball League 2083 — Social Media & Campaign Engagement Tracker

🔗 **[View Live Interactive Dashboard in Google Sheets](https://docs.google.com/spreadsheets/d/1f9qqUp-j7jl7vvMUkxxpXiA_IRO9Uy-lgoGt30Y2rPg/edit?usp=sharing)**

---

## 📌 Project Overview
Analyzed multi-platform social media performance for **Let's Go Basketball Academy's U-19 Girls Basketball League 2083** (`Jun 17 – Oct 7, 2026`) across **Instagram**, **Facebook**, and **TikTok** (`478` total records: `255` Facebook posts, `113` Instagram daily records, `110` TikTok daily records).

**Goal:** Measure reach, engagement rate, Month-over-Month (MoM) growth, and post-type/schedule performance to recommend a higher-performing content strategy.

---

## 🛠️ Tools & Spreadsheet Skills Used
- **Tools:** Google Sheets (compatible with Microsoft Excel)
- **Formulas & Modeling:** `XLOOKUP`, `SUMIFS`, `COUNTIFS`, `IFERROR`, `IFS`, `IF`, `TEXT`, `HOUR`, MoM Growth `%`
- **Dashboarding:** Multi-tab Data Modeling (`Lookup_Tables` → `Monthly_Summary` → `Dashboard`), Pivot Tables, Line/Bar Charts, Interactive Slicers

---

## 📊 Headline Metrics (Verified)
- **1,044,689** Combined Reported Views (`779,189` Instagram | `153,686` Facebook | `111,814` TikTok)
- **296,796** Combined Summed Reach (`197,423` Instagram | `99,373` Facebook)
- **5,848** Total Engagements (`3,560` TikTok | `2,288` Facebook)
- **2.30%** Facebook Engagement Rate *(by Reach)* | **3.18%** TikTok Engagement Rate *(by Video Views)*

---

## 💡 Key Insights & Recommendations
1. **Platform Growth & Peak Timing:** Instagram generated **74.6%** of total views and peaked during **August Mid-Season** (`335,830` views), matching TikTok's August peak (`56,706` views). Facebook continued growing to a **September Playoffs** peak (`90,625` views).
2. **Post-Type Performance (Facebook):** Photos accounted for **75.3%** of all posts (`192/255`) and drove the highest total volume (`113,918` views), but **Videos (`639` avg views/post)** and the test **Reel (`1,318` views)** outperformed Photos (**`593` avg views/post**) on a per-post basis.  
   → *Recommendation:* Reallocate posting effort from static Photos toward short-form **Reels and Videos**.
3. **Recommended Posting Schedule (Facebook):**  
   → *Top Performing Day & Time:* **[INSERT YOUR WINNING DAY_OF_WEEK & TIME_SLOT HERE from Pivot Tables 3 & 4]**

---

## ⚠️ Data Modeling & Caveats
- **Granularity Separation:** Instagram and TikTok exports are **daily account-level** totals, while Facebook data is **post-level**. Raw tabs were kept separate and rolled up into a unified `Monthly_Summary` tab (`SUMIFS` / `COUNTIFS`) to avoid mixing "posts" with "days."
- **Metric Definitions:** Combined views and summed reach represent arithmetic totals across platforms/days rather than deduplicated unique users. Engagement Rate uses *Reach* as the denominator on Facebook and *Video Views* on TikTok.
- **Partial Month Caveat:** October (`2026-10`) covers only 7 days (`Oct 1–7`), explaining the negative MoM `%` drop compared to full 30-day September.

