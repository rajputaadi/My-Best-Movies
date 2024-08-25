# Movie Library Application

This is a Flask-based web application that allows users to manage a personal movie library. Users can add movies, rate them, leave reviews, and delete entries from the library. The application fetches movie data from The Movie Database (TMDb) API.

## Features

- **Add Movies:** Search for movies by title using TMDb API and add them to your library.
- **Rate and Review:** Update the rating and review for each movie.
- **Manage Library:** View all movies in your library and delete entries as needed.

## Prerequisites

Before running the application, make sure you have the following installed:

- [Python 3.x](https://www.python.org/downloads/)
- [Flask](https://pypi.org/project/Flask/)
- [Flask-SQLAlchemy](https://pypi.org/project/Flask-SQLAlchemy/)
- [Flask-Bootstrap](https://pypi.org/project/Flask-Bootstrap/)
- [Flask-WTF](https://pypi.org/project/Flask-WTF/)
- [Requests](https://pypi.org/project/requests/)
- [python-dotenv](https://pypi.org/project/python-dotenv/)

## Installation

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/yourusername/movielibrary.git
   cd movielibrary
2. **Install Required Packages:**
   ```bash
   pip install Flask Flask-SQLAlchemy Flask-Bootstrap Flask-WTF requests python-dotenv
3. **Set Up Environment Variables:**
   ```bash
   API_KEY=your_tmdb_api_key_here
4. **Run the Application: **
   ```bash
   python app.py
