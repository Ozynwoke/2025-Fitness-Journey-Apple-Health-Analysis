# 2025 Fitness Journey – Apple Health Movement Analysis

A personal fitness analytics project using Apple Health data to track daily movement, exercise intensity, and progress throughout 2025. The project focuses on steps, walking distance, active calories, and exercise minutes, summarized and visualized with Power BI.

The goal is to show consistency, effort, and resilience — not just weight loss — and to demonstrate how everyday health data can be turned into a story of progress.

---

## Project Roadmap

This project follows a simple, structured workflow:

1. **Project Setup**
   - Define goals, metrics, and time period (January–November 2025).
   - Export Apple Health movement data.
   - Store data and Power BI assets in a clean GitHub structure.

2. **Data Collection & Preparation**
   - Export daily movement records from Apple Health.
   - Build a clean table with:
     - Date  
     - Steps  
     - Walking distance (km)  
     - Flights climbed  
     - Active calories  
     - Exercise minutes  
     - Activity intensity flag (Low / Moderate / High)

3. **Data Modeling**
   - Load data into Power BI.
   - Create date table (if needed) for time intelligence.
   - Build relationships and calculated measures:
     - Average daily steps  
     - Average daily walking distance  
     - Average active calories  
     - Average exercise minutes  
     - Activity intensity distribution

4. **Dashboard Design**
   - Create a **single-page Power BI dashboard** themed as:

     **“My 2025 Fitness Journey”**

   - Key elements:
     - Big KPIs for:
       - Average daily steps  
       - Average daily calories  
       - Average daily walking distance (km)  
       - Average daily exercise minutes  
     - A **monthly step trend** line/area chart.
     - Filters for period selection (e.g., last N months).
     - Motivational message and hero image for the journey.

5. **Insights & Storytelling**
   - Summarize the story in clear points:
     - How consistent daily movement has been.
     - How many days are **High / Moderate / Low** activity.
     - How exercise time and steps align with goals.
     - What changed over months (peaks, dips, recovery periods).

---

## Dataset – Apple Health Daily Movement

The main dataset is stored in:

`data/apple_health_daily_activity_2025.csv`

Each row represents **one day** of movement.  
Columns:

| Column              | Description                                                                 |
|---------------------|-----------------------------------------------------------------------------|
| `Date`              | Calendar date (YYYY-MM-DD)                                                  |
| `Steps`             | Total steps taken that day                                                  |
| `WalkingDistance_km`| Total walking distance (in kilometers)                                      |
| `FlightsClimbed`    | Flights of stairs climbed                                                   |
| `ActiveCalories`    | Active calories burned (Apple Health / Watch estimate)                      |
| `ExerciseMinutes`   | Exercise minutes recorded for the day                                      |
| `ActivityFlag`      | Intensity classification: `Low`, `Moderate`, or `High` based on activity    |

### ActivityFlag Logic (Conceptual)

- **High** – Very active days with high steps and long exercise time  
- **Moderate** – Good movement but not peak effort  
- **Low** – Light activity or recovery days

> This field can be used to analyze how often intense movement happens compared to moderate or low days.

---

## Key Metrics (from Dashboard)

From the Power BI dashboard (January–November 2025):

- **15K** – Average daily steps  
- **12 KM** – Average daily walking distance  
- **766** – Average daily active calories  
- **138 mins** – Average daily exercise minutes  

These metrics show **high overall movement intensity** across the year, with a mix of high-activity and recovery days.

---

## Dashboard Preview

Dashboard screenshots are stored in:

`Dashboard Visuals/`

Example file naming:

- `Dashboard Visuals/2025-fitness-journey-dashboard.png`

The dashboard highlights:

- Hero section titled **“MY 2025 FITNESS JOURNEY”**
- A profile / running image
- KPI cards for steps, calories, distance, and exercise minutes
- A **Monthly Step Trend** chart showing volatility and consistency over the year
- Quote box to capture the mindset behind the journey

---

## Skills Demonstrated

- Data sourcing from Apple Health
- Data structuring and manual data cleaning
- Metric and KPI design for personal analytics
- Power BI dashboard design and layout
- Insight storytelling using real-world health data
- GitHub project organization for analytics portfolios

---

## Tools Used

- **Apple Health / Apple Watch** – Source of raw movement data  
- **Excel / CSV** – For organizing daily exports before loading into Power BI  
- **Power BI** – For modeling, DAX measures, and dashboard visuals  
- **GitHub** – For version control and portfolio presentation  

---

## How to Use This Project

1. **Clone or download** the repository.  
2. Open the `data/apple_health_daily_activity_2025.csv` file to review the daily data.  
3. Open the Power BI file in the `powerbi/` folder (once added) to explore the model, measures, and visuals.  
4. Adapt the structure to your own Apple Health export if you want to recreate a similar personal fitness dashboard.

---

## About

This project documents a plus-size fitness journey where **consistency and resilience** matter more than size. The focus is on showing up daily, tracking effort honestly, and turning raw movement data into a story of growth.
