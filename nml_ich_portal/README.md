NML ICH Complaint Portal — Liquid Glass UI (PHP + MySQL / XAMPP)

INSTALL (Windows XAMPP)
1. Copy this folder `nml_ich_portal` to C:\xampp\htdocs\
2. Start Apache and MySQL in XAMPP Control Panel.
3. Open http://localhost/phpmyadmin/ and import database.sql.
4. Check config.php: default XAMPP database user is root with blank password.
5. Open http://localhost/nml_ich_portal/setup_admin.php and create an admin (12+ character password).
6. DELETE setup_admin.php after creating the admin.
7. Open http://localhost/nml_ich_portal/ and create an employee account.
Admin login: http://localhost/nml_ich_portal/admin_login.php

Includes liquid-glass responsive UI, employee signup/login, complaint submit/list/track, admin-only login, dashboard, complaint status and remarks management. Profile and Notification features are removed.

Security: Starter project only. Obtain NTPC IT approval before LAN use. Configure HTTPS, server access control, strong unique passwords, regular database backups and audit before entering real complaint data. Do not expose MySQL/phpMyAdmin to the office LAN or internet. Email/SMS and file uploads are not included in this starter.
