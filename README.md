# PROJECT AWARDS


## Built By [Ian Sani](https://github.com/iansani/)

## Description
This is a web application that allows different developers to post their projects and peers can review the same by grading the projects in terms of userbility, design and content.


## User Stories
These are the behaviours/features that the application implements for use by a user.

Users would like to:
* View all projects submitted by any user.
* Click on links to visit a live site.
* Search for users.
* Must be signed up to vote
* See averages for the three grading criterias
* Grade Projects.


## Admin Abilities
These are the behaviours/features that the application implements for use by the admin.

Admin should:
* Sign in to the application
* Add, Edit and Delete projects
* Delete projects
* Manage the application.


## Specifications
| Behaviour | Input | Output |
| :---------------- | :---------------: | ------------------: |
| Admin Authentication | **On demand** | Access Admin dashboard |
| Admin Authentication | **On demand, verify emails before proceeding** | Access Admin dashboard |
| Display all projects with grading | **Home page** | Clickable links to open live projects in different sites |
| To add an project  | **Through Admin dashboard and homepage** | Click on add and upload respectively|
| To edit project  | **Through Admin dashboard** | Redirected to the  project form details and editing happens|
| To delete an project  | **Through Admin dashboard** | click on project object and confirm by delete button|
| To search projects by title | **Enter text in search bar** | Users can search by Project Title|
| Comment on projects | **Add comments below respective project** | Users can add comments on any project|
| Vote on projects | **vote** | Users can review projects they like and comment|


## SetUp / Installation Requirements
### Prerequisites
* python3.6
* pip
* virtualenv
* Requirements.txt

### Cloning
* In your terminal:

        $ git clone https://github.com/iansani/Awwards
        $ cd Awards

## Running the Application
* Creating the virtual environment

        $ python3.6 -m venv --without-pip virtual
        $ source virtual/bin/activate
        $ curl https://bootstrap.pypa.io/get-pip.py | python

* Installing Django and other Modules

        $ see Requirements.txt

* To run the application, in your terminal:

        $ python3.6 manage.py runserver

## Testing the Application
* To run the tests for the class files:

        $ python3.6 manage.py test projects

## Technologies Used
* Python3.6
* Django  framework and postgresql database

## Known Bugs

* Multiple votes can be done on single project

## License

Copyright (c) 2018 iansani
