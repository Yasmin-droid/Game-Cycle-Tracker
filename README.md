### README
# Game Cycle Tracker - Progressive Web App (PWA)

## Description
The Game Cycle Tracker is a Progressive Web App (PWA) designed to assist teams in monitoring their performance during game sessions. Initially created to automate training for a single team, this tool tracks each cycle, collects relevant data about the elements gathered, and stores the results for each game session.

In the future, this project will be expanded and modified to support the scouting process, allowing teams to store and analyze data on other teams' performance as well.

This app works seamlessly both online and offline, allowing users to track their cycles and performance during the game without the need for an internet connection.

## Features:
**Track Cycles:** Each cycle starts when the "Start Cycle" button is pressed and ends when an element is added (such as "Add Algae" or "Add Coral L2") or manually finished.

**Scoring System:** Each element added corresponds to specific points, which are added to the total score of the cycle and game.

**Time Tracking:** The duration of each cycle is tracked and stored. The total time of the game is limited to 2:15 minutes (135 seconds), at which point the data is transferred to the "Games" sheet.

**Game Summary:** The "Games" sheet records:
1. The number of the game;
2. The number of cycles;
3. The time spent in each cycle;
4. The element that ended each cycle (or "error" if manually finished);
5. The average cycle duration;
6. The total number of elements collected;
7. The total points scored;
8. The game status ("Bad", "Average", or "Good" based on the number of elements collected).

**Data Preservation:** Every time the game is formatted (using the "Format" button), previous data is saved along with the date and time of the formatting, ensuring no data is lost between sessions.

## Created by Yasmin Bzra:
This tool was designed and developed by Yasmin Bzra, a 15-year-old competitor from the FRC Team 9219 - Nine Tails. She created this app to help her team and others in their competitive efforts, with a focus on tracking in-game performance and improving cycle management.

## Usage
**Starting a New Cycle:**
Press the "Start Cycle" button to begin the cycle.
Add in-game elements (such as "Add Algae" or "Add Coral L2") to finalize the cycle and score points.
Alternatively, you can manually end the cycle by selecting "End Cycle".
**Formatting:**
Click the "Format" button to reset the game for a new session. This will clear current data and start a new game while saving the previous game’s data.
**Data Tracking:**
Each cycle’s duration is tracked and stored.
The tool automatically logs the total number of cycles, elements collected, and points scored during each game.

## Setup
To use the Game Cycle Tracker as a PWA, follow these steps:

**Open the app in your browser.**
Click the "Add to Home Screen" button (in Chrome, this can be done from the browser menu).
The app will be saved on your device, and you can access it directly from the home screen as a standalone app.
It works offline once the app is installed, and all your data will be saved locally on your device.

## Contributing
Feel free to fork the project and submit pull requests for improvements or new features. Please ensure that any changes maintain the tool’s usability and provide clear documentation for any new additions.

## License
This project is licensed under the MIT License - see the LICENSE file for details.

# Thanks for reading, enjoy your new tool!
# Gracious Professionalism! Hey!
