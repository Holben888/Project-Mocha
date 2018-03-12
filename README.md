## Setting up the project

* Activate environment using: ```source django2env/bin/activate```
    * Once activated, you may now safely add libraries to the project without changing any files on your machine
    * We do this since different python projects may need different versions of libraries, like Django
    
* Run ```pip install django``` __after__ activating the environment
* Run project using: ```python manage.py runserver``` and visite the URL that is displayed

__You may get a warning after running that you need to migrate.__ If so, simply execute: ```python manage.py migrate```

### That's all! Happy hacking :)
