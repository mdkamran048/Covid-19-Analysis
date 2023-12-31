![Covid-19 image](https://github.com/mdkamran048/Covid-19-Analysis/assets/143988392/0edff2c1-2222-4578-9400-4cd6441bd405)

# Introduction

The COVID-19 Data Analysis Project is a comprehensive examination of the global impact of the COVID-19 pandemic. In the wake of this unprecedented global crisis, our project seeks to shed light on the pandemic's spread, effects, and the data-driven insights that can help in understanding and mitigating its impact.

# Objective

This project aims to analyze the COVID-19 pandemic using publicly available data. The project includes a Jupyter notebook with Python code to extract, clean, and visualize COVID-19 data from various sources. Additionally, the project provides a dashboard to explore the data interactively.
 
# 📈COVID-19_ANALYSIS - 📑Brief Summary

- Used Pandas and Json to gather data from API and then data cleaning.

- For K.P.I.’s and insights Used SQL to get useful data sets.

- Then transferred datasets to Excel for visualization.
  
- For the presentation used M.S. PowerPoint with the help of team members.


# 🔡Data Extraction & Cleaning

1. Import the data from API using the requests library.

2. The imported data was in JSON format hence we used JSON library to read the data.

![Screenshot (265)](https://github.com/mdkamran048/Covid-19-Analysis/assets/143988392/d25f5aff-bd99-47a0-adcc-28ef518292b8)
![Screenshot (266)](https://github.com/mdkamran048/Covid-19-Analysis/assets/143988392/364a1577-fb20-4aa3-a90c-569b3d4cbeec)


3. We looked for null values and replaced them with zero, looking for duplicates.

4. Stated analyzing the data by using pandas functions like group by, sort_values, etc.

5. Used nested 'for' loops to extract the relevant data from the nested dictionary.

![Screenshot (262)](https://github.com/mdkamran048/Covid-19-Analysis/assets/143988392/0f068ec0-0c75-4126-a127-81385301e447)
![Screenshot (263)](https://github.com/mdkamran048/Covid-19-Analysis/assets/143988392/45feeca4-8191-422c-809c-10aa4804dcfc)
![Screenshot (264)](https://github.com/mdkamran048/Covid-19-Analysis/assets/143988392/c0f64647-8a1d-4ed4-a436-e5aa0cf888b2)

6. Extracted the individual state data from the data frame in CSV format and imported data into MySQL.

7. Aggregated the distribution by month and week wise for each state.

8. Imported the aggregated data into Excel for further Analysis.

# Analysis

![Screenshot (267)](https://github.com/mdkamran048/Covid-19-Analysis/assets/143988392/0681f22f-d84d-4d29-b562-6370437247f7)
![Screenshot (268)](https://github.com/mdkamran048/Covid-19-Analysis/assets/143988392/32abfc35-a9da-44da-abbd-bb6855814cef)
![Screenshot (269)](https://github.com/mdkamran048/Covid-19-Analysis/assets/143988392/cb7fdc46-fd03-4206-9fd4-20d70b313154)
![Screenshot (270)](https://github.com/mdkamran048/Covid-19-Analysis/assets/143988392/68f06d36-770e-4a9d-bb0b-cd42948b0562)


# 📊Dashboard

![Screenshot (271)](https://github.com/mdkamran048/Covid-19-Analysis/assets/143988392/96b90e42-a505-40ba-bbe7-1d03c2fa2506)

 # 🪨Challenges and 🧠learnings
 
 Data Extraction from JSON : This process involves parsing structured JSON data to access, manipulate, and analyze valuable information.

 Data Cleaning and Pre-Processing : Real-World data is inconsistent and unorganized.

 Creating an Interactive Dashboard : Creating an interactive dashboard to understand data effectively.

 # Conclusion

1. The analysis focused on the weekly progression of COVID-19 cases, recoveries, deaths, and tests, providing valuable insights into the pandemic's impact across various 
   regions and timeframes.

2. Fluctuations in the number of cases and deaths were observed, underscoring the dynamic nature of the pandemic's effects in different geographical areas.

3. Through effective data visualization using charts and graphs, the project facilitated a clearer understanding of the data, aiding in the interpretation of trends and 
   patterns.

4. The project's findings hold practical significance for public health authorities, enabling them to devise more targeted and efficient strategies for containing the 
   virus's transmission.

5. Policymakers can benefit from the analysis by making informed decisions on resource allocation, directing support to regions experiencing the highest impact from the 
   pandemic.






