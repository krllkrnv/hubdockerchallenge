# Статический сайт

Простой сайт для развертывания на play-with-docker.

## Файлы
- `index.html` - страница
- `styles.css` - стили
- `script.js` - код
- `docker-compose.yml` - запуск

## Как запустить

### Локально
```bash
docker-compose up -d
```

### На play-with-docker
1. Скачайте артефакт из GitHub Actions
2. Создайте файлы в терминале
3. Запустите: `docker-compose up -d`
4. Откройте порт 80

## Команды
```bash
docker-compose up -d    # запуск
docker-compose down     # остановка
```