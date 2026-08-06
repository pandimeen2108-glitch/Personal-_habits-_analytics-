Personal Habits Analytics – Problem Statement

1. Title

Personal Habits Analytics System

2. Domain

Health Management / Productivity Management / Data Analytics

3. Who is the User?



* Registers and logs into the system.

* Records daily habits such as sleep, study, exercise, water intake, and mobile usage.

* Sets personal goals and views analytics reports.

 Coach / Mentor

* Views assigned users’ progress.

* Monitors habit trends and goal completion.

* Provides feedback and improvement suggestions.

 Admin

* Manages users and mentors.

* Monitors system activity.

* Generates overall reports and maintains system settings.

4. What Problem Are We Solving?

Many people want to improve habits such as studying regularly, sleeping on time, exercising daily, and reducing excessive mobile usage. However, they often fail to track these activities consistently. Without proper tracking and analysis, it becomes difficult to understand progress or identify unhealthy patterns.

For example, a college student may believe that they study for four hours every day, but the actual recorded study time may be much lower. Similarly, irregular sleep patterns and high mobile usage may negatively affect productivity and health. This application provides a centralized digital platform to record habits, analyze trends, and help users improve their lifestyle through data-driven insights.

5. Proposed Solution

The application will allow users to record daily habits through a simple dashboard. The system will store the data securely and generate weekly and monthly analytics using charts and reports. Users can set goals for habits such as study hours, sleep duration, water intake, and exercise time. The system will provide reminders, progress tracking, and improvement suggestions. Mentors can monitor assigned users, while administrators can manage the overall platform and generate reports.

6. Core Entities / Database Tables

* Users

* Mentors

* Habits

* HabitEntries

* Goals

* GoalProgress

* Reminders

* Reports

* Notifications

7. User Roles & Permissions

 Admin

* Manage users and mentors.

* View all habit records.

* Generate system reports.

* Monitor platform activity.

* Configure system settings.

Mentor / Coach

* View assigned users.

* Track habit progress.

* Review analytics.

* Provide feedback and suggestions.

 User

* Register and log in.

* Add, edit, or delete habit entries.

* Set personal goals.

* View analytics and reports.

* Manage reminders and profile.

8. Success Criteria

* A user should be able to add a daily habit entry within 30 seconds.

* Weekly analytics should load within 5 seconds.

* The system should generate monthly reports automatically.

* Users should receive reminders when goals are not completed.

* Admin should be able to access overall system statistics instantly.

9. Out of Scope

* AI-based health diagnosis.

* Integration with smart watches or fitness bands.

* Real SMS or WhatsApp notifications.

* Social media sharing.

* Multi-language support.

* Payment gateway integration.

* Cloud scalability optimization.

* Medical or psychological assessment features.

10. Chosen Track

Backend: Python Django

Frontend: React.js

Database: MySQL

ORM: Django ORM

Authentication: Django Authentication & JWT

Build Tool: pip & Vite

Version Control: Git & GitHub

Deployment: Render / Railway / AWS EC2 (or any cloud platform)
