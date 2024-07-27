 <h1>Project Setup Guide</h1>

    <h2>Prerequisites</h2>
    <p>Before you begin, ensure you have the following installed on your local machine:</p>
    <ul>
        <li><a href="https://www.apachefriends.org/index.html"><strong>XAMPP</strong></a> (or any other local server like WAMP, MAMP, etc.)</li>
    </ul>

    <h2>Step-by-Step Instructions</h2>

    <h3>1. Clone the Repository</h3>
    <p>First, download the source code or clone the repository using Git.</p>
    <p><strong>To clone the repository:</strong></p>
    <pre><code>git clone https://github.com/your-username/your-repository-name.git</code></pre>
    <p>Alternatively, you can download the source code as a ZIP file and extract it to your desired location.</p>

    <h3>2. Set Up the Database</h3>
    <ol>
        <li>Open <a href="http://localhost/phpmyadmin"><strong>phpMyAdmin</strong></a> by navigating to <code>http://localhost/phpmyadmin</code> in your web browser.</li>
        <li>Create two new databases:
            <ul>
                <li><code>nusers</code></li>
                <li><code>studies</code></li>
            </ul>
        </li>
        <li>Import the SQL files provided in the <code>sql</code> folder into the respective databases:
            <ul>
                <li>Click on the <code>nusers</code> database, then go to the <strong>Import</strong> tab and select the <code>nusers.sql</code> file from the <code>sql</code> folder. Click <strong>Go</strong> to import the file.</li>
                <li>Repeat the process for the <code>studies</code> database by importing the <code>studies.sql</code> file.</li>
            </ul>
        </li>
    </ol>

    <h3>3. Configure the Project</h3>
    <p>If using XAMPP, store the project files in the <code>htdocs</code> directory.</p>
    <ol>
        <li>Copy the cloned project folder to the <code>htdocs</code> directory:
            <pre><code>cp -r your-repository-name /path-to-xampp/htdocs/</code></pre>
            <p>Adjust the path to your XAMPP installation as necessary.</p>
        </li>
    </ol>

    <h3>4. Run the Project</h3>
    <ol>
        <li>Start the Apache and MySQL services from the XAMPP Control Panel.</li>
        <li>Open your web browser and navigate to <code>http://localhost/your-repository-name</code>.</li>
    </ol>

    <h3>5. Troubleshooting</h3>
    <ul>
        <li>Ensure the Apache and MySQL services are running.</li>
        <li>Verify that the database names and import files are correct.</li>
        <li>Check your database connection settings in the project's configuration file if necessary.</li>
    </ul>
