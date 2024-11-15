Создайте бота в BotFather и сохраните токен. Активируйте MiniApp в настройках бота

Введите ссылку, сгенерированную Ngrok, в качестве временного URL для MiniApp

Установите зависимости:

```bash
pip install -r requirements.txt
```

Создайте файл .env с вашими настройками 
(пример файла .env - файл .env.example)

Запустите приложение:

```bash
uvicorn app.main:app --reload
```