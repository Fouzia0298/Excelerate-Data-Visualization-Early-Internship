# 🧠 Week 3 – Data Visualization & Dashboard Creation  
> Part of the **Data Visualization Early Internship by Exelerate**  
> Presented by **Team 9 – 0505 SLU DVT**

This folder contains all deliverables from **Week 3**, where we created data visualizations and dashboards to support our recommendations for optimizing Facebook ad campaigns for the **Superhero U event**.

---

## 📄 Key Deliverables in This Folder

- 📊 `CPR_Bar_Chart.png` – Horizontal bar chart showing CPR by Campaign ID  
- 📈 `Reach_vs_Spend_Chart.png` – Combo chart comparing campaign reach vs spend  
- 🧠 `ULC_vs_CTR_Bubble_Chart.png` – Bubble chart showing engagement efficiency  
- 🟡 `Budget_Allocation_Pie_Charts.png` – Before and after budget allocation  
- 📋 `Campaign_Performance_Table.png` – Summary table of all 11 campaigns  

Also includes:
- 🔗 Exported Google Colab notebook (if applicable)
- 🖼 Final dashboard visuals for PowerPoint or Canva

---

## 🎯 Objectives

In Week 3, we focused on turning our cleaned campaign data into **actionable insights** through visual storytelling:

| Goal | Description |
|------|-------------|
| 📉 Visualize Underperformance | Highlight high-cost, low-engagement campaigns using bar charts |
| 💰 Budget Reallocation Plan | Show how funds can be shifted from underperforming campaigns to top performers |
| 📊 Engagement Analysis | Use bubble charts to compare ULC, CTR, and Spend |
| 🧭 Monitor Danger Zone | Identify medium-risk campaigns (Canada, USA) needing optimization |

---

## 📊 Key Charts Created

### 1. **Cost Per Result (CPR) by Campaign ID**
- Shows Campaign 3 (Australia) and 10 (UK) have the highest CPR
- Color-coded by performance tier:
  - 🔴 Red = Discontinued
  - 🟡 Orange = Danger Zone
  - 🟢 Green = High-performing

### 2. **Reach vs Spend Combo Chart**
- Bar chart shows reach per campaign
- Line chart shows spend per campaign
- Clearly highlights inefficient spending in Australia and UK

### 3. **ULC vs CTR Bubble Chart**
- Size = Spend
- X-axis = CTR
- Y-axis = ULC
- Helps identify which campaigns are most efficient

### 4. **Budget Allocation Pie Charts**
- Before reallocation: Campaigns 3 and 10 take 20% of total budget
- After reallocation: Funds moved to India (6), Nigeria (8), Ghana (5)

### 5. **Campaign Performance Table**
| Campaign ID | Country | CPR (₹) | Reach | Status |
|------------|---------|--------|-------|--------|
| Campaign 3 | Australia | ₹19.78 | 3,187 | ❌ Discontinued |
| Campaign 4 | Canada    | ₹8.25  | 3,307 | ⚠️ Monitor |
| Campaign 6 | India     | ₹0.96  | 31,831 | ✅ Scale Up |
| Campaign 8 | Nigeria   | ₹0.99  | 21,929 | ✅ Scale Up |
| Campaign 10| UK        | ₹14.05 | 3,636 | ❌ Discontinued |
| Campaign 11| USA       | ₹7.28  | 2,555 | ⚠️ Monitor |

---

## 🧩 Why These Visuals Matter

The visuals clearly justify our recommendations:
- 📉 **Low reach** despite high cost → Inefficient campaigns
- 💸 **High CPR** in Australia and UK → Not worth investment
- 📈 **Strong ROI** in India and Nigeria → Justifies budget increase
- 🧠 **Ghana and Nepal** show potential → Worth optimizing

We recommend reallocating budget toward high-performing regions and exploring new markets like **Bangladesh, Myanmar, Kenya**.

---

## 🛠 Tools Used

- **Python (Google Colab)** – For data cleaning and visualization generation
- **Matplotlib / Seaborn** – To create all charts
- **Pandas** – For grouping and summarizing data
- **Canva / PowerPoint** – For final slide design

---

## 📦 How to Replicate

All visuals were generated programmatically in Google Colab using the cleaned dataset from Week 2.

To replicate:
1. Open Google Colab
2. Upload `cleaned_campaign_data_short.xls`
3. Run the notebook
4. Download exported `.png` images
5. Insert into slides or dashboards

---

## 📌 Want to View the Visuals?

You can view the generated visuals in this folder:
- `CPR_Bar_Chart.png`
- `Reach_vs_Spend_Chart.png`
- `ULC_vs_CTR_Bubble_Chart.png`
- `Budget_Allocation_Pie_Charts.png`
- `Campaign_Performance_Table.png`

These visuals were used in the **final Week 4 presentation**.

---

## 🧾 License

MIT License – Feel free to use this as a template or portfolio piece.
