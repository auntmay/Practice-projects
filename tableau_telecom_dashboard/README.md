# 📊 Project Overview: NPS Analysis for a Telecommunications Company

### 🛠 Technologies Used:
- Python
- pandas
- SQL, SQLite
- SQLAlchemy
- Tableau

### 🔍 Project Summary:
The client for this study is a large telecommunications company. The company tasked us with analyzing its current level of customer engagement, specifically the Net Promoter Score (NPS) among its client base. To assess the NPS, the company conducted a large survey asking clients a simple question: “On a scale from 1 to 10, how likely are you to recommend our company to friends and family?”

Results are interpreted as follows:
- **9-10 points** — “Promoters” 👍
- **7-8 points** — “Passives” 😐
- **0-6 points** — “Detractors” 👎

The final NPS score is calculated using the formula: **% promoters - % detractors**. The goal of this project is to investigate the NPS score for the company.

### 🎯 Project Goals and Objectives:

1. **Develop a Project Plan** 
2. **Connect to the Database, Read, and Perform a Basic Data Integrity Check** 
   - Connect to the database using SQLAlchemy
   - Display the first few rows of the dataset and basic data information using `.info()`
3. **Create a Data Mart and Export to CSV** 
   - Write an SQL query to extract data based on specified criteria
   - Read the SQL query with `pd.read_sql()`
   - Check data integrity
   - Export the data to CSV
4. **Load the CSV File into Tableau and Answer Key Questions through Visualizations and Dashboards:** 
   - How are survey participants distributed by age and gender? Are there more new or returning users? Which cities had the highest participation rates?
   - Which groups of users are most loyal to the service? Which are the least?
   - What is the overall NPS among all respondents?
   - How would you describe the customers who fall into the "promoters" category?

### 📈 Project Insights:

1. Successfully completed the research, created a dashboard, and presented it to the client.
2. Discovered interesting trends in the data. For example, NPS strongly correlates with age: the older the user, the more satisfied they are with the service. This may be because older users tend to have fewer expectations from telecom operators, while younger users are more tech-savvy and accustomed to demanding more from their services.
3. Notably, the longer a customer has been with the service, the less likely they are to be satisfied. A similar pattern was observed with traffic consumption: the more a user pays, the more they feel entitled to demand better service — a natural behavior.
4. The most loyal age group turned out to be those 66+ years old, regardless of gender.
5. The proportion of new versus returning users was nearly identical across genders, although in absolute numbers, the service has more female users.
6. The overall NPS for the company was **0.219**. It’s hard to say definitively whether this is good or bad, but there’s certainly room for improvement.

