# Аналитический проект с REST API

Проект для анализа данных с использованием REST API, PostgreSQL и визуализации.

## 🚀 Быстрый старт (Windows)

### Установка и настройка

1. **Клонируйте репозиторий или создайте папку проекта**

2. **Откройте PowerShell в папке проекта**

3. **Выполните команды по одной:**

# 1. Перейдите в папку проекта
```powershell
cd C:\projects\rest_api_analitics
```

# 2. Проверьте/установите uv
```powershell
uv --version
```
# Если не работает:
```powershell
python -m pip install uv
```
# 3. Инициализируйте проект
```powershell
uv init
```

# 4. Установите зависимости
```powershell
uv sync
uv sync --dev
```
# 5. Создайте папки
```powershell
mkdir -Force data/raw, data/processed, logs, notebooks
```
# 6. Скопируйте .env файл если нужно

# 7. Активируйте окружение
```powershell
.venv\Scripts\Activate
```

# 8. Проверьте что все работает
```powershell
python --version
```
```powershell
pip list | findstr pandas
```