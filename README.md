# social_network
Social Network project for CS253

Overview

A basic Flask web app where users can register, log in, post updates, add friends, and view posts from friends.
Features

    User signup/login (session-based)

    Create/view posts

    Add friends

    View user profiles

    Search users

Files

    app.py: Main Flask app and logic

    users.db: SQLite database (auto-generated)

    templates/: HTML templates

How to Run

    Install Flask:

pip install flask

Start the server:

    python app.py

    Go to http://127.0.0.1:5000/

Database Tables

    users(id, name, username, password, age)

    posts(id, username, post_content, timestamp)

    friendships(id, user1_id, user2_id)
