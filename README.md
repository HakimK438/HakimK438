<p align="center">
  <img src="./assets/header.svg" alt="Hakim Shaikh: Applied AI, Backend Systems, Data. B.Tech IT, Vidyalankar Institute of Technology, Mumbai, CGPI 9.6" width="100%" />
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=20&duration=2800&pause=1100&color=9CC8FF&center=true&vCenter=true&width=620&lines=Every+system+starts+as+scattered+data.;I+give+it+structure.;I+teach+it+to+predict.;Then+I+make+it+useful+to+people." alt="Every system starts as scattered data. I give it structure. I teach it to predict. Then I make it useful to people." />
</p>

<br>

## <img src="https://api.iconify.design/lucide/orbit.svg?color=%2358a6ff" height="26" alt="" /> Origin

I'm currently pursuing a **B.Tech in Information Technology at Vidyalankar Institute of Technology, Mumbai**, with a CGPI of 9.6, working at the point where **machine learning meets software engineering**.

I like to break a problem down until I understand the principle underneath it, then build the solution from an empty repository: schema first, then pipelines, then models, then something a real person can use. I care about transparent results, so my projects compare models against simple baselines and state their limits openly.

What follows is the story so far, told in the order I built it. The last chapter is still being written.

<br>

## <img src="https://api.iconify.design/lucide/database.svg?color=%2358a6ff" height="26" alt="" /> Chapter I · Learning to read data
<sub>DEC 2025</sub>

I started with raw business data and a question: *what is actually true in these numbers?* I learned to validate data in SQL before trusting any chart.

