# WebApp Deployment Assignment

This project is a simple static web application created for Week 2 assignment. The main goal of this project is to practice Linux directory management, Git version control, branching, configuration management, and repository hosting on GitHub or GitLab.

The application contains two HTML pages: index.html and about.html. These pages are connected using hyperlinks and styled using a single CSS file called style.css. The purpose is to simulate a lightweight deployable website.

In addition to frontend files, this repository includes Nginx and Apache server configuration files. The nginx.conf file defines a server block that serves the application using Nginx, while apache.conf defines a VirtualHost configuration for Apache HTTP Server.

A .gitignore file is also added to ignore temporary log files, backup files, and Python cache directories. Git branching is used in this assignment by creating a develop branch, completing the work there, and later merging it back into the main branch.

## Deployment Notes

To deploy this web application, copy all HTML and CSS files to the /var/www/webapp directory. Then place nginx.conf inside /etc/nginx/sites-available/ or apache.conf inside Apache sites configuration depending on the web server used. Restart the selected web server after enabling the configuration. The website will then be accessible through localhost on port 80.
