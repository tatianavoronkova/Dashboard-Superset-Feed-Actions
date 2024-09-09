# Дашборд аналитики продаж (RU)
Этот проект представляет собой дашборд, созданный в **Apache Superset** для отслеживания и анализа ключевых метрик приложения новостной ленты. 
Дашборд помогает аналитикам и маркетологам следить за активностью пользователей, оценивать популярность контента и быстро обнаруживать аномалии в поведении метрик.

<image src="/Dashboard-Superset-feed-operative-data.jpg" alt="Superset Dashboard">
  
## ЦЕЛЬ
1. **Визуализация ключевых метрик**
2. **Обнаружение аномалий:**
  - Мониторинг резких изменений в метриках для раннего предупреждения о возможных проблемах
  - Использование визуализаций для выявления аномалий и отклонений в данных
3. **Поддержка принятия решений:**
  - Оптимизация контентных стратегий на основе анализа поведения пользователей
  - Оценка эффективности маркетинговых кампаний и контента

## МЕТРИКИ

### Числовые метрики:
- **Users** - число активных пользователей в ленте новостей (DAU) и сравнение с тем же днем неделей ранее
- **Views** - количество просмотров новостей
- **Likes** - взаимодействия пользователей (количество лайков)
- **Views per user** - количество просмотров на пользователя
- **Likes per user** - количество лайков на пользователя
- **CTR (Click-Through Rate)** — коэффициент кликабельности (Это отношение числа кликов на число просмотров)
- **Retention (удержание пользователей)** - показывает, сколько пользователей продолжает использовать сервис на следующий день
- **Stickiness (показатель "прилипчивости")** - отношение DAU/MAU, показывает, насколько часто пользователи возвращаются в сервис

### Графики:
- **All actions** - суммарное количество всех действий пользователей в течение дня (и для сравнения такой же показатель 1 день и неделю назад)
- **Views/Likes** - графики просмотров и лайков по-отдельности
- **TOP-5 posts** - 5 самых популярных постов за день


## КЛЮЧЕВЫЕ ОСОБЕННОСТИ
1. **Мониторинг в реальном времени:** Дашборд предоставляет информацию о текущем состоянии ключевых метрик, таких как количество активных пользователей (**DAU**), просмотры, лайки и **CTR**, с возможностью отслеживания изменений в режиме реального времени.
2. **Сравнение с предыдущими периодами:** Для метрик **Users** и **All actions** предусмотрено сравнение с показателями аналогичного дня на прошлой неделе, что помогает лучше понять динамику изменений и выявить тренды.
3. **Анализ взаимодействий на уровне пользователя:** Метрики **Views per user** и **Likes per user** дают возможность оценить среднюю активность одного пользователя, что помогает выявить сегменты наиболее вовлеченных пользователей.
4. **Оценка эффективности контента:** Блок **TOP-5 posts** показывает пять самых популярных постов за день, что позволяет быстро оценить, какой контент вызывает наибольший интерес у пользователей.
5. **Анализ удержания и вовлеченности:** Метрики **Retention** и **Stickiness** помогают отслеживать, насколько эффективно приложение удерживает пользователей и как часто они возвращаются в сервис, что важно для долгосрочного планирования роста и оптимизации.

## РЕЗУЛЬТАТ
Дашборд предоставляет всесторонний анализ пользовательской активности в ленте новостей. Он помогает оперативно выявлять резкие изменения в поведении пользователей (например, падение просмотров или снижение удержания), а также понимать, какие посты и элементы приложения наиболее привлекательны для аудитории. Сравнительные графики с прошлыми периодами позволяют быстро выявить как положительные тренды, так и аномалии, что способствует принятию обоснованных решений по улучшению приложения.

#### Этот дашборд можно использовать для:
- Оптимизации контентных стратегий,
- Оценки эффективности нововведений и маркетинговых кампаний,
- Повышения удержания и вовлеченности пользователей,
- Оперативного реагирования на изменения в поведении аудитории.
