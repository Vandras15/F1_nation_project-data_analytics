# **F1 all nation statistics dashboard**

<img width="1606" height="751" alt="1" src="https://github.com/user-attachments/assets/2ab557f3-47d5-43eb-a316-04a9f6768f94" />

## Introduction

This dashboard was created to show my Excel skills. I'm currently learning to become a Data Analyst, and wanted test my new skills. Also, F1 is one of my favourite sport. 75 years of F1 history, with a tons of data.

In this spreadsheet, I wanted to see, and show all F1 nations statistics.
You can download here: [f1_nation.xlsx](https://github.com/user-attachments/files/21162541/f1_nation.xlsx)

### Excel skills, and tools I used
1. 📑 Pivot Tables
2. 📊 Charts
3. ✅ Data Validation
4. 🧮 Formulas and Functions

### Main indicators
In Formula 1, these indicators are the most common, and used in statistics.
- Points
- Entries
- Starts
- Podiums
- Wins
- Pole Positions
- Fastest laps
- Nation most success driver

## How do I build up?

🧹 **Data cleaning**
Imported the data from Wikipedia

<img width="1442" height="755" alt="2" src="https://github.com/user-attachments/assets/4bf0bd6a-5b2f-404e-af0a-21071b4f80a2" />

I needed to clean the data, especially in points column. There were a several points system in F1, and a lot of drivers got subpoints (X.5, X.3 etc...). I cleaned it, however I left the halfpoints in, because in the recent points system drivers can get halfpoints.




🚩 **Make nation datasheet**

<img width="381" height="739" alt="3" src="https://github.com/user-attachments/assets/b285ef34-3f3f-4caf-89bd-a498aff2a830" />

Deleted duplicated nation, then sorted in alphabetic order.




🧮 **Make indicators datasheets**

<img width="1155" height="316" alt="4" src="https://github.com/user-attachments/assets/a1d44bac-1f18-4e11-8953-6ec55f186022" />

I sorted the nations, and the related points to them. I used *SUMIFS* to summarise all points, wins, poles etc...
After that, I used *XLOOKUP* to search, to look up the data I need. Naturally I always sorted in alphabetic order.




✅ **Data Validations**

<img width="1273" height="423" alt="5" src="https://github.com/user-attachments/assets/62cfb058-50f4-461e-b24a-a166071e13a3" />

On the dashboard sheet, I made a data validation (list) to chose which nation show on the dashboard, with data, and on the charts.




📊 **Chart**

<img width="858" height="722" alt="6" src="https://github.com/user-attachments/assets/2feca050-5aaa-40a4-b52d-63f6e25787b4" />

The final steps. Inserted a clustered bar chart. I put not only the selected nation, but also the all nation median, and average data.




📟 **KPI**

<img width="544" height="310" alt="7" src="https://github.com/user-attachments/assets/d3701c81-cd16-4c85-9ee8-a5488b188361" />

Next to the chart, we see the selected nation (in this sample, Poland) statistics. This KPIs are all linked to their sheets.


## Conclusion

This dashboard was good for me to test, and prove my skill. Also, I can show which is the most success, and of course *oldest* nation in the Formula 1 history. Finally, it was a good pratice, project to show my skill, and check where I am right now in Excel knowledge.



