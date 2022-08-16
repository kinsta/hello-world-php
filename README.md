# Kinsta - Hello World - PHP
An example of how to set your PHP application up to enable deployment on Kinsta App Hosting services.

> Kinsta’s Application Hosting is a service to run your web apps and any databases side by side in a hassle-free environment, tailored for developer needs and ease of use. App Hosting is currently in an invite-only beta phase, sign up for a test account at [kinsta.com/application-hosting](https://kinsta.com/application-hosting/).

## Dependency Management
During the deployment process Kinsta will automatically install dependencies defined in your `composer.json` file.

## Web Server Setup
Kinsta will automatically configure an apache web server which will serve from the main directory of the project in the usual fashion; create an `index.php` file in your project folder as the entry-point.
