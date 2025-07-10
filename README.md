# 📊 AI Tool Usage by Indian College Students (2025)

An end-to-end data analysis project exploring the usage of generative AI tools among college students in India. This study investigates students' AI usage patterns, trust levels, academic impact, and preferences—providing insights for educators, policymakers, and ed-tech developers.

---

## 📁 Table of Contents

- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Key Objectives](#key-objectives)
- [Technologies Used](#-technologies-used)
- [Data Analysis Workflow](#data-analysis-workflow)
- [Visualizations & Insights](#visualizations--insights)
- [Results Summary](#results-summary)
- [How to Run](#how-to-run)
- [Project Structure](#project-structure)
- [License](#license)

---

## 🚀 Project Overview

This analysis provides an in-depth look at how Indian college students are integrating AI tools into their daily academic lives. It explores patterns across streams, usage hours, grades, trust factors, and awareness levels.

---

## 📂 Dataset

- **Name:** `Students.csv`
- **Records:** 3,614 entries
- **Features:** 16 attributes including:
  - Student demographics and academic stream
  - AI tool usage hours
  - Trust level and academic impact
  - Awareness and willingness to pay
  - Device type, internet access, and more

> 🧼 Cleaned version saved as `ai_tool_usage_analysis_cleaned_file.csv`

---

## 🎯 Key Objectives

- Analyze generative AI adoption across streams and years
- Identify most-used AI tools and use cases
- Examine correlation between AI usage and grades
- Visualize awareness and trust distribution
- Assess device and internet access trends
- Support data-driven decisions for education tech policy

---

## 🛠️ Technologies Used

| Tool / Library     | Purpose                      |
|--------------------|------------------------------|
| Python             | Programming Language         |
| Pandas             | Data Manipulation            |
| Seaborn & Matplotlib | Visualization              |
| Jupyter Notebook   | Exploratory Data Analysis    |
| Git & GitHub       | Version Control & Collaboration |

---

## 🔍 Data Analysis Workflow

1. **Import Libraries**
2. **Load Dataset**
3. **Initial Inspection**
4. **Missing Value Imputation**
5. **Exploratory Data Analysis (EDA)**
6. **Visualization of Key Trends**
7. **Correlation Analysis**
8. **Save Cleaned Dataset**

---

## 📊 Visualizations & Insights

- **🎓 Stream Distribution:** Number of students per academic stream
- **🧠 Top AI Tools:** Frequency of usage (e.g., ChatGPT, Bard, etc.)
- **📈 Usage vs. Grades:** Boxplot analysis of impact on academic performance
- **💡 Trust Levels:** Histogram of students' trust in AI tools
- **📚 Stream-wise Usage:** Average usage hours by academic stream
- **📌 Correlation Heatmap:** Numeric correlation across variables

---

## 📌 Results Summary

- Highest adoption observed in tech and management streams
- Strong usage clusters around 1–3 hours/day
- Students using AI moderately showed slight improvement in grades
- ChatGPT emerged as the most preferred tool
- ~55% of students are willing to pay for AI access
- Some states lacked data, which was filled using mode values

---

## 🖥️ How to Run

1. Clone the repo:
   ```bash
   git clone https://github.com/your-username/ai-tool-usage-analysis.git
   cd ai-tool-usage-analysis
