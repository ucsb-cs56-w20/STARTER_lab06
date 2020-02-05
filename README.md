A simple Spring Boot webapp using:
* Thymeleaf templating
* Pulling in Bootstrap from CDN.
* Github OAuth



| Type this | to get this result |
|-----------|------------|
| `mvn package` | to make a jar file|
| `mvn spring-boot:run` | to run the web app|
| `./checkLocalhost.py` | to check the syntax of your `localhost.json` file |
| `./setHerokuEnv.py` --app APPNAME` | to check the syntax of your `heroku.json` file  and set the configuration variables for Heroku app `APPNAME` (requires logging in to Heroku CLI first)|


Note that this app must be configured for GitHub OAuth.

Visit this link to learn more: <https://ucsb-cs56.github.io/w20/lab/lab06/>