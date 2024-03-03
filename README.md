Drive Test Appointment System
This project is a web application designed to facilitate the scheduling and management of drive test appointments for individuals seeking to obtain their G or G2 driver's license. It consists of three main interfaces:

Driver Interface: Allows individuals to sign up, log in, and book appointments for their G or G2 drive tests. Users can select their preferred time slots and provide necessary information.

Examiner Interface: Examiner interface enables examiners to view scheduled appointments, filter them based on test type (G or G2), review driver details, conduct the drive test, add comments, and mark the driver as pass or fail.

Admin Interface: Admins have the authority to manage the system by adding schedules, reviewing pass/fail candidates, and issuing orders for driver licenses.

Features:
Users can sign up as drivers, examiners, or admins, each with different access privileges.
Driver interface allows booking appointments by selecting preferred time slots.
Examiner interface displays a list of appointments, filters by test type, and enables marking drivers as pass or fail with comments.
Admin interface facilitates the management of schedules and review of pass/fail candidates.
Updates:
Added functionality for booking appointments and selecting time slots.
Integrated examiner interface allowing examiners to view and manage appointments.
Modified login UI to allow selection of user type from a dropdown.
Implemented middleware to restrict access to specific views based on user type.
Extended user model to include fields for TestType (G2 or G), Comment, Pass/Fail data.
Enhanced admin view to list pass/fail candidates for further processing.

You can check the live demo of this site on following URL: https://drivte-test-book.onrender.com/
Admin Credentials:
Username: admin
Password: admin

Examiner Credentials:
Username: examiner
Password: examiner

Driver Credentials:
Username: driver
Password: driver