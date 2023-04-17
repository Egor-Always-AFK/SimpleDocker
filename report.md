## Part1

#### С помощью команды `docker pull nginx` запулим образ докер

![1.1](img/1.1.png)

#### Проверим наличие докера через `docker images`

![1.2](img/1.2.png)

#### Запустим контейнер через `docker run -d [image_id|reposixtory]`

![1.3](img/1.3.png)

#### Проверим что образ запустился(через `docker ps`)

![1.4](img/1.4.PNG)

#### Посмотрим информацию о контейнере через `docker inspect [image_id|container_name]`

![1.5](img/1.5.png)

#### Посмотрим размер контейнера

![1.6](img/1.6.png)

#### Посмотрим список замапленных портов

![1.7](img/1.7.png)

#### Посмотрим ip контейнера

![1.8](img/1.8.png)

#### Остановим работу контейнера(через docker stop [container_id|container_name])

![1.9](img/1.9.png)

#### Проверим, что образ остановился(через docker ps)

![1.10](img/1.10.png)

#### Запустим докер с портами 80 и 443 через команду `run` и проверим его работоспособность через `docker ps`

![1.11](img/1.11.png)

#### Перезапустим докер через команду `docker restart [container_id|container_name]` и проверим его работоспособность через `docker ps`

![1.12](img/1.12.png)

#### Стартовая страница nginx по адресу localhost:80

![1.13](img/1.13.png)



## Part 2