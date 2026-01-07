# Daily-task-manager 
https://claude.ai/public/artifacts/cfae7d1a-b77e-4d29-adbd-55ccffe310c2
Daily task manager helps to maintain the pace in the work we do in the time-line in our busy schedule day.

**Daily Activity Tracker (PWA)**
A mobile-friendly Progressive Web App (PWA) built using HTML, CSS, and JavaScript that helps users track daily activities, manage timers, set goals, and analyze productivity.
The app works offline, can be installed on mobile devices, and does not require any backend or database.


**FEATURES OVERVIEW**
Core Features
Add, delete, and manage daily tasks
Set timers (minutes and seconds) for each task
Mark tasks as:
Completed
Partially Done (with notes)
Celebration animation and sound when a task is completed
Countdown showing remaining time in the current year
Custom goal countdown with date and time selection
Analytics Dashboard
Displays number of completed, partial, and pending tasks
Calculates task completion rate
Bar chart showing task completion status
Pie chart showing time distribution across tasks
Automatically generated:
Compliments
Suggestions
Partial task analysis
**Customization**
Multiple built-in themes (Dark, Purple, Ocean, Sunset, Forest, Rose)
Fully customizable color picker
Responsive design for mobile and desktop screens


**Progressive Web App (PWA)**
Installable on supported devices
Offline support using Service Workers
App-like user experience



**TECHNOLOGIES USED**
HTML5
Used to structure the application and UI components.
CSS3
Used for styling, animations, transitions, and responsive layout.
JavaScript (Vanilla)
Handles all logic including task management, timers, analytics, and UI updates.
Chart.js
Used to create bar and pie charts for productivity analytics.
Tone.js
Used to play success sounds when tasks are completed.
Service Workers
Enable offline functionality and PWA installation.
PROJECT STRUCTURE
Daily-Activity-Tracker
index.html (contains HTML, CSS, and JavaScript)
README.md (project documentation)
This project is intentionally written in a single HTML file so beginners can easily understand and modify it.



**HOW TO RUN THE PROJECT**
Option 1: Run Locally
Download or clone the repository
Open index.html in any modern web browser
The app will start immediately
Option 2: GitHub Pages
Push the project to GitHub
Go to repository Settings
Open the Pages section
Select:
Source: main branch
Folder: root
Save and open the generated URL



**HOW THE APPLICATION WORKS**
Task Management
Tasks are stored in a JavaScript array.
Each task contains:
id
name
remaining time
completion status
partial status
notes
Users can add, delete, and update tasks dynamically.
Timer System
Each task can have a countdown timer.
The timer uses setInterval to decrease seconds every second.
When the timer finishes:
The task stops
A celebration animation appears
A success sound plays
Completion States
Completed tasks appear green
Partially completed tasks appear yellow
Partial tasks allow users to enter a reason or note
Goal Countdown
Users can set a goal with:
Goal name
Target date and time
The app calculates and displays the remaining:
Years
Days
Hours
Minutes
Seconds
Year Countdown
A live countdown shows how much time is left in the current year.
This updates every second automatically.



**ANALYTICS EXPLANATION**
Completion Rate
Calculated using:
Completed tasks divided by total tasks multiplied by 100
Bar Chart
Shows task status:
Green for completed
Yellow for partial
Red for pending
Pie Chart
Shows time distribution between tasks using estimated time values.
Smart Feedback
Based on task completion, the app automatically generates:
Compliments to motivate the user
Suggestions to improve productivity
Analysis of partially completed tasks



**THEMES AND CUSTOMIZATION**
Users can choose from predefined themes or create a custom theme.
Theme changes dynamically update:
Background gradient
Button colors
Input borders
Headings and highlights



**PWA INSTALLATION**
When supported by the browser:
The app shows an install prompt
The app can be installed like a native application
The app works offline after the first load



**SOUND AND ANIMATIONS**
Countdown animation before a timer starts
Celebration animation when a task is completed
Sound effects using Tone.js
Automatically handled by browser permissions



**BROWSER COMPATIBILITY**
Chrome: Supported
Edge: Supported
Firefox: Supported
Safari: Supported (limited PWA features)


\\**WHO THIS PROJECT IS FOR**
Beginners learning JavaScript
Students tracking daily activities
Productivity-focused users
Anyone who wants a simple offline activity tracker


**POSSIBLE FUTURE IMPROVEMENTS**
Save data using LocalStorage
Weekly and monthly reports
Cloud synchronization
Multiple goal support
Automatic dark mode
Export analytics as PDF or CSV


**LICENSE**
This project is open-source and free to use for learning and personal projects.


**FINAL NOTE**
This project is designed to be simple, customizable, and beginner-friendly.
It is a great starting point for learning real-world JavaScript and building Progressive Web Apps.




