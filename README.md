<h1>Drive Test Appointment System</h1>
<p>This project is a web application designed to facilitate the scheduling and management of drive test appointments for individuals seeking to obtain their G or G2 driver's license. It consists of three main interfaces:</p>
<br/><br/>
<ul>
<li><b>Driver Interface:</b> Allows individuals to sign up, log in, and book appointments for their G or G2 drive tests. Users can select their preferred time slots and provide necessary information.</li>
<li><b>Examiner Interface:</b> Examiner interface enables examiners to view scheduled appointments, filter them based on test type (G or G2), review driver details, conduct the drive test, add comments, and mark the driver as pass or fail.</li>
<li><b>Admin Interface:</b> Admins have the authority to manage the system by adding schedules, reviewing pass/fail candidates, and issuing orders for driver licenses.</li>
</ul>
<br/><br/>
<h2>Features:</h2>
<ul>
<li>Users can sign up as drivers, examiners, or admins, each with different access privileges.</li>
Driver interface allows booking appointments by selecting preferred time slots.</li>
<li>Examiner interface displays a list of appointments, filters by test type, and enables marking drivers as pass or fail with comments.</li>
<li>Admin interface facilitates the management of schedules and review of pass/fail candidates.</li>
</ul>
<br/><br/>
<h2>Updates:</h2>
<ul>
<li>Added functionality for booking appointments and selecting time slots.</li>
<li>Integrated examiner interface allowing examiners to view and manage appointments.</li>
<li>Modified login UI to allow selection of user type from a dropdown.</li>
<li>Implemented middleware to restrict access to specific views based on user type.</li>
<li>Extended user model to include fields for TestType (G2 or G), Comment, Pass/Fail data.</li>
<li>Enhanced admin view to list pass/fail candidates for further processing.</li>
</ul>
<br/><br/>
<p>You can check the live demo of this site on following URL: https://drivte-test-book.onrender.com/</p>
<br/>
<h3>Admin Credentials:</h3>
<p>Username: admin</p>
<p>Password: admin</p>
<br/>
<h3>Examiner Credentials:</h3>
<p>Username: examiner</p>
<p>Password: examiner</p>
<br/>
<h3>Driver Credentials:</h3>
<p>Username: driver</p>
<p>Password: driver</p>