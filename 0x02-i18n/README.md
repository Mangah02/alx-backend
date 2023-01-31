i18n project done in alx school

file description
0. Basic Flask app
1. Install the Babel Flask extension:
2. Create a get_locale function with the babel.localeselector decorator. Use request.accept_languages to determine the best match with our supported languages.
3. Use the _ or gettext function to parametrize your templates. Use the message IDs home_title and home_header
4. In this task, you will implement a way to force a particular locale by passing the locale=fr parameter to your app’s URLs.
5. Creating a user login system is outside the scope of this project. To emulate a similar behavior, copy the following user table in 5-app.py.
6. Change your get_locale function to use a user’s preferred local if it is supported.
7. Define a get_timezone function and use the babel.timezoneselector decorator.
8. Based on the inferred time zone, display the current time on the home page in the default format. For example:
