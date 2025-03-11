# CircusCircus

https://github.com/user-attachments/assets/de9f66d7-c4c5-46d3-8700-7eee69a54f62


Circus Circus is a feature-rich online forum designed for the ZipCode Wilmington community. It provides an interactive platform where users can create posts, leave comments, react with emojis, send direct messages, and manage their content with ease. Built with modularity and scalability in mind, Circus Circus supports both public and private posts, user authentication, and rich media integration.

# Features

User Authentication: Secure login and registration system.

Public & Private Posts: Public posts are visible to everyone, while private posts require user authentication.

Markdown Support: Posts can be written in plain text or Markdown for enhanced formatting.

Rich Media Integration: Users can insert image and video links in their posts.

Bootstrap Styling: Clean, responsive, and modern UI based on Bootstrap.

Footer Information: Copyright, About page, and other essential links on every page.

# User Interaction

Post Creation & Management: Users can create, edit, and delete their posts.

Comments: Each post supports multiple comments for discussions.

Reactions: Users can like, dislike, or react with emojis on posts.

Direct Messaging: Users can send private messages to one another.

# User Settings

Profile Management: Users can update their settings and preferences.

Privacy Controls: Manage who can view posts and interactions.

# Tech Stack

Backend: Python (Flask)

Database: MySQL (migrated from SQLite3)

Frontend: HTML, CSS, JavaScript, Bootstrap

Authentication: Flask-Login


```
$ python3 -m venv venv
$ source venv/bin/activate
$ pip install -r requirements.txt
$ ./run.sh
```

and it should appear on port 5000

`http://0.0.0.0:5000`
