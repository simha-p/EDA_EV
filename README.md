***Distribution Analysis For EV'S***

![Ev](https://github.com/user-attachments/assets/c8a84d3c-bc8c-4e7c-b631-b3693849d4ca)


***Business***


EVCharge Utilities is a prominent electric utility provider.The company's Primary mission is to ensure reliabl delivery of electrical power to millions of customers.

The company has witnessed a significant Transformation in adoption of EV's as part of global efforts to reduce Carbon emissions and climate change


***Business Problem***

EVCharge Utilites encounters several critical challenges due to growing adoption of EV'S

*----Increase Load Demand ----*

Widespread EV adoption has caused a significant spike in electricity demand,This Strains the existing distribution of network

*---Grid overload---*

Frequent overloads in distribution network leads to voltage fluctuations and outages in some areas,affecting Grid reliability

*----Customer Satisfaction----*

Ev Owners except reliable and convenient charging services .Ensuring this level of service is essential to maintain customer satisfaction.

*---Cost Management---*

Balancing increased load demand.Company must optimize network to manage epense effectively.



***Scope of Project***


1.Exploratory Data Analysis
To gain insights into Electricity Consumption and Network Performance

2.Capacity Assessment
Using Historical Data to access the current network capacity and identify areas 

3.Network Optimization
To identify cost-effctive network-upgrades 

4.Recommendations
Present Insights,network upgrdes to  executive members for decisions 



***Exploratory Data Analysis***

**univariate Analysis**


1.visualize the distribution of elctricity consumption

2.Analyze the ev types,customer type, charging habits


![Screenshot 2024-07-21 002445](https://github.com/user-attachments/assets/03890419-edda-4e9a-943d-573c8533075d)


**BiVariate Analysis**


1.use geospitial_data to visualize locations of substations and EV charging stations.


![Screenshot 2024-07-21 005535](https://github.com/user-attachments/assets/8fabc63d-eabf-4277-a69c-4afebc7d4c98)


Zoom in One substation and its associated Ev Charging Stations


![Screenshot 2024-07-21 004848](https://github.com/user-attachments/assets/0ae14ee3-080b-4fbf-a661-71a41b242fdd)


**Observation:**

Ev Charging station is far from it's Substation, this could be contributing factor to grid overload.



**2.Analyze capacity of transmission lines**

*Network_Capacity_data*

![Screenshot 2024-07-21 010125](https://github.com/user-attachments/assets/16ee5cad-d5a9-4fb8-8399-1067f04a09bb)


**Correlatio_ratio**

Calculate correlation b/w Number of EV'S and Consumption Ratio


![Screenshot 2024-07-21 004937](https://github.com/user-attachments/assets/f8c05d51-50f9-4d94-a69f-7c8270b4b106)


**OBSERVATIONS:**

The Map above shows Consumption_to_Capacity_Ratio for each Substation

---substations in red,have higher consumption capacity ratio,indicating potential overloads in network

---substations in blue,have lower consumption capacity ratio,indicating network capacity is sufficient for load.

---The Correlation between EV's to overload is weak.so it can't uantified as teh reasons for overload.


**OPTIMIZING NETWORK Upgrades**

--- Upgrading transmission_lines/additional capacity in these areas can help in managing the increase load and grid reliability.

-- Geographical distributions of EV Charging stations because EV Stations are far from Substations.


**Correlation With Weather Data**

Analying correlation between Weather data and electricity consumption can provide insights into how weather affects distribution network.

![Screenshot 2024-07-21 011001](https://github.com/user-attachments/assets/bd0dd6f4-940e-46ca-a77b-ee1fa192b0f2)

The Correlation matrix shows the coefficients between Electricity,temperature and Preceptation are weak.

Visualize  correlation relationship b/w Electricity, Temperature and Preciption


![Screenshot 2024-07-21 005035](https://github.com/user-attachments/assets/6b3b8d4c-ce52-4dd8-a872-8f29b6746fee)

**OBSERVATIONS:**

Based on dataset,weather conditions have weak correlation with electricity consumption in distribution.others factors are more influential in affecting electricity consumption.

Its important to consider weather data because etreme weather conditions can impact on distribution network.


**Recommendations**

This is based on the analysis done and the business problems at hand, all these should be incorporated into the business.

Prioritize Substation Upgrades: Prioritize upgrades at substations where the Consumption_to_Capacity_Ratio is high, indicating potential overloads. Upgrade the transmission lines because the subsataions are too far from their corresponding Substations.

Geospatial Analysis for Upgrade Planning: Use geospatial analysis to determine the optimal locations for new substations or upgrades to existing ones. Consider factors like the proximity to high load demand areas (areas with high consumption to capcity ratio) and geographical constraints.

Demand Side Management: Implement demand-side management strategies to balance the load on the grid. Encourage customers to charge their EVs during off-peak hours through incentives or dynamic pricing.

Advanced Monitoring and Analytics: Deploy advanced monitoring systems to continuously monitor the health and performance of the distribution network. Use analytics to predict potential issues and take preventive action.

Cost-Benefit Analysis: Conduct a comprehensive cost-benefit analysis for different upgrade options. Consider factors like the cost of upgrades, operational costs, potential revenue from increased capacity, and the impact on service reliability and customer satisfaction.

Customer Engagement: Engage with customers to understand their needs and expectations. Provide clear communication about network upgrades and how they will enhance service reliability and meet the growing demand for EV charging.

Continuous Improvement: Continuously monitor and assess the performance of the distribution network. Gather feedback from customers and other stakeholders, and use this feedback to make further improvements and optimizations.

By following these steps, EVCharge Utilities can develop an effective optimization strategy to manage the increased load demand from EV charging stations, ensure the reliability and resilience of the distribution network, and meet the expectations of customers, all while optimizing costs and ensuring regulatory compliance.

