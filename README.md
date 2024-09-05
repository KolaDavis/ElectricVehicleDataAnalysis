### README for Electric Vehicle (EV) Dashboard

![dashboard](https://github.com/user-attachments/assets/926f0cf7-0918-4d33-ac88-e369dfb985cb)

# Registered Electric Vehicle (BEVs + PHEVs) Analysis Dashboard

This Power BI dashboard provides a comprehensive analysis of Battery Electric Vehicles (BEVs) and Plug-in Hybrid Electric Vehicles (PHEVs) registered across multiple states. The dashboard is designed to provide insights into the adoption of electric vehicles in the U.S., focusing on metrics like total registrations, electric range, vehicle manufacturers, and MSRP. It helps users explore and analyze the data from various perspectives, such as vehicle type, make, model, and region.

---

## Key Features

### 1. **Total Vehicles Registered**
   - A card displaying the total number of registered electric vehicles (200,044 vehicles). This gives an immediate high-level overview of all BEVs and PHEVs registered in the dataset.

### 2. **Registered EVs by Type**
   - Pie chart dividing the vehicle population into Battery Electric Vehicles (BEVs) and Plug-in Hybrid Electric Vehicles (PHEVs), breakdown showing that 78.46% of the vehicles are BEVs, while 21.54% are PHEVs. This provides insight into the more popular type of electric vehicle among consumers.

### 3. **Total Vehicles Registered by Model Year and EV Type**
   - Line chart displaying total vehicle registrations by model year, with a breakdown between BEVs and PHEVs. This visualisation helps track the growth of electric vehicle adoption over time, with a clear upward trend from 2012 to 2024. A spike around 2023 indicates the peak of vehicle registrations.
     
![image](https://github.com/user-attachments/assets/e699bb91-0391-432c-925b-3d5783bae140)

### 4. **Average Electric Range by Make**
   - Bar chart displaying the average electric range (in miles) for different vehicle manufacturers (e.g., Jaguar, Chevrolet, Nissan, Tesla). Jaguar has the highest average electric range of 204.50 miles, while other brands like Chevrolet and Nissan have a lower range. This helps users compare the efficiency and battery capacity across manufacturers.
     
![image](https://github.com/user-attachments/assets/5a5e9ca7-b334-4308-9b57-2051c9e0f7ef)

### 5. **Total Vehicles Registered by Make**
   - Bar chart showing the total number of vehicles registered by vehicle manufacturer (Make). Tesla is the clear leader in electric vehicle registrations, with over 88,000 vehicles, followed by Chevrolet and Nissan. This chart reveals which brands dominate the electric vehicle market.

### 6. **Highest Base Manufacturer's Suggested Retail Price (MSRP) by Model**
   - TreeMap showing the highest base MSRP for different EV models (e.g., Roadster, Model S, XC90). The Roadster leads with a base MSRP of $111,000, followed by the Model S ($70,000) and XC90 ($65,000). This visualisation gives insights into the most expensive EV models in the market.
     
![image](https://github.com/user-attachments/assets/49ade662-ca9d-4e8c-98a9-f8e1e93dfe27)

### 7. **Average of Base MSRP by EV Type**
   - Pie chart showing the average base MSRP split between BEVs and PHEVs. The average base MSRP for BEVs is $1.47K (84.61% of the dataset), while PHEVs have an average MSRP of $0.80K (35.39%). This helps compare the pricing strategies of both types of vehicles.

### 8. **Total Vehicles Registered by State and Make**
   - Map visualisation with state-wise registrations. This map allows users to analyse the geographic spread of electric vehicles, helping identify hotspots of adoption and which brands are popular in certain regions.

## Filters

- **City Filter**: Allows users to filter the data by specific cities, providing detailed insights into local EV adoption.
- **Utility Filter**: Enables filtering based on utility providers.
- **EV Type Filter**: Users can toggle between BEVs and PHEVs, to narrow down the visualisations based on the type of electric vehicle.
- **State Filters**: Includes multiple states like Washington, California, Texas, and more, allowing for state-level comparisons and analysis.


## Insights and Applications

This dashboard is designed for various stakeholders in the electric vehicle ecosystem, including:

- **Policymakers**: To track EV adoption trends across different states and regions and to understand the most popular EV types and manufacturers.
- **Automotive Manufacturers**: To analyse competitive positioning by examining electric range, market share by model, and regional performance.
- **Energy Providers and Utilities**: To evaluate where EV adoption is highest, potentially informing infrastructure planning for EV charging stations.
- **Consumers**: To get a sense of which EV models are the most popular, which brands offer the highest electric range, and compare vehicle prices.

## Future Improvements

- **Time-Based Analysis**: Adding forecast functionality to predict future trends in electric vehicle registrations.
- **Advanced Comparisons**: Enhancing comparisons between various states and cities based on incentives, charging infrastructure, and vehicle availability.
- **EV Charging Station Data**: Integrating data on EV charging station locations and availability for more context.


## Credits

- **Designed by**: K. Davis, 2024
- **Data Source**: Washington State Department of Licensing (DOL)
