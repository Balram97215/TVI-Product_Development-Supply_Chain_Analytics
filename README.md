# Warehouse Operations Analytics & Process Optimization

![Project Status](https://img.shields.io/badge/Status-Completed-success)
![Role](https://img.shields.io/badge/Role-Product_Operations_Executive-blue)
![Domain](https://img.shields.io/badge/Domain-Supply_Chain_%26_Logistics-orange)
![Methodology](https://img.shields.io/badge/Methodology-Lean_Six_Sigma-green)

## 📋 Executive Summary
**Client:** Transview Enterprise (TVI) — Exclusive Management Consultant for **QNET** (Global Direct Selling E-Commerce).  
**Goal:** To eliminate operational bottlenecks in a high-velocity fulfillment center characterized by thousands of daily SKUs and strict global SLAs.  
**Outcome:** Reduced "Pack-to-Load" times from **3 days to <24 hours**, improved picking throughput by **30%**, and established a data-driven culture for product launches.

---

## 🧐 The Challenge: "Gut Feeling" vs. Operational Reality
The warehouse environment was characterized by operational silos and subjective decision-making. Marketing launched bundles without logistical consultation, and warehouse layouts were changed without data backing. This friction led to two critical failures:

1.  **Fulfillment Delays:** "Pack-to-Load" times ballooned to 3 days, severely impacting customer satisfaction.
2.  **Dead Stock:** Product bundles launched on "intuition" rather than data resulted in slow-moving inventory occupying valuable storage space.

---

## 🛠️ The Solution: Data-Driven Process Engineering

I shifted the organizational culture from "Opinion-Based" to "Evidence-Based" using a three-pronged approach:

### 1. Lean Six Sigma (DMAIC) for "Pack-to-Load" Optimization
Stakeholders initially blamed external couriers for delays. I used **Exploratory Data Analysis (EDA)** on order timestamps to prove the bottleneck was internal: the time from *Order Printed* to *Truck Loaded* averaged 72 hours.

* **Root Cause Analysis (Gemba Walk):** Identified that High-Velocity (Class A) SKUs were stored in deep racks, forcing packers to travel excessive distances.
* **The Fix (ABC Slotting & Kanban):**
    * **Class A (Top 20% Volume):** Relocated immediately adjacent to the packing line.
    * **Class C (Low Volume):** Moved to deep storage.
    * **Kanban:** Deployed visual triggers for packaging materials to prevent line stoppages.

```mermaid
graph TD
    A[Analyze Order Timestamps] -->|Find Bottleneck| B(Internal Processing Lag)
    B --> C{Root Cause Analysis}
    C -->|Gemba Walk| D[Inefficient Slotting]
    D --> E[Implement ABC Slotting]
    E --> F[Deploy Kanban System]
    F --> G[SLA Recovery (<24hrs)]
