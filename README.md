## Vicarial Winemap            

### Dev Setup
* Server uses python3, django and mongodb
* Install [mongodb] (https://www.mongodb.com/download-center?jmp=nav#community)
```shell
$ mkdir winemap && cd "$_"
$ pip install virtualenv
$ virtualenv venv
$ source venv/bin/activate
$ git clone https://github.com/cxplanet/vicarial-winemap .
$ cd server
$ pip install -r requirements.txt
$ python manage.py runserver
```

### Run Tests
```shell
$ python manage.py test main
```

### PyLint
```shell
$ pylint -r n main
```


