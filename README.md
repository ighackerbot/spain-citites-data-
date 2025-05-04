📊 Benford’s Law Analysis on Spanish City Populations
This project investigates whether the populations of Spanish cities follow Benford’s Law, a principle that predicts the frequency distribution of the first digit in many real-world numerical datasets.

🔍 Project Overview
Using population data of Spanish cities, we:

Perform data cleaning and preprocessing.

Extract the first digits of population numbers.

Compare the actual first-digit distribution to Benford's expected distribution.

Use visualizations and a Chi-Square test to evaluate conformity.

Highlight deviations and explore outliers.

📁 Dataset
The dataset was sourced from a public CSV link:

bash
Copy
Edit
https://drive.google.com/uc?id=1hlm7hiAGniIMuMnKcNlQ1YRqBr8b_koJ
It includes:

City name, coordinates, population, and administrative details.

A total of 285 cities from Spain.

📌 Key Features
📐 Statistical Analysis

df.describe(), correlation heatmap, outlier detection with boxplots.

🔢 Benford’s Law Distribution

Computed expected vs. actual frequency of leading digits.

Chi-Square test used to verify statistical alignment.

📊 Visualizations

Bar charts, line plots, pie charts, heatmaps, and boxplots using matplotlib, seaborn.

🔬 Findings

P-value = 0.0436 from Chi-Square test.

Conclusion: Spanish city populations do NOT strictly follow Benford’s Law (statistically significant deviation).

🧪 Libraries Used
python
Copy
Edit
pandas
numpy
matplotlib
seaborn
scipy.stats
📈 Sample Visuals
Benford vs Actual Leading Digit Bar Chart

Population Distribution Histogram

Correlation Heatmap of Numeric Features

Pie Chart of First Digit Shares

Top 10 Most Populated Spanish Cities

📉 Key Insight
Even though real-world datasets often follow Benford’s Law, the population of Spanish cities shows a slight but statistically significant deviation — especially noticeable in digits like 1 and 2 appearing more often than expected.

💻 How to Run
Clone the repo:

bash
Copy
Edit
git clone https://github.com/your-username/benford-spain-population.git
cd benford-spain-population
Install dependencies:

bash
Copy
Edit
pip install pandas matplotlib seaborn scipy
Run the Jupyter Notebook or Python script containing the analysis.

📬 Contact
Feel free to reach out via GitHub issues for suggestions, contributions, or feedback!
