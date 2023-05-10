![Photo by Yoksel 🌿 Zok on Unsplash](https://user-images.githubusercontent.com/2342458/202706130-d6d2995a-9171-4619-ab15-abc93603fa86.png)

# Kinsta - Hello World - PHP
An example of how to set your PHP application up to enable deployment on Kinsta App Hosting services.

---
Kinsta is a developer-centric cloud host / PaaS. We’re striving to make it easier for you to share your web projects with your users. Focus on coding and building, and we’ll take care of deployment and provide fast, scalable hosting. + 24/7 expert-only support.

- [Start your free trial](https://kinsta.com/signup/?product_type=app-db)
- [Application Hosting](https://kinsta.com/application-hosting)
- [Database Hosting](https://kinsta.com/database-hosting)

## Dependency Management
During the deployment process Kinsta will automatically install dependencies defined in your `composer.json` file.

## Web Server Setup
Kinsta will automatically configure an apache web server which will serve from the main directory of the project in the usual fashion; create an `index.php` file in your project folder as the entry-point.
