
# DT Fellowship Simulation Assignment  
**Growth by Data: Orchestrating Funnels, Reducing CAC**  

This repository contains my detailed solution for the DT Fellowship simulation.  
The assignment focuses on designing a sales funnel, structuring a CRM, building nurturing strategies, analyzing CAC, and summarizing growth philosophy.  

---

## 📌 Part 1: Funnel Design + CRM Structuring  

### Funnel Design  

- **Lead** → Any inbound/outbound contact (ads, LinkedIn, referrals). *Owner: Marketing*  
- **MQL** → Lead fits ICP + shows interest (industry, budget, resource download). *Owner: Marketing → Sales*  
- **Opportunity (Bonus Stage)** → MQLs actively pursued by Sales. Helps prioritize hot deals.  
- **SQL** → Clear buying intent (demo booked, positive call). *Owner: Sales*  
- **Customer** → Closed deal, contract signed. *Owner: Sales → Customer Success*  

### CRM Blueprint  

**Key Fields**  
- Lead source, industry, role, company size  
- Engagement score, stage, last contact date, next follow-up date  
- Budget, UTM tags, owner  

**Automations**  
- Auto-tagging by channel  
- Lead scoring (MQL threshold)  
- Stage updates when criteria met  
- Follow-up reminders for inactivity  

**Dashboards**  
- **Sales Rep** → Pipeline by stage, follow-up tasks  
- **Growth Manager** → Funnel health, drop-offs, channel ROI  
- **CEO** → CAC vs LTV, high-level funnel insights, revenue forecast  

---

## 📌 Part 2: Nurturing Mechanism  

### High-Intent (Demo booked, no close)  
- **Frequency**: 2–3 follow-ups in 2 weeks  
- **Channels**: Email, WhatsApp, LinkedIn  
- **Content**: Case studies, ROI tools, founder notes, offers  
- **Metric**: Demo-to-close conversion  

### Mid-Intent (Webinar / resource engagement)  
- **Frequency**: Weekly for 4 weeks  
- **Channels**: Email drip, LinkedIn message  
- **Content**: Guides, success stories, tutorials  
- **Metric**: Demo requests  

### Low-Intent (Newsletter subscriber)  
- **Frequency**: Monthly  
- **Channels**: Newsletter  
- **Content**: Blogs, insights, social proof  
- **Metric**: Engagement (open/click rate)  

**AI Tools**:  
- ChatGPT → personalized follow-up emails  
- HubSpot AI → lead scoring  
- Grammarly AI → tone refinement  

---

## 📌 Part 3: Funnel Analytics & CAC Optimization  

### Mock Data  

| Channel        | Leads | Cost   | Conversions | Conv. Rate | Cost/Conv. |
|----------------|-------|--------|-------------|------------|------------|
| Facebook Ads   | 3000  | ₹90,000 | 30          | 1%         | ₹3,000     |
| Email Campaign | 1000  | ₹10,000 | 25          | 2.5%       | ₹400       |
| LinkedIn DMs   | 500   | ₹25,000 | 10          | 2%         | ₹2,500     |

- **Weakest Channel**: Facebook Ads → highest cost per conversion, lowest conversion rate.  

### Experiments  

1. **Narrow targeting + Pre-qualification**  
   - Target ICP only, add a 2-question qualifier on landing page.  
   - Expected result: conversion improves from 1% → 2%.  

2. **Budget Reallocation to Email Retargeting**  
   - Shift 20% of FB budget to email retargeting.  
   - Expected result: lower CAC (< ₹1,200 per conversion).  

### CAC:LTV Dashboard Metrics  

- CAC per channel  
- LTV estimate & CAC:LTV ratio  
- Payback period  
- Funnel conversion % by stage  
- Revenue per channel  

**Viewers**  
- CEO → weekly snapshot  
- Growth Manager → weekly detailed view  
- Sales Reps → daily operational view  

---

## 📌 Part 4: Strategic Summary  

Funnels are not static pipelines; they are **systems for making better decisions**. The goal is to reduce waste, direct resources toward the right prospects, and keep marketing, sales, and leadership aligned.  

The right balance lies in combining **data-driven structure** with **human judgment**. A CRM can qualify someone as SQL, but only a sales conversation reveals true intent.  

Equally critical is data storytelling. Numbers alone are noise unless they drive action. A founder does not need to see open rates; they need to know which channel to double down on. My approach is to turn analytics into **clear, actionable insights**.  

A strong funnel is therefore a **living decision-making framework**. It adapts with behavior, lowers CAC by providing visibility, and accelerates growth by aligning teams on what matters.  

---

## ✅ Deliverables  

- Funnel definitions & CRM structuring  
- Nurturing tracks for high, mid, low intent leads  
- CAC analysis with experiments & dashboard plan  
- Strategic summary (growth philosophy)  

---

## 🛠️ Tech Add-On (Optional for portfolio)   
- `data/` folder with mock CSV files (`leads.csv`, `campaigns.csv`)  
- `analysis.ipynb` notebook with Python/Pandas CAC calculations  
- Screenshots of sample funnel dashboards (Tableau/Power BI)  

---
