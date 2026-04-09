# Flask App

A simple Flask web application.

## Setup

1. Clone the repository:
```bash
git clone https://github.com/Sachi-chin/flask-app.git
cd flask-app
```

2. Create a virtual environment:
```bash
python -m venv venv
# On Windows:
venv\Scripts\activate
# On macOS/Linux:
source venv/bin/activate
```

3. Install dependencies:
```bash
pip install -r requirements.txt
```

4. Run the app:
```bash
python app.py
```

The app will be available at http://localhost:5000

## Deploy

### Option 1: PythonAnywhere (Free)
1. Sign up at pythonanywhere.com
2. Upload your files
3. Configure the web app
4. Get a live URL

### Option 2: Heroku
```bash
heroku create your-app-name
git push heroku main
```

### Option 3: Replit
1. Import from GitHub
2. Click "Run"