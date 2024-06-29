# Level-up-fitness
This file is related to an application of fitness which include personalised workout , nutrition and diet plans . Detailed nutrition information and activity tracking.

# HOME
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Click Image to Navigate</title>
    <style>
        body, html {
            margin: 0;
            padding: 0;
            height: 100%;
        }
        #clickable-image {
            width: 100%;
            height: 100%;
            object-fit: cover;
            cursor: pointer;
        }
    </style>
</head>
<body>
    <img id="clickable-image" src="https://i.ibb.co/hy2Yx2h/IMG-20240629-WA0006.jpg" alt="IMG-20240629-WA0006" border="0"></a>" alt="Clickable Image">

    <script>
        document.getElementById('clickable-image').addEventListener('click', function() {
            window.location.href = 'index.html';
        });
    </script>
</body>
</html>

# INDEX
 
   <!DOCTYPE html>
   <html lang="en">
   <head>
       <meta charset="UTF-8">
       <meta name="viewport" content="width=device-width, initial-scale=1.0">
       <title>Level Up Fitness - Get Fit, Level Up Your Life</title>
       <style>
           body {
               font-family: Arial, sans-serif;
               line-height: 1.6;
               margin: 0;
               padding: 0;
               background-color: #f4f4f4;
           }
           header {
               background-color: #b12c52;
               color: #fff;
               text-align: center;
               padding: 1rem;
           }
           main {
               padding: 2rem;
               max-width: 800px;
               margin: 0 auto;
           }
           h1 {
               color: #f0f0f0;
           }
           .cta-button {
               display: inline-block;
               background-color: #b12c52;
               color: white;
               padding: 10px 20px;
               text-decoration: none;
               border-radius: 5px;
               font-weight: bold;
           }
       </style>
   </head>
   <body>
       <header>
           <h1>FitnessFreak</h1>
           <p>Level Up Your Fitness</p>
       </header>
   
       <main>
           <h2>Welcome to Level Up Fitness</h2>
           <p>Are you ready to take your fitness journey to the next level? Level Up Fitness is here to help you achieve your health and wellness goals.</p>
   
           <h3>What We Offer:</h3>
           <ul>
               <li>Personalized workout plans</li>
               <li>Nutrition guidance</li>
               <li>One-on-one coaching</li>
               <li>Group fitness classes</li>
               <li>State-of-the-art equipment</li>
           </ul>
   
           <p>Whether you're a beginner or an experienced athlete, we have the tools and expertise to help you level up your fitness game.</p>
   
           <p>Ready to start your journey?</p>
           <!-- <a href="#" class="cta-button">Join Now</a> -->
           <a href="register.html" class="cta-button">Get Started Now</a>

       </main>
   </body>
   </html>

# REGISTER
   <!-- <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Fitness App - Register</title>
</head>
<body>
    <h1><b>Register</b></h1>
    <form action="register.html" method="post">
        <label for="username">Username:</label>
        <input type="text" id="username" name="username" required>
        <br />
        <label for="password">Password:</label>
        <input type="password" id="password" name="password" required>
        <br />
        <input type="submit" value="Register">
    </form>
    <p>Already have an account? <a href="login.html">Login here</a></p>
</body>
</html> -->
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Level Up App Registration</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            margin: 0;
            padding: 20px;
        }
        .container {
            max-width: 400px;
            margin: 0 auto;
        }
        h1 {
            text-align: center;
        }
        form {
            background: #f4f4f4;
            padding: 20px;
            border-radius: 5px;
        }
        label {
            display: block;
            margin-bottom: 5px;
        }
        input[type="text"],
        input[type="email"],
        input[type="password"] {
            width: 100%;
            padding: 8px;
            margin-bottom: 10px;
            border: 1px solid #b12c52;
            border-radius: 3px;
        }
        input[type="submit"] {
            display: block;
            width: 100%;
            padding: 10px;
            background: #b12c52;
            color: #fff;
            border: none;
            border-radius: 3px;
            cursor: pointer;
        }
        input[type="submit"]:hover {
            background: #b12c52;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Level Up App Registration</h1>
        <form action="#" method="POST">
            <label for="username">Username:</label>
            <input type="text" id="username" name="username" required>

            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>

            <label for="password">Password:</label>
            <input type="password" id="password" name="password" required>

            <label for="confirm-password">Confirm Password:</label>
            <input type="password" id="confirm-password" name="confirm-password" required>

            <input type="submit" value="Register">
            <p>Already have an account? <a href="login.html">Login here</a></p>
        </form>
    </div>
    


</body>
</html>

# LOGIN
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Level Up Fitness - Login</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f0f0f0;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
        }
        .login-container {
            background-color: white;
            padding: 2rem;
            border-radius: 5px;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
        }
        h1 {
            text-align: center;
            color: #333;
        }
        form {
            display: flex;
            flex-direction: column;
        }
        input {
            margin: 10px 0;
            padding: 10px;
            border: 1px solid #b12c52;
            border-radius: 4px;
        }
        button {
            background-color: #b12c52;
            color: white;
            border: none;
            padding: 10px;
            border-radius: 4px;
            cursor: pointer;
        }
        button:hover {
            background-color: #b12c52;
        }
    </style>
