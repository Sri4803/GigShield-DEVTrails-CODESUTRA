# GigShield-DEVTrails-CODESUTRA
# GigShield AI: Parametric Income Protection for Food Delivery Partners

## 1. Requirement & Persona Analysis:
**Persona:** Food Delivery Partners (e.g., Zomato/Swiggy).
**Scenario:** Delivery partners often lose 20-30% of their weekly earnings due to heavy rain, extreme heat, or local curfews. 
**Workflow:**
* **Onboarding:** Partner connects their ID and selects a weekly coverage plan.
***Monitoring:** The system continuously tracks hyper-local weather and social disruption APIs.
***Trigger:** When a parametric threshold is met (e.g., >15mm rain/hr), a claim is automatically initiated.
* **Payout:** AI calculates the average lost wages for the disruption duration and issues an instant payout.

## 2. Financial Model: Weekly Pricing 
* **Structure:** Premiums are deducted on a **Weekly basis** to align with the gig worker’s payout cycle.
* **Dynamic Pricing:** Our AI model adjusts the premium every Monday based on the 7-day weather forecast and historical risk data for that specific zone.
* **Exclusions:** This policy **strictly excludes** coverage for health, life, accidents, or vehicle repairs—focusing solely on **Loss of Income**.

## 3. AI/ML Integration Strategy 
* **Risk Profiling:** Uses historical disruption data to categorize zones into High, Medium, and Low risk to set fair premiums.
* **Intelligent Fraud Detection:** * **GPS Validation:** Ensures the worker was actually in the disruption zone during the event.
    * **Anomaly Detection:** Flags partners who attempt to claim multiple times for the same event or use GPS spoofing.

## 4. Technical Stack & Development Plan
* **Mobile App:** Flutter/React Native (Optimized for on-the-go workers).
* **Backend:** Node.js with a FastAPI layer for ML models.
* **APIs:** OpenWeatherMap API (Environmental), Google Maps API (Location), and Simulated Platform APIs (Earnings/Status).
* **Database:** MongoDB for policy management and historical claim logs.
