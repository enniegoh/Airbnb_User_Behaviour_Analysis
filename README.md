# Airbnb User Behavior Analysis

## Project Overview
Analyzed Airbnb session log data from **135,000+ users** to engineer behavioral features for booking intent prediction. Built interpretable user personas and identified friction points impacting conversion.

## Key Objectives
- Transform raw clickstream data into user-level behavioral features
- Build user intent personas (price-sensitive, communicator, visual-oriented, trust-seeker)
- Identify friction points for churn intervention

## Tech Stack
- Pandas, NumPy

## Key Features Engineered
| Feature | Description |
|---------|-------------|
| `conversion_rate` | Actual booking conversion rate per user |
| `regret_ratio` | Abandonment / cancellation frequency |
| `decision_complexity` | (Searches + Evaluations) / Booking attempts |
| `price_intensity` | Price-related action frequency |
| `browsing_depth` | Detail page views / search result views |

## 👤 User Personas
- **Price Seeker** – actively applies coupons
- **Proactive Communicator** – frequently contacts hosts
- **Visual-Oriented** – engages with photos content
- **Trust Seeker** – checks reviews
