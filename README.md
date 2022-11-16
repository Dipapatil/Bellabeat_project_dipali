# Bellabeat_project_dipali

This project is about analyzing Fitbit users dataset to unlock the growth opportunities for Bellabeat.

Tools used : Tableau, Bigquery, Google Sheets.

Project contains :
  - Documentation
  - Queries
  - Visualization
  - Dataset



Bellabeat Marketing Strategy

Overview : - Bellabeat is a high tech company that manufactures heath focused smart products for women around the world. 
Bellabeat was founded in 2013.
Bellabeat has grown rapidly and quickly, by 2016 Bellabeat had opened offices around the world and launched multiple products.
Bellabeat focuses on digital marketing extensively.
Bellabeat has potential to become a larger player in the global smart device market.

Product launched by bellabeat

Bellabeat app :  provides health data related to activity, sleep, stress and mindfulness habits.
Data can help users better understand their habits and make healthy decisions.
Leaf :  This tracker can be worn as a bracelet , necklaces  or clip. It connects to bellabeat app.
Time :  Timeless classic watch with smart technology. Tracks activity , sleep ,stress. 
 Connect to bellabeat app.
Spring : water bottle that tracks daily water intake using smart technology to ensure that you are hydrated throughout the day. Connect to bellabeat app to track hydration level.


Senario : Analyze Fitbit fitness data to unlock new growth opportunities for Bellabeat. We are focusing on the ‘Time’ product of Bellabeat.

Six phases of Data Analysis 

ASK : 

Business Task : Let’s add  new features to our product ‘Time’ in order to increase our revenue and help women to be aware of health and fitness.

Stakeholders : 
Bellabeats cofounder
Chief creative officer
Bellabeat marketing analytics team.
		Goals : 
Unlock the new growth opportunities.
Increase revenue
Better service for women
Improve health and habits
Become a larger player in the global smart device market.
Prepare : 
	Data source : Fitbit fitness tracker data.
	This is a kaggle dataset of 30 fitbit users over the   period of 30 days. It includes information about daily activity, steps , calories, heart rate that can be used to explore the user's habits.

Does your data ROCCC

R (Reliable ) : This is not a reliable dataset ,it does not represent the whole population. We don’t know the user's gender and  age group and also specific conditions of health. Data can be biased. 

O (Original) : not original datasource. Collected from a third party.

C (Comprehensive) : Dataset is missing information about recommended steps or calories. 
Limited data. 

C (Current) : Data is not Current, data is collected in 2016.

C ( Cited) : evidence of justification. Data is not cited.

This data is not reliable, and it is biased.

Data Table used :
dailyActivity
dailyCalories
dailyIntensities
dailySteps
hourlyCalories
hourlySteps
minuteMET
sleepDay
weightBMI

3. Process : 
 	Tools used : 
		Basic Cleaning and formatting : google sheets
		Query : Big Query (sql)
		Visualization : Tableau Public

To check data’s integrity by writing queries in SQL and found out that there are 33 users but data shows 30 user’s only.
Also calculated Total distance in SQL to check if the numbers are correct.
Checked data types , did basic formatting like alignment and bold. 

Documentation of Cleaning of data Tables

dailyAcitivity, dailyIntensities : all distances related to columns format changed to Number with 2 decimal places.
hourlyCalories , hourlySteps, minuteMET: set datetime format for date column.
weightBMI : weight, BMI column changed to Number format with w decimal places.
Sleepday : changed column sleepday format from datetime to date.

4. Analysis : Used SQL to summarize the data.


Found positive correlation between Total number of Steps and Calories.
  As the total number of steps increases , then calories also increase.
Daily average steps of users - 7637
Monday and Friday have more sedentary minutes , people are less active on these days.
Maximum number of steps on Tuesday and Saturdays.
Maximum distance covered by users on Tuesday and saturday.
Afternoon is the most active time according to the number of steps.
More Calories are used at Afternoon time.
Users MET(Metabolic Equivalent of Task)  is higher at afternoon time.
Amount of energy used.
1.5 or lower  -> sedentary
1.6 - 3.0       -> light intensity
3.0 - 6.0       -> moderate
6.0 +            -> vigorous
Total time in bed is more than actual sleep time of users.

BMI : (Body Mass Index )
Healthy range of BMI users are more likely to be active. 

lower than 18.5 –    underweight
between 18.5 and 24.9 – healthy range
between 25 and 29.9 –    overweight.
between 30 and 39.9 –     obesity.
40 or over – severe obesity.
 
 
 
 
 
 
5.  Share : 
Total daily recommended steps by CDC is 10,000 and in fitbit user dataset approximately average total daily steps are 7500.
Steps and Calories have positive correlation.

Less Active time recorded for user’s

Actual sleep time is less than total time in bed


5. BMI : healthy range of BMI users are more active than overweight users. As the BMI increases Activity decreases.

Suggesting exercises to users according to BMI.
6. Users are less active on Monday and Friday

7. Saturday and Tuesday are more active days

8. At what time of day users are more active




Add reminder pop up feature every hour to increase activity.

6. Act : 
“Adding new features to our product ‘Time’ will result in an increase in our sales and Bellabeat will be the larger player in smart device fitness products to empower women in health and fitness.”

Introduce new features like to track calories, heart rate, suggest exercise according to BMI.
Hourly reminder popup to encourage users to be active.
Also add remainder to less active days.
add health tips option.
Before sleep, encourage users to avoid screen time and do meditation.
Users should be able to choose features that they are interested in from the Bellabeat app to add on their ‘Time’ watch. Features like Steps, heart rate, exercise, Weight, sleep, calories, BMI, meditation.
If the user's exercise target is completed then praising words should pop up. Like congratulations, great work.
Also offer membership discounts to encourage users to use Time watch. This will result in more users and also it will increase popularity among smart device products for fitness.
After adding features surveys should be done. To see how the users are more satisfied with new features in watch.

