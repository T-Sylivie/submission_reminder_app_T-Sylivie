HERE ARE THE STEPS TO BE ABLE TO RUN THIS PROGRAM CORRECTLY:

To run the Submission Reminder application, open your terminal and navigate to the submission_reminder_emmanuel directory. Once inside the directory, start the program by running the startup.sh script using the command ./startup.sh. This script will initialize the application by loading environment variables from config/config.env and calling the main logic located in app/reminder.sh. The reminder script may use helper functions defined in modules/functions.sh, and it reads submission data from assets/submissions.txt to process reminders accordingly.

This is a Bash-based submission reminder system that helps manage and remind students about upcoming submission deadlines. The project is structured in folders for modularity, with scripts handling logic, configuration, and data.

##  Project Structure
```plaintext

submission_reminder_app_T-Sylvie/
├── app/
│ └── reminder.sh
├── modules/
│ └── functions.sh
├── assets/
│ └── submissions.txt
├── config/
│ └── config.env
└── startup.sh
```

##  Description

- `reminder.sh`: Core logic that sends reminders.
- `functions.sh`: Contains reusable functions used by the app.
- `submissions.txt`: A list of student submissions.
- `config.env`: Configuration file for environment variables.
- `startup.sh`: Initializes the environment and starts the app.

## How to Run the Application

1. **Navigate to the project folder:**
   ```bash
   cd submission_reminder_app_T-Sylvie
Then run each of these commands and follow the instructions:

**Run the environment creation script:
```bash
./create_environment.sh
```

Run the copilot script to check for assignment submissions:
```bash
./copilot_shell_script.sh
