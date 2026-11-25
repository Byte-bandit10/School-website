AL-FATAH SECONDARY SCHOOL MANAGEMENT SYSTEM
============================================

TECHNOLOGY
- PHP 8+
- MySQL / MariaDB
- HTML, CSS and JavaScript
- XAMPP / Apache

INSTALLATION
1. Extract the "al_fatah_school" folder into C:\xampp\htdocs\
2. Open XAMPP Control Panel and start Apache and MySQL.
3. Open http://localhost/phpmyadmin
4. Click Import and import:
   al_fatah_school/database/al_fatah_school.sql
   The SQL creates the database named al_fatah_school.
5. Check config/database.php:
   host = localhost
   dbname = al_fatah_school
   dbuser = root
   dbpass = (blank by default in XAMPP)
6. Visit http://localhost/al_fatah_school/install.php
7. Then visit http://localhost/al_fatah_school/
8. Sign in:
   Username: admin
   Password: Admin@123
9. Immediately change the administrator password in Settings.
10. Delete install.php after successful setup.

MODULES
- Login / logout with PHP sessions and password hashing
- Dashboard with live database totals
- Student registration, editing, deleting and searching
- Teacher records
- Classes and streams
- Subjects
- Daily attendance
- Fee payment records (KES)
- Examinations
- Student results with automatic grade suggestion
- Reports and print view
- Administrator password settings

NOTES
- This package is a starter school administration system. It is not yet a complete
  production deployment with backups, granular staff permissions, parent/student
  portals, SMS, M-Pesa integration, or a full timetable editor.
- Sample classes and subjects are inserted by the SQL file. Student and teacher
  records are intentionally empty so you can enter real school data.
- Do not upload real student data to a public server until HTTPS, backups,
  access controls, privacy notices, and deployment security have been reviewed.
