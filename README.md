# Project Setup Guide

## Prerequisites
Before you begin, ensure you have the following installed on your local machine:
- [**XAMPP**](https://www.apachefriends.org/index.html) (or any other local server like WAMP, MAMP, etc.)

## Step-by-Step Instructions

### 1. Clone the Repository
First, download the source code or clone the repository using Git.

**To clone the repository:**
```bash
git clone https://github.com/your-username/your-repository-name.git


```
## Setup Instructions

### 1. Download the Source Code

- Download the source code as a ZIP file.
- Extract the ZIP file to your desired location.

### 2. Set Up the Database

1. Open phpMyAdmin by navigating to `http://localhost/phpmyadmin` in your web browser.
   
2. Create two new databases:
   - `nusers`
   - `studies`

3. Import the SQL files provided in the `sql` folder into the respective databases:
   - Click on the `nusers` database, go to the **Import** tab, and select the `nusers.sql` file from the `sql` folder. Click **Go** to import the file.
   - Repeat the process for the `studies` database by importing the `studies.sql` file.

### 3. Configure the Project

If using XAMPP, store the project files in the `htdocs` directory:

1. Copy the cloned project folder to the `htdocs` directory:
   ```bash
   cp -r your-repository-name /path-to-xampp/htdocs/

