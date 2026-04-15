# tg📰 HDSPTV — International Professional News Platform
Overview

HDSPTV is a modern, scalable, and professional digital news platform designed to evolve into an international newsroom system. It includes a public news website and a powerful admin/newsroom CMS for content creation, publishing, live updates, and management.

The platform is built with a focus on:

🌍 Global scalability
⚡ High performance
🧠 Editorial workflow
📱 Mobile-first experience
🎯 Easy usability for readers and admins
🎯 Project Goal

Transform this project into a world-class international news website similar to:

BBC
CNN
Reuters
Al Jazeera

With:

Clean UI/UX
Fast content delivery
Strong editorial tools
Multilingual-ready architecture
Live and breaking news capabilities
🧩 Features
🌐 Public Website
Homepage with editorial layout
Breaking News page
Live TV / Live Updates
Category & Subcategory pages
Article detail pages
Video news
Photo gallery
Search system
Trending & Most Viewed
Reporter profile pages
User login & saved articles
🏢 Admin / Newsroom CMS
Dashboard (analytics + KPIs)
News management (CRUD)
Draft / Review / Publish workflow
Breaking news manager
Live TV / stream control
Homepage content manager
Category & tags management
Media & video library
Notifications / push alerts
Comments moderation
SEO manager
Ads & banners management
Users & roles system
System health monitoring
🏗️ Project Structure (Fixed & Cleaned)
/ (root)
├── admin/
│   ├── includes/
│   ├── pages/
│   └── assets/
├── includes/
├── assets/
│   ├── css/
│   ├── js/
│   ├── images/
├── vendor/
├── js/
├── config/
├── auth/
├── public/
├── writable/
│   ├── logs/
│   ├── uploads/
├── .env.example
├── index.php
├── README.md
🔧 Fixes Applied
✅ File Structure Fixes
Removed broken/missing asset references
Added missing JS/CSS dependencies
Standardized folder structure
Added required directories:
/writable/uploads
/writable/logs
Added .gitkeep for empty directories
✅ Config Fixes
Cleaned config files (removed invalid HTML output)
Added environment-based configuration support
Prevented session/header issues
✅ Admin Login Fix
Supports email + username login
Converted to prepared statements (secure)
Fixed incorrect SQL logic
✅ Security Improvements
Input sanitization
Output escaping
Session handling improvements
Prepared SQL queries
⚙️ Installation Guide
1. Upload Files

Upload the project to your server root (e.g. public_html/)

2. Create Database
Create a MySQL database
Import the provided .sql file
3. Configure Environment

Create .env.php (or update existing):

<?php
$HS_APP_NAME = 'HDSPTV';
$HS_BASE_URL = 'https://yourdomain.com/';
$HS_DB_HOST = 'localhost';
$HS_DB_NAME = 'your_db';
$HS_DB_USER = 'your_user';
$HS_DB_PASS = 'your_password';
4. Set Permissions

Ensure these folders are writable:

/writable/
/writable/logs/
/writable/uploads/
5. Access Website
Frontend: https://yourdomain.com
Admin: https://yourdomain.com/admin
🚀 Future Development Roadmap
Phase 1 — Core Fix & UI Upgrade
Clean homepage UI
Improve article page readability
Fix layout alignment issues
Optimize mobile UI
Phase 2 — Professional CMS
Advanced editorial workflow
Role-based permissions
Homepage drag-and-drop manager
Better media system
Phase 3 — International Features
Multilingual support
Region-based editions
Timezone handling
Localization-ready SEO
Phase 4 — Advanced Features
Live streaming integration
Push notifications
Analytics dashboard
Ad monetization system
AI content tools
📱 UX Principles

The platform is designed with:

Easy navigation
Fast reading experience
Clean typography
Clear hierarchy
Minimal clutter
Strong visual consistency
Mobile-first layout
🔐 Security Best Practices
Use HTTPS
Secure admin access
Limit login attempts
Validate all inputs
Escape outputs
Keep dependencies updated
📌 Notes
This project is now structurally fixed and stable
It is ready to be upgraded into a full international news system
Current version is a solid base, not final enterprise product
🏁 Final Statement

HDSPTV is designed to evolve into a complete international news platform with a powerful newsroom CMS, clean frontend experience, scalable architecture, and professional editorial workflow.
