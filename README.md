![Covid-19 image](https://github.com/mdkamran048/Covid-19-Analysis/assets/143988392/0edff2c1-2222-4578-9400-4cd6441bd405)

# Introduction

The COVID-19 Data Analysis Project is a comprehensive examination of the global impact of the COVID-19 pandemic. In the wake of this unprecedented global crisis, our project seeks to shed light on the pandemic's spread, effects, and the data-driven insights that can help in understanding and mitigating its impact.

# Objective

This project aims to analyze the COVID-19 pandemic using publicly available data. The project includes a Jupyter notebook with Python code to extract, clean, and visualize COVID-19 data from various sources. Additionally, the project provides a dashboard to explore the data interactively.
 
# 📈COVID-19_ANALYSIS - 📑Brief Summary
</h1>
- Used Pandas and Json to gather data from API and then data cleaning.
<br>
- For K.P.I.’s and insights Used SQL to get useful data sets.
<br>
- Then transferred datasets to Excel for visualization.
<br>
- For the presentation used M.S. PowerPoint with the help of team members.
<h2>
 🪨Challenges and 🧠learnings-
</h2>
- API handling | Error Handling | Impactful presentation
<h2> 
  🔡Data Extraction & Cleaning
 <br>
 <br>
1. Import the data from API using the requests library.
<br>
<br>
2. The imported data was in JSON format hence we used JSON library to read the data.

![Screenshot (265)](https://github.com/mdkamran048/Covid-19-Analysis/assets/143988392/d25f5aff-bd99-47a0-adcc-28ef518292b8)
![Screenshot (266)](https://github.com/mdkamran048/Covid-19-Analysis/assets/143988392/364a1577-fb20-4aa3-a90c-569b3d4cbeec)




3. We looked for null values and replaced them with zero, looking for duplicates.
<br>
4. Stated analyzing the data by using pandas functions like group by, sort_values, etc.
<br>
<br>
5. Used nested 'for' loops to extract the relevant data from the nested dictionary.

![Screenshot (262)](https://github.com/mdkamran048/Covid-19-Analysis/assets/143988392/0f068ec0-0c75-4126-a127-81385301e447)
![Screenshot (263)](https://github.com/mdkamran048/Covid-19-Analysis/assets/143988392/45feeca4-8191-422c-809c-10aa4804dcfc)
![Screenshot (264)](https://github.com/mdkamran048/Covid-19-Analysis/assets/143988392/c0f64647-8a1d-4ed4-a436-e5aa0cf888b2)

6. Extracted the individual state data from the data frame in CSV format and imported data into MySQL.
<br>
7. Aggregated the distribution by month and week wise for each state.
<br>
<br>
8. Imported the aggregated data into Excel for further Analysis.
<br>
<br>
📊Dashboard
