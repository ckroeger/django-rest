# A simple Django-Rest-Example

## run application
```shell
python3 manage.py runserver
```

## create db-modell 
```shell
python3 manage.py makemigrations
```

## apply schema to database
```shell
python3 manage.py migrate
```

## create requirements.txt
```shell
pip3 freeze > requirements.txt
```

## add data via shell
```shell
python3 manage.py shell

>>> from base.models import Item
>>> Item.objects.create(name="Item #1")
```
## build image locally
```shell
sudo docker build -t django .
```

## GET
![GET](docs/img/get_root.jpg)

## /add
![GET](docs/img/add_item_post_1.jpg)

## /add after post
![GET](docs/img/add_item_post_2.jpg)
