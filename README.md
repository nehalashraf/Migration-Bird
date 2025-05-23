# 🐦 Migration Bird Dashboard - Power BI Project

## 📌 Overview

This project presents a comprehensive **Power BI Dashboard** that analyzes bird migration patterns using real-world inspired tracking data. The dataset includes environmental, biological, and behavioral data collected from tagged birds during migration journeys.

The goal is to visualize and interpret how various factors—such as weather, altitude, region, flock size, and food availability—influence migration success and behavior.

---

## 📊 Dashboard Features

- **Migration Route Mapping:** Visualizes start and end coordinates of each bird's migration.
- **Flight Performance Metrics:** Shows average speed, altitude range, distance, and duration.
- **Environmental Analysis:** Highlights how temperature, humidity, wind speed, and visibility affect migration.
- **Success & Interruption Analysis:** Analyzes reasons for interrupted migrations and correlates them with weather or biological issues.
- **Flock Behavior:** Tracks whether the bird migrated solo or in a flock, along with flock size.
- **Battery & Signal Tracking:** Monitors tag battery levels and signal strengths during flight.
- **Interactive Filtering:** Allows filtering by species, habitat, region, migration months, and more.

---

## 🛠️ Tools & Technologies

- **Power BI**: For data modeling, visualization, and dashboard design
- **Power Query**: For data cleaning and transformation
- **DAX (Data Analysis Expressions)**: For calculated columns and measures

---

## 📁 Dataset Fields (Sample)

| Column                    | Description                                         |
|--------------------------|-----------------------------------------------------|
| Bird_ID                  | Unique identifier for each bird                     |
| Species                 | Bird species name                                   |
| Region, Habitat         | Ecological region and habitat type                  |
| Weather_Condition       | Conditions during flight                            |
| Start/End Latitude/Longitude | Migration start and end points                  |
| Flight_Distance_km       | Distance traveled during migration                  |
| Max/Min Altitude_m       | Altitude range during flight                        |
| Migration_Reason         | Why the bird migrated (e.g., breeding, food)        |
| Migration_Success        | Indicates whether the migration was completed       |
| Migration_Interrupted    | Boolean flag + reason                               |

---

## 📈 Key Insights

- Most successful migrations occurred with moderate temperatures and low wind speeds.
- Birds in larger flocks had higher nesting success.
- Tag battery level had a strong correlation with tracking quality and recovery success.
- The majority of interrupted migrations were due to extreme weather or signal loss.

---

## 🙋‍♀️ Author

**Nehal Ashraf**  
📌 Data Engineer | Specialized in data pipeline design, analytics & dashboard development  
🔗 [LinkedIn Profile]((https://www.linkedin.com/in/nehal-ashraf22/)) *(replace with your actual profile)*

---

## 📎 Screenshot

![Dashboard Preview](path-to-dashboard-image.png)

---

## 📜 License

This project is for educational and portfolio purposes. Data is synthetic and for demonstration only.

