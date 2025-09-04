# Hey, I’m Mateusz 🚀

## Visit my website!🤓 ---> www.dalkedev.pl

**Backend-first** developer turning raw data into **real-time, production-ready apps**.  
I build pragmatic systems end-to-end: APIs → streaming → storage → dashboards — and I ship **every day**.

---

## ⚡ Snapshot
- Real-time backends (Django/DRF/Channels, FastAPI) with Redis/PostgreSQL/Kafka
- Data/ML pipelines with scikit-learn; **learning PyTorch** for applied projects
- Clean DevEx: Dockerized stacks, CI/CD, readable docs, and tests

---

## 🚀 Featured Projects

### 1) dummysensors — Dummy sensor data generator (PyPI package)
Lightweight tool for generating synthetic sensor data for IoT/ML testing. Supports Python API + CLI, JSONL/CSV outputs, YAML configs.
- **Stack:** Python · CLI · PyPI Trusted Publishing · CI/CD
- **Demo project:** [ds-test](https://github.com/SculptTechProject/ds-test)
- **Repo:** https://github.com/SculptTechProject/dummysensors

<img width="790" height="657" alt="image" src="https://github.com/user-attachments/assets/132a7800-9c51-4ae5-93f9-7327382fd806" /> 

>Live plot

<img width="785" height="559" alt="image" src="https://github.com/user-attachments/assets/4f22a680-b81f-49e6-ab01-3d7424335ceb" />

```bash
=== Head of dataframe ===
ts device_id sensor_id         type      value
0  0.0  engine-A    temp-0  temperature  84.620850
1  0.0  engine-A     vib-0    vibration   0.179118
2  0.5  engine-A    temp-0  temperature  76.254692
3  0.5  engine-A     vib-0    vibration   0.166054
4  1.0  engine-A    temp-0  temperature  76.256331

Average values by type:
type
temperature    76.844964
vibration      -0.017095
Name: value, dtype: float64

```
> Analysis with Pandas

### 2) Servo-Sens-App *(WIP)* — Real-time sensor monitoring
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

### 3) FleetStream — Fleet management SaaS
Vehicle telemetry to live map, roles/permissions, alerts, and exports.  
- **Highlights:** Multi-user & roles, Leaflet/Mapbox map, CSV/PDF export  
- **Stack:** Django/FastAPI · PostgreSQL · Kafka · Leaflet/Mapbox · Docker  
- **Repo:** [FleetStream](https://github.com/SculptTechProject/FleetStream)  

**Planned features:**
- Real-time aggregation via Spark Structured Streaming
- Geofencing & trip segmentation
- Alert notifications (speeding, idle, low fuel)
- Dashboard with KPIs + map heatmaps

*Demo*:

<img width="1907" height="985" alt="image" src="https://github.com/user-attachments/assets/c4176428-45df-41e0-ab00-9c986468575a" />

![2025-08-09 17-43-04](https://github.com/user-attachments/assets/d924a183-afb3-4440-9727-5239a08599c7)

---

### 4) CarWorth-ML — Car price prediction

From dataset → feature engineering → model selection → **/predict** API → tiny UI.

* **Highlights:** Pipelines, 5-fold CV, RMSE/MAE metrics, FastAPI endpoint
* **Stack:** scikit-learn · Pandas · FastAPI · Pydantic · Docker
* **Repo:** [CarWorth-ML](https://github.com/SculptTechProject/CarWorth-ML).

<img width="1899" height="528" alt="image" src="https://github.com/user-attachments/assets/669a8614-dcd2-4a03-b7c1-6da8b74d87e0" />

<img width="640" height="480" alt="Residuals plot" src="https://github.com/user-attachments/assets/fd28034b-81b4-4719-9ee6-acb5f82da858" />

**Planned features:**

* Frontend form → API → instant valuation
* Model retraining pipeline with new data
* Deployment on Hugging Face Spaces
* CSV batch prediction mode

---

### 5) GinioCrawler — Lead finder & contact extractor
Search by phrase (e.g., “granulate manufacturers Poland”), crawl result pages, and extract emails/phones. Exports CSV/XLSX; ships as a one-file Windows EXE; tiny GUI included.  
- **Highlights:** CLI + GUI, respects `robots.txt`, follows Contact link (depth=1), CSV/XLSX with hyperlinks  
- **Stack:** Python · httpx · BeautifulSoup · Tkinter · Pandas · openpyxl · SerpAPI · PyInstaller  
- **Repo:** [GinioCrawler](https://github.com/SculptTechProject/GinioCrawler)

<img width="1177" height="520" alt="image" src="https://github.com/user-attachments/assets/ef1bad28-6b57-4fe2-a276-afb1ba4ebfa1" />

<img width="2035" height="373" alt="image" src="https://github.com/user-attachments/assets/c40467fb-cbc4-4770-9e83-1f998023fa60" />


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
* **Databases:** PostgreSQL · Redis
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
