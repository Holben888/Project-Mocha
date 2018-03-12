## Setting up the project

__This assumes you already have Python installed. Macs have a version of Python installed by default.__

* After cloning the repository, install virtualenv using: ```pip install virtualenv```
* Create a virtualenv in the repo using: ```virtualenv [ENV_NAME]```

* Activate environment using: ```source [ENV_NAME]/bin/activate```
    * It's recommended you activate every time you add libraries to the project, or just activate whenever you open the repo
    * We do this since different python projects may need different versions of libraries, like Django
    
* Run ```pip install django``` __after__ activating the environment
* Run project using: ```python project-mocha/manage.py runserver``` and visit the URL that is displayed

__You may get a warning after running that you need to migrate.__ If so, simply execute: ```python project-mocha/manage.py migrate```

### That's all! Happy hacking :)
