# Demand-and-Supply-Analysis
Analyzed demand and supply using a cab ride dataset to explore gaps between ride requests and driver availability. Identified patterns in peak hours, shortages, and supply trends. Useful for optimizing resource allocation, reducing cancellations, and building predictive demand models.
🔍 Project Objective
-Understand the core concepts of demand (ride requests) and supply (available cabs).

-Quantify the demand-supply gap by analyzing timestamps and statuses of rides.

-Uncover patterns in unmet demand, peak hours, and driver shortage trends.

-Visualize insights to support data-driven decision-making for cab dispatch and driver allocation.

📁 Dataset Description
The dataset includes:

-Request ID: Unique ride request identifier

-Pickup Point: City or airport pickup

-Status: Trip Completed, Cancelled, or No Cars Available

-Request & Drop Timestamps: Time of ride request and completion

-Driver ID: Available only for completed trips

This data allows us to:

-Track ride demand over time

-Analyze cancellations due to unavailability

-Explore temporal and spatial trends in ride fulfillment

🛠 Tools & Libraries
-Python 3

-Pandas & NumPy – data manipulation and preprocessing

-Matplotlib & Seaborn – data visualization

-Jupyter Notebook – development and analysis interface

📈 Key Insights
-Most unmet demand occurs during morning (5–10 AM) and evening (5–10 PM) peaks.

-Airport pickup point suffers more from cab unavailability compared to city pickups.

-A significant portion of trips were not completed due to driver unavailability, rather than user cancellations.

-Weekend behavior differs from weekdays in both demand and supply.

📊 Visualizations Included
-Demand and supply trends by hour

-Heatmaps showing peak demand gaps

-Status-wise trip breakdown

-Comparison of city vs. airport pickups

🔮 Future Scope
-Develop a forecasting model to predict ride demand and driver availability using time-series or regression techniques.

-Apply clustering (e.g., K-Means) to segment high-demand pickup zones.

-Extend the project into a real-time dashboard for dispatch optimization.
