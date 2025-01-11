# SQL-Case-1-Vision-Entertainment-Agency

### 1. Case Statement

**1) Background**

  +  Vision Entertainment Agency (VEA) is a premier agency managing entertainers, agents, customers, and bookings across diverse regions. The database is crucial for tracking engagements, customer preferences, and entertainer styles while ensuring seamless coordination between agents and clients. As Chief Data Scientist, I have been tasked by the CEO to address key operational questions to support the agency's strategic objectives.
<br>
**2) Objective**

  +  **Entertainer Details**: Identify entertainers meeting specific criteria to improve communication and outreach.
  +  **Engagement Analysis**: Analyze engagement durations and trends to optimize booking strategies.
  +  **Customer Engagements**: Identify key entertainers contributing to strong customer relationships.
  +  **Unbooked or Incomplete Profiles**: Detect unbooked entertainers or incomplete profiles to ensure accuracy and efficiency.

<br>

### 2. Queries

**1) Case Questions**

  + Show a list of entertainers based in ‘Bellevue,’ ‘Redmond,’ or ‘Woodinville’ who do not have a registered email address. Include their stage name, phone number, and city.
  + List entertainers who have either never been booked or do not have a webpage or email address. Sort by entertainer ID in ascending order.
  + List entertainers who specialize in a specific musical style (e.g., Jazz or Pop) but have not performed any engagements in the past two years. Include their stage name, musical style, and last engagement date.
  + Identify entertainers who are managed by more than one agent. Provide their stage name, agent names, and contact details.
  + Summarize engagements by month for the year 2018, including the total number of engagements and average contract price. Sort by month in ascending order.
  + Identify the top 5 entertainers with the longest cumulative engagement durations (in days) for the year 2017. For each entertainer, include their stage name, total number of engagements, cumulative engagement days, and average contract price. Also, categorize them based on their engagement frequency: "High Frequency" (10 or more), "Moderate Frequency" (5-9), "Low Frequency" (fewer than 5).
  + Identify the top 5 customers with the highest total engagement spending in 2017. Include customer name, total spending, and number of engagements booked.
  + List customers who booked engagements with entertainers in more than three different musical styles. Include customer name, total engagement count, and musical styles booked.
  + Identify entertainers who have missing or invalid phone numbers (e.g., NULL values or incorrectly formatted numbers). Include their stage name, phone number, and city, sorted alphabetically by stage name.
  + For each entertainer, include their stage name, city, missing/invalid fields (e.g., Email/Phone), and number of distinct musical styles they are associated with but have no engagements for. Sort the results alphabetically by stage name.
