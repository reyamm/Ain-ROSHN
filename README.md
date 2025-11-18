

# **AIN – AI-Powered Construction Monitoring System 🏗️🤖**

AIN is an intelligent system designed to bring **clarity**, **speed**, and **automation** to large-scale housing projects.
It replaces scattered WhatsApp updates, delayed site visits, and inconsistent reporting with **real-time AI insights**, **verified progress tracking**, and **predictive forecasting**—all in a unified, modern platform.

---

## 📌 **1. Project Overview**

Large construction projects suffer from slow updates, inconsistent reporting, and lack of visibility.
AIN solves this by delivering:

* AI-driven real-time exterior phase detection
* Verified interior photo progress logs
* A fully unified dashboard
* Predictive ML-powered timeline forecasting
* Automated reporting for supervisors

Designed for high-volume villa developments and modern construction workflows.

---

## 🧠 **2. System Capabilities**

### **2.1 Exterior Construction Stage Detection (AI Camera)**

A fixed outdoor camera + EfficientNet-B0 automatically detects the current construction phase.
No more random site visits or relying on workers sending inconsistent photos.

We also **labeled our own dataset** to train the exterior model for higher accuracy.

---

### **2.2 Interior Task Verification (Human-in-the-Loop)**

Workers submit photos for interior tasks such as:

* Electrical
* Plumbing
* HVAC
* Finishing

AIN validates each submission, timestamps it, and adds it to the villa’s timeline as visual evidence.

---

### **2.3 Unified Project Dashboard 📊**

A single dashboard shows everything supervisors need:

* Current stage
* % completion
* Timeline of every update
* Photo evidence for each step
* Progress comparison across villas

This replaces scattered chats and manual spreadsheets.

---

### **2.4 Predictive Timeline Forecasting ⏳ (ML Model)**

Since **no public dataset exists** that predicts villa construction duration from its characteristics:

➡️ **We built a synthetic dataset** based on realistic Saudi construction timelines and industry standards.

Synthetic features include:

* Plot area
* Number of floors
* Number of rooms
* Structural complexity

Our ML model uses these features to estimate:

* Total construction duration
* Expected duration for each phase
* Whether the villa is ahead or behind schedule

As AIN gets deployed, real on-site start/end timestamps will allow training a more accurate, Saudi-data-based prediction model.

---

### **2.5 Cross-Villa Benchmarking 🏘️**

AIN automatically groups villas with the same design type or start date and compares their progress.

If one villa falls behind the others, the system flags it immediately for early intervention.

---

### **2.6 Automated Supervisor Reports 📝🤖**

AIN’s LLM engine generates structured reports that summarize:

* Completed work
* Remaining work
* Delay alerts
* Forecasted completion date
* Next expected phase

These reports remove the need for manual write-ups and keep all stakeholders aligned.

---

## 🛠️ **3. Tech Stack**

### **Frontend**

* Next.js
* React
* Tailwind CSS
* Figma UI

### **Backend**

* Node.js
* Supabase (PostgreSQL + Storage)

### **AI / ML**

* TensorFlow / Keras
* EfficientNet-B0
* ML Timeline Prediction Model
* LLM for Reporting

---

## 🎯 **4. Why AIN Matters**

AIN addresses the biggest operational gaps in construction supervision:

❌ Inconsistent updates
❌ Scattered WhatsApp communication
❌ No real-time tracking
❌ Hard to compare villas
❌ No forecasting or delay prediction

AIN provides:

✔ Real-time visibility
✔ Verified progress evidence
✔ Predictive timelines
✔ Automated reporting
✔ Smarter, faster supervision

---

## 👥 **5. Team AIN**

* **Ghala Alotaibi**
* **Reyam Albalihi**
* **Layan Alhidaan**



