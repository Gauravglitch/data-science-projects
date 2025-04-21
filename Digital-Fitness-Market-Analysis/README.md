# Data-Driven Product Management: Conducting a Market Analysis
![gym](media/gym.png)

### Project Overview
This project analyzes the demand for digital fitness classes by exploring the popularity of the keywords **"workout," "home workout," "home gym,"** and **"gym workout"** using Python. The analysis includes global trends, keyword popularity during COVID-19, and regional interest to help identify growth areas in digital fitness.

### The Data

#### workout.csv
| Column        | Description              |
|---------------|--------------------------|
| `'month'`     | Month of data measurement. |
| `'workout_worldwide'` | Popularity index for the keyword "workout" (0-100). |

#### three_keywords.csv
| Column         | Description              |
|----------------|--------------------------|
| `'month'`      | Month of data measurement. |
| `'home_workout_worldwide'` | Popularity of "home workout" (0-100). |
| `'gym_workout_worldwide'` | Popularity of "gym workout" (0-100). |
| `'home_gym_worldwide'` | Popularity of "home gym" (0-100). |

#### workout_geo.csv
| Column         | Description              |
|----------------|--------------------------|
| `'country'`    | Country where data was measured. |
| `'workout_2018_2023'` | Popularity index of "workout" (2018-2023). |

#### three_keywords_geo.csv
| Column         | Description              |
|----------------|--------------------------|
| `'country'`    | Country where data was measured. |
| `'home_workout_2018_2023'` | Popularity of "home workout" (2018-2023). |
| `'gym_workout_2018_2023'` | Popularity of "gym workout" (2018-2023). |
| `'home_gym_2018_2023'` | Popularity of "home gym" (2018-2023). |

### Key Features
- **Peak Global 'Workout' Searches**: Identified peak global interest in "workout."
- **Most Popular Keywords**: Analyzed the top fitness-related keywords for the current year and during COVID-19.
- **Country with the Highest Interest**: Found the country with the highest search interest for workouts.
- **Home Workouts: Philippines vs. Malaysia**: Compared interest in "home workouts" between the Philippines and Malaysia.

### Technologies Used
- **Pandas** for data manipulation.
- **Matplotlib** for data visualization.
- **VS Code** for development.