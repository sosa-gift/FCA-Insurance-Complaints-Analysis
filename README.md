# FCA-Insurance-Complaints-Analysis
An Excel-based analysis of Financial Conduct Authority (FCA) complaints data for July - December 2025, focusing on the Insurance & Pure Protection sector.

## **Project Overview**

This project examines how 15 selected UK insurance firms compare in terms of complaint frequency and complaint-handling performance.
I wanted to understand whether firms receiving fewer complaints relative to their size also tended to resolve complaints more quickly, and identify areas that might benefit from further investigation.
The analysis uses publicly available FCA data and includes a comparative ranking, Excel dashboard and written findings.

## **Dataset and Methodology**

Data source: FCA Firm-Level Complaints Data, 2025 H2 (July–December 2025).

I selected the 15 highest-volume eligible firms using the following criteria:
- Reported under Insurance & Pure Protection.
- Reporting period of 1 July to 31 December 2025.
- No joint reporting with other firms.
- Available Context A complaints-per-1,000-policies data.
- Ranked among the 15 highest eligible firms by complaints opened.

I compared the firms using:
- Number of complaints opened and closed.
- Complaints per 1,000 policies.
- Percentage of complaints closed within three days.
- Percentage closed within eight weeks.
- Percentage closed after eight weeks.
- Percentage of complaints upheld.

## **Ranking Method**

I created a combined performance ranking using two measures:
- Complaint rate: Lower complaints per 1,000 policies received a stronger rank.
- Eight-week closure rate: A higher percentage of complaints closed within eight weeks received a stronger rank.

Both measures were given equal weight:
- Combined Score = (Complaint Rate Rank + Eight-Week Closure Rank) / 2
- A lower combined score represents a stronger position under these two measures.

The uphold rate was analysed separately rather than included in the combined score, as it is not necessarily a direct measure of complaint-handling quality.

## **Key Findings**

1. Assurant performed strongest under the combined ranking.
Assurant General Insurance Limited recorded 1.18 complaints per 1,000 policies and closed 99.08% of complaints within eight weeks. It achieved the strongest combined ranking in the selected sample.

2. Munich Re Digital Partners had a notably high complaint rate.
Munich Re Digital Partners Limited recorded 53.54 complaints per 1,000 policies, compared with 12.25 for the next-highest firm. The available data does not establish why this difference exists.

3. Liverpool Victoria had the lowest eight-week closure rate.
Liverpool Victoria Insurance Company Limited closed 84.27% of complaints within eight weeks, with 15.73% closed after eight weeks. This may warrant further investigation into complaint-handling processes.

4. Complaint frequency and closure speed did not always align.
AXA PPP Healthcare Limited recorded a relatively high complaint rate of 12.25 per 1,000 policies, while still closing 98.48% of complaints within eight weeks. This highlights the importance of considering multiple performance measures.

## **Excel Skills Demonstrated**

- Data cleaning and organisation.
- Filtering and selection using defined criteria.
- Combining data from multiple tables.
- Formula-based calculations and rankings.
- Comparative performance analysis.
- Data visualisation using Excel charts.
- Interpreting results and identifying areas for further investigation.

## **Workbook Structure**

| Worksheet | Purpose |
|---|---|
| 00_Project_Guide | Project scope, methodology and sources |
| 01_Firm_Selection | Eligibility checks and selection of 15 firms |
| 02–07_Raw_Data | Original FCA complaint data organised by measure |
| 08_Master_Analysis | Combined dataset, calculations and rankings |
| 09_Dashboard_Data | Supporting data for the charts |
| 10_Dashboard | Visual comparison of complaint rates and closure performance |
| 11_Findings | Written findings, recommendations and limitations |

## **Limitations**
- The analysis covers only one six-month reporting period, so it cannot identify trends over time.
- The selected firms may differ in their products, customers and business models.
- Equal weighting of the two ranking measures is a subjective analytical decision.
- Rankings show relative positions but do not fully reflect the size of differences between firms.
- The data identifies differences in performance but does not establish their underlying causes.
- The rankings are my own analytical framework and do not represent official FCA assessments or ratings.

## **Files**

[View the completed Excel analysis](UK_Insurance_Complaints_Analysis.xlsx)

## **Data Sources**

FCA — Firm-Level Complaints Data: https://www.fca.org.uk/data/complaints-data/firm-level

FCA — About Our Complaints Data: https://www.fca.org.uk/data/complaints-data/about-data

**Tools Used**

Microsoft Excel
