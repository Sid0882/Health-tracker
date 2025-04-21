
Data Management:

Tracks health metrics like steps, sleep, calories, and water consumption.
Stores data in JSON files for persistence (health_data.json and user_profile.json).
Uses pandas for efficient data handling and analysis.

User Profile:
Manages user attributes such as name, age, gender, height, weight, and health goals.
Calculates BMI and categorizes it (e.g., "Underweight", "Normal weight").
Estimates daily calorie needs using the Basal Metabolic Rate (BMR) formula.

Weekly Reporting:
Generates a detailed weekly health report summarizing performance against goals.
Provides insights and recommendations to improve health metrics.

Visualization:
Plots weekly trends for specific metrics like steps or sleep.
Compares weekly averages against goals using bar charts.
Creates a comprehensive dashboard with all health metrics visualized.

Interactive Command-Line Interface (CLI):
Offers an intuitive menu for users to add/update health data, view reports, and manage profiles.
Allows tracking of both current and past data interactively.

Flexibility and Insights:
Handles missing data gracefully, filling gaps with default values.
Provides actionable insights based on weekly performance.

Customizable Goals:
Enables users to set personalized health goals for steps, sleep, calories, and water intake.
Tracks progress towards these goals and highlights areas needing improvement.
