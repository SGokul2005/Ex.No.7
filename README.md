# Exno.7-Develop a prompt-based application tailored to their personal needs, fostering creativity and practical problem-solving skills while leveraging the capabilities of large language models.

# Date:18-03-2026
# Register no.212223040051
# Aim: To develop a prompt-based application using ChatGPT - To demonstrate how to create a prompt-based application to organize daily tasks, showing the progression from simple to more advanced prompt designs and their corresponding outputs.

# AI Tools Required: 
# Chatgpt


# Explanation: 
Prompt:
"Design a personal productivity assistant that can help manage daily tasks, schedule reminders, suggest wellness tips, and answer general queries. The assistant should interact using natural language and be adaptable to the user’s changing preferences over time."
# Procedure:
1. Define the core requirements of a personal productivity assistant.
2. Identify and construct appropriate prompts for each task using an LLM (e.g., ChatGPT).
3. Simulate natural user interaction through a simple interface or command-line system.
4. Collect feedback or inputs from users and adapt responses accordingly.
5. (Optional) Integrate basic memory to simulate preference adaptation.
EXPECTED OUTPUT: - (attached the drive link)
Output (Example Response by LLM):
Personal Productivity Assistant Features:
1. Daily Task Manager:
o Accept tasks via natural language (e.g., "Remind me to call mom at 6 PM").
o Organize tasks by priority and deadline.
o Provide daily summaries and pending items.
2. Smart Scheduler:
o Schedule events and set reminders using contextual understanding.
o Notify user of overlapping appointments or free time slots.
3. Wellness Tips Generator:
o Suggest daily wellness advice (hydration, exercise, screen-time breaks).
o Adapt suggestions based on past user preferences and responses.

# Phase 1 – Basic Prompt

# Prompt:
“Help me plan my day.”
~~~
Example Response:

7:30 AM – Wake up and get ready

9:00 AM – Start work/study

12:30 PM – Lunch break

3:00 PM – Continue work

6:30 PM – Relax or hobbies

9:30 PM – Prepare for sleep
~~~
Note:
This stage shows a very simple interaction with general suggestions and no personalization.
# Phase 2 – Structured Prompt

Prompt:
“Create a schedule for today. I have a class at 9 AM and a meeting at 4 PM. I need 3 hours for studying and 1 hour for exercise.”

Example Output:

7:00 – 8:00 AM : Morning routine

9:00 – 10:00 AM : Class

10:30 – 1:30 PM : Study session

1:30 – 2:00 PM : Lunch break

4:00 – 5:00 PM : Meeting

6:00 – 7:00 PM : Exercise

Note:
The prompt includes specific details, leading to a more organized and useful schedule.
# Phase 3 – Role-Based Prompt

Prompt:
“You are a smart productivity assistant. Create a daily plan including a class at 9 AM, a meeting at 4 PM, 3 hours of study time, and 1 hour of fitness activity. Display the result in a table format.”

Example Output:
| Time          | Activity        | Notes                |
| ------------- | --------------- | -------------------- |
| 7:00–8:00 AM  | Morning routine | Breakfast & planning |
| 9:00–10:00 AM | Class           | Attend lecture       |
| 10:30–1:30 PM | Study Session   | Deep focus learning  |
| 1:30–2:00 PM  | Lunch           | Relax                |
| 4:00–5:00 PM  | Meeting         | Discussion/updates   |
| 6:00–7:00 PM  | Fitness         | Gym or walking       |
Note:
Role prompting ensures structured, professional, and consistent output.
# Phase 4 – Adaptive Prompt

Prompt:
“You are my AI productivity assistant. I prefer studying in the morning and exercising in the evening. I take short breaks every 2 hours. Generate a personalized daily schedule with reminders.”

Example Output:

6:30 AM – Wake up and freshen up

7:00–10:00 AM – Study session (high focus time)

9:00 AM – 💧 Drink water reminder

10:00 AM – Short break

1:00 PM – Lunch break

4:00 PM – Meeting

6:30–7:30 PM – Exercise (preferred time)

8:00 PM – Light relaxation

10:00 PM – Sleep

Note:
This stage demonstrates personalization and adaptive behavior, improving user experience.
# 💻 Converting Prompts into an Application
🔄 Workflow

User Input → Application → Structured Prompt → ChatGPT → Generated Response → Display Output

📌 Example Integration

User Input:

Class: 9 AM

Meeting: 4 PM

Study Duration: 3 hours

Exercise: 1 hour

Preference: Morning study

Application Output:

📅 Daily Schedule

⏰ Reminder Notifications

💡 Wellness Suggestions

📊 Smart Adjustments

# 🔍 Additional Use Cases
| Feature           | Example Prompt                         | Example Output            |
| ----------------- | -------------------------------------- | ------------------------- |
| Task Organizer    | Plan my day for 6 productive hours     | Structured schedule       |
| Wellness Reminder | Remind me to take breaks every 2 hours | Break notifications       |
| Smart Alerts      | Remind me to review notes before sleep | Reminder list             |
| General Queries   | Suggest a quick relaxation activity    | Meditation tip            |
| Adaptive Behavior | I feel more active at night            | Adjusted future schedules |
# 🛠 Prompt Engineering Techniques Used
~~~
| Technique              | Purpose                             |
| ---------------------- | ----------------------------------- |
| Role Prompting         | Defines assistant behavior          |
| Structured Prompting   | Produces organized output           |
| Parameter Prompting    | Adds customization (time, duration) |
| Natural Language Input | Improves interaction experience     |
| Adaptive Prompting     | Personalizes based on preferences   |
~~~
# Conclusion:

This experiment shows that prompt engineering is essential for building effective AI applications. As prompts evolve:

Responses become more structured

Outputs become more relevant

Interaction becomes more personalized

# Result: 
The lab exercise resulted in the creation of a prototype concept for a personal assistant powered by large language models. Students were able to:
 Understand how to tailor LLM prompts to real-life applications.
 Foster creativity by designing features suited to their personal or academic lives.
 Learn prompt engineering techniques for optimal interaction with AI tools.
 Experience the versatility and utility of generative AI in solving everyday problems.
