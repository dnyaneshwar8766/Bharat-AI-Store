# Mini Bharat AI Store

## Overview
This project is a prototype for an **Integrated Retail Intelligence System**.  
It demonstrates how Kirana stores, wholesalers, and logistics providers can be digitally connected and intelligently managed using AI and WhatsApp-like interfaces.  

The system is designed to work in **low-data environments** and be accessible via **basic smartphones**.

---

## Features
- Simulated WhatsApp-style chat interface  
- Automated inventory updates (add/deduct)  
- Delivery booking and logistics tracking  
- Credit scoring for retailers  
- Demand forecasting for products across multiple stores  
- Expiry risk identification and reorder suggestions  
- Local vs online price comparison  
- Delivery route optimization  

---

## Deliverables
1. **System Integration Prototype**
   - Chatbot-style interface (UI simulation)
   - APIs for inventory, delivery booking, and credit scoring
   - Mock data integration (FMCG offers, retailer transactions, logistics)

2. **Data Intelligence Dashboard**
   - Demand forecasting (3 products, 5 stores)
   - Expiry alerts and reorder points
   - Price comparison (local vs online for 10 items)
   - Route optimization (10 orders)
   - Insights shown in dashboard + PDF/Markdown summary

3. **Documentation**
   - Setup guide & architecture overview
   - Code comments and explanations
   - Summary of insights and decisions

4. **Demo**
   - 5-minute video walkthrough or live demo
   - Showcasing key features, logic, and user experience

---

## Tech Stack
- **Frontend:** React, TypeScript, TailwindCSS, Vite  
- **Backend/APIs:** Mock APIs (extendable to real data sources)  
- **Dashboard:** Streamlit / Power BI / HTML  

---

## Setup Guide
1. Clone the repository:
   ```bash
   git clone <repo-link>
   cd retail-buddy-dash-main
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Run the development server:
   ```bash
   npm run dev
   ```
4. Open the app in your browser at `http://localhost:5173`.

---

## Architecture Overview
- **UI Layer:** WhatsApp-like chat interface + dashboard  
- **API Layer:** Handles inventory, logistics, and credit scoring logic  
- **Data Sources:** FMCG offers, retailer transactions, logistics data  
- **Intelligence Layer:** Forecasting, expiry risk detection, price comparison, and route optimization  

---

## License
This project is created as an academic/prototype solution.  
Free to use and extend for learning and development.  
