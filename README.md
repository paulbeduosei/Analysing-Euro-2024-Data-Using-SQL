# Analysing-Euro-2024-Data-Using-SQL
🚀 Euro 2024 Data Analysis in SQL (DuckDB) — Event-Level Insights

I analyzed 838 football match events from Euro 2024 using SQL to understand scoring patterns, time distributions, and player impact.

Here’s the breakdown of what I did in each step:

1️⃣ Data Quality Check
Verified total rows + unique IDs to ensure the dataset was clean and had no duplicates.

2️⃣ Column Summary (Profiling)
Used SUMMARIZE to quickly review min/max, averages, and distributions across all fields.

3️⃣ Event Timing Analysis
Grouped events by match minute to see when actions (goals, cards, subs) peak.

4️⃣ 90th-Minute Event Breakdown
Examined what types of events occur at minute 90 — most were yellow cards + substitutions.

5️⃣ Added-Time (Extra Minute) Study
Analyzed how often referees extend the match (1–11 minutes of extra time).

6️⃣ Created 5-Minute Buckets
Transformed raw minutes into clean analytical time windows (0–5, 5–10, 10–15…).

7️⃣ Extracted All Goal Events
Created a clean goals dataset with standardized time formatting + buckets.

8️⃣ Goal Distribution by Match Period
Counted how many goals happen in each 5-minute window — spikes around 55’–75’.

9️⃣ “Joker Goals” Feature Engineering
Flagged goals scored within 15 minutes of a substitution (instant-impact players).

🔟 Highest-Scoring Matches

Identified the matches with the most goals — Germany vs Scotland led with 6.

This project helped me apply real SQL techniques—data profiling, grouping, feature engineering, and pattern detection—on a real-world sports dataset.
