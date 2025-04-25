# 🧪 Practical: Project Metrics Estimation using COCOMO Model

---

## 🎯 Aim:
To estimate project metrics such as effort, time, and cost using the COCOMO (Constructive Cost Model) for the project: **"Campus Map with Interactive Navigation"**.

---

## 📚 Objective:
- Understand and apply COCOMO estimation techniques.
- Estimate the effort (person-months) and time (development months).
- Identify cost drivers relevant to the project.
- Analyze advantages and drawbacks of the COCOMO model.

---

## 📖 Theory:

### 📐 1. Project Estimation Techniques:
Project estimation refers to predicting the time, effort, cost, and resources required to complete a software project.  
Common estimation techniques include:
- Expert judgment
- Analogy-based estimation
- Parametric models (e.g., COCOMO)
- Use-case estimation

---

### 🔹 2. COCOMO (Constructive Cost Model):
A widely used algorithmic estimation model developed by Barry Boehm. It estimates effort based on lines of code (LOC) and a set of project-specific attributes.

**COCOMO has three levels:**
- **Basic** – Quick estimation using LOC and project type.
- **Intermediate** – Includes cost drivers like reliability, complexity.
- **Detailed** – Adds analysis of all software components.

---

### 🗺️ 3. Use Case: Campus Map with Interactive Navigation

**Description:**
A web/mobile application that allows users to:
- View the campus map.
- Search buildings (e.g., library, labs).
- Get real-time walking directions.
- Interact with 3D or zoomable map interfaces.
- Include accessibility features and offline mode.

---

### 🧮 4. Applying Basic COCOMO Model

**Formulas:**

Effort (E) = `a × (KLOC)^b`  
Development Time (D) = `c × (E)^d`

Where:
- `a, b, c, d` are constants depending on project type:
  - **Organic**: Small, simple software – a=2.4, b=1.05, c=2.5, d=0.38
  - **Semi-Detached**: Intermediate – a=3.0, b=1.12, c=2.5, d=0.35
  - **Embedded**: Complex, hardware-tied – a=3.6, b=1.20, c=2.5, d=0.32

---

**Assumptions:**
- Estimated size = **12,000 LOC (12 KLOC)**
- Project Type = **Semi-Detached**

**Calculations:**

- **Effort (E)** = 3.0 × (12)^1.12 ≈ 3.0 × 17.1 = **51.3 person-months**
- **Development Time (D)** = 2.5 × (51.3)^0.35 ≈ 2.5 × 4.3 = **10.75 months**

---

### 💸 5. Project Cost Estimation:

Assume:
- Cost per person-month = **₹60,000**

Thus:
- **Total Cost** = 51.3 × 60,000 = **₹30,78,000**

---

### ✅ 6. Advantages of COCOMO:
- Provides early estimates during planning.
- Helps in budgeting and resource allocation.
- Based on empirical data – quantifiable.
- Useful for cost-benefit analysis.

---

### ⚠️ 7. Drawbacks of COCOMO:
- Depends heavily on accurate LOC estimation.
- Doesn’t factor in modern agile practices.
- Less accurate for new/innovative projects.
- Doesn’t consider reuse, AI, or automation tools.

---

## 📋 Result:
Estimated that the **Campus Map with Interactive Navigation** project will require **51.3 person-months**, take approximately **10.75 months** to develop, and cost around **₹30.78 Lakhs**, based on the **Basic COCOMO Model**.

---

## 📌 Conclusion:
The COCOMO model is a powerful technique for estimating software projects, especially when clear code size and project type are known.  
It helps in setting realistic expectations and efficient planning.
