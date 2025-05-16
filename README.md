Dosa Restaurant Backend API

This project powers the backend operations for a dosa restaurant, enabling seamless management of customers, menu items, and orders. Developed with FastAPI and SQLite, it offers speed, simplicity, and dependability.

Core Capabilities:
	•	Customer Management: Create, update, view, and delete customer records.
	•	Menu Management: Add, edit, view, or remove menu items.
	•	Order Management: Handle placing, updating, viewing, or canceling orders.

Getting Started:
	1.	Install Dependencies:
Run this to install the necessary packages:
pip install fastapi uvicorn
	2.	Initialize the Database:
Set up the database by executing the setup script:
python init_db.py
	3.	Run the Application:
Launch the main server file (main.py) using the command:
python -m uvicorn main:app --reload

Accessing the API:

Once the server is live, open this link in your browser to explore and test the API using the Swagger interface:
http://127.0.0.1:8000/docs

This page offers a user-friendly UI for interacting with all available endpoints.
