# Soundtrackd
A music reviewing social media terminal application, powered by Spotify's Web API and using a MySQL database.

## Instructions
- Run installation.sh to ensure the required Python packages are up to date
- Run "Python soundtrackd.py" to start Soundtracked
- *NOTE: Soundtrackd stores data in a MySQL database, users can choose between using a local installation or a public online hosted one*
  - **Online-hosted MySQL**: After running soundtrackd.py, answer y to the online database prompt, and enter the online database password (email adam_burton1@outlook.com for the password)
  - **Local hosted MySQL**: Run initialize.sql in your local MySQL to create a new database with the expected schema. After running soudntrackd.py, answer n to the online database prompt and enter your local MySQL username and password to connect to the database that was created.
-   Follow the prompts in the soundtrackd.py application to register/log in to your account and start tracking your favorite music with soundtrackd!
