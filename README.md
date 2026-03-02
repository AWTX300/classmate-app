📱 Classmate — Student Life Manager

An independent Android app built in Java that goes far beyond a calendar — Classmate uses AI to help students manage coursework, predict academic performance, and optimize study time automatically.


📌 About the Project
Classmate is a personal project I built independently from the ground up. As a student-athlete juggling coursework, practices, and work, I needed more than a calendar — I needed something that could think about my schedule with me. So I built it.
Classmate combines intelligent scheduling, syllabus parsing, and grade prediction into a single app that acts more like a study assistant than a planner.

🆚 Why Not Just Use a Calendar App?

Calendar apps record what you tell them. Classmate figures out what you should be doing.
Here's what sets it apart:

✅ Syllabus auto-import — Upload a syllabus and all assignments are scheduled for you. No manual entry.

✅ AI study block suggestions — Classmate analyzes your class times, work shifts, and deadlines to recommend when to study, not just what to study.

✅ Grade prediction — Log your grades as you go and Classmate models your projected final grade, alerting you before it's too late to course-correct.

✅ Study group coordination — Find overlapping free time across multiple students' schedules automatically and create shared study sessions in-app.

✅ Conflict detection — Classmate spots scheduling conflicts across your coursework, work, and personal time — before they catch you off guard.

✅ Deadline urgency ranking — Tasks aren't just listed; they're ranked by urgency so the most critical work always surfaces to the top.

A calendar tells you what's happening. Classmate tells you what to do next.
✨ Features
📄 Syllabus Upload & Auto-Scheduling

Upload a course syllabus (PDF or text) and Classmate parses it automatically
Extracts assignment names, due dates, and exam dates
Populates your schedule without manual entry

🤖 AI-Powered Study Time Management

Analyzes your class schedule, work shifts, and assignment deadlines
Intelligently suggests optimal study blocks based on available time and task priority
Adapts recommendations as your schedule changes throughout the semester

📊 Grade Prediction

Tracks grades as you log them and models projected final grades per course
Alerts you when a course grade is trending below your target
Helps students make informed decisions about where to focus effort

👥 Study Group Scheduling

Coordinate availability with classmates for group study sessions
Find overlapping free time across multiple users' schedules automatically
Create and share study events within the app

📅 Unified Dashboard

See coursework deadlines, class times, work shifts, and study blocks in one view
Deadline urgency ranking — most critical items surface to the top
Conflict detection alerts when scheduling overlaps


🛠️ Tech Stack
LayerTechnologyLanguageJavaPlatformAndroidIDEAndroid StudioArchitectureObject-Oriented Programming (OOP)AI / Scheduling LogicRule-based & predictive algorithmsDocument ParsingSyllabus text extractionVersion ControlGit / GitHub

🚀 Getting Started
bash# Clone the repository
git clone https://github.com/AWTX300/classmate-app.git

Open the project in Android Studio
Let Gradle sync the dependencies
Run on an emulator or connected Android device
Upload a sample syllabus to see auto-scheduling in action


🏗️ Architecture & Design
Classmate is built using object-oriented design principles with a focus on maintainable, modular code:

Separation of concerns — distinct classes for data models, AI scheduling logic, UI, and parsing
Modular feature structure — syllabus parser, grade tracker, study scheduler, and group coordination are independently developed modules
Predictive algorithms — grade projection and study time optimization use weighted models built on current performance data
Software testing — core features validated with unit tests; scheduling logic tested against edge cases
Documentation — architecture, data models, and test cases documented throughout


💡 Why I Built This
I'm a student-athlete and I found myself dropping tasks because no existing tool connected all the pieces — syllabi, work schedules, grades, study time, and group coordination. Classmate is my solution to that problem, and a project that let me explore AI-assisted scheduling and predictive modeling while going through the full development lifecycle independently.

🗺️ Roadmap

 Natural language input ("remind me to study for calc before Thursday")
 LMS integration (Canvas, Blackboard) for automatic grade sync
 Pomodoro-style study session timer with focus tracking
 Push notification support for deadline reminders


📄 License
This project is open for portfolio review.
