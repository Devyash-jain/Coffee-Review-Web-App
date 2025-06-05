````markdown
# ☕ Coffee Review Web App

A simple Flask-based web application that allows users to submit and view reviews of cafes, including their coffee quality, wifi strength, and power socket availability.

## 🌐 Live Preview (Optional)
If deployed, add your live link here.

## 🛠 Features

- Add cafe details including:
  - Name
  - Google Maps Location
  - Opening and Closing Times
  - Coffee, Wifi, and Power Ratings
- View all submitted cafes in a tabular format
- Clean UI with Bootstrap5 and custom CSS overrides

## 📸 Screenshots

_Add screenshots of your `/add` form and `/cafes` list page here (optional)_

## 🚀 Getting Started

### Prerequisites

Ensure you have Python installed. You can check by running:

```bash
python --version
````

### Clone the repository

```bash
git clone https://github.com/your-username/coffee-review-app.git
cd coffee-review-app
```

### Install Dependencies

It's recommended to use a virtual environment:

```bash
python -m venv venv
source venv/bin/activate  # On Windows use: venv\Scripts\activate
```

Then install required packages:

```bash
pip install -r requirements.txt
```

If you don’t have a `requirements.txt`, create one with:

```bash
pip freeze > requirements.txt
```

### Run the Application

```bash
python main.py
```

Visit `http://localhost:5002` in your browser.

## 📁 Project Structure

```
coffee-review-app/
│
├── main.py              # Flask application logic
├── styles.css           # Custom CSS for UI
├── cafe-data.csv        # CSV to store cafe data
├── templates/
│   ├── index.html       # Home page
│   ├── add.html         # Form page to add cafe
│   └── cafes.html       # Page to display all cafes
└── requirements.txt     # Python package dependencies
```

## 📦 Dependencies

* Flask
* Flask-Bootstrap (Bootstrap5)
* Flask-WTF
* WTForms

Install them via:

```bash
pip install flask flask-bootstrap flask-wtf
```

## 🧪 Development Notes

* Ensure `SECRET_KEY` is set in production (use environment variables).
* Data is stored in `cafe-data.csv`. For production, consider using a database.


Feel free to fork and improve!


