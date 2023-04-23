# Запускаем через Docker
1) Клонируем репозиторий:
```
git clone https://github.com/RussianProgram/simple_bot_test.git
```

2) Билдим образы и поднимаем контейнеры через docker-compose

```
cd /simple_bot_test
docker build -t bot:test .
```

3) Запускаем/останавливаем контейнер
```
docker run --name bot bot:test
docker stop bot
docker start bot
```