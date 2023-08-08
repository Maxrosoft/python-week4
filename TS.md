# FitBot - Telegram Bot for Fitness and Nutrition

FitBot is a Telegram bot designed to assist users in achieving their fitness and nutrition goals. This document provides a detailed technical specification (TS) for the development of such a bot.

**answer any incorrectly entered data with "I don't understand you, write /help"** 

### Features

1. **Greeting**
   FitBot will warmly welcome users during their initial interaction and introduce itself.

2. **User Data Storage**
   FitBot will securely store essential user data, including Height, Weight, Age, Gender, and Activity Level (ranging from 1 to 5).

3. **Daily Calorie Intake Calculation**
   FitBot will employ standard formulas for Basal Metabolic Rate (BMR) and activity level to calculate the user's recommended daily calorie intake, taking into account their activity level.

4. **Body Mass Index (BMI) Calculation**
   FitBot will accurately compute the user's Body Mass Index (BMI) based on the provided height and weight, utilizing recognized formulas.

5. **Water Consumption Calculation**
   FitBot will determine the user's recommended daily water intake by considering weight and activity level, adhering to established guidelines for water consumption.

6. **Tracked Calorie Consumption**
   FitBot will utilize a comprehensive food calorie database to monitor and track the user's calorie consumption.

7. **Adding New Foods**
   In cases where a specific food item is not present in the calorie database, FitBot will guide the user through the process of adding it. Users can input the food name and its corresponding calorie count.

8. **Calorie Reset**
   FitBot will grant users the capability to reset their tracked calorie consumption, promoting flexibility in their tracking journey.

9. **Display of Consumed Calories**
   FitBot will promptly display the user's current tally of consumed calories, providing real-time feedback on their progress.

10. **Exercise Recommendations**
    FitBot will offer tailored exercise recommendations to aid in calorie expenditure. These suggestions will factor in the user's gender and surplus calorie intake.

### Complexity Rating

Number of points for each task **(maximum 160)**:

- Greeting: **2**
- User Data Storage: **10**
- Daily Calorie Intake Calculation: **10**
- BMI Calculation: **10**
- Water Consumption Calculation: **10**
- Tracked Calorie Consumption: **30**
- Adding New Foods: **40**
- Calorie Reset: **4**
- Display of Consumed Calories: **4**
- Exercise Recommendations: **40**

With this comprehensive technical specification, FitBot aims to provide users with an integrated and user-friendly experience to assist them in their fitness and nutrition endeavors.
