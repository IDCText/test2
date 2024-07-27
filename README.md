Project Setup Guide
Prerequisites
Before you begin, ensure you have the following installed on your local machine:

XAMPP (or any other local server like WAMP, MAMP, etc.)
Step-by-Step Instructions
1. Clone the Repository
First, download the source code or clone the repository using Git.

To clone the repository:

bash
Copy code
git clone https://github.com/your-username/your-repository-name.git
Alternatively, you can download the source code as a ZIP file and extract it to your desired location.

2. Set Up the Database
Open phpMyAdmin by navigating to http://localhost/phpmyadmin in your web browser.

Create two new databases:

nusers
studies
Import the SQL files provided in the sql folder into the respective databases:

Click on the nusers database, then go to the Import tab and select the nusers.sql file from the sql folder. Click Go to import the file.
Repeat the process for the studies database by importing the studies.sql file.
3. Configure the Project
If using XAMPP, store the project files in the htdocs directory.

Copy the cloned project folder to the htdocs directory:
bash
Copy code
cp -r your-repository-name /path-to-xampp/htdocs/
Adjust the path to your XAMPP installation as necessary.
4. Run the Project
Start the Apache and MySQL services from the XAMPP Control Panel.

Open your web browser and navigate to http://localhost/your-repository-name.

5. Troubleshooting
Ensure the Apache and MySQL services are running.
Verify that the database names and import files are correct.
Check your database connection settings in the project's configuration file if necessary.
