# RTFP - Real-Time Farming Platform

A Django-based web application for managing farming and auction-related activities.

## Technology Stack

### Backend
- **Django 4.2.1**: A high-level Python web framework
- **SQLite**: Lightweight database for development
- **Python 3.x**: Programming language

### Frontend
- HTML5
- CSS3
- JavaScript

### Dependencies
- asgiref==3.6.0
- python-dateutil==2.8.2
- pytz==2023.3
- six==1.16.0
- sqlparse==0.4.4
- tzdata==2023.3

## Project Structure
- `bid_app/`: Main application for bidding functionality
- `Auction/`: Core project settings and configurations
- `media/`: Directory for storing uploaded files
- `manage.py`: Django's command-line utility

## Prerequisites

Before you begin, ensure you have the following installed:
1. Python 3.x
2. pip (Python package installer)
3. Virtual environment (recommended)

## Installation and Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/hnsk1809/RTFP-New.git
   cd RTFP-New
   ```

2. **Create and activate a virtual environment**
   ```bash
   # On Windows
   python -m venv venv
   venv\Scripts\activate

   # On macOS/Linux
   python3 -m venv venv
   source venv/bin/activate
   ```

3. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

4. **Run database migrations**
   ```bash
   python manage.py migrate
   ```

5. **Create a superuser (admin)**
   ```bash
   python manage.py createsuperuser
   ```

## Running the Application

1. **Start the development server**
   ```bash
   python manage.py runserver
   ```

2. **Access the application**
   - Open your web browser and navigate to `http://127.0.0.1:8000/`
   - Admin interface: `http://127.0.0.1:8000/admin/`

## Features
- User authentication and authorization
- Bidding system
- Auction management
- Media file handling
- Admin dashboard