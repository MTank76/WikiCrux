# WikiCrux (Wikipedia In a Crux)

A simple Django-based Wikipedia search application developed to provide quick Wikipedia article summaries. This project uses the Wikipedia API to fetch and display summaries of articles based on user search input. It served as a foundational experience in working with Django views, forms, templates, and integrating external libraries.

## Requirements

- Python 3.8 or higher
- Django 4.0 or higher
- SQLite3 (included with Python)
- Wikipedia library (Python package)

## Key Features

- **Wikipedia Search**: Allows users to search for Wikipedia articles and view summaries.
- **Django Admin Integration**: Basic Django admin interface to manage application settings.
- **SQLite3 Database**: Uses SQLite3 for lightweight and efficient data storage (although the database is not actively used for search data in this app).

## Deployment Instructions

### Clone the repository

```bash
git clone https://github.com/yourusername/Wikipedia-Search-App.git
cd Wikipedia-Search-App
```

Install required dependencies: Install the necessary Python packages:

```bash
pip install -r requirements.txt
```

Apply Migrations: Prepare the database (SQLite3 by default):
```bash
python manage.py makemigrations
python manage.py migrate
```

Run the Server: Start the Django development server:
```bash
python manage.py runserver
```

Access the application: Open your web browser and go to http://127.0.0.1:8000 to start using the Wikipedia Search App.

## Contributing
If you'd like to contribute to the Wikipedia Search App, please fork the repository and submit a pull request with your changes. For bug reports or feature requests, open an issue on GitHub.
