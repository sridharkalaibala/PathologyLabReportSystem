    Pathology Lab Reporting System
    ==============================


    What Is This?
    -------------

		This is Pathology Lab Reporting System based on PHP Codeigniter framwork.
		
		Demo: Patient:  http://sridharb.com/demo/path    Admin: http://sridharb.com/demo/path/admin  username:admin password:admin


    How To Use (Overview)
    ---------------------
	  	
      Patients:

			1. Patients can view their Reports online and login through http://sridharb.com/demo/path with their 
			   full name and passcode

			2. After log into system, patients can view, download and send email their reports
			
			3. Patients will receive SMS if their login created by Lab Technicians 
	 
      Admins: ( Lab Technicians )
	
			1. Lab Technician (Admin) can manage their patiens and their reports online.

			2. Admin can login through http://sridharb.com/demo/path with their username and password [ Ex. Username: admin and Password: admin].
			
			3. Patients section admin can add / update / delete patient information. Patient passcode can be send as SMS by clicking sms link.
			
			4. For each patient, we can add multiple reports by choosing add Report in dropdown action menu. 
			
			5. Reports can be added / edited as Text or Pdf file.
			
			6. Reports can be send as email by clicking email link.
	
	
    Pre-Requirements
	-----------------
	
			1. PHP version 5.4 or newer is recommended.
			   (It should work on 5.2.4 as well, but we strongly advise you NOT to run such old versions of PHP, because of potential security and performance issues, as well as missing features.)
			
			2. MySQL (5.1+) via the mysql (deprecated), mysqli and pdo drivers.
			
			3. PHP OpenSSL extension for PHPMailer SSL login.
			
			4. PHP CURL extension for third party SMS service.
			
			5. PDF plugin in browser to view PDF files. 
	
	
    How To Install The application
    ------------------------------

			1. Copy Source files into web server document directory ( Ex. project/src/ to /var/www/htdocs/path)
			
			2. Enter Project base url in config file. (path: /application/config/config.php   ex. $config['base_url'] = 'http://localhost/path';)
			
			3. Enter MySQL DB database credentials in database config file (path: /application/config/database.php)
			
			4. Import DB.sql file in desired database 
			
			5. Enter Email configuration deatail in email confir file (path: /application/config/email.php)
			
			6. Optional Twilio API SMS configration can be done in helper file   (path: /application/helper/twilio_helper.php)
			
			7. Thats it! you can open patient report area like http://localhost/projectpath/  and admin area http://localhost/projectpath/admin ( username: admin and password: admin)
	
	
    Feedback to Improve
	-------------------
	
			1. Patient name and passcode authendication will not suits for all situation. There is chance to have Same name and same password. 
			   However i have handled to prevent dublicate But better to give unique username instead of Full Name. 
			
	
	
	
	


