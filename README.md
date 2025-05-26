# 🚀 A/B Testing Analysis for Product Growth

This repository contains an end-to-end A/B testing analysis notebook designed to assess the impact of a new pricing page on user conversion and revenue. The project showcases practical experimentation strategy, data-driven product decisions, and machine learning insights for growth teams and product managers.

---
## 📊 Dashboards

### 📍 Executive Summary Dashboard  
Quick view of experiment goals, business questions, and key takeaways.
![executive summary](https://github.com/user-attachments/assets/3f95df7f-bdf1-49b6-aec9-dc6147d3149d)


### 🤖 Machine Learning Summary Dashboard
Feature importance and predictive insights from ML models to guide personalization and marketing.
![ml](https://github.com/user-attachments/assets/dc565aa5-9c91-4766-909c-6b92e5d2afa2)



___

## 📋 Executive Summary

**Business Question:** Should we ship the new pricing page (Variant B) to improve conversions and revenue?

**Bottom Line:**  
Variant B demonstrates a statistically significant improvement 


---

## 🎯 Experiment Overview

**🧪 Hypothesis:**  
Variant B (new pricing page) will reduce friction in the signup flow and increase conversions.

**📌 Setup:**
- Duration: 25 days (May 1–25, 2025)  
- Sample Size: 15,000 users (split 50/50)  
- Primary Metric: Conversion Rate (CVR)  
- Secondary Metrics: CTR, ARPU, Plan Mix  

**👥 Segments:**
- Students (45%)  
- Professionals (35%)  
- Teachers (20%)  

**📲 Traffic Sources:**
- Web (50%), Mobile (30%), Social (15%), Email (5%)

**💳 Plan Types:**
- Basic ($99), Pro ($199), Enterprise ($499)

---

## 📊 Business Metrics Dashboard

**Questions Answered:**
- Which variant performs better?
- Are improvements statistically significant?
- Which segments drive the most impact?
- What is the projected business outcome?

---

## 🔬 Statistical Significance Testing

**Methods Used:**
- ✅ Chi-square tests for conversion rate  
- ✅ Welch's t-tests for revenue  
- ✅ Effect size & confidence intervals  

**Thresholds:**
- α = 0.05 (95% confidence)  
- Power > 80%  
- Minimum Effect Size > 5%

**Why It Matters for PMs:**  
Avoiding false positives and quantifying practical impact ensures better prioritization and justifies implementation costs.

---

## 🔎 Advanced Segmentation Analysis

Deep dive into user behavior across:

- User types  
- Traffic sources  
- Conversion heatmaps by segment + source  

**Insights:**
- Identify high-performing segments to double down on  
- Spot underperformers needing attention  
- Understand traffic quality differences

---

## 🤖 Machine Learning Insights

**Models Used:**
- Gradient Boosting for conversion and revenue prediction

**Applications:**
- Personalization: Target high-propensity users  
- Acquisition: Focus on high-performing segments  
- Product: Prioritize features for revenue-driving users

**Why It Matters:**  
ML helps move beyond A/B stats to actionable user behavior modeling.

---

## 💰 Business Impact Projection

**Assumptions:**
- 50,000 monthly users  
- Test results generalize to full user base  
- No major seasonality bias  

**Risk Management:**
- Conservative estimates  
- Confidence intervals on projections  
- Rollout monitoring plan

---

## 📦 Product Management Decision Framework

| Decision Criteria         | Status  |
|--------------------------|---------|
| Statistical Significance | ✅ Yes  |
| Practical Significance   | ✅ Yes  |
| Risk Assessment          | ✅ Low  |
| Implementation Cost      | ✅ Justified |
| UX Impact                | ✅ Positive |

**Rollout Plan:**
1. **Phase 1 (Week 1-2):** 25% traffic → monitor metrics  
2. **Phase 2 (Week 3-4):** 75% if metrics hold  
3. **Phase 3 (Week 5+):** 100% rollout + retention tracking

---

## 🧠 Key Learnings & Recommendations

**What We Learned:**
- Variant B outperforms in conversion + revenue
- Professionals show highest lift → focus B2B
- Mobile performs best → validate mobile-first UX
- Price sensitivity remains stable (no plan mix shifts)

**Next Steps:**
- ✅ Ship Variant B via phased rollout  
- 🔍 Deep dive into professional segment  
- 📱 Optimize for mobile further  
- 📊 Study long-term retention impact

**Future Experiments:**
- 💸 Pricing strategy tweaks  
- 🧬 Segment-based personalization  
- 🚀 Onboarding flow improvements  
- 💬 Value prop messaging tests

---

## ✅ Final Recommendation

**Decision:**  
> **SHIP VARIANT B**

- **Confidence Level:** High (95%+)  
- **Expected Impact:** +X% CVR, $XXXk annual revenue  
- **Risk:** Low  
- **Action:** Begin 25% rollout, monitor KPIs daily  

---


## 🛠️ Tech Stack

- **Python** (pandas, numpy, scipy, scikit-learn, matplotlib, seaborn)
- **Notebook:** Jupyter / Google Colab
- **ML Models:** Gradient Boosting (XGBoost/LightGBM)
- **Stat Tests:** Chi-square, Welch’s t-test
- **Data:** Synthetic but realistic A/B testing data


