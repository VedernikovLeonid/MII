# Лабораторная работа 1

Анализ данных с помощью Pandas и визуализация средствами Matplotlib/Seaborn.

## Состав проекта

- `notebooks/lab1.ipynb` — выполненный ноутбук с пояснениями, операциями над DataFrame, графиками и ответами на контрольные вопросы.
- `data/` — создаётся ноутбуком; содержит исходный и очищенный CSV.
- `outputs/figures/` — графики, сохранённые ноутбуком.
- `pyproject.toml` — зависимости и настройки Poetry.
- `.vscode/` — рекомендуемый интерпретатор и настройки Jupyter для VSCode.

## Запуск

```powershell
poetry install
poetry run python -m ipykernel install --user --name lab1-pandas --display-name "Python (lab1-pandas)"
poetry run jupyter notebook notebooks/lab1.ipynb
```

В VSCode выберите kernel `Python (lab1-pandas)` и выполните `Run All`.

Ноутбук не зависит от внешнего сайта или закрытого датасета: он генерирует небольшой воспроизводимый набор данных о продажах с фиксированным seed, сохраняет его в CSV и демонстрирует все операции из задания.

