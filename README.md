# lunar-logistics-thermal-model<img width="4546" height="2167" alt="LunarModel" src="https://github.com/user-attachments/assets/84339c07-7002-4511-b726-951680cbe4a0" />
# Project: Lunar Surface Logistics Availability Model

### Executive Summary
Standard revenue modeling for lunar logistics assumes 100% equipment availability. However, thermal simulation of the Lunar South Pole reveals a **"Thermal Availability Gap"** where extreme surface heat flux (>450 W/m²) exceeds physical heat rejection limits.

**The Bottom Line:** At Lunar Noon, payload availability must be throttled. Logistics contracts must account for this exclusion window to prevent SLA (Service Level Agreement) breaches.

### Analysis Output
![Lunar Model Output](LunarModel.jpg)

### Methodology
* **Tooling:** Custom Python simulation (NumPy) modeling the Stefan-Boltzmann Law.
* **Parameters:** Stress-tested radiator surface area against variable lunar surface temperatures (100K - 390K) and regolith dust degradation.
* **Status:** First-order feasibility estimate for commercial planning.
