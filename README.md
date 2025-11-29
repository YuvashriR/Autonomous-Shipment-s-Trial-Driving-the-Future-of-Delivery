🤖 Autonomous Shipment Trial — Driving the Future of Delivery
Multi-Criteria Decision Analysis (WSM) + Linear Optimization

This project demonstrates how autonomous delivery robots can be selected and allocated for commercial trials using MCDA (Weighted Sum Model) and Linear Optimization.
The analysis evaluates multiple robot prototypes based on capacity, speed, battery life, cost and reliability — helping identify the best-performing robot and optimal deployment strategy.

📍 Problem Statement

A retail chain plans to trial autonomous robot delivery across three store types:

🛒 Grocery Store

👗 Clothing Store

🏏 Sports Equipment Store

To execute the rollout efficiently, the company must choose:

Which robot prototype should be deployed?

How many robots should be allocated to each store?

How to maximize daily order fulfillment under budget + labor constraints?

🔍 Techniques Used
Method	Purpose
MCDA — Weighted Sum Model (WSM)	Select best robot prototype
Min-Max Normalization	Standardize criteria during evaluation
Positive Ideal Solution (PIS) / Negative Ideal Solution (NIS)	Benchmark model for ranking
Linear Optimization	Maximize order processing per day
Decision Recommendation	Allocation strategy for trial deployment
🧠 Dataset Attributes
Criteria	Objective
Carrying Capacity	Maximize 📈
Battery Size	Maximize 📈
Average Speed	Maximize 📈
Cost per Unit	Minimize 📉
Reliability	Maximize 📈

Resulting PIS and NIS values were computed for weighted ranking.

🔥 Key Findings
🔹 Best Robot Prototype → Deviant

Highest reliability

Strongest battery performance

Fastest operational speed

Despite a slightly higher cost, it delivers maximum operational efficiency.

📦 Final Allocation Strategy (Optimal)
Store Type	Robots Assigned
Grocery Store	19
Clothing Store	5
Sports Store	5

📌 Total Robots Deployed: 29
📌 Max Orders Fulfilled Per Day: 221
📌 Fits budget, labor & operational constraints ✔

🧾 Summary

This project proves how analytical decision models help industries adopt autonomous delivery systems efficiently.
Using WSM for robot selection + Optimization for task allocation, we achieved:

Goal	Achieved?
Best robot identified	✔ Deviant
Maximum delivery capacity	✔ 221/day
Budget + labor compliance	✔ Fully satisfied
Strategic resource deployment	✔ Optimized
🚀 Future Enhancements

Introduce energy consumption + maintenance cost criteria

Build simulation model for real-time route efficiency

Add stochastic optimization for demand fluctuations

Visual dashboard for management decision making

⭐ If this work interests you — Feel free to star the repository!
