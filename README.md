
- build the containers:
```sh
$ sudo docker-compose build
```

- Launch the containers:
```sh
$ sudo docker-compose up -d
```

- Create a superuser:
```sh
 $ sudo docker exec -it hospicare_api_1 python manage.py createsuperuser
Email: <example@esi.dz>
First name: <first_name>
Last name: <last_name>
User type: superuser
Password: <password>
Password (again): <password>
```
