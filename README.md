# Auth0 Python Web App Sample

This sample demonstrates how to add authentication to a Django web app using Auth0.

# Running the App

To run the application:

1. Make sure you have `python`, `pip` installed..
2. Install the needed dependencies with `pip install -r requirements.txt`
3. Run `python manage.py migrate` to migrate the database schema
4. Run `python manage.py runserver 3000` to run the server.

The app will be served at [http://127.0.0.1:3000/](http://127.0.0.1:3000/).

# Running the App with Docker

To run the sample with `docker`:

1. Run `sh exec.sh` to build and run the docker image in Linux.

The app will be served at [http://0.0.0.0:3000/](http://0.0.0.0:3000/).

## What is Auth0?

Auth0 helps you to:

- Add authentication with [multiple authentication sources](https://docs.auth0.com/identityproviders),
  either social like **Google, Facebook, Microsoft Account, LinkedIn, GitHub, Twitter, Box, Salesforce, among others**,
  or enterprise identity systems like **Windows Azure AD, Google Apps, Active Directory,
  ADFS or any SAML Identity Provider**.
- Add authentication through more traditional
  **[username/password databases](https://docs.auth0.com/mysql-connection-tutorial)**.
- Add support for **[linking different user accounts](https://docs.auth0.com/link-accounts)**
  with the same user.
- Support for generating signed [JSON Web Tokens](https://docs.auth0.com/jwt) to call your APIs and
  **flow the user identity** securely.
- Analytics of how, when and where users are logging in.
- Pull data from other sources and add it to the user profile, through [JavaScript rules](https://docs.auth0.com/rules).
