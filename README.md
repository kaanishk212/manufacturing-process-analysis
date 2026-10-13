# Manufacturing Process Analysis & Digital Optimization

A manufacturing analytics project using Python, Excel, and Power BI to explore production performance, downtime, cycle time, material waiting, and output achievement.

> **Note:** This project uses synthetic data created for learning and portfolio demonstration. The results are illustrative and do not represent measurements from a real factory.

## Project Objectives

- Analyze production performance across three manufacturing lines.
- Compare planned production with actual output.
- Examine downtime, cycle time, and material waiting.
- Identify production lines that may warrant further investigation.
- Present key performance indicators through a Power BI dashboard.

## Tools Used

- **Python:** Data analysis
- **Pandas:** Data manipulation and aggregation
- **Excel / CSV:** Dataset storage and review
- **Power BI:** Interactive performance visualizations
- **Google Colab:** Python notebook environment
- **GitHub:** Project documentation and version control

## Dataset

The synthetic dataset contains 180 production records.

Key variables include:

- Production line, machine, product, and shift
- Planned units and actual units
- Cycle time per unit
- Downtime in minutes
- Scrap units and scrap rate
- Material waiting time
- Output achievement percentage

## Key Findings

Based on the synthetic dataset:

- **Line 1:** Average output achievement of 90.65%.
- **Line 2:** Average output achievement of 89.03%.
- **Line 3:** Average output achievement of 88.92%.
- **Line 3:** Highest average cycle time at 30.77 seconds per unit.
- **Line 3:** Highest average material waiting time at 18.28 minutes.
- **Downtime and output achievement:** Correlation of approximately -0.77, indicating a negative association in this dataset.

These findings suggest that Line 3 could be prioritized for further investigation in this illustrative scenario. Correlation does not establish causation, and the analysis does not prove that reducing downtime alone will improve output.

## Power BI Dashboard

The dashboard compares production-line performance using:

- Output achievement
- Total downtime
- Average cycle time
- Average material waiting time
- Planned and actual production
- Machine-level downtime comparisons

Dashboard screenshots will be added to the `dashboard/` folder.

## Repository Structure

```text
manufacturing-process-analysis/
├── data/
│   ├── README.md
│   └── manufacturing_process_analysis_practice_data.csv
├── notebooks/
│   ├── README.md
│   └── manufacturing_process_analysis.ipynb
├── dashboard/
│   └── dashboard_screenshots/
└── README.md
```

*Filenames may differ slightly depending on the files uploaded to the repository.*

## Future Improvements

- Investigate the relationship between downtime and production output.
- Compare machine performance using normalized metrics.
- Explore scrap patterns and potential quality-related bottlenecks.
- Add filters and KPI cards to improve dashboard usability.
- Test hypothetical improvement scenarios without treating them as proven results.

## Disclaimer

This is an educational portfolio project based on synthetic data. The findings are illustrative and should not be interpreted as verified industrial results or actual factory improvement outcomes.
