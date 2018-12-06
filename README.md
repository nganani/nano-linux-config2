# Linux Server Configuration
Project for Udacity full stack web developer nanodegree
## What's in it?
* AWS LightSail Ubuntu server
* URL: http://ec2-54-93-99-7.eu-central-1.compute.amazonaws.com/ 
  * Please note, lightsail server is currently shutdown, so cannot reach the site.
* Server IP: 54.93.99.7
* Installed software: 
  * Flask
  * sqlalchemy
  * requests
  * oauth2client
  * Python 3 mod_wsgi
  * Python Virtualenv 
  * PostgreSQL
  * Git
* Configurations made
  * Firewall setup, allowing only SSH (non-defualt port), HTTP and NTP
  * grader user created and granted sudo permissions
  * root access disabled 
  * postgres starts with server
  * apache sites-available configuration files, to point to the right app


## How to run
* Go to http://ec2-54-93-99-7.eu-central-1.compute.amazonaws.com/ 
* Follow options on the screen


## License 
* Project is released under the [MIT License](http://opensource.org/licenses/MIT).
