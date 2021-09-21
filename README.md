# The Holberton School Airbnb Clone project
This Repo is a collection of all the iterations of the Airbnb clone project we had to create over six months with each step having a paired programming aspect to it and some test-driven development.

As a whole, this project was designed to teach us how a web application is pieced together. Furthermore, help develop soft skill such are a collaboration through peer programming and shared Github repository as well as organization and documentation. Some other aspects are covered list below.

- Building models
- Building a console
- working with Json
- Working with MySQL via ORM (using SQLAlchemy)
- Build Flask application to service a frontent
- Build an RESTful API
- Building a frontend with HTML and CSS
- Use a template engine (JinJa)
- Use JS/Jquery to create a dynamic frontend


Version 4 is the last coding project before the deployment step.

# Projects :building_construction:

## [v1: Models, File system and Static pages](https://gitlab.com/Hraesvel/AirBnB_clone) 

In this step of the project, we create the models and a console for the
Airbnb project. While at this time we're not using any kind database we
create a file system engine to read/write to a JSON file.

We also create the scaffolding of the static HTML page which we will later
use as for them as templates for JinJa/Jquery frontend.

## [v2: Mysql, SqlAlchemy and Flask](https://gitlab.com/Hraesvel/AirBnB_clone_v2)
 In this step, we polish up the console and implement a database
engine using SQLAlchemy + MySQL. We then create our first Flask
application withing the static HTML + jinja to service the frontend.

## [v3: RESTful API](https://gitlab.com/Hraesvel/AirBnB_clone_v3)
This step of the project we learn about implement a REST API server for
the application using Flask.

## [v4: Dynamic Frontend](https://gitlab.com/Hraesvel/AirBnB_clone_v4) :gear:
This step we move away from server-side rendering via `jinja` and use
the REST API created in the last step to make the frontend dynamic with
JS/JQuery.

## [Deployment](https://gitlab.com/Hraesvel/HBNB_Airbnb) :airplane: 
The concluding portion of the Airbnb project, deploy the web application to servers. I took this as an opportunity to learn to use Puppet Bolt to automate the deployment process.

## Change log:

- Commit [22e9279](https://github.com/Hraesvel/HBNB_Airbnb/commit/22e9279ee199d54229eb625747846bfb34f0ceac)
  - updated submodules to use gitlab version


## Technology Stack

### Languages
 - Python :snake:
 - Javascript
 - HTML 
 - CSS
 
### Frameworks & Libs
- Flask 
- SQLAlchemy 
- JQuery

### Tool
- Docker :whale:
- Nginx
- Haproxy 
- Puppet Bolt
- Ubuntu
