# Garmin Connect Exercise List & Reference

This repository provides a comprehensive, emoji-enhanced list of all official exercises available in Garmin Connect, including their categories, targeted primary and secondary muscles, and associated equipment. The data is extracted from the Garmin Connect Forum and is intended to help users:

- Quickly find the closest matching official exercise name for their workout logging in Garmin Connect.
- Map custom/named exercises to Garmin Connect’s list for accurate tracking.
- Explore all available exercises to build your own plans, or feed the list to an AI assistant for personalized workout generation.

## Quick Links

- [Full Garmin Connect Exercise List](garmin_connect_exercise_list.md)
- [Example Weekly Workout Plan](weekly_workout_plan.md)

## Why Use This List?

Garmin Connect only allows logging exercises from its official database. If your preferred exercise name is missing, use this list to:
- Search for similar or alternative official names.
- Ensure your workout logs are compatible with Garmin Connect.
- Save time and avoid frustration when building or tracking workouts.

## What’s Inside?

- **garmin_connect_exercise_list.md**: A Markdown table of all official Garmin Connect exercises, with icons for muscle groups and equipment, plus a legend for easy reference.
- **workouts.json**: The raw data source from Garmin Connect, useful for developers or advanced users.
- **weekly_workout_plan.md**: An example beginner-friendly weekly workout plan using official Garmin Connect exercise names.

## Emoji Legend

**Muscle Groups:**
- 🦵 QUADS, HAMSTRINGS, ADDUCTORS, ABDUCTORS, HIPS
- 🍑 GLUTES
- 💪 BICEPS, TRICEPS
- 🏋️ SHOULDERS, CHEST
- 🧘 ABS, OBLIQUES
- 🔙 LOWER_BACK
- 🦾 LATS, TRAPS
- ✋ FOREARM
- 🦶 CALVES

**Equipment / Category:**
- 🏋️ Barbell, Dumbbell, Kettlebell, Plate
- 🚴 Bike, Elliptical
- 🟦 Band
- ⚽ Swiss Ball
- 🪑 Bench
- 🪢 Rope
- 🚣 Row
- 🔗 Cable
- 🤸 Bodyweight
- 🛠️ Machine

## Data Source

- Exercise names and muscle mapping are sourced from Garmin Connect’s and community resources.
- For more details, see the [Garmin Forums](https://forums.garmin.com/apps-software/mobile-apps-web/f/garmin-connect-web/152237/strength-workout---list-of-exercise-available-in-english-and-french).

---

### Generating Your Own Plan with AI

You can use an AI chat assistant to create a personalized workout plan similar to the [Example Weekly Workout Plan](weekly_workout_plan.md). Here's an example of how you might do it:

1.  **Provide Context to the AI:**
    *   Share the content of the `garmin_connect_exercise_list.md` file with the AI. This gives it the official exercise names, muscle groups, and equipment emojis.
    *   Tell the AI your available equipment (e.g., "I only have a Cable Machine and a Power Tower").
    *   Specify your fitness level (e.g., "I am a beginner").
    *   Describe your desired weekly structure (e.g., "I want a 3-day split focusing on Upper Body, Lower Body, and Core, with 2 rest days").

2.  **Give a Prompt to the AI:**
    You could use a prompt like this:
    ```
    "Please generate a beginner-friendly weekly workout plan.
    - Equipment: Cable Machine and Power Tower only.
    - Use exercise names, primary muscle groups (with emojis), and equipment emojis exactly as listed in the `garmin_connect_exercise_list.md` I provided.
    - The plan should have dedicated days for Upper Body, Lower Body, and Abs/Core.
    - Include 2-3 sets per exercise and 8-15 reps, adjusting for exercise type.
    - Format the output as a markdown table, similar to the example weekly workout plan.
    - Include a weekly schedule overview table.
    - Ensure all exercises are suitable for a beginner and the specified equipment."
    ```

3.  **Review and Refine:** The AI will generate a plan. Review it, and if needed, ask the AI for adjustments (e.g., "Can you replace X exercise with another one for the same muscle group?" or "Can you add more exercises for shoulders?").

This approach allows you to tailor a workout plan to your specific needs and preferences using AI assistance.

---

Feel free to use, share, or adapt this list for your own workout planning, app development, or AI-powered fitness tools.