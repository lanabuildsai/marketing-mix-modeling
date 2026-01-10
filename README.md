# Marketing Mix Model: Channel Attribution & Budget Optimization

**A data-driven framework for optimizing marketing spend across digital channels**

## 🎯 Project Overview

Built a Marketing Mix Model to quantify channel effectiveness and identify budget reallocation opportunities across Google Ads, Facebook Ads, Email Marketing, Paid Views, and Organic traffic.

## 📊 Key Findings

- **Model Performance:** R² = 0.787 (explains 78.7% of sales variance)
- **Efficiency Gap:** Identified $783K difference between most and least efficient channels
- **Critical Discovery:** Paid Views showed statistically significant **negative ROI** (-$366K per 1M views, p=0.003)
- **Top Performers:** Facebook Ads 4.4x more efficient than Google Ads, Email 3.3x more efficient
- **Business Impact:** Projected 15-20% marketing efficiency gains, $200K-500K annual revenue increase

## 🔍 Technical Approach

### Regression Analysis
- **Model:** OLS regression with statsmodels
- **Dataset:** 3,051 weekly marketing periods
- **Predictors:** 5 marketing channels (impressions/views)
- **Target:** Weekly sales revenue
- **Validation:** Durbin-Watson test (DW=2.050) confirmed no time series dependency

### Strategic Framework
- Developed 3 budget reallocation scenarios (Conservative, Aggressive, Elimination)
- Phased implementation roadmap with A/B validation gates
- Risk-based approach with control group methodology

## 💼 Business Value

**Strategic Recommendations:**
1. Eliminate or dramatically reduce Paid Views (negative ROI channel)
2. Shift budget to high-efficiency channels (Facebook, Email)
3. Implement controlled A/B tests before full rollout
4. Expected outcomes: 12-18% CAC reduction, $200K-500K revenue lift

**Implementation Roadmap:**
- Phase 1: Validation through controlled experiments (4 weeks)
- Phase 2: Pilot rollout in test markets (4 weeks)  
- Phase 3: Full deployment with monitoring (4 weeks)

## 🛠️ Tools & Technologies

- **Python:** pandas, numpy, scikit-learn, statsmodels
- **Visualization:** matplotlib, seaborn
- **Statistics:** OLS regression, hypothesis testing, time series validation
- **Business Analytics:** Marketing attribution, ROI optimization, A/B testing framework

## 📁 Project Files

- **marketing_data.csv** - Dataset with 3,051 weekly marketing periods
- **Notebook** - Complete analysis with model building, validation, and strategic framework

## 🚀 How to View

Open the Jupyter notebook to see:
- Exploratory data analysis
- Model development & validation
- Channel efficiency analysis
- Strategic budget optimization framework
- Implementation roadmap

## 📈 Skills Demonstrated

- Marketing Mix Modeling (MMM)
- Statistical regression analysis & validation
- Channel attribution & ROI optimization
- Strategic business framework development
- Data-driven decision making with risk mitigation
- Cross-functional communication (CMO/CFO/PM perspectives)

## 👤 About

**Lana Baturytski** | Senior Product & Analytics Leader  
14+ years at Microsoft, AWS, Expedia | Seeking Director Marketing Analytics / Growth PM roles

---

*This project demonstrates the intersection of technical analytics rigor and strategic business thinking - quantifying marketing effectiveness while building actionable frameworks for budget optimization.*
```

---

## **NOW LET'S COMMIT & PUSH:**

**In GitHub Desktop:**

1. **Bottom left:** In the "Summary" box, type:
```
   Initial commit: Complete Marketing Mix Model
