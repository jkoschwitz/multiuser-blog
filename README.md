Getting Started
In the course “Intro to Backend,” we walk you through the development of a blog application using Google App Engine. But the course excludes certain features that you’ll need to implement for this project.

This document is intended to guide you through implementing the entire project, including what has been taught in the course. Note that some details are omitted from this document, so refer to the rubric for details. If you’ve already completed the project from the course, go to step 5.

Note: Google App Engine has changed a lot recently! Fortunately their documentation is very good. If you encounter error messages while deploying your project, check out the documentation or ask on the Udacity discussion forums!

Let’s Get Started

--Setup
Install Python if necessary.
Install Google App Engine SDK.
Sign Up for a Google App Engine Account.
Create a new project in Google’s Developer Console using a unique name.
Follow the App Engine Quickstart to get a sample app up and running.
Deploy your project with gcloud app deploy.
View your project at unique-name.appspot.com.
You should see “Hello World!”
When developing locally, you can use dev_appserver.py to run a copy of your app on your own computer, and access it at http://localhost:8080/.
Install Jinja and create helper functions for using Jinja, follow the directions here.
If you’re unfamiliar with Jinja watch Lesson 2 and/or check out the docs.

--Step 1: Create a Basic Blog
Blog must include the following features:
Front page that lists blog posts.
A form to submit new entries.
Blog posts have their own page.
View instructions and solutions here.

--Step 2: Add User Registration
Have a registration form that validates user input, and displays the error(s) when necessary.
After a successful registration, a user is directed to a welcome page with a greeting, “Welcome, [User]” where [User] is a name set in a cookie.
If a user attempts to visit the welcome page without being signed in (without having a cookie), then redirect to the Signup page.
Watch the demo for more details.
Be sure to store passwords securely.

--Step 3: Add Login
Have a login form that validates user input, and displays the error(s) when necessary.
After a successful login, the user is directed to the same welcome page from Step 2.
Watch the demo for more details.

--Step 4: Add Logout
Have a logout form that validates user input, and displays the error(s) when necessary.
After logging out, the cookie is cleared and user is redirected to the Signup page from Step 2.
Watch the demo for more details.

--Step 5: Add Other Features on Your Own
Users should only be able to edit/delete their posts. They receive an error message if they disobey this rule.
Users can like/unlike posts, but not their own. They receive an error message if they disobey this rule.
Users can comment on posts. They can only edit/delete their own posts, and they should receive an error message if they disobey this rule.

--Step 6: Final Touches
Create a README.md file explaining how to run your code.
Refactor your code so it is well structured, well commented, and conforms to the Python Style Guide.
Make sure your project conforms to the rubric.
Deploy your app to appspot.com using gcloud app deploy.
Submit your project.
Revise your project and resubmit as necessary.
Pat yourself on the back!
