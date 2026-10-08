# 🌐 Global Cybersecurity Threats Analysis (2015-2024)

### 📊 Data-Driven Insights into Cyber Attacks, Financial Impact & Defense Strategies

## 📌 Overview
This project performs an in-depth Exploratory Data Analysis (EDA) on global cybersecurity incidents from 2015 to 2024. The goal is to identify trends in attack types, most targeted industries, financial losses, and the effectiveness of defense mechanisms.

This analysis is highly relevant for Business Analysts and Data Analysts to understand cyber-risk from a business perspective.

## 📁 Dataset Information
**File:** `Global_Cybersecurity_Threats_2015-2024.csv`
**Records:** 3000+ incidents
**Time Period:** 2015-2024
**Geography:** Global (India, USA, UK, China, Germany, etc.)

**Columns:**
- `Year` - Year of attack
- `Attack Type` - Phishing, Ransomware, DDoS, SQL Injection, Malware, Man-in-the-Middle
- `Target Industry` - IT, Retail, Education, Healthcare, Telecommunications, etc.
- `Financial Loss (in Million $)` - Financial impact of the attack
- `Number of Affected Users` - Scale of user impact
- `Attack Source` - Hacker Group, Nation-state, Insider
- `Security Vulnerability Type` - Unpatched Software, Weak Passwords, Social Engineering
- `Defense Mechanism Used` - VPN, Firewall, AI-based Detection, etc.
- `Incident Resolution Time (in Hours)` - Time taken to resolve

## 🛠️ Tech Stack & Skills Used
**Language:** Python
**Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Plotly

**Analytical Skills Demonstrated:**
- Data Cleaning & Data Wrangling
- Exploratory Data Analysis (EDA)
- Descriptive Statistics
- Data Visualization
- Insight Generation & Business Reporting
- SQL (for querying, if converted to database)

## 🔍 Key Analysis Performed
1.  **Trend Analysis:** Year-wise growth of cyber attacks (2015-2024)
2.  **Attack Vector Analysis:** Which attack type is most common? (DDoS, Phishing)
3.  **Industry Impact:** Which industry is most targeted and suffers highest financial loss?
4.  **Financial Analysis:** Total financial loss and average loss per attack type
5.  **Source Analysis:** Major source of attacks (Hacker Group vs Nation-state)
6.  **Defense Effectiveness:** Which defense mechanism reduces resolution time and financial loss?
7.  **Correlation Analysis:** Relation between Affected Users, Financial Loss, and Resolution Time

## 📈 Visualizations
- Bar Chart - Attack Types Distribution
- Line Chart - Financial Loss Trend Over Years
- Pie Chart - Target Industry Share
- Heatmap - Correlation between numerical features
- Box Plot - Resolution Time by Defense Mechanism

## 💡 Key Insights (Sample)
- Phishing and DDoS are among the top attack types globally.
- Financial sector and IT are highly targeted.
- AI-based Detection shows lower resolution time compared to traditional defenses.
- Financial loss has increased significantly post 2020.

## 🚀 How to Run
```bash
# Clone the repo
git clone https://github.com/your-username/Global-Cybersecurity-Threats-Analysis-2015-2024.git

# Install dependencies
pip install pandas numpy matplotlib seaborn plotly jupyter

# Run the notebook
jupyter notebook analysis.ipynb
