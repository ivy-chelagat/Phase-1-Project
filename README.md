# Aircraft Risk Analysis for Business Expansion  

## Project Overview  
 As our company considers expanding into the aviation industry, it's critical to make informed and data-backed decisions about which aircraft types to invest in for both private and commercial operations. This project analyzes aviation accident data to identify trends, assess risk levels, and recommend safer aircraft models for investment.
The analysis spans data from 1962 to 2023, sourced from the National Transportation Safety Board (NTSB). It focuses on understanding how accident patterns vary across aircraft types, locations, causes, and severity levels to guide strategic aviation investments.

## Business Understanding

**Stakeholder:**  
Company executives and business development managers responsible for expansion strategy and investment in aircraft assets.

**Key Business Questions:**
- Which aircraft models and engine types are safest for investment?
- What are the most common causes of aircraft accidents?
- Which flight phases and locations pose the highest safety risks?
- What strategies can minimize operational risk in aviation?

## Tools and Technologies
Python: Data cleaning, analysis and visual exploration (Pandas, Matplotlib, Seaborn)
Tableau: Dashboard creation and presentation of key insights for stakeholders

## Data Understanding and Analysis

### Source of Data
The dataset was obtained from the **National Transportation Safety Board (NTSB)** public records and includes detailed reports of aircraft accidents from 1962 to 2023.

###  Description of Data
The dataset includes:
- **Aircraft Make & Model**
- **Accident Location**
- **Injury Severity** (Fatal, Serious, Minor)
- **Engine Type** (Turboprop, Piston, Jet, etc.)
- **Phase of Flight** (Takeoff, Cruise, Landing, etc.)
- **Weather Conditions**
- **Probable Cause of Accident**

### Key Visualizations

1. **Total Fatal Injuries by Flight Phase:**
   ![Total Fatal Injuries by Flight Phase (1)](https://github.com/user-attachments/assets/df5ebb94-c735-4251-b8a0-14dcb03d0044)

While many accidents fall under "unknown" flight phase, the high numbers during cruise and maneuvering suggest that risks persist even in stable flight. Training and monitoring should cover the entire flight path.

   
2. **Accidents by Aircraft Make:**  
  ![Accidents by Aircraft Make (1)](https://github.com/user-attachments/assets/369db53f-e18a-46a6-affc-37b07d4ff4b0)

Brands like Cessna, Piper, and Beech appear frequently, but they also dominate the market.
High accident counts may reflect high usage, not necessarily high risk. These models still deserve closer risk analysis based on severity


3. **Accident Trends Over Time:**  
   ![Accident Trends Over Time (1)](https://github.com/user-attachments/assets/c43cf4db-fc90-44d8-9bee-97d249541897)

 Safety standards, better training, and improved aircraft systems are working. This is the right environment for safe investment.


   _These same visualizations are presented in the Jupyter Notebook and the final Tableau Dashboard._

## Key Insights
Aircraft Type Matters.
Accident Phases: Many incidents occur outside takeoff and landing — especially during cruise and maneuvering, pointing to training gaps.
Weather Is a Major Risk Factor: Poor weather conditions and incomplete data frequently contribute to accidents, highlighting the need for better preparedness and reporting.

## Recommendations
Invest in Aircraft with Proven Safety Records:
Focus on reliable models like Cessna with turboprop or modern reciprocating engines that offer solid performance and lower risk.
Enhance Full-Phase Pilot Training:
Expand training to include less-emphasized flight phases like cruising and maneuvering, where many avoidable accidents occur.
Strengthen Weather Preparedness:
Equip aircraft with advanced weather detection tools, provide weather-specific training, and encourage complete, accurate reporting to reduce weather-related incidents

## Conclusion
This analysis shows that aviation safety is influenced by aircraft design, pilot readiness, and environmental factors.
By understanding these patterns, our company can invest in the aviation sector more confidently and responsibly — reducing risk while enabling sustainable growth.
