FIRE RESCUE SERVICES :
The Online Fire Reporting System (OFRS) is a web-based platform that allows users to report fire-related incidents quickly and efficiently. The system is designed to enable users to report emergencies in real-time, ensuring faster responses from fire stations.

This README provides the necessary information on how to access and use the system, along with login credentials for the admin interface.

How to Run the Online Fire Reporting System Project
Follow the instructions below to set up and run the project locally:

Download and Extract Files

Download the project zip file.
Extract the zip file on your local machine.
Move the Project Files

Copy the ofrs folder to the root directory of your web server:
For XAMPP: Move it to xampp/htdocs
For WAMP: Move it to wamp/www
For LAMP: Move it to var/www/html
Set Up the Database

Open PHPMyAdmin (http://localhost/phpmyadmin).
Create a new database named ofrsdb.
Import the ofrsdb.sql file found in the SQL folder inside the project.
Access the System

In your browser, navigate to http://localhost/ofrs to open the Online Fire Reporting System.
Admin Credentials
The system has an Admin login for managing reports and user access:

Username: admin
Password: Test@123
These credentials will give you access to the admin dashboard to manage all incoming fire reports.

Project Features:
Fire Incident Reporting: Allows users to submit fire-related reports.
Admin Dashboard: View and manage all reported incidents.
