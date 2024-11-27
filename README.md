# **Motor Vehicle Collisions Dashboard** 🚗

This Streamlit dashboard provides an interactive analysis of motor vehicle collisions in New York City. It allows users to explore data visually, filter by conditions, and gain insights into collision patterns.

---

## **Features**
1. **Injured People Analysis**  
   - Filter and visualize collision hotspots on a map based on the number of injured persons.
   
2. **Hourly Collision Trends**  
   - Analyze collisions occurring during specific hours of the day using a PyDeck hexagon map.

3. **Collision Breakdown by Minute**  
   - Explore the frequency of collisions within a selected hour using a histogram.

4. **Dangerous Streets Analysis**  
   - Identify the top 5 most dangerous streets for pedestrians, cyclists, or motorists.

5. **Raw Data Viewer**  
   - Option to display the raw dataset for deeper analysis.

<img src="" alt="dashboard" height="600">
<img src="" alt="dashboard" height="600">
<img src="" alt="dashboard" height="600">
---

## **Installation**
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/motor-vehicle-collisions-dashboard.git
   cd motor-vehicle-collisions-dashboard
   ```

2. Install the required libraries:
   ```bash
   pip install streamlit pandas numpy pydeck plotly
   ```

3. Place the dataset (`Motor_Vehicle_Collisions_-_Crashes.csv`) in the project directory.

---

## **Usage**
1. Run the Streamlit app:
   ```bash
   streamlit run app.py
   ```

2. Open the provided URL (e.g., `http://localhost:8501`) in your web browser.

---

## **Dataset**
The dashboard uses the **Motor Vehicle Collisions - Crashes** dataset from NYC Open Data. Ensure that the dataset file path in the code matches your setup.

---

## **Future Enhancements**
- Add more detailed visualizations and filters.
- Incorporate real-time data updates.
- Provide advanced analytics like clustering and trend forecasting.

---

Feel free to contribute or customize the dashboard to suit your needs! 🎉
