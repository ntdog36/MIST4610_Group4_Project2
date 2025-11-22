# MIST 4610 Group Project 2

## Team Name and Members

62755 - Group 4

- Nathan Teal: https://github.com/ntdog36/MIST4610_Group4_Project2
- George Zupko: https://github.com/gvzupko/MIST4610_Group4_Project2
- Kelly Stephenson: https://github.com/kms25583-tech/MIST4610_Group4_Project2
- Kevin Wang:  https://github.com/kkw01911/MIST4610_Group4_Project2
- Alexis Melchiorre: https://github.com/amm-melch/MIST4610_Group4_Project2

## Our Data Set
Monthly and Annual Energy Consumption by Sector

It contains columns corresponding to the following items:
- Month/Year (1973-2024) (Date)
- Total Fossil Fuels Production (Number)
- Nuclear Electric Power Production (Number)
- Total Renewable Energy Production (Number)
- Total Primary Energy Production (Number)
- Primary Energy Imports (Number)
- Primary Energy Exports (Number)
- Primary Energy Net Imports (Number)
- Primary Energy Stock Change and Other (Number)
- Total Fossil Fuels Consumption (Number)
- Nuclear Electric Power Consumption (Number)
- Total Renewable Energy Consumption (Number)
- Total Primary Energy Consumption (Number)


- Total Rows: 631
- Total Columns: 13
- Units: Quadrillion Btu = 1,000,000,000,000,000 (10¹⁵) Btu

We found our data set on data.gov. The data set is provided by the Department of Energy.

## Importance of Our Selected Data Set
- Climate change
- Sustainability
- Limited resources such as fossil fuels  
- Shows progress toward goals
- Renewable vs non-renewable energy
- Drives future decisions
- Affects public health

The data set we selected on energy consumption is important because it helps us understand several critical issues that impact both our environment and society. By tracking how much energy we use and where it comes from, the data provides insight into climate change and our overall progress toward sustainability goals. It also highlights our continued dependence on limited resources such as fossil fuels, while allowing us to compare renewable and non-renewable energy sources. This information is essential for shaping future decisions around energy policy, technology investments, and environmental planning. Beyond environmental impacts, energy consumption patterns also affect public health, making the data set valuable for understanding broader community outcomes and long-term societal well-being.

## Question 1
### Which month experiences the highest/lowest rate of consumption by energy source?

*This question is important because it helps us understand…*

- At what point is the energy grid used most?
- At what point is the energy grid used the least?
- How do renewables different from traditional sources in month by month consumption. 
- Help understand which months will experience the highest and lowest energy costs.
- These results would provides actionable insights for grid designers that could improve reliability and support planning/investment.

No data manipulations were done for this question

Fossil Fuels:

<img width="350" height="304" alt="Screenshot 2025-11-21 at 2 03 06 PM" src="https://github.com/user-attachments/assets/599f51d2-53a6-47f8-ba90-54b63a6ab98f" />
<img width="334" height="307" alt="Screenshot 2025-11-21 at 2 03 40 PM" src="https://github.com/user-attachments/assets/d8055240-45ce-4846-b595-c25192323cfe" />

Nuclear:

<img width="337" height="326" alt="Screenshot 2025-11-21 at 2 04 04 PM" src="https://github.com/user-attachments/assets/b3bb7300-09a6-4bed-a216-3a531971711d" />
<img width="339" height="325" alt="Screenshot 2025-11-21 at 2 04 25 PM" src="https://github.com/user-attachments/assets/11dce790-c8ca-4a19-b958-3e8aa66d92ed" />

Renewable:

<img width="366" height="306" alt="Screenshot 2025-11-21 at 2 04 45 PM" src="https://github.com/user-attachments/assets/4f083344-f8e9-4d07-9492-e39aff22c48e" />
<img width="321" height="307" alt="Screenshot 2025-11-21 at 2 05 00 PM" src="https://github.com/user-attachments/assets/d2105860-2a44-4a40-aa8c-630d3981014e" />


Summary(High/Low):
- Fossil Fuels: January/September
- Nuclear Power: January/April
- Renewables: May/September
Trends: January seems to be the highest consumption rate, while September has the lowest. 

This means that grid operators need to build their grid to withstand the high demands of January. Gird operators could also schedule maintenance and upgrades to happen in September where the grid is under less strain. High energy usage industries like AI should use the September lows to reduce energy costs. The growth of AI(and AI energy costs) could also pose a threat to the grid in January as AI energy usage would be steady throughout the year so if grids are not properly upgraded power scarcity could become a real thing. Renewables usage peaks in the summer months which shows the importance of solar panels to that industry. This also shows how fickle and reliant on good weather renewables still are. 

## Question 2
### What is the predicted percentage of each energy consumption type out of total energy consumption in the next 10 years?

*This questions is important because it helps us understand…*

- How the energy mix will look in the next decade
- Identify which energy types are expected to increase/decrease
- Reveal how dependent we are on non-renewable energy sources 
- Highlight future investment needs in renewable energy infrastructure or energy storage
- These results would provide actionable insights that guide policy, sustainability goals, and long-term energy planning

Data Manipulation:
Created Fields - Percentage Fossil Fuel Consumption, Percentage Nuclear Consumption, Percentage Renewable Consumtpion
Purpose - 

<img width="848" height="547" alt="Screenshot 2025-11-21 at 1 45 01 PM" src="https://github.com/user-attachments/assets/89d70faa-00e2-4198-a33c-460cbb51987b" />

## Summary

Fossil Fuels are decreasing and expected to be at 81.36% in 2035.

Renewables are increasing and expected to be at 11.158% in 2035.

Fossil Fuels are decreasing slightly and are expected to be at 8.361% in 2035.

Overall Fossil Fuels will maintain their dominance over our energy consumption despite its decline. But, the renewable share is increasing rapidly. We could see this continue especially if the current governmental regulations and subsidies are maintained or increased. But we are unlikely to see renewables become the majority of our energy consumption for a long time. Unless there is a major breakthrough in renewables such as much longer lasting batteries or innovations in tidal power. Nuclear Power will likely maintain its steady decline til fusion technology become viable where we could see nuclear power rapidly become dominant.
