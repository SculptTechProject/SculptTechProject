# Hey, I’m Mateusz 🚀

**Backend-first** developer turning raw data into **real-time, production-ready apps**.  
I build pragmatic systems end-to-end: APIs → streaming → storage → dashboards — and I ship **every day**.

---

## ⚡ Snapshot
- Real-time backends (Django/DRF/Channels, FastAPI) with Redis/PostgreSQL/Kafka
- Data/ML pipelines with scikit-learn; **learning PyTorch** for applied projects
- Clean DevEx: Dockerized stacks, CI/CD, readable docs, and tests

---

## 🚀 Featured Projects

### 1) Servo-Sens-App *(WIP)* — Real-time sensor monitoring
Real-time readings & alerts over WebSockets, token auth, one-click seed/quickstart.  
- **Highlights:** Channels (ASGI/Redis), JWT auth, alert rules, Docker Compose  
- **Stack:** Django · DRF · Channels · Redis · PostgreSQL · Nuxt 3 · Docker  
- **Repo:** [Servo-Sens-App](https://github.com/SculptTechProject/Servo-Sens-App)  

  <img width="1752" height="903" alt="ServoSense dashboard" src="https://github.com/user-attachments/assets/7ff58418-53fd-4d14-af04-c976e9900212" />

**Planned features:**
- Sensor simulation mode in Docker
- Multi-user auth & role-based access
- Alert rules editor
- Grafana/Prometheus integration

---

### 2) FleetStream — Fleet management SaaS
Vehicle telemetry to live map, roles/permissions, alerts, and exports.  
- **Highlights:** Multi-user & roles, Leaflet/Mapbox map, CSV/PDF export  
- **Stack:** Django/FastAPI · PostgreSQL · Kafka · Leaflet/Mapbox · Docker  
- **Repo:** [FleetStream](https://github.com/SculptTechProject/FleetStream)  

**Planned features:**
- Real-time aggregation via Spark Structured Streaming
- Geofencing & trip segmentation
- Alert notifications (speeding, idle, low fuel)
- Dashboard with KPIs + map heatmaps

*Example of simulator output:*
<details>
<summary>Click to view sample telemetry data</summary>

```text
TESTCAR01 | {"vehicle_id": "TESTCAR01", "timestamp": "2025-08-08T09:35:28.593229+00:00", "location": {"lat": 52.230391, "lon": 21.014133}, "speed_kmh": 0.0, "engine_rpm": 800, "gear": 1, "fuel_level_pct": 95.0, "fault_codes": []}
TESTCAR01 | {"vehicle_id": "TESTCAR01", "timestamp": "2025-08-08T09:35:29.596480+00:00", "location": {"lat": 52.230396, "lon": 21.014184}, "speed_kmh": 12.8, "engine_rpm": 1409, "gear": 1, "fuel_level_pct": 95.0, "fault_codes": []}
TESTCAR01 | {"vehicle_id": "TESTCAR01", "timestamp": "2025-08-08T09:35:30.597429+00:00", "location": {"lat": 52.230412, "lon": 21.014306}, "speed_kmh": 30.4, "engine_rpm": 2130, "gear": 2, "fuel_level_pct": 95.0, "fault_codes": []}
TESTCAR01 | {"vehicle_id": "TESTCAR01", "timestamp": "2025-08-08T09:35:31.600347+00:00", "location": {"lat": 52.230436, "lon": 21.014472}, "speed_kmh": 42.0, "engine_rpm": 2937, "gear": 2, "fuel_level_pct": 95.0, "fault_codes": []}
````

</details>

---

### 3) CarWorth-ML — Car price prediction

From dataset → feature engineering → model selection → **/predict** API → tiny UI.

* **Highlights:** Pipelines, 5-fold CV, RMSE/MAE metrics, FastAPI endpoint
* **Stack:** scikit-learn · Pandas · FastAPI · Pydantic · Docker
* **Repo:** [CarWorth-ML](https://github.com/SculptTechProject/CarWorth-ML)

 <img width="640" height="480" alt="Residuals plot" src="https://github.com/user-attachments/assets/fd28034b-81b4-4719-9ee6-acb5f82da858" />

**Planned features:**

* Frontend form → API → instant valuation
* Model retraining pipeline with new data
* Deployment on Hugging Face Spaces
* CSV batch prediction mode

---

### ☘️ For fun: MultiHandPaint

“Air-brush” drawing — control the canvas with your hands; clear with a mouth gesture.

* **Stack:** Python · OpenCV · MediaPipe
* **Repo:** [MultiHandPaint](https://github.com/SculptTechProject/MultiHandPaint)
> Try, very interesting!

---

## 🧰 Toolbox

* **Languages:** Python · TypeScript · C++ · SQL
* **Backend:** Django · DRF · Channels (ASGI) · FastAPI · Express.js
* **Data/ML:** scikit-learn · Pandas · (🔥 learning) PyTorch · Spark · Delta Lake · Kafka · Airflow
* **Frontend:** Nuxt 3 · Next.js · Vue 3 · Tailwind CSS
* **Databases:** PostgreSQL · Redis · Kafka
* **DevOps:** Docker · GitHub Actions · Prometheus · Grafana

---

## 📈 How I work

* I prototype quickly, then harden: tests → CI/CD → docs → release.
* I ask “**why**” before “how”; architecture first, code second.
* AI helps me reason and review. **I write the code.**

---

## 🎯 Currently

* BSc (Applied Computer Science), 2nd year — Bydgoszcz University of Science & Technology
* Building production-grade open-source projects in public (GitHub commits daily)
* Lifting at the gym 🏋️ and geeking out over cars 🚗

---

## 🤝 Let’s Connect

**LinkedIn:** [mateusz-dalke](https://www.linkedin.com/in/mateusz-dalke)
**Email:** [dalke.dev@gmail.com](mailto:dalke.dev@gmail.com)

> Open to backend, data engineering, and ML roles — ready for mid-level challenges.

---
