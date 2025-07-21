# 🚗 Coupon Acceptance Analysis: Restaurant(20–50) Case Study

## 📁 Project Overview

This project investigates behavioral and contextual traits that influence drivers' likelihood of accepting coupons for upscale restaurants ($20–$50 per person). Using survey data sourced from the UCI Machine Learning Repository, we explore which combinations of demographics, driving scenarios, and lifestyle indicators correspond to higher acceptance rates.

> 🔍 Key question: What patterns differentiate customers who accept a driving coupon versus those who do not?

---

## 📊 Dataset Summary

- **Source**: UCI Machine Learning Repository (via Amazon Mechanical Turk survey)
- **Entries**: 12,684 observations
- **Target variable**: `Y` (`1` for accepted, `0` for declined)
- **Coupon types**: Less expensive restaurants, Coffee Houses, Carry Away, Bar, and Restaurant(20–50)

---

## 🧠 Key Findings (Restaurant(20–50) Focus)

| Scenario | Acceptance Rate |
|----------|------------------|
| Partner passenger at 2PM | **80.0%** |
| Frequent Restaurant(20–50) diner + 1-day expiration | **74.7%** |
| Management occupation + income > $50K | **69.2%** |
| General population baseline | ~**43%** |

These segments suggest that **social planning, income level, and redemption flexibility** play substantial roles in coupon engagement.

---

## 💡 Hypothesis

Drivers most likely to accept Restaurant(20–50) coupons tend to be:
- **Socially engaged** (e.g. with partner passengers)
- **Financially flexible** (e.g. income > $100K, managerial roles)
- **Lifestyle-oriented planners** (frequent diners who prefer coupons with longer expiration windows)

---

## 🚀 Next Steps

### ✅ Immediate Actions
- Deploy behavior-triggered coupon delivery strategies using top predictors (`passenger`, `time`, `expiration`, `occupation`)
- Extend expiration windows to 1 day for upscale dining coupons
- Build data-driven personas for targeted outreach

### 🔍 Further Analysis
- Machine learning classification to model acceptance probability
- Feature engineering: create compound traits (e.g. `partner_2pm`, `frequent_diner_expiration`)
- Clustering to uncover latent behavioral groups
- Lift estimation to simulate impact of targeted campaigns

---

## 🛠️ Tools Used

- Python (Pandas, Matplotlib, Seaborn)
- Statistical testing: Chi-square
- Exploratory Data Analysis (EDA)
- GitHub for public portfolio publishing

---

## 👤 Author

**Amina Abacon** — Data analyst with a deep curiosity for actionable insights, AI mechanisms, and strategic applications. This project reflects her analytical approach, collaborative mindset, and ability to translate data into meaningful narratives.

---

## 📎 License

This project is open-source and free to use under the [MIT License](LICENSE).