</head>
<body>
    <div class="login-container">
        <h1>Level Up Fitness</h1>
        <form action="/login" method="POST">
            <input type="text" name="username" placeholder="Username" required>
            <input type="password" name="password" placeholder="Password" required>
            <button type="submit">Login</button>
        </form>
    </div>
</body>
</html>

# Python code done
import mysql.connector

# MySQL connection settings
username = 'root'
password = 'shreya1'
host = 'localhost'
database = 'fitness'

# Connect to MySQL database
cnx = mysql.connector.connect(
    user=username,
    password=password,
    host=host,
    database=database
)

# Create a cursor object to execute queries
cursor = cnx.cursor()

class UserProfile:
    def _init_(self, user_id, age, gender, weight, height, fitness_goals, health_conditions, name):
        self.user_id = user_id
        self.age = age
        self.gender = gender
        self.weight = weight
        self.height = height
        self.fitness_goals = fitness_goals
        self.health_conditions = health_conditions
        self.name = name

    def update_profile(self, age=None, gender=None, weight=None, height=None, fitness_goals=None, health_conditions=None):
        if age:
            self.age = age
        if gender:
            self.gender = gender
        if weight:
            self.weight = weight
        if height:
            self.height = height
        if fitness_goals:
            self.fitness_goals = fitness_goals
        if health_conditions:
            self.health_conditions = health_conditions

        # Update user profile in database
        query = "UPDATE user_profiles SET age = %s, gender = %s, weight = %s, height = %s, fitness_goals = %s, health_conditions = %s WHERE user_id = %s"
        cursor.execute(query, (self.age, self.gender, self.weight, self.height, self.fitness_goals, self.health_conditions, self.user_id))
        cnx.commit()

    def track_progress(self):
        # Retrieve user's activity logs from database
        query = "SELECT * FROM activity_logs WHERE user_id = %s"
        cursor.execute(query, (self.user_id,))
        activity_logs = cursor.fetchall()

        # Calculate progress metrics (e.g., total workouts, total duration, etc.)
        total_workouts = len(activity_logs)
        total_duration = sum(log[2] for log in activity_logs)

        # Return progress metrics
        return total_workouts, total_duration

def main():
    user_id = input("Enter user ID: ")
    age = int(input("Enter age: "))
    gender = input("Enter gender: ")
    weight = float(input("Enter weight: "))
    height = float(input("Enter height: "))
    fitness_goals = input("Enter fitness goals: ")
    health_conditions = input("Enter health conditions: ")
    name = input("Enter name: ")

    user_profile = UserProfile(user_id, age, gender, weight, height, fitness_goals, health_conditions, name)

    print("User Profile:")
    print("Age:", user_profile.age)
    print("Gender:", user_profile.gender)
    print("Weight:", user_profile.weight)
    print("Height:", user_profile.height)
    print("Fitness Goals:", user_profile.fitness_goals)
    print("Health Conditions:", user_profile.health_conditions)

    # Update user profile
    user_profile.update_profile(age=30, gender="Female", weight=60.0, height=165.0)


    # Track progress
    progress_metrics = user_profile.track_progress()
    print("Progress Metrics:")
    print("Total Workouts:", progress_metrics[0])
    print("Total Duration:", progress_metrics[1])

    # Generate workout plan
    workout_plan_generator = WorkoutPlanGenerator()
    workout_plan = workout_plan_generator.generate_workout_plan(user_id, "beginner")
    print("Workout Plan:")
    print("Exercises:", workout_plan.exercises)
    print("Video Tutorials:", workout_plan.get_video_tutorials())
    print("Step-by-Step Instructions:", workout_plan.get_step_by_step_instructions())

    # Generate diet plan
    diet_plan_generator = DietPlanGenerator()
    diet_plan = diet_plan_generator.generate_diet_plan(user_id, "vegetarian")
    print("Diet Plan:")
    print("Meals:", diet_plan.meals)
    print("Nutritional Information:", diet_plan.get_nutritional_information())
    print("Recipes and Meal Prep Instructions:", diet_plan.get_recipes_and_meal_prep_instructions())

    # Log a workout
    activity_log = ActivityLog(user_id, "push-ups", 30, "2023-03-01")
    activity_log.log_workout()
    print("Workout logged successfully!")


