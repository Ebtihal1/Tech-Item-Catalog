# Udacity | Full Stack Web Developer | Project 2 : Item Catalog
##### Created by: Ebtihal Abduallah

### Introduction:
Catalog Tech App website provides a list of items within a variety of IT categories as well as provide a user registration and authentication system. Registered users will have the ability to add, edit and delete their own items.
Using the Python, Flask framework and SQLAlchemy object relational mapper (ORM) along with implementing third-party authentication (Google API OAuth2.0).

### Configuration:
- 	Install Vagrant and VirtualBox latest versions 
- 	Clone the `fullstack-nanodegree-vm` [click here](https://github.com/udacity/fullstack-nanodegree-vm)
- Launch the Vagrant VM `vagrant up`
- Log into Vagrant VM `vagrant ssh`
- Navigate to `cd /vagrant/catalog` as instructed in terminal
- Install all requirement librarys download **requirements.txt** [click here](https://drive.google.com/file/d/1xW1l8x9Q2qW5OOu38xKAegh1VgizE2hB/view?usp=sharing)
in terminal run the coomand `pip install -r requirements.txt`
- Configure Google Sign-in API, to create your Client ID Key follow the instruction [click here](https://drive.google.com/open?id=1Ojb7KK96MOlqhZlxNz0vy2m7I6oDkXeEh-KRPWY1w2w)

### Installation:
On terminal run the command:
•	python `database_setup.py`
•	python `data.py`
•	python `final.py`
In the browser visit: http://localhost:8000/

### JSON Endpoints:
* Explor catalogs: http://localhost:8000/catalog/JSON
* Explor items: http://localhost:8000/catalog/1/item/JSON
* Explor item details: http://localhost:8000/catalog/1/item/1/JSON


### Resource: 
* www.udacity.com
* https://developers.google.com/+/web/samples/python
* http://flask.pocoo.org/docs/0.12/patterns/sqlalchemy/
* https://developer.mozilla.org/en-US/docs/Learn/HTML/Forms/Form_validation