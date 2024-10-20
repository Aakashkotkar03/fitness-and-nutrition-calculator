# Fitness Calculator

## Overview
The Fitness Calculator is a web application designed to help users calculate various fitness metrics such as BMI, BMR, and daily caloric needs. This tool is useful for individuals looking to track their fitness progress and make informed decisions about their health and fitness routines.

## Features
- **BMI Calculation**: Calculate Body Mass Index based on height and weight.
- **BMR Calculation**: Calculate Basal Metabolic Rate using different formulas (Harris-Benedict, Mifflin-St Jeor).
- **Daily Caloric Needs**: Estimate daily caloric needs based on activity level.
- **User-Friendly Interface**: Easy-to-use interface with clear input fields and results display.

## Formulas Used
### BMI (Body Mass Index)
\[ \text{BMI} = \frac{\text{weight (kg)}}{\text{height (m)}^2} \]

### BMR (Basal Metabolic Rate)
#### Harris-Benedict Equation:
- **For Men**: 
\[ \text{BMR} = 88.362 + (13.397 \times \text{weight (kg)}) + (4.799 \times \text{height (cm)}) - (5.677 \times \text{age (years)}) \]
- **For Women**: 
\[ \text{BMR} = 447.593 + (9.247 \times \text{weight (kg)}) + (3.098 \times \text{height (cm)}) - (4.330 \times \text{age (years)}) \]

#### Mifflin-St Jeor Equation:
- **For Men**: 
\[ \text{BMR} = (10 \times \text{weight (kg)}) + (6.25 \times \text{height (cm)}) - (5 \times \text{age (years)}) + 5 \]
- **For Women**: 
\[ \text{BMR} = (10 \times \text{weight (kg)}) + (6.25 \times \text{height (cm)}) - (5 \times \text{age (years)}) - 161 \]

### Daily Caloric Needs
\[ \text{Calories} = \text{BMR} \times \text{Activity Level} \]

Activity Levels:
- Sedentary (little or no exercise): BMR \(\times\) 1.2
- Lightly active (light exercise/sports 1-3 days/week): BMR \(\times\) 1.375
- Moderately active (moderate exercise/sports 3-5 days/week): BMR \(\times\) 1.55
- Very active (hard exercise/sports 6-7 days a week): BMR \(\times\) 1.725
- Super active (very hard exercise/sports & physical job or 2x training): BMR \(\times\) 1.9

## How It Works
1. **Input Data**: Users input their personal data such as age, gender, height, weight, and activity level.
2. **Select Calculation**: Users choose the type of calculation they want to perform (BMI, BMR, Daily Caloric Needs).
3. **View Results**: The application processes the input data using the relevant formulas and displays the results.

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/fitness-calculator.git