if _name_ == "_main_":
    main()
    

# Personalized Workout Plans
class WorkoutPlan:
    def init(self, user_id, difficulty_level, exercises):
        self.user_id = user_id
        self.difficulty_level = difficulty_level
        self.exercises = exercises

    def get_video_tutorials(self):
        # Retrieve video tutorials for each exercise from database or external API
        video_tutorials = []
        for exercise in self.exercises:
            query = "SELECT video_url FROM exercise_videos WHERE exercise_name = %s"
            cursor.execute(query, (exercise,))
            video_url = cursor.fetchone()[0]
            video_tutorials.append(video_url)
        return video_tutorials

    def get_step_by_step_instructions(self):
        # Retrieve step-by-step instructions for each exercise from database or external API
        instructions = []
        for exercise in self.exercises:
            query = "SELECT instructions FROM exercise_instructions WHERE exercise_name = %s"
            cursor.execute(query, (exercise,))
            instruction = cursor.fetchone()[0]
            instructions.append(instruction)
        return instructions

class WorkoutPlanGenerator:
    def init(self):
        self.workout_plans = {}

    def generate_workout_plan(self, user_id, difficulty_level):
        # Implement logic to generate a workout plan based on user profile and fitness goals done
        # Retrieve user profile from database
        query = "SELECT * FROM user_profiles WHERE user_id = %s"
        cursor.execute(query, (user_id,))
        user_profile = cursor.fetchone()

        # Determine exercises based on user profile and fitness goals
        exercises = []
        if user_profile[1] < 30:  # Age < 30
            if difficulty_level == 'beginner':
                exercises = ['push-ups', 'squats', 'lunges', 'planks']
            elif difficulty_level == 'intermediate':
                exercises = ['bench press', 'deadlifts', 'bicep curls', 'tricep dips']
            elif difficulty_level == 'advanced':
                exercises = ['weightlifting', 'high-intensity interval training', 'plyometrics']
        elif user_profile[1] >= 30 and user_profile[1] < 50:  # Age 30-49
            if difficulty_level == 'beginner':
                exercises = ['brisk walking', 'swimming', 'cycling', 'yoga']
            elif difficulty_level == 'intermediate':
                exercises = ['jogging', 'jumping rope', 'boxing', 'kickboxing']
            elif difficulty_level == 'advanced':
                exercises = ['marathon training', 'triathlon training', ' CrossFit']
        else:  # Age 50+
            if difficulty_level == 'beginner':
               exercises = ['stretching', 'light yoga', 'short walks', 'swimming']
            elif difficulty_level == 'intermediate':
               exercises = ['brisk walking', 'jogging', 'cycling', 'dancing']
            elif difficulty_level == 'advanced':
               exercises = ['high-intensity interval training', 'strength training', 'balance exercises']

        # Create a WorkoutPlan object with the generated exercises
        plan = WorkoutPlan(user_id, difficulty_level, exercises)
        self.workout_plans[user_id] = plan
        return plan

    def get_workout_plan(self, user_id):
        return self.workout_plans.get(user_id)

# Nutrition and Diet Plans
class DietPlan:
    def init(self, user_id, dietary_preferences, meals):
        self.user_id = user_id
        self.dietary_preferences = dietary_preferences
        self.meals = meals

    def get_nutritional_information(self):
        # Implement logic to retrieve detailed nutritional information for each meal done
        # Retrieve nutritional information for each meal from database or external API
        nutritional_info = []
        for meal in self.meals:
            query = "SELECT nutritional_info FROM meal_nutrition WHERE meal_name = %s"
            cursor.execute(query, (meal,))
            info = cursor.fetchone()[0]
            nutritional_info.append(info)
        return nutritional_info

    def get_recipes_and_meal_prep_instructions(self):
        # Implement logic to retrieve recipes and meal prep instructions done
        # Retrieve recipes and meal prep instructions for each meal from database or external API
        recipes_and_instructions = []
        for meal in self.meals:
            query = "SELECT recipe, instructions FROM meal_recipes WHERE meal_name = %s"
            cursor.execute(query, (meal,))
            recipe, instructions = cursor.fetchone()
            recipes_and_instructions.append((recipe, instructions))
        return recipes_and_instructions