- [**Bank Loan Analysis**](https://github.com/HakimK438/bank-loan-analysis-postgreSQL-powerbi): my first complete analytics project. Loan performance, risk exposure and MTD trends in PostgreSQL and Power BI.
- [**E-commerce Revenue Intelligence**](https://github.com/HakimK438/Ecommerce-revenue-intelligence): revenue calculated twice and reconciled in SQL. If the numbers disagree, the dashboard doesn't get built.
- [**Customer Churn Behaviour**](https://github.com/HakimK438/customer-churn-behavior-analysis): finding *when* and *why* 7,043 customers leave, and which segments cost the most.

<br>

## <img src="https://api.iconify.design/lucide/brain-circuit.svg?color=%2358a6ff" height="26" alt="" /> Chapter II · Teaching machines to predict
<sub>JAN – JUN 2026</sub>

Next came models, and the realisation that **accuracy alone doesn't tell the whole story**. On imbalanced data, the mistakes that matter are the expensive ones.

- [**Flight Delay Risk**](https://github.com/HakimK438/flight-delay-risk-classification): low / moderate / high risk using only pre-departure features, with leakage deliberately removed.
- [**Air Quality Prediction**](https://github.com/HakimK438/Air-Quality-Prediction): multi-class classification judged by macro-F1 and confusion matrices so hazardous cases aren't overlooked.
- [**ML Projects Portfolio**](https://github.com/HakimK438/machinelearning-projects-portfolio): ten end-to-end projects, from credit default to customer segmentation.
- [**Superconductor T<sub>c</sub>**](https://github.com/HakimK438/Superconductor-Critical-Temperature-Prediction) and [**Online Shoppers**](https://github.com/HakimK438/Online-Shoppers-Purchase-Prediction): regression and classification on scientific and behavioural data.

<br>

## <img src="https://api.iconify.design/lucide/layers-3.svg?color=%2358a6ff" height="26" alt="" /> Chapter III · Building complete systems
<sub>MAR – OCT 2026</sub>

Models alone don't help anyone, so I started building the whole system around them: databases, APIs, interfaces and tests. It began with a [**multi-mode reservation system**](https://github.com/HakimK438/Multi-Mode-ReservationSystem) and a [**hospital VLAN network**](https://github.com/HakimK438/Hospital-Network-Design-using-VLAN), and grew into these four products, each aimed at a problem I can see in Mumbai.

<table>
<tr>
<td width="50%" valign="top">

### <img src="https://api.iconify.design/lucide/shopping-cart.svg?color=%2358a6ff" height="22" alt="" /> [AutoCART](https://github.com/HakimK438/AutoCART)
**Local stores, online.** A marketplace connecting shoppers with nearby Mumbai shops, with customer, seller and admin experiences.

- AI assistants **Saathi** and **Munim** that answer only from the live database
- Server-side checkout, per-store stock, store map, Razorpay test mode
- Seller onboarding, earnings dashboard, admin daily briefing
- 119 backend tests

<img src="https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white" alt="Django" /> <img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB" alt="React" /> <img src="https://img.shields.io/badge/Gemini-8E75B2?style=flat-square&logo=googlegemini&logoColor=white" alt="Gemini" /> <img src="https://img.shields.io/badge/OpenStreetMap-7EBC6F?style=flat-square&logo=openstreetmap&logoColor=white" alt="OpenStreetMap" />

</td>
<td width="50%" valign="top">

### <img src="https://api.iconify.design/lucide/building-2.svg?color=%2358a6ff" height="22" alt="" /> [iREPORT](https://github.com/HakimK438/iREPORT)
**Potholes to action.** Citizens report civic problems in a few taps, and ward offices work from a hazard-sorted control room.

- Duplicate detection within 50 m using PostGIS
- On-device ONNX models suggest a category, always marked unverified
- Full complaint lifecycle with citizen confirmation
- English, Hindi and Marathi

<img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" alt="FastAPI" /> <img src="https://img.shields.io/badge/PostGIS-336791?style=flat-square&logo=postgresql&logoColor=white" alt="PostGIS" /> <img src="https://img.shields.io/badge/ONNX-005CED?style=flat-square&logo=onnx&logoColor=white" alt="ONNX" /> <img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB" alt="React" /> <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker" />

</td>
</tr>
<tr>
<td width="50%" valign="top">

### <img src="https://api.iconify.design/lucide/shield-check.svg?color=%2358a6ff" height="22" alt="" /> [UPI Safety Check](https://github.com/HakimK438/upi-safety-check)
**Did the money really arrive?** A payment-safety tool for UPI merchants who face fake payment screenshots.

- Screenshot verification with on-device OCR, works offline
- Calibrated scam-message classifier
- UPI-ID look-alike detection and complaint drafting kit
- English and Hindi

<img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" alt="FastAPI" /> <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white" alt="scikit-learn" /> <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript" /> <img src="https://img.shields.io/badge/Tesseract_OCR-3C3C3C?style=flat-square" alt="Tesseract OCR" />

</td>
<td width="50%" valign="top">

### <img src="https://api.iconify.design/lucide/cloud-sun-rain.svg?color=%2358a6ff" height="22" alt="" /> [India Weather Intelligence](https://github.com/HakimK438/india-weather-intelligence)
**21 years of sky, in a warehouse.** Hourly ERA5 weather for 10 Indian cities in a PostgreSQL star schema.

- Idempotent ETL with validation and quarantine
- SQL / OLAP analysis and materialised views
- Heat and heavy-rain models tested against baselines on a time-based split
- FastAPI dashboard, 30 tests

<img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL" /> <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" alt="FastAPI" /> <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white" alt="scikit-learn" /> <img src="https://img.shields.io/badge/ETL-3C3C3C?style=flat-square" alt="ETL" />

</td>
</tr>
</table>

<br>

## <img src="https://api.iconify.design/lucide/radar.svg?color=%2358a6ff" height="26" alt="" /> Chapter IV · Signals from the lab
<sub>IN PROGRESS</sub>

Two experiments are taking shape right now. Open a signal to see what it's about.

<details>
<summary><img src="https://api.iconify.design/lucide/scan-eye.svg?color=%2358a6ff" height="18" alt="" /> <b>Project IRIS</b> · <i>Can a machine see colour in the dark?</i></summary>
<br>

Infrared cameras see what our eyes can't, but their images are grey, noisy and hard to read. IRIS is a deep-learning pipeline that **enhances infrared images and colourises them** into something a person can understand at a glance.

<img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" alt="PyTorch" /> <img src="https://img.shields.io/badge/Computer_Vision-3C3C3C?style=flat-square" alt="Computer Vision" /> <img src="https://img.shields.io/badge/status-in_the_lab-58a6ff?style=flat-square" alt="Status: in the lab" />

</details>

<details>
<summary><img src="https://api.iconify.design/lucide/workflow.svg?color=%2358a6ff" height="18" alt="" /> <b>Project Autopilot</b> · <i>What if routine business work ran itself?</i></summary>
<br>

Small businesses lose hours to repetitive tasks such as follow-ups, order updates and reports. This project connects **LLM agents with n8n workflows** so those tasks run on their own and a person steps in only when a decision is needed.

<img src="https://img.shields.io/badge/n8n-EA4B71?style=flat-square&logo=n8n&logoColor=white" alt="n8n" /> <img src="https://img.shields.io/badge/AI_Agents-3C3C3C?style=flat-square" alt="AI Agents" /> <img src="https://img.shields.io/badge/status-in_the_lab-58a6ff?style=flat-square" alt="Status: in the lab" />

</details>

<p><sub><img src="https://api.iconify.design/lucide/telescope.svg?color=%238b949e" height="14" alt="" /> Follow or star this profile to catch the next launch.</sub></p>

<br>

## <img src="https://api.iconify.design/lucide/wrench.svg?color=%2358a6ff" height="26" alt="" /> Toolkit

<p>
  <img src="https://skillicons.dev/icons?i=python,java,ts,js,postgres,mysql,fastapi,django,react,nextjs,tailwind&theme=dark" alt="Python, Java, TypeScript, JavaScript, PostgreSQL, MySQL, FastAPI, Django, React, Next.js, Tailwind" />
  <br>
  <img src="https://skillicons.dev/icons?i=pytorch,sklearn,docker,git,github,n8n,powerbi,vscode&theme=dark" alt="PyTorch, scikit-learn, Docker, Git, GitHub, n8n, Power BI, VS Code" />
</p>

**Also:** Pandas · NumPy · XGBoost · PostGIS · SQLAlchemy · ONNX Runtime · REST APIs · LLM APIs

<br>

<p align="center">
  <img src="./assets/footer.svg" alt="Still building. More orbits to come." width="100%" />
</p>
