# **Optimization of Marketing Expenses in Yandex.Afisha: Analysis and Recommendations**  

## **Project Description:**  
This project focuses on optimizing the marketing expenses for the Yandex.Afisha platform. The primary goal is to analyze the effectiveness of various marketing channels to identify the most profitable traffic sources. This analysis will help redistribute the budget, increase the return on investment (ROI), and enhance long-term strategic planning.

## **Dataset:**
The visits table (server logs with data on website visits):
- Uid — user's unique identifier
- Device — user's device
- Start Ts — session start date and time
- End Ts — session end date and time
- Source Id — identifier of the ad source the user came from

The orders table (data on orders):
- Uid — unique identifier of the user making an order
- Buy Ts — order date and time
- Revenue — Yandex.Afisha's revenue from the order

The costs table (data on marketing expenses):
- source_id — ad source identifier
- dt — date
- costs — expenses on this ad source on this day

## **Tools Used:** 
- Python (pandas, numpy, matplotlib, seaborn, plotly)  
- Exploratory Data Analysis (EDA)  
- DAU, WAU, MAU, average session duration, retention rate
- LTV, CAC, ROI
- Сohorts
