# Student Risk & Intervention Analytics

> *A personal data project simulating early identification of at-risk students using attendance and behavioural referral data — designed to support evidence-based intervention strategies in Singapore schools.*

**Author**: Pang Kah Hwee  
**Role Target**: Data & AI Analyst, Character and Citizenship Education Branch (CCEB), MOE Singapore  
**Tools Used**: Python (Pandas, Matplotlib, Seaborn), Excel, Googles Colab 
**Date**: April 2025

---

## 🎯 Project Goal

To demonstrate how simple data analysis and visualisation can uncover patterns in student behaviour — helping schools prioritise early interventions for students at risk of disengagement (e.g., from Values in Action or Uniformed Groups programmes).

This project simulates real-world school data to answer:
- Which students are most at risk?
- What interventions are most effective?
- What patterns (e.g., Friday absenteeism) signal emerging issues?

---

## 📊 Dataset

- **Source**: Simulated dataset based on 3+ years of frontline student welfare experience in a MOE school.
- **Size**: 111 anonymised student records.
- **Columns**:
  - `Student ID`, `Age`, `Gender`, `Grade`
  - `Absent Days (Term)`, `Late Count`, `Referral Count`
  - `Referral Reason` (e.g., Withdrawn, Disruptive, Bullying)
  - `Intervention Received` (e.g., Peer Mentor, Counselling, Parent Meeting)
  - `Improved?` (Yes/No)

---

## 🔍 Key Insights

1. **Risk Scoring**:  
   Engineered a simple risk score:  
   `Risk_Score = (Absent Days × 0.4) + (Referral Count × 0.6)`  
   → Top 10 at-risk students identified for prioritised support.

2. **Intervention Success**:  
   - **Peer Mentor**: 78% success rate  
   - **Counselling**: 42% success rate  
   → Suggests peer-based support may be more effective for disengaged students.

3. **Behavioural Patterns**:  
   - High correlation between “Withdrawn” referrals and Friday absenteeism.  
   → Recommend proactive Friday check-ins for these students.

---

## 📈 Visualisations Included

- Scatter plot: Absenteeism vs. Referrals (coloured by improvement status)
- Bar chart: Intervention success rates
- Histogram: Distribution of risk scores

---

## 💡 Why This Matters for CCEB

This project mirrors the exact work CCEB needs:
- Evaluating programme effectiveness (VIA/UG)
- Predicting student disengagement
- Optimising resource allocation through data

My goal: Scale this approach from 111 students to thousands — helping every Singapore student thrive.

---

## 🛠️ How to Run This Project

1. Clone this repo.
2. Install required libraries:  
   `pip install pandas matplotlib seaborn jupyter`
3. Open `student_risk_analysis.ipynb` in Jupyter Notebook or Google Colab.
4. Run all cells to reproduce analysis and visualisations.

---

## 📬 Contact

Pang Kah Hwee  
📧 lunawave@hotmail.com  
📱 +65 9880 4768