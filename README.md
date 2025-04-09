.gitignore Этот файл указывает Git, какие файлы и папки не нужно отслеживать и добавлять в репозиторий.
README.md Это файл с описанием проекта в формате Markdown
config.py Файл с настройками и конфиденциальными данными (API-ключи, пароли и т.д.).
config_template.py Шаблон файла конфигурации без конфидециальных данных.
main.py Главный исполняемый файл проекта.
Файл config.py добавляют в .gitignore, чтобы избежать случайного попадания конфиденциальных данных (например, API-ключей, паролей, токенов) в публичный репозиторий Git (например, на GitHub).
git pull делает две вещи:
1. Скачивает изменения из удалённого репозитория (например, с GitHub, GitLab или другого сервера).
2. Обновляет текущую локальную ветку, применяя эти изменения.
