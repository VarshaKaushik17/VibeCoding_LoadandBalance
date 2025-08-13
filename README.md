# VibeBalancer - Aircraft Weight & Balance Calculator

A full-stack application for calculating aircraft weight and balance parameters. The application helps pilots and operators determine safe cargo weights while maintaining the center of gravity within acceptable limits.

## Features

- Calculate total moment and center of gravity
- Determine maximum allowable cargo weight
- Real-time validation of inputs
- Clear visualization of results
- Professional, clean user interface

## Tech Stack

- Frontend: React
- Backend: Flask
- Styling: CSS

## Setup Instructions

### Backend Setup

1. Create a virtual environment:
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Run the Flask server:
```bash
python backend/app.py
```

### Frontend Setup

1. Install dependencies:
```bash
cd frontend
npm install
```

2. Run the development server:
```bash
npm start
```

The application will be available at http://localhost:3000 
