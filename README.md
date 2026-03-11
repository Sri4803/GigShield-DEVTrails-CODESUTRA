# GigShield AI: Climate-Resilient Income Protection for Food Delivery Partners

## 1. Requirement & Persona Analysis
**Persona:** The High-Frequency Food Delivery Partner (e.g., Zomato/Swiggy).
**Scenario:** Our "Climate-Resilient" model protects workers against year-round environmental threats that halt deliveries and cause a 20-30% loss in income.
**Workflow:**
* **Onboarding:** Partner connects their ID and selects a weekly coverage plan.
* **Real-Time Monitoring:** The system tracks hyper-local APIs for specific environmental thresholds.
***Zero-Touch Trigger:** Claims are initiated automatically—no manual input required from the worker.
* **Instant Payout:** AI calculates average lost wages and issues an instant payout to the worker's digital wallet.

## 2. Financial Model: Weekly Pricing
* **Structure:** Premiums are structured on a **Weekly basis** to match the gig worker's typical payout cycle.
* **Dynamic Pricing:** Our Python-based ML model adjusts the premium every Monday based on the 7-day risk forecast (e.g., higher premiums during peak monsoon or heatwave weeks).
* **Strict Exclusion:** This policy covers **LOSS OF INCOME ONLY**.It excludes health, life, accidents, and vehicle repairs.

## 3. The Climate-Resilient Trigger Logic (AI/ML)
Our platform uses Python to monitor three core environmental "Disruption Thresholds":
1. **Summer (Extreme Heat):** Triggered when temperatures exceed 42°C, making outdoor riding hazardous.
2. **Monsoon (Heavy Rain):** Triggered when rainfall exceeds 15mm/hour, leading to waterlogging and halted deliveries.
3. **Winter (Severe Pollution):** Triggered when the AQI exceeds 400, protecting workers from severe health risks.



## 4. Intelligent Fraud Detection
To ensure platform sustainability, we implement:
* **Location Validation:** Cross-referencing GPS data to ensure the worker was in the affected disruption zone.
* **Activity Check:** Verifying the worker was "Online" and active on the delivery platform during the disruption.
* **Duplicate Prevention:** AI ensures only one payout per worker for a single environmental event.

## 5. Technical Stack
* **Language:** Python (for Risk Modeling & Trigger Logic).
* **Framework:** Flutter/React Native (Mobile-first for on-the-go partners).
* **APIs:** OpenWeatherMap API, Google Maps API, and Simulated Platform APIs.
