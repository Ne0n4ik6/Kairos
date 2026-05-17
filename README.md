# Kairos - Online Banking Platform
The front-end part was implemented using HTML, CSS, and JavaScript. I implemented the back-end part of the site using PHP.

## About the Project
Kairos is a modern online banking platform with cryptocurrency integration and Google OAuth2 authentication.

## Technologies
- PHP
- Google OAuth2 API
- HTML5, CSS3, JavaScript
- Open Server

## Installation and launch
1. Download the archive

2. Setting up a local server using OpenServer 
1) Copy the project folder to OSPanel\domains\kairos.com\

2) Run Open Server

3) In the Open Server menu, select Settings → Domains
Add a domain:
Name: kairos.com

3. Setting up Google OAuth2

1) Go to the Google Cloud Console

2) Create a new project

3) Go to APIs & Services → Credentials

4) Click Create Credentials → OAuth Client ID

5) Select Web application

6) Add Authorized redirect URIs: http://kairos.com/auth/callback.php

7) Copy the Client ID and Client Secret

4. Configuration setup

1) Create a .env file in the root of the project and fill it with the following (Point 3.7):
GOOGLE_CLIENT_ID=your_client_id.apps.googleusercontent.com
GOOGLE_CLIENT_SECRET=your_client_secret

5. Run localhost with Open Server

6. Or follow the link http://d33672ng.beget.tech/
