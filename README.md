## test10
# Постройка:
docker build -t everricvlvm/test10:v1 .
# Запуск:
docker run -dtp 80:80 --privileged --name test10 everricvlvm/test10:v1
# Выполнить баш:
docker exec -it test10 /bin/bash
# SSH (Student):
ssh student@172.17.0.2

- git add .
- git commit -m "num"
- git push -u origin master
