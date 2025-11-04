
# **SARIMA Forecasting for Travel Data**

### **Author:** A. Maria Nivetha  
**College:** Kumaraguru College of Technology  
**Roll No:** 22BAD058  

---

## **1. Aim of the Project**
The goal of this project is to predict how many people will use different transport services—such as Light Rail, Local Route, Rapid Route, and School buses—over the next 7 days.  
The dataset contains daily travel data along with details like holidays and lockdown periods.

---

## **2. Insights from the Dataset**
- Consistent ridership trends with minor weekly fluctuations.  
- Light Rail and Rapid Route show the highest and most stable demand.  
- Local Route and School services display dips during holidays.  
- Peak Service varies slightly, showing shifting commuter behavior.  
- Overall, travel usage is reliable with no major disruptions.

---

## **3. Data Cleaning Process**
- Lockdown days were removed due to abnormally low values.  
- The Date column was formatted and sorted chronologically.  
- Missing and zero values were replaced using average values.  
- The cleaned data revealed a clear weekly travel pattern.

---

## **4. Models Used**
- **SARIMA:** Used for most services to capture seasonal and weekly patterns.  
- **Exponential Smoothing:** Used for the “Other” category due to its random, non-seasonal behavior.

---

## **5. Model Function**
- **SARIMA:** Learns from past seasonal and trend patterns to predict future ridership.  
- **Exponential Smoothing:** Focuses on recent values to make smooth short-term predictions.

---

## **6. 7-Day Forecast Summary**
- All services show stable or slightly fluctuating trends.  
- **Local Route** and **Light Rail**: Consistent daily usage.  
- **Rapid Route** and **Peak Service**: Minor short-term changes.  
- **School Service**: Cyclic pattern tied to academic schedules.  
- **Other (ARIMA model)**: Steady increase around 60 passengers per day.

---

## **7. Final Conclusion**
The 7-day forecast shows stable performance across all services.  
SARIMA handled repeating weekly patterns effectively, while ARIMA gave smoother forecasts for irregular data.  
Overall, the analysis indicates steady demand and supports efficient short-term transport planning.
