🧠 Project Overview: Bug Tracking System
👥 Roles:
Admin – manages users, projects, and bugs

Project Manager – assigns bugs to developers

Developer – views and updates bugs

Tester – creates and logs bugs

✅ Core Features
🔐 Authentication & Roles
Login/Registration (JWT token-based)

Role-based access using guards in Angular

🧾 Bug Module
Create bug: title, description, severity, priority, attachments

Status: Open → In Progress → Resolved → Closed

Assign to user, attach screenshots

Comment thread on each bug

📁 Project Management
Create/edit/delete projects

Assign team members to a project

📊 Dashboard
Overview of:

Total bugs by status

Bugs per project

Bugs assigned to the user

Charts using ngx-charts or Chart.js

📂 Others
File upload for bug screenshots

Date-wise filtering of bugs

Activity log for bug status changes