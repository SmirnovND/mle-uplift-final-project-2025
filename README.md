# Запуск проекта

Проект рассчитан на запуск в отдельном виртуальном окружении внутри репозитория.

## 1. Клонирование

```bash
git clone <repo-url>
cd mle-uplift-final-project-2025
```

## 2. Создание виртуального окружения

Рекомендуемый интерпретатор: `python3.10`.

Если на машине нет `python3.10`, локально проверено, что проект также разворачивается на `python3.12`.

```bash
python3.10 -m venv .venv
```

Если `python3.10` недоступен:

```bash
python3.12 -m venv .venv
```

## 3. Активация окружения

```bash
source .venv/bin/activate
```

## 4. Установка зависимостей

```bash
pip install -r requirements.txt
```

## 5. Работа с ноутбуком

Основной файл проекта:

```bash
final_project_template.ipynb
```

При необходимости можно выбрать интерпретатор `.venv/bin/python` как kernel в VS Code или Jupyter.

# Содержимое репозитория

- `final_project_template.ipynb` — основной ноутбук проекта.
- `uplift_fp_data.csv` — датасет.
- `utils.py` — вспомогательная функция для визуализации uplift по перцентилям.
- `requirements.txt` — минимальный набор зависимостей, достаточный для запуска ноутбука.
