<h1 align="center">🏠 Household Energy Consumption Analysis & Anomaly Detection</h1>

<p align="center">
This project analyzes household electricity consumption data to understand <strong>usage patterns</strong>, <strong>peak demand hours</strong>, and <strong>unusual energy behavior</strong>. 
It applies <strong>Machine Learning</strong> techniques to generate actionable insights for energy optimization.
</p>

---

<h2>📌 Project Overview</h2>
<ul>
  <li>Analyzes real-world household energy data.</li>
  <li>Detects peak hours and unusual consumption patterns (anomalies).</li>
  <li>Applies <strong>Random Forest Regression</strong> to predict energy consumption.</li>
  <li>Provides energy optimization recommendations based on model insights.</li>
</ul>

---

<h2>📊 Dataset Description</h2>
<p><strong>Source:</strong> UCI Machine Learning Repository</p>
<p><strong>Dataset Name:</strong> Household Power Consumption Dataset</p>
<p><strong>Data Type:</strong> Time-series household energy usage</p>

<h3>🔑 Columns</h3>
<table>
  <tr>
    <th>Column Name</th>
    <th>Description</th>
  </tr>
  <tr><td>Date</td><td>Date of observation</td></tr>
  <tr><td>Time</td><td>Time of observation</td></tr>
  <tr><td>Global_active_power</td><td>Household total active power (kW)</td></tr>
  <tr><td>Global_reactive_power</td><td>Reactive power (kW)</td></tr>
  <tr><td>Voltage</td><td>Voltage (V)</td></tr>
  <tr><td>Global_intensity</td><td>Current intensity (A)</td></tr>
  <tr><td>Sub_metering_1</td><td>Energy for kitchen (Wh)</td></tr>
  <tr><td>Sub_metering_2</td><td>Energy for laundry (Wh)</td></tr>
  <tr><td>Sub_metering_3</td><td>Energy for AC & heating (Wh)</td></tr>
</table>

---

<h2>⚡ Key Analysis Steps</h2>
<ol>
  <li><strong>Data Preprocessing:</strong> Convert timestamps, handle missing values, extract temporal features (hour, day, month, weekday).</li>
  <li><strong>Feature Engineering:</strong> Calculate lag features (1h, 2h, 24h), rolling averages, and total sub-metering.</li>
  <li><strong>Exploratory Analysis:</strong> Identify peak hours and sub-metering patterns using plots.</li>
  <li><strong>Anomaly Detection:</strong> Detect unusual spikes in power consumption.</li>
  <li><strong>Modeling:</strong> Random Forest Regression for predicting global active power.</li>
  <li><strong>Evaluation:</strong> Metrics like RMSE, MAE, and R² for model performance assessment.</li>
  <li><strong>Optimization Recommendations:</strong> Shift loads to off-peak hours, optimize appliance usage, and address anomalies.</li>
</ol>

---

<h2>📈 Insights & Results</h2>
<ul>
  <li>Peak hours detected around 7–8 AM and 6–8 PM.</li>
  <li>Sub-metering shows AC & water heater consume the highest share of electricity.</li>
  <li>Random Forest Regression predicts energy consumption accurately (R² > 0.8 on test set).</li>
  <li>Potential savings: 25–35% through smart scheduling and optimization.</li>
</ul>

---

<h2>💡 Key Takeaways</h2>
<ul>
  <li>Time-based features and lagged consumption help improve prediction accuracy.</li>
  <li>Random Forest handles non-linear patterns better than linear regression.</li>
  <li>Energy optimization requires understanding both usage patterns and anomalies.</li>
</ul>

---

<h2>📂 Future Work</h2>
<ul>
  <li>Integrate real-time smart meter data for live prediction.</li>
  <li>Use deep learning models (LSTM) for better time-series prediction.</li>
  <li>Develop a dashboard for actionable insights and automated alerts.</li>
</ul>
