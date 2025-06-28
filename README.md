## MenuGPT
An automated meal planner that scrapes your school's dining menu, matches meals to your dietary needs and calorie goals, and uses ChatGPT to recommend the best options each day.

## Features
- Daily scraping of campus dining menu
- JSON-based storage of daily meal items
- Custom user preferences via config files
- Automated ChatGPT query submission (via logged-in Chrome session)
- Summarized meal recommendations based on:
  - Dietary restrictions (vegetarian, nut-free, etc.)
  - Calorie goals
  - Balanced macros and variety

## Tech Stack
- **Python** – Core programming language
- **BeautifulSoup4 / Requests** – For scraping the dining menu site
- **JSON** – For storing daily meal data and ChatGPT query metadata
- **.cfg / ConfigParser** – For storing user settings like dietary restrictions and calorie targets
- **Selenium – To automate browser-based ChatGPT interactions
- **Chrome (with persistent profile)** – Authenticated browser session for ChatGPT queries

## How To Run
- Clone Repo
- Run Python enviroment
- Run meal.py
