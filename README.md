# Aquanetics: Autonomous, Self-Powered Water Telemetry & Analytics

**Aquanetics** is an intelligent, real-time residential water monitoring platform engineered for precision fluid analytics, consumption tracking, and proactive pipeline health diagnostics. Designed to bridge low-power embedded sensing with modern cloud architecture, the platform captures high-frequency telemetry from inline micro-hydro sensor nodes to deliver immediate visibility into domestic fluid dynamics—without relying on traditional battery maintenance.

---

### Core Highlights

* **Real-Time Telemetry Streaming:** Instantaneous flow rate rendering, dynamic pulse-to-volume mathematical conversion, and live chart animations powered by WebSocket-driven PostgreSQL change data capture.
* **Autonomous Anomaly Detection:** Automated, edge-informed diagnostics that instantly detect and flag pipeline anomalies, separating normal water flow ($5-8\text{ L/min}$) from catastrophic pipe bursts ($\ge 22.0\text{ L/min}$).
* **Multi-Node Architecture:** Granular, multi-pipe monitoring support that maps distinct household lines (e.g., Main Inlet, Kitchen, Bathroom) to dedicated calibration profiles.
* **On-the-Fly Calibration:** Interactive front-end K-Factor parameter tuning, allowing real-time adjustment of sensor pulses-per-liter constants without firmware modification.
* **Temporal Consumption Analytics:** Aggregated usage summaries categorizing domestic water consumption across customizable daily and monthly intervals.