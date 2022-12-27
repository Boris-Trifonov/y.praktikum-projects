# Защита персональных данных клиентов

# Цель исследования:
- Защитить данные клиентов страховой компании.
- Разработать метод преобразования данных, чтобы по ним было сложно восстановить персональную информацию.

# Задачи:
- Ответить на вопрос: Изменится ли качество линейной регрессии, при умножении признаков на обратимую матрицу?
- Предложить алгоритм преобразования данных для решения задачи.
- Запрограммировать алгоритм, применив матричные операции. Проверить, что качество линейной регрессии из sklearn не отличается до и после преобразования. Применить метрику R2.

# Условия задачи:
- Защитить данные, чтобы при преобразовании качество моделей машинного обучения не ухудшилось.
- Подбирать наилучшую модель не требуется.

# Основные выводы:
- Загрузили данные:
  - Размер датасета 5 столбцов (4 признака + 1 целевой) и 5000 строк.
  - Типы данных устраивают. Оставили без изменения.
  - Пропусков нет.
  - Выбросов и аномалий нет.
  - Избавились от 153 дубликатов.

- Произвели расчет и ответили на вопрос: Изменится ли качество линейной регрессии, при умножении признаков на обратимую матрицу?
  - Качество не изменится. Вывод обосновали и проверили на следующем этапе.
- Предложили алгоритм преобразования данных для решения задачи, основываясь на предыдущем шаге.
- Запрограммировали алгоритм, применив матричные операции.
  - Согласно условиям, проверили, что качество линейной регрессии из sklearn не отличается до и после преобразования.
  - Применили метрику R2.