# Платформа «OTUS», курс «Microservice Architecture», 1 месяц, занятие 2 (домашняя работа)

**Предусловия:**

1. Установлен Docker

**Порядок запуска:**

1. Скачать репозиторий.
2. Запустить Docker.
3. Запустить терминал в корневой папке проекта, там где расположен файл **README.md**.
4. Выполнить в терминале следующие команды:

```shell
docker build -t project-name .
docker run -dp 8000:5000 project-name
```

5. Открыть в браузере ссылку: [http://localhost:8000/health](http://localhost:8000/health)