class DietPlanGenerator:
    def init(self):
        self.diet_plans = {}

    def generate_diet_plan(self, user_id, dietary_preferences):
        # Implement logic to generate a diet plan based on user profile and dietary preferences done
        # Get user profile from database
        cursor.execute("SELECT * FROM users WHERE id = %s", (user_id,))
        user = cursor.fetchone()
        if not user:
            raise ValueError("User not found")

        # Get dietary preferences from database
        cursor.execute("SELECT * FROM dietary_preferences WHERE id = %s", (dietary_preferences,))
        diet_pref = cursor.fetchone()
        if not diet_pref:
            raise ValueError("Dietary preference not found")

        # Calculate daily calorie needs based on user profile
        daily_calories = self.calculate_daily_calories(user)

        # Generate meal plan based on dietary preferences and daily calorie needs
        meals = self.generate_meal_plan(diet_pref, daily_calories)

        # Create a DietPlan object
        plan = DietPlan(user_id, dietary_preferences, meals)
        self.diet_plans[user_id] = plan
        return plan

    def calculate_daily_calories(self, user):
        # Simplified calculation based on user profile
        if user['gender'] == 'male':
            daily_calories = 2500 + (user['weight'] * 10) + (user['height'] * 6.25) - (user['age'] * 5)
        else:
            daily_calories = 2000 + (user['weight'] * 10) + (user['height'] * 6.25) - (user['age'] * 5)

        # Adjust for activity level
        if user['activity_level'] == 'edentary':
            daily_calories *= 1.2
        elif user['activity_level'] == 'lightly active':
            daily_calories *= 1.375
        elif user['activity_level'] == 'oderately active':
            daily_calories *= 1.55
        elif user['activity_level'] == 'ery active':
            daily_calories *= 1.725
        elif user['activity_level'] == 'extremely active':
            daily_calories *= 1.9

        return daily_calories

    def generate_meal_plan(self, diet_pref, daily_calories):
        # Simplified meal plan generation based on dietary preferences and daily calorie needs
        meals = []
        for meal_type in ['breakfast', 'lunch', 'dinner', 'nack']:
            meal = self.generate_meal(diet_pref, daily_calories, meal_type)
            meals.append(meal)
        return meals

    def generate_meal(self, diet_pref, daily_calories, meal_type):
        # Simplified meal generation based on dietary preferences and daily calorie needs
        meal = {}
        if meal_type == 'breakfast':
            meal['food'] = 'oatmeal with fruits'
            meal['calories'] = daily_calories * 0.3
        elif meal_type == 'lunch':
            meal['food'] = 'grilled chicken with quinoa and vegetables'
            meal['calories'] = daily_calories * 0.4
        elif meal_type == 'dinner':
            meal['food'] = 'baked salmon with sweet potato and green beans'
            meal['calories'] = daily_calories * 0.4
        elif meal_type == 'nack':
            meal['food'] = 'apple slices with almond butter'
            meal['calories'] = daily_calories * 0.1

        # Adjust meal based on dietary preferences
        if diet_pref['diet_type'] == 'egetarian':
            meal['food'] = meal['food'].replace('chicken', 'tofu')
        elif diet_pref['diet_type'] == 'gluten-free':
            meal['food'] = meal['food'].replace('quinoa', 'gluten-free rice')

        return meal

    def get_diet_plan(self, user_id):
        return self.diet_plans.get(user_id)

