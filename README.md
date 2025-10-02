# itelma - LCT hack

## Ссылки

- [Backend репозиторий](https://digital-fracture/itelma-backend)
- [Frontend репозиторий](https://github.com/scarlettnik/lct)
- [Демонстрация](https://lct-chi.vercel.app)
- [Дополнительные ресурсы](https://drive.google.com/drive/folders/1a9HcEjjYKTA2ni9vWTC7QlA8ipzxdzXS?usp=drive_link)


## Документация

### [Документация ML](./ML.md)

### [Документация API](https://hack.nearby-project.ru/docs)

### Развертывание проекта

**Требования:**
- Linux
- cURL
- Docker
- Make

1. Подготовка
   ```shell
   mkdir itelma-deploy
   cd itelma-deploy
   curl https://raw.githubusercontent.com/digital-fracture/itelma-deploy/refs/heads/main/Makefile -o Makefile
   make setup
   ```

2. Запуск
   ```shell
   make start
   ```

3. Остановка
   ```shell
   make stop
   ```

4. Перезапуск
   ```shell
   make restart
   ```
