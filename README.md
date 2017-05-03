# Flask-MongoDB-Login

This app provides user session management for Flask. It handles the common
tasks of logging in, logging out, and remembering your users' sessions over
extended periods of time.

## Installation
Need to pip render_template, url_for, request, session, redirect, flash modules

Then add the mongodb details
```
app.config['MONGO_dbname'] = 'users'
app.config['MONGO_URI'] = 'mongodb://localhost:27017/users'
```

## Usage

Once installed, Start the app with:

```
python app.py
```

We now have a basic working application that makes use of session-based
authentication. To round things off, we should provide a callback for login
failures:

## Contributing

We welcome contributions! If you would like to hack on Flask-MongoDB-Login, please
follow these steps:

1. Fork this repository
2. Make your changes
3. Install the requirements
4. Submit a pull request after running `make check` (ensure it does not error!)

Please give us adequate time to review your submission. Thanks!
