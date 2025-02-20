Electric Vehicle Data Analysis 🚗⚡
This repository contains a dataset and a Tableau dashboard analyzing Electric Vehicle trends.

📁 Files in this Repository
1️⃣ Dataset Files (Split CSV)
Due to GitHub's file size limit, the dataset is split into two files:

part1.csv
part2.csv
🔄 How to Combine the Files After Downloading
To merge these files back into a single dataset, use the following Python (Pandas) script:

import pandas as pd

# Load both CSV files
df1 = pd.read_csv("part1.csv")
df2 = pd.read_csv("part2.csv")

# Combine and save as a single CSV file
combined_df = pd.concat([df1, df2])
combined_df.to_csv("Electric_Vehicles_Complete.csv", index=False)

print("CSV files combined successfully!")


📊 Tableau Dashboard
Project Overview
This dashboard provides insights into Electric Vehicle trends, including:

Total Vehicles analyzed: 150,413
Top EV manufacturers (Tesla, Nissan, Chevrolet, etc.)
EV adoption trends over the years
State-wise distribution of electric vehicles
EV type breakdown (BEV vs. PHEV)
CAFV Eligibility status
📸 Dashboard Preview

🚀 How to View the Tableau Dashboard
Download the Tableau workbook (.twbx file) from this repository.
Open it using Tableau Public or Tableau Desktop.
Interact with the dashboard for insights!
