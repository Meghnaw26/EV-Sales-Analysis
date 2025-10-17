# ⚡ Electric Vehicle (EV) Sales Analysis 

---

## Project: Data Analyst/ Data Science (EDA & Visualization)

---

##  Overview
This project explores **Electric Vehicle (EV) sales trends** across regions, vehicle types, and years.  
The goal is to identify **market growth patterns, EV adoption trends across India and consumer adoption insights** using **Python (Jupyter Notebook)** and **Tableau**.

- Analyzed how EV sales have evolved over the years  
- Compared sales across different vehicle categories  
- Visualized adoption trends by geography and time
- Built Machine Learning Model to predict the EV sales
- Present findings through an interactive Tableau dashboard
  
---

###  Tools & Technologies Used
| Tool | Purpose |
|------|----------|
| **Python (Pandas, Numpy, Matplotlib, Seaborn)** | Data cleaning, Analysis, and Visualization |
| **Jupyter Notebook** | Exploratory data analysis (EDA) |
| **Tableau** | Interactive dashboards and storytelling |
| **Excel/CSV** | Data source format |

---

### Data Preprocessing and Feature Engineering 
- Removed irrelevant columns
- Encoded Categorical variables using One Hot Encoding
- Reduced the number of unique values making it sparse classes for better Model making

---

### Predictive Modeling
- Built a baseline Dummy Regressor model to set a reference performance for predicting EV sales.
- Developed a Linear Regression model to capture linear relationships between features and EV sales.
- Implemented a Random Forest Regressor, which outperformed both the baseline and linear models in terms of accuracy and predictive power.
- Evaluated all models using metrics such as RMSE, MAE, and R² score to compare their performance.
- Selected the Random Forest model as the final predictive model for EV sales forecasting due to its superior performance.

---

### Key Insights
- 2-Wheelers and 3-Wheelers are the most popular vehicle categories for electric vehicles, with sales in these categories far exceeding others like 4-Wheelers and Buses.
- The data shows a growing trend in electric 2W and 3W, which are more affordable and practical for urban areas
- The M-Cycle/Scooter class dominates, indicating the increasing adoption of electric scooters and bikes.
- E-Rickshaw (Passenger) and Motor Cars are also contributing to the overall EV sales but at a lower rate compared to scooters.
- This also points towards the possibility of regional policies, incentives, or infrastructure developments contributing to these sales.
- The EV sales have grown exponentially from 2014 to 2023, with noticeable growth in the last few years.
- May and November have shown the highest EV sales in 2023, suggesting possible seasonal trends or promotions during these months.
- A geographic analysis reveals significant adoption in states like Uttar Pradesh, Maharashtra, Tamil Nadu, and Gujarat, while states like Kerala, West Bengal, and North-East regions are still lagging behind

---

### Conclusion and Recommendations
1. **Focus on Expanding Infrastructure:**
   - Given that UP, MH, and KN are leading the charge in EV adoption, further government investments and incentives should be directed towards these regions for building infrastructure (charging stations, service centers) to support the increasing number of EVs.
   - Other states like Kerala and Bihar can benefit from similar infrastructure investments to improve their EV adoption rates.
  

2.	**Promote Electric 2-Wheelers and 3-Wheelers:**
   - Since electric 2-wheelers and 3-wheelers represent a significant portion of the market, targeted marketing and campaigns to raise awareness about the benefits of electric scooters in urban and semi-urban regions should be continued.
   - Collaborations with local transport providers could be explored to increase the adoption of E-Rickshaws.


3.	**State-Specific Policies:**
   - 	Tailored state-level incentives and subsidies could boost adoption further. Each state could have customized plans considering local infrastructure and population density.
   -  Special focus should be given to underperforming states like West Bengal, Mizoram, and the North-Eastern regions, where EV adoption is still low.


4.	**Month-Wise Marketing Campaigns:**
   - Since May and November have high sales, manufacturers and distributors could focus on seasonal offers and discounts during these months.
   - Events or awareness campaigns around the May-June period could see even higher sales growth.


5.	**Invest in Electric Car Infrastructure:**
   - Although electric motor cars have a lower share compared to two- and three-wheelers, the rise in environmental consciousness suggests that electric cars will gain traction. Investing in charging infrastructure for cars, particularly in top-performing states, could ensure long-term adoption.


6.	**Sustain Growth through Continuous Data Monitoring:**
   -  Regular data audits and updates are essential for understanding the market dynamics and adjusting strategies based on sales trends.
   -  Companies should continue monitoring monthly trends to identify any dips or surges in sales and adjust campaigns or production accordingly.

---






