## Проект: Прогнозирование Активности Пользователей Приложения

**Цель:**

Предсказать изменения в активности пользователей приложения в течение следующего месяца. Это позволит заблаговременно подготовить инфраструктуру к потенциальным пиковым нагрузкам, предотвратить сбои и обеспечить стабильную работу сервиса.

**Задачи проекта:**

1.  **Метрика Активности:**
    *   Определить и обосновать ключевую метрику, наиболее точно отражающую общую активность пользователей приложения.

2.  **Временное Разрешение:**
    *   Выбрать и обосновать оптимальное временное разрешение (например, почасовое, ежедневное) для анализа и прогнозирования.

3.  **Регрессоры:**
    *   Выявить и обосновать внешние факторы (регрессоры), влияющие на активность, и включить их в модель.

4.  **Моделирование с Orbit:**
    *   Использовать библиотеку Orbit для построения и оценки моделей прогнозирования временных рядов.
    *   Протестировать модели на исторических данных и с учетом выбранных регрессоров.

5.  **Бэктестинг:**
    *   Провести бэктестинг.

6.  **Выбор и Ограничения:**
    *   Сравнить производительность моделей, используя соответствующие метрики качества.
    *   Выбрать лучшую модель на основе результатов валидации.
    *   Проанализировать и задокументировать ограничения выбранной модели.

### Технические детали:
*   **Инструменты:** Python (Pandas, NumPy, Orbit)
*   **Источники данных:** Данные для анализа были получены из системы управления базами данных (СУБД) ClickHouse.
*   **Код:** Ознакомиться с кодом можно в файле `project_1.ipynb`
