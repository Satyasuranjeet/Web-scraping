# Web Scraping Application

This is a web scraping application built with React for the frontend, Flask for the backend, and MongoDB as the database. It allows users to enter a URL and fetch the HTML content of the webpage.

## Tech Stack

### Frontend
- **Framework**: React
- **Routing**: React Router
- **Styling**: Tailwind CSS
- **HTTP Client**: Axios
- **Code Highlighting**: React Codex

### Backend
- **Framework**: Flask
- **Web Scraping**: Beautiful Soup
- **HTTP Client**: Flask-CORS

### Database
- **Database**: MongoDB
- **MongoDB Client**: PyMongo

## How to Run

### Frontend
1. Navigate to the `frontend` directory.
2. Install dependencies: `npm install`
3. Start the development server: `npm start`

### Backend
1. Navigate to the `backend` directory.
2. Set up a virtual environment: `python3 -m venv venv`
3. Activate the virtual environment:
   - On Windows: `venv\Scripts\activate`
   - On macOS/Linux: `source venv/bin/activate`
4. Install dependencies: `pip install -r requirements.txt`
5. Start the Flask server: `python app.py`

### MongoDB
1. Install MongoDB: [MongoDB Installation Guide](https://docs.mongodb.com/manual/installation/)
2. Start MongoDB service: `mongod`
3. Connect to MongoDB shell: `mongo`
4. Create a new database for the application: `use web_scraping_app`

## Usage
1. Open the application in your web browser.
2. Enter a URL in the search input and click the search button.
3. View the fetched HTML content.

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.