# Activity Tracking
class ActivityLog:
    def init(self, user_id, workout, duration, date):
        self.user_id = user_id
        self.workout = workout
        self.duration = duration
        self.date = date

    def log_workout(self):
        # Implement logic to log workout in database
        query = "INSERT INTO activity_logs (user_id, workout, duration, date) VALUES (%s, %s, %s, %s)"
        cursor.execute(query, (self.user_id, self.workout, self.duration, self.date))
        cnx.commit()

        # Calculate progress metrics (e.g., total workouts, total duration)
        self.calculate_progress_metrics(cnx, cursor)

    def calculate_progress_metrics(self, cnx, cursor):
        # Calculate total workouts
        query = "SELECT COUNT(*) FROM activity_logs WHERE user_id = %s"
        cursor.execute(query, (self.user_id,))
        total_workouts = cursor.fetchone()[0]

        # Calculate total duration
        query = "SELECT SUM(duration) FROM activity_logs WHERE user_id = %s"
        cursor.execute(query, (self.user_id,))
        total_duration = cursor.fetchone()[0]

        # Update user's progress metrics
        query = "UPDATE users SET total_workouts = %s, total_duration = %s WHERE id = %s"
        cursor.execute(query, (total_workouts, total_duration, self.user_id))
        cnx.commit()
        query = "INSERT INTO activity_logs (user_id, workout, duration, date) VALUES (%s, %s, %s, %s)"
        cursor.execute(query, (self.user_id, self.workout, self.duration, self.date))
        cnx.commit()



def main():
    user_id = input("Enter user ID: ")
    user_profile = UserProfile(user_id)
    print("User Profile:")
    print("Age:", user_profile.age)
    print("Gender:", user_profile.gender)
    print("Weight:", user_profile.weight)
    print("Height:", user_profile.height)
    print("Fitness Goals:", user_profile.fitness_goals)
    print("Health Conditions:", user_profile.health_conditions)

    # Update user profile
    user_profile.update_profile(age=30, gender="Female", weight=60.0, height=165.0)

    # Track progress
    user_profile.track_progress()


    main()

# MYSQL DATABASE
    create database fitness;
USE fitness;

CREATE TABLE user_profiles (
  user_id INT PRIMARY KEY,
  age INT,
  gender ENUM('Male', 'Female'),
  weight DECIMAL(5, 2),
  height DECIMAL(5, 2),
  fitness_goals TEXT,
  health_conditions TEXT
);
INSERT INTO user_profiles (user_id, age, gender, weight, height, fitness_goals, health_conditions)
VALUES
  (1, 25, 'Male', 70.50, 175.00, 'Lose weight', 'None'),
  (2, 30, 'Female', 55.00, 160.00, 'Gain muscle', 'Diabetes'),
  (3, 28, 'Male', 80.00, 185.00, 'Increase endurance', 'High blood pressure');

CREATE TABLE activity_logs (
  log_id INT PRIMARY KEY,
  user_id INT,
  workout VARCHAR(50),
  duration TIME,
  date DATE,
  FOREIGN KEY (user_id) REFERENCES user_profiles (user_id)
);
INSERT INTO activity_logs (log_id, user_id, workout, duration, date)
VALUES
  (1, 1, 'Running', '00:30:00', '2022-01-01'),
  (2, 1, 'Swimming', '00:45:00', '2022-01-03'),
  (3, 2, 'Yoga', '00:20:00', '2022-01-05'),
  (4, 3, 'Cycling', '01:00:00', '2022-01-07');
  
CREATE TABLE workout_plans (
  workout_plan_id INT PRIMARY KEY,
  user_id INT,
  difficulty_level ENUM('Beginner', 'Intermediate', 'Advanced'),
  created_at TIMESTAMP DEFAULT CURRENT_TIMESTAMP,
  FOREIGN KEY (user_id) REFERENCES user_profiles (user_id)
);
INSERT INTO workout_plans (workout_plan_id, user_id, difficulty_level, created_at)
VALUES
  (1, 1, 'Beginner', '2022-01-01 00:00:00'),
  (2, 2, 'Intermediate', '2022-01-05 00:00:00'),
  (3, 3, 'Advanced', '2022-01-10 00:00:00');

CREATE TABLE video_tutorials (
  video_tutorial_id INT PRIMARY KEY,
  exercise_id INT,
  video_url VARCHAR(255),
  FOREIGN KEY (exercise_id) REFERENCES exercises (exercise_id)
);
INSERT INTO video_tutorials (video_tutorial_id, exercise_id, video_url)
VALUES
  (1, 1, 'https://example.com/pushups_tutorial'),
  (2, 2, 'https://example.com/squats_tutorial'),
  (3, 3, 'https://example.com/lunges_tutorial');

