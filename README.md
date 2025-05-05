# 🛍️ E-Commerce User Behavior Dashboard | Google Analytics + Power BI

This is a self-initiated analytics project where I explored user behavior on a simulated e-commerce platform using **Google Analytics 4 (GA4)** data from **BigQuery**, processed it in **Python**, and visualized it using **Power BI**.

## 🚀 Project Overview

The goal was to identify:
- Where users drop off in the buying process
- How different products and locations influence sales
- Opportunities to optimize conversion and engagement

The final output is an **interactive Power BI dashboard** that includes:
- **Sankey Chart** showing the user journey from session start to purchase
- KPI tiles for Conversion Rate, AOV, Revenue, Bounce Rate, etc.
- Cart Analysis (CTR, BTDR, Cart Abandonment)
- Revenue breakdown by product category and city

## 🧠 Key Findings
- **Cart Abandonment Rate**: 81.67% – most users drop off after adding to cart
- **Buy-to-Detail Rate**: < 1% – low conversion across popular products
- **Top Revenue Cities**: Johor Bahru, New York, Agra
- Major user drop-off between **begin_checkout** and **add_payment_info** steps

## 🛠️ Tools & Technologies
- **Google BigQuery** – source of raw GA4 data
- **Python (pandas, google.cloud)** – for data querying, transformation, and feature engineering
- **Power BI** – for dashboard design and data storytelling
- **Excel** – intermediate step for data import into Power BI

## 📁 Project Structure
