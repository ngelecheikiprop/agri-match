# Agri-Match 🌾

## Overview
Agri-Match is a platform designed to connect **machine operators, machine owners , and poeple who want to rent machines** within the agricultural sector. It streamlines the process of **renting agricultural machines**, ensuring that anyone who wants to rent a farm machine can easily find one
## Features 🚀
- 🛒 **Mechine listing** – People wuth farm machines can list them.
- 🤝 **Mechine rentings** –People can rent out machines.
- 📍 **DPrice info** –Price of renting machine is available

## Tech Stack 🛠️
Agri-Match is built using modern web technologies:
- **Frontend:** html, css, bootstrap
- **Backend:** Django 
- **Database:** Mysql lite

## Installation 🏗️
To run the project locally, follow these steps:

cd 1. **Clone the Repository**
   ```bash
   git clone https://github.com/wbsjael/agri-match.git
   cd agri-match
   ```

2. **Install Dependencies**
   ```bash
   pip install -r requirements.txt
   ```

3. **Apply Migrations**
   ```bash
   python3 manage.py migrate
   ```

4. **Run the Server**
   ```bash
   python3 manage.py runserver
   ```

## Running the Application 🚀
To run the application, open your web browser and navigate to:
```
http://127.0.0.1:8000/
```

If you encounter issues, try the following troubleshooting steps:

1. **Check the Server Status**
   Ensure that the Django development server is running. You should see output in the terminal indicating that the server is running at `http://127.0.0.1:8000/`.

2. **Check Firewall and Proxy Settings**
   Ensure that your firewall or proxy settings are not blocking the connection to `127.0.0.1`.

3. **Check for Errors in the Terminal**
   Look for any error messages in the terminal where you started the server. These messages can provide clues about what might be going wrong.

4. **Restart the Server**
   Sometimes, simply stopping and restarting the server can resolve issues. Use `Ctrl+C` to stop the server and then run `python3 manage.py runserver` again.