CREATE TABLE exercises (
  exercise_id INT PRIMARY KEY,
  name VARCHAR(50),
  description TEXT,
  video_url VARCHAR(255),
  instructions TEXT
);
INSERT INTO exercises (exercise_id, name, description, video_url, instructions)
VALUES
  (1, 'Push-ups', 'Upper body exercise', 'https://example.com/pushups', 'Do 3 sets of 10 reps'),
  (2, 'Squats', 'Lower body exercise', 'https://example.com/squats', 'Do 3 sets of 12 reps'),
  (3, 'Lunges', 'Lower body exercise', 'https://example.com/lunges', 'Do 3 sets of 10 reps per leg');
  
CREATE TABLE exercise_instructions (
  exercise_instruction_id INT PRIMARY KEY,
  exercise_id INT,
  instructions TEXT,
  FOREIGN KEY (exercise_id) REFERENCES exercises (exercise_id)
);
INSERT INTO exercise_instructions (exercise_instruction_id, exercise_id, instructions)
VALUES
  (1, 1, 'Start in a plank position'),
  (2, 1, 'Lower your body until your chest almost touches the ground'),
  (3, 2, 'Stand with your feet shoulder-width apart'),
  (4, 2, 'Lower your body until your thighs are parallel to the ground');
  
CREATE TABLE workout_plan_exercises (
  workout_plan_id INT,
  exercise_id INT,
  PRIMARY KEY (workout_plan_id, exercise_id),
  FOREIGN KEY (workout_plan_id) REFERENCES workout_plans (workout_plan_id),
  FOREIGN KEY (exercise_id) REFERENCES exercises (exercise_id)
);
INSERT INTO workout_plan_exercises (workout_plan_id, exercise_id)
VALUES
  (1, 1),  -- Workout plan 1 includes Push-ups
  (1, 2),  -- Workout plan 1 includes Squats
  (1, 3),  -- Workout plan 1 includes Lunges
  (2, 2),  -- Workout plan 2 includes Squats
  (2, 3),  -- Workout plan 2 includes Lunges
  (3, 1),  -- Workout plan 3 includes Push-ups
  (3, 2),  -- Workout plan 3 includes Squats
  (3, 3);  -- Workout plan 3 includes Lunges

CREATE TABLE diet_plans (
  diet_plan_id INT PRIMARY KEY,
  user_id INT,
  dietary_preferences TEXT,
  created_at TIMESTAMP DEFAULT CURRENT_TIMESTAMP,
  FOREIGN KEY (user_id) REFERENCES user_profiles (user_id)
);
INSERT INTO diet_plans (diet_plan_id, user_id, dietary_preferences, created_at)
VALUES
  (1, 1, 'Vegetarian', '2022-01-01 00:00:00'),
  (2, 2, 'Gluten-free', '2022-01-05 00:00:00'),
  (3, 3, 'Keto', '2022-01-10 00:00:00');
  
CREATE TABLE meals (
  meal_id INT PRIMARY KEY,
  name VARCHAR(50),
  description TEXT,
  nutritional_info TEXT,
  recipe TEXT
);
INSERT INTO meals (meal_id, name, description, nutritional_info, recipe)
VALUES
  (1, 'Veggie Burger', 'Healthy burger option', '300 calories, 20g protein', 'https://example.com/veggie_burger_recipe'),
  (2, 'Grilled Chicken', 'High-protein meal', '400 calories, 35g protein', 'https://example.com/grilled_chicken_recipe'),
  (3, 'Keto Salad', 'Low-carb salad', '200 calories, 10g fat', 'https://example.com/keto_salad_recipe');

CREATE TABLE diet_plan_meals (
  diet_plan_id INT,
  meal_id INT,
  PRIMARY KEY (diet_plan_id, meal_id),
  FOREIGN KEY (diet_plan_id) REFERENCES diet_plans (diet_plan_id),
  FOREIGN KEY (meal_id) REFERENCES meals (meal_id)
);
INSERT INTO diet_plan_meals (diet_plan_id, meal_id)
VALUES
  (1, 1),  -- User 1's diet plan includes Veggie Burger
  (1, 3),  -- User 1's diet plan includes Keto Salad
  (2, 2),  -- User 2's diet plan includes Grilled Chicken
  (2, 1),  -- User 2's diet plan includes Veggie Burger
  (3, 2),  -- User 3's diet plan includes Grilled Chicken
  (3, 3);  -- User 3's diet plan includes Keto Salad
