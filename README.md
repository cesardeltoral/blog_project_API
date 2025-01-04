Flask Blog Project
This project is a simple Flask-based blog application that demonstrates how to work with APIs, object-oriented programming, and dynamic rendering of HTML templates.

Features:
Dynamic Blog Posts: Fetches blog data from an external API and generates content dynamically.
Object-Oriented Approach: Utilizes a Post class to create blog post objects for easy data management.
Routing: Implements Flask routes to display all posts on the homepage and individual post details on separate pages.
HTML Templates: Uses Jinja2 templates (index.html and post.html) for rendering the homepage and post details.
How It Works:
Fetches blog data from a JSON API (https://api.npoint.io/c790b4d5cab58020d391).
Converts each blog entry into a Post object with attributes such as id, title, subtitle, and body.
Renders the homepage with all blog posts and provides links to view detailed content for each post.
How to Run:
Clone the repository.
Install the required dependencies using pip install flask.
Run the application with python app.py.
Open your browser and navigate to http://127.0.0.1:5000/.

