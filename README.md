# Climate-Clash
An extensive analysis that aims to identify the specific climatic factors in VIT Bhopal responsible for causing my medical issues by analyzing and comparing the climatic data of VIT Bhopal with somewhere much more humid such as in Kerala.

## Screenshots

### Analysis

<img width="810" alt="Screenshot 2025-02-16 at 3 00 12 PM" src="https://github.com/user-attachments/assets/aa366474-021b-487d-8936-5075d29b5f03" />

### Dashboard
<img width="818" alt="Screenshot 2025-02-16 at 2 31 59 PM" src="https://github.com/user-attachments/assets/dac2df10-b7c6-41cf-8d2b-6532683cc8ff" />

<img width="820" alt="Screenshot 2025-02-16 at 2 32 07 PM" src="https://github.com/user-attachments/assets/78e885ee-49bd-43fe-b3d3-8b2e884b86a3" />


## Process
To begin my analysis, I collected data on various weather parameters such as temperature, humidity, precipitation, wind speed, etc for both locations. I obtained historical weather data for the corresponding periods of time when I was sick over a span of 12 months.
I loaded the data into a `PostgreSQL` database and analysed this data using `SQL` queries to answer questions such as:
- When was the hottest day on campus?
- When was the hottest day at Kerala?
- What was the temperature when one of the two places was experiencing its hottest day?
- When was the coldest day on campus?
- When was the coldest day at Kerala?
- What was the average temperature of each month?
  
After answering these questions, I visualized this data, using Tableau, in multiple ways to gain the necessary insights required to reach a detailed answer.

## Reflection
After looking at all the parameters I was able to understand that, though the varying temperature did play a role but, the main reason behind my sickness was actually the humidity and the wind speed. The difference in the wind speed and humidity between the 2 places was  more significant and more influential on my health as compared to the temperature.
