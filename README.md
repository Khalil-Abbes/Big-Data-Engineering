# Fame-Based Social Network

**Course:** Big Data Engineering, Saarland University

## Project Context
This repository contains my student implementations for a custom social network. 

**Provided by the University:**
The foundational Django project, including the base data models, user authentication, simple timeline views, basic posting functionality, unit tests, and a mockup AI for truth-rating posts.

**Implemented by Me:**
I designed and implemented the backend logic and corresponding HTML views for the "Fame Profile" system.

## Tech Stack
* Python, Django
* SQLite / Django ORM
* HTML, CSS

## My Contributions
* **Automated Moderation:** Modified the post submission API to block misinformation, dynamically downgrade user fame levels, and automatically ban users.
* **Algorithmic Ranking:** Implemented an algorithm (`api.bullshitters`) to aggregate and rank users with negative fame across expertise areas.
* **Dynamic Communities:** Extended data models and API to support exclusive communities for high-fame users, including timeline toggling and automatic eviction.
* **Similarity Scoring:** Built a custom recommendation algorithm (`api.similar_users`) to rank user similarity based on expertise areas and fame values.
* **Frontend:** Developed the HTML views and templates to expose the ranking, community, and similarity features.

*Key files containing my implementations: `socialnetwork/api.py`, `socialnetwork/models.py`, and `socialnetwork/views/html.py`.*
